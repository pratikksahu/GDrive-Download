# GDrive-Download
[Reference](https://developers.google.com/drive/api/v3/quickstart/python)

* Run in background
```bash
nohup python -u GD -f [filename] -s [sleepTime][Optionale] > output.log
```
* Change download folder
```python
folderID = '1SZ4a2j_rpHKTCSed8PSK7D5uopXUBasd' #Replace this with your own folder
```
* Change retry wait time
```python
sleep(100) #Replace this with your own time (in seconds)
```
