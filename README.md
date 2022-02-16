# tx2ds
txconverter is a tx16wx sampler conversion tool for the decent sampler format

![img](http://https://github.com/eodowd/tx2ds/blob/main/screenshot.PNG)


# requirements
```bash
pip install git+git://github.com/widdershin/flask-desktop.git
```
```bash
pip install pyinstaller (opptional)
```
# Creating an exe 
```bash
pyinstaller -w -F --add-data "templates;templates" --add-data "static;static" --icon=static/icon.ico --name=txconverter main.py
```
