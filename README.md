# Table_Data_Extraction

# Step 1: Install tesseract ocr in windows 
# Step 2: set environment 
- search 'Edit the system environment variables'>Environment Variables...> under system variable click on path and click on edit > add new> and paste the path
- path can be found out at c:\programfiles\tesseract ocr.
 
Now
# (*)create a new environment in anaconda:
1.  pip install opencv-contrib-python
2.  pip install pytesseract 
3.  pip install pillow
4.  pip install matplotlib

- Run the ocr.ipynb in jupyter to detect and extract the table data
- for only table data detection you can run data_extraction_using_opencv.ipynb using opencv
