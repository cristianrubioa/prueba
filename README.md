# Pyhon Naoqi Installation Guide For Mac

<div align="left">

<a href="https://www.python.org/downloads/"><img alt="Python 2.7+" src="https://img.shields.io/badge/python-2.7+-yellow.svg" /></a>


## Naoqi for Python

1. You can download the SDK from SoftBank Robotics Community website. https://sso.aldebaran-robotics.com/pf/adapter2adapter.ping?TargetResource=https%3A%2F%2Fcommunity.ald.softbankrobotics.com%2Fen%2Fresources%2Fsoftware%2Flanguage%2Fen-gb

2. Add environment variables:

```
$ export PYTHONPATH=${PYTHONPATH}:/path/to/python-sdk
$ export DYLD_LIBRARY_PATH=${DYLD_LIBRARY_PATH}:/path/to/python-sdk
```

3. Run the following command on your terminal:

``` 
$ open ~/.bash_profile 
```

4. To make it use globally, copy the commands from Step-2 and paste it in .bash_profile, for example: 

```
$ export PYTHONPATH=${PHTHONPATH}:/Users/admin/Documents/pynaoqi/lib/python2.7/site-packages
$ export DYLD_LIBRARY_PATH=${DYLD_LIBRARY_PATH}:/Users/admin/Documents/pynaoqi/lib
```


5. Save the file and close the editor .bash_profile.

6. Force the execution of the .bash_profile file to see the changes immediately without having to restart.

``` 
$ source ~/.bash_profile 
```
