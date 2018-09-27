# tstamp

### python packages needed:

pdf2image, opencv, pil, poppler, numpy, pandas, pytesseract

for pytesseract use:
>conda install -c jiayi_anaconda pytesseract
 
### Manually compile tesseract: 
https://github.com/tesseract-ocr/tesseract/wiki/Compiling

(Note: pytesseract is just a wrapper executing tesseract binary!)

### Set tessdata environment variable, eg.:

>export TESSDATA_PREFIX="$HOME/tesseract/tessdata"

