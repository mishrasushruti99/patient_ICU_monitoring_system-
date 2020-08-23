# Installation
Prerequisits: Yarn, Cython
```
# For frontend
$ git clone https://github.com/ankitpriyarup/Patient-Monitoring-System
$ cd Patient-Monitoring-System
$ yarn install

# For backend open another terminal
$ cd Patient-Monitoring-System/flask-server
$ virtualenv -p python3 .
$ source bin/activate
$ pip3 install -r requirements.txt
$ cd rest-api
$ pip3 install -e .
$ cd CliNER
$ pip3 install -r requirements.txt

# First run backend using following at /flask-server/rest-api
$ python3 app.py

# Later run frontend using following at /.
$ yarn dev
```