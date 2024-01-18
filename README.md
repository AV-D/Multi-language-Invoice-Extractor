# Multi Language Invoice Extractor

## Introduction
The Multi Language Invoice Extractor is a project that leverages the Gemini Pro Vision generative model from Google Generative AI to extract information from invoices in multiple languages. This Streamlit app allows users to input a prompt related to the invoice and upload an image of the invoice. The model then generates a response based on the input prompt and the content of the uploaded invoice image.

## Requirements
Before running the application, ensure that you have the following dependencies installed:

* Python > 3.10
* `dotenv` library
* `streamlit` library
* `PIL` (Pillow) library
* `google.generativeai` library (Gemini Pro Vision model)

You can install these dependencies using the following command:
```
pip install python-dotenv streamlit Pillow google-generativeai
```

## Configuration
1. Create a `.env` file in the project directory.
2. Add your Google API key to the `.env` file:
   ```env
   GOOGLE_API_KEY=your_api_key_here
   ```

## Usage
1. Run the application script:
   ```bash
   streamlit run app.py
   ```
   Replace `app.py` with the name of your Python script containing the provided code.

2. Access the application in your web browser.

3. Input a prompt in the designated text field.

4. Upload an image of the invoice.

5. Click the "Tell me about the invoice" button to generate a response based on the input prompt and the uploaded invoice image.

## Notes
* The project uses the Gemini Pro Vision generative model for content generation. Ensure that you have the necessary API key and permissions to use this model.

* The application provides an interactive interface for extracting information from invoices. Customize the input prompt and explore different invoice images to see the model's responses.

* Make sure to handle sensitive information, such as API keys, securely and follow best practices for secure coding.

## Potential Applications
The Multi Language Invoice Extractor project has several potential applications across various industries. Here are some of the key areas where this project can be utilized:

1. Financial Services
Invoice Processing: Automate the extraction of information from invoices, speeding up the invoice processing workflow.
Expense Management: Assist in extracting relevant details from receipts and invoices for efficient expense tracking.
2. Retail and E-Commerce
Order Processing: Streamline order processing by extracting essential details from purchase invoices.
Inventory Management: Automate inventory updates by extracting information from supplier invoices.
3. Accounting and Bookkeeping
Data Entry Automation: Reduce manual data entry efforts by automatically extracting data from invoices.
Financial Reporting: Facilitate accurate financial reporting by extracting information from financial documents.
4. Small Business Management
Invoice Tracking: Help small businesses track and manage their invoices more effectively.
Document Organization: Simplify document management by extracting and categorizing information from various documents.

## Acknowledgements
This project was inspired by Krish Naik's tutorial on Youtube. The tutorial provided valuable insights and served as a foundation for the Multi Language Invoice Extractor project.


