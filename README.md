# tesseract ocr

Download and install tesseract ocr.

https://tesseract-ocr.github.io/tessdoc/Installation.html


Then, modify the tesseract path in [`config.ini`](config.ini) 

# Initialization
On windows,

```
python -m venv venv
venv\Scripts\activate
```


On Linux,
```
python -m venv venv
source venv\bin\activate
```

After activate venv, then
```
pip install -r req.txt
git clone https://github.com/zzzDavid/ICDAR-2019-SROIE.git
```

# Usage

See the file [`make_prediction.ipynb`](make_prediction.ipynb)


# Reference

https://github.com/spro/practical-pytorch/tree/master/seq2seq-translation
