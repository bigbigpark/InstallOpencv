# How to opencv
<br/>
OS: Ubuntu 20.04 Focal
Package: OpenCV 3.4.5
<br/>
## 1. Remove pre-installed opencv
두번째 명령어 실행시 관련된 다른 패키지도영향을 받을 수 있음
i.e. 
~~~bash
$ sudo apt purge libopencv* python3-opencv
$ sudo apt autoremove -y
~~~
