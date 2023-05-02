# Convert-PDF-to-DOCX
convert pdf to docx python

from pdf2docx import Converter
obj = Converter('karun.pdf')
obj.convert('karun.docx')
obj.close()
