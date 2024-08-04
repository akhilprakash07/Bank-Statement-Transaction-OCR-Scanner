**Bank-Statement-Transaction-OCR-Scanner** <br />
**PDFPlumber** <br />
"pdfplumber" is a Python library for extracting text, tables, and metadata from PDF files and not an OCR library. It provides a simple interface for working with PDF content, including the ability to extract text and tables in a structured format.

**Instructions:** <br />
**1**.Prepare Your PDF File: <br />
**2**.Ensure you have a PDF file that you want to process. Place this file in an accessible directory. <br />
**3**.Create or Update the Python Script: <br />
 Create a Python script and add the code to extract tables from the PDF. The code should include: <br />
   -Opening the PDF file. <br />
   -Extracting tables from each page. <br />
   -Saving the extracted tables to an csv file. <br />
   -Make sure to replace placeholder file paths with the actual paths to your PDF and output files. <br />
**4**.Update File Paths: <br />
   -Set the path to your PDF file in the script. <br />
   -Specify the path where you want to save the Excel file. <br />
   -Run the Script: <br />


**Additional Library Experience:**<br />
I tested two OCR libraries, Tesseract and DOCTR, to extract text from PDFs.<br />

**Tesseract:** This library was able to extract text from the PDF, but the output was raw and not structured in tabular form. I attempted to use regular expressions to format the text and extract information, such as dates, but was not successful in retrieving the information effectively.<br />

**DOCTR:** This library also extracted text, but it did not process the content in a meaningful way, particularly in terms of maintaining tabular structure.<br />

Given these challenges, I then used PDFPlumber. Although PDFPlumber is not an OCR library, it effectively extracted tabular data from the PDF, correctly preserving the structure of the tables.<br />
For reference, I have uploaded the Tesseract and DOCTR Python files and their respective output files. These examples illustrate the challenges faced with text extraction and highlight how PDFPlumber addressed the issue by accurately handling tabular data.<br />
