# datt  
  
ftp 21번  
sftp 22  
ssh  
telnet  
  
http 80번 포트사용
https 443번 사용
  
포트포워딩  
  
  
bit nibnle byte word 
inpv4 32bit  A~e class가 있다  
a class는 0~127 정부나 통신사 
b class 129~191 학교등애서 사용 
c class 192~223 일반피플들이 
d class 224~239  
e class 240~255  
a b c 만 쓸수있음 아래로는 연구기관에서 사용  
  
 
subnet mask(net mask)  
255.0.0.0  
255.255.0.0  
//.0.0  
//.0  
0= 256 개임  
  
  
사설아이피 (내부아이피(  
10점대로 시작  
172.16.0.0 ~172.31.255.255  
192.168.0.0~192.168.255.255  
  
  
프로토콜 :아이피 통일하는것  
포트로 연결  
  
  
  
파일종류  
- ,d ,b,c,l,s 로 시작  
-일반파일 
d 디렉토리 /붙음
b 블록디바이스(장치) 
c 문자디바이스  
l 링크 @붙음
s 소켓  
파이피 파일 = 붙음 ls -l | more (보는방법)
실행파일은 * 붙음  
  
rwx =권한  
소유자u그릅g다른사용자o일케 3개씩  
r = read  
w = write  
x =excute (실행)  
  
https://www.leafcats.com/138  
  
권한 +두가지  
소유권 허가권  
  
절대경로
cd  /bin 루트밑에 빈으로 이동  
cd 만 누르면 접속한게정의 홈으로 이동  
cd ~ 위랑 똑같음  
cd - 이전경로로 이동
  
.(현재위치)..(한단계위)이용해서 이동하는게 상대굥로  

  
  
> 새로만드는거임  
>> 추가  
<  
echo는 출력  
  
압축해제  
tar xvfz 소스파일명.tar.gz  
tar xvfj          .tar.bz2  
  
configure 환경설정  
make 콤파일  
make install 설치  
mysql.sh 만들고 chmod 755 mysql.sb
