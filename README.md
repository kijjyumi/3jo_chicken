# 1. 프로젝트 명 :오늘은 치킨이 닭!🍗🍗🍗🍗🍗
# 2. 프로젝트 소개
저희 프로젝트는 치킨리뷰를 남기고, 브랜드별로 리뷰를 볼 수 있는 페이지입니다. 
# 3. 와이어프레임
1. 로그인 

![로그인 페이지](https://user-images.githubusercontent.com/107826749/174544262-15747c66-6524-4641-ad4f-51d4cef56436.JPG)

2. 회원가입

![회원가입 페이지](https://user-images.githubusercontent.com/107826749/174544433-ca2e27e2-0265-4b80-90d7-c49eeaf4ab0e.JPG)

4. 치킨리뷰 작성

![리뷰 작성 페이지](https://user-images.githubusercontent.com/107826749/174544398-16f4d168-b0ab-4ec2-bfab-99069fb51f80.JPG)

6. 리뷰 보여주기

![리뷰 페이지](https://user-images.githubusercontent.com/107826749/174544418-12168148-9e78-4090-99f9-c692dac864c7.JPG)

# 4. 개발해야 할 기능들

 |기능|method|url|request|respeonse|
|------|------|--------|-------------------|-------------|
|로그인|POST|/login|{'id':id,'pw':pw,}||
|회원가입|POST|/signup|{'id':id,"pw':pw,'birth':birth}|가입완료 메시지|
|보여주기|GET|/review|{{'image':image,<br>'star':star,<br>'name':name.<br>'brand':brand,<br>'comment':comment}||
|작성하기|POST|/review|{'image':image,<br>'star':star,<br>'name':name.<br>'brand':brand,<br>'comment':comment}||
# 5. public github repo 주소

https://github.com/kijjyumi/3jo_chicken/blob/main/README.md
