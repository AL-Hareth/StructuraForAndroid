# StructuraForAndroid

## Installing
First of all you need to install termux(terminal emulator) from the link:
[Termux](https://play.google.com/store/apps/details?id=com.termux&hl=en&gl=US)

Now launch termux and follow these commands:

-Installing Git

`pkg install git`


-Installing python

`pkg install python`


-Installing the project

`git clone https://github.com/AL-Hareth/StructuraForAndroid.git`

Now the project is installed on your machine

--Installing python libraries

`pip install -r requirements.txt`


--Installing Pillow
```
pip install wheel
pkg install libjpeg-turbo
LDFLAGS="-L/system/lib/" CFLAGS="-I/data/data/com.termux/files/usr/include/" pip install Pillow
```

## Running
Now you need to enter the project folder

`cd StructuraForAndroid`

run the app

`python structura.py`

Now put this data in the app

```git
Path to your structure: <path including the .mcstructure file>
Insert your pack name: <the name of the resource pack>
```

Now you have the mcpack file in the same folder you are in and you can move it to the resource_packs folder
