# Multilingual OCR using Tesseract

With this Python code you can extract text from scanned PDF documents, even entire books, in any language [Google’s Tesseract-OCR Engine](https://github.com/tesseract-ocr/tesseract) supports, even if the text is in multiple languages.

The code uses:  
- PyMuPDF to inspect and extract the images from a scanned PDF file.
- PIL, cv2 to preprocess the images.
- PyTesseract (Python wrapper for Tesseract) to extract text from the extracted images.

My tests were for Greek mixed with English texts.  

The code has some image preprocessing part for better OCR results.  
It also has some Greek text processing, as Tesseract seems to prefer older intonated characters in Greek.  

It is not a perfect solution, but it's completely free.  
Please feel free to test, change the code, and have fun.  