![image](https://github.com/user-attachments/assets/8395fdf7-c6d5-48eb-9967-e5a45361c93c)


html to pdf converter v4

a gui tool for converting .html files to .pdf format using either:
- raw text extraction (reportlab)
- pretty conversion via wkhtmltopdf (pdfkit)

features:
- drag & drop or directory scan for html input
- scan entire directory and process all the html files in it
- select separate or single merged pdf output
- supports wkhtmltopdf auto-detection and manual config
- dark-themed customtkinter interface
- progress feedback and error handling

requirements:
- python 3.x
- customtkinter
- tkinterdnd2
- pdfkit
- wkhtmltopdf (optional for pretty mode)
- bs4, reportlab, pypdf

run with:
python htmlizer.py

