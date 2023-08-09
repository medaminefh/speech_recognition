# Convert Speech to text

You need first to install:

### Windows
You can just pip install it:

```
$ pip3 install pyaudio
```

### Linux
You need to first install the dependencies:

```
$ sudo apt-get install python-pyaudio python3-pyaudio
$ pip3 install pyaudio
```

### MacOS
You need to first install portaudio, then you can just pip install it:

```
$ brew install portaudio
$ pip3 install pyaudio
```

### Create your virtual env (I'm using virtualenv):

```
$ virtualenv venv
$ source venv/bin/activate
```

### Install the deps

```
$ pip3 install -r requirements.txt
```

### Run the project 

```
$ python3 speech.py
```
