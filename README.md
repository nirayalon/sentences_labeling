# sentences_labeling

# Getting Started
1. **Clone the repository**:
  ```bash
  git clone [https://github.com/YOUR_USERNAME/sentences_labeling.git](https://www.google.com/search?q=https://github.com/YOUR_USERNAME/sentences_labeling.git)  # Replace with your repo URL
  cd sentences_labeling
  ```

2. **Set up your Google Cloud credentials**:  You'll need to create a service account and download the JSON key file.  Store the contents of this file as a Streamlit secret named credentials.  See the Streamlit documentation for how to manage secrets.

  
3. **Set up your Google Sheet**: Create a Google Sheet named "classification_DB" with two worksheets: "ClassificationSheet" and "RowsDivider".  "ClassificationSheet" should contain the sentences to be labeled, and "RowsDivider" should contain user information. The structure of these sheets is implicitly defined by the code and should be adhered to.

4. **Run the Streamlit app**:
If using the devcontainer, VS Code will handle this for you. Otherwise, install the requirements and run:
  ```bash
  pip install -r requirements.txt
  streamlit run streamlit_classification_app.py
  ```
5. **Open the app in your browser**: Streamlit will provide a URL to access the application.


# Usage
1. Choose your name from the radio button on the home page.
2. Click "Apply".
3. You will be taken to the labeling page, where you will see pairs of sentences.
4. Select the appropriate label for each pair.
5. Click "Submit" to save your label.
6. Click "Next" to move to the next pair.
7. Click "Done for today" when you are finished labeling.

# Contributing
Contributions are welcome!  Please open an issue or submit a pull request.
