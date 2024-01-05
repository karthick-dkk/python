
**#Install Requirements for Compile** 
yum install gcc openssl-devel bzip2-devel libffi-devel

**Download Python form source code**
Downlaod Link: https://www.python.org/ftp/python/3.12.1/Python-3.12.1.tgz
```
cd /opt/ && wget https://www.python.org/ftp/python/3.12.1/Python-3.12.1.tgz
Extract: tar xzf Python-3.7.4.tgz
```
**Compile:**
```
cd Python-3.7.4
./configure --enable-optimizations
make altinstall
```
**Execute Python**

/opt/Python-3.7.4/python3.7 --version
/opt/Python-3.7.4//pip3.7 --version

**Link python to system command**
```
ln -s /opt/Python-3.7.4/python3.7 /bin/python3
python3 --version
ln -s /opt/Python-3.7.4/python3.7/pip3.7 /bin/pip3
```
**Check Python version**
```
pip3 --version
pip3 install boto3
```

