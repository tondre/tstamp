# tstamp

### python packages:

>conda install -c jiayi_anaconda pytesseract
>pip install pdf2image
>conda install opencv
>conda install poppler

### Manually compile tesseract: 
https://github.com/tesseract-ocr/tesseract/wiki/Compiling
(Note: pytesseract is just a wrapper executing tesseract binary!)

### Set tessdata environment variable, eg.:

>export TESSDATA_PREFIX="$HOME/tesseract/tessdata"

