#tar
tar, tar.gz를 압축하거나 풀어야 할 때 사용하는 명령어
<br><br>
*예제의 압축된 파일명은 abc, 압축할 폴더명은 cab
##tar
###압축
$ tar -cvf abc.tar cab
###압축풀기
$ tar -xvf abc.tar
<br><br>
##tar.gz
###압축
$ tar -zcvf abc.tar.gz cab
###압축풀기
$ tar -zxvf abc.tar.gz

## Tip! 옵션특징
-c : 파일을 tar로 묶음
-p : 파일권한을 저장
-v : 압축의 과정을화면으로 출력
-f : 파일 이름을 지정
-C : 경로를 지정
-x : tar 압축을 풂
-z : gzip으로 압축및 풀기
