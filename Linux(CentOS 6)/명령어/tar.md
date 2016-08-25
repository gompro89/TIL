#tar
tar, tar.gz를 압축하거나 풀어야 할 때 사용하는 명령어
<br><br>

##1. tar
###### *예제의 압축된 파일명은 abc, 압축할 폴더명은 cab
<br>
###압축
~~~~
$ tar -cvf abc.tar cab
~~~~
###압축풀기
~~~~
$ tar -xvf abc.tar
~~~~
<br>
##2. tar.gz
###압축
~~~~
$ tar -zcvf abc.tar.gz cab
~~~~
###압축풀기
~~~~
$ tar -zxvf abc.tar.gz
~~~~
## Tip! 옵션특징
-c : 파일을 tar로 묶음<br>
-p : 파일권한을 저장<br>
-v : 압축의 과정을화면으로 출력<br>
-f : 파일 이름을 지정<br>
-C : 경로를 지정<br>
-x : tar 압축을 풂<br>
-z : gzip으로 압축및 풀기<br>
