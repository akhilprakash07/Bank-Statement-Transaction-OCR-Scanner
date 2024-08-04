**Bank-Statement-Transaction-OCR-Scanner**
**PDFPlumber**
"pdfplumber" is a Python library for extracting text, tables, and metadata from PDF files and not an OCR library. It provides a simple interface for working with PDF content, including the ability to extract text and tables in a structured format.

**Instructions:**
1.Prepare Your PDF File:
2.Ensure you have a PDF file that you want to process. Place this file in an accessible directory.
3.Create or Update the Python Script:
Create a Python script and add the code to extract tables from the PDF. The code should include:
-Opening the PDF file.
-Extracting tables from each page.
-Saving the extracted tables to an csv file.
-Make sure to replace placeholder file paths with the actual paths to your PDF and output files.
5.Update File Paths:
-Set the path to your PDF file in the script.
-Specify the path where you want to save the Excel file.
-Run the Script:


**Additional Library Experience:**
I tested two OCR libraries, Tesseract and DOCTR, to extract text from PDFs.

**Tesseract:** This library was able to extract text from the PDF, but the output was raw and not structured in tabular form. I attempted to use regular expressions to format the text and extract information, such as dates, but was not successful in retrieving the information effectively.

**DOCTR:** This library also extracted text, but it did not process the content in a meaningful way, particularly in terms of maintaining tabular structure.

Given these challenges, I then used PDFPlumber. Although PDFPlumber is not an OCR library, it effectively extracted tabular data from the PDF, correctly preserving the structure of the tables.
For reference, I have uploaded the Tesseract and DOCTR Python files and their respective output files. These examples illustrate the challenges faced with text extraction and highlight how PDFPlumber addressed the issue by accurately handling tabular data.
