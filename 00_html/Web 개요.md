# Web

1. Web의미 

   인테넷에 연결된, 컴퓨터들을 통해, 사람들이 정보를 공유할 수 있는 정보 공간

2. Web Service

   브라우저가 서버한테 응답을 받아서 받은 특정 문서를 우리가 보기 편하게 만들어주는 것

3. get, post

   get요청 = 주세요! 라고하는 요청(달라고하는 것)

   post -> 문서 처리하달라고 하는 것

   - user --- request --> computer(Program) -- response (우리는 프로그램을 개발한다.)
   - 우리는 서버 컴퓨터에서 요청과 응답을 처리할 프로그램을 개발

### Static Web

https://www.google.com/  -> 멀티캠퍼스

172.217.27.78 ->IP주소(멀티캠퍼스 주소)

google.com이 남의 주소 -> 남의 컴퓨터주소/dir1/dic2/../

![1564537904920](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1564537904920.png)

URL : 네트웨크 상의 특정 서버컴퓨터가 가지고 잇는 특정 위치까지 가리키는 것

브라우저를 통해 특정 리소스까지 url로 접근 가능

- static web = 잘 만들어놓은 html 문서 (매번 같은 문서로 응답하는 것) ex. 사전							(매번 가공할 필요없이 똑같은 페이지만 저장되어있는 것을 보여주는 것)
- https://hphk/lectures/1 => 해피해킹이라는 곳 내에 lectures라는 리소스 내에 1번째 문서



## URL

```
1. url - jpg(파일)을 특정지어서 그 곳을 가지러가는 것 
	   -> 네트워크 상에서 자원이 어디에 있는지를 알려주기 위한 고유 규약(파일 식별자)

2. uri - 우리가 구글에 파이썬을 검색했을 때, 검색 결과(매번 변화)
	   -> 검색 결과는 매번 다를 수 있음.(통합자원 식별자)
	  
ex. www.google.com/logo.jpg -> 구글 로고 사진 (url, static web)
	www.google.com/search?q=파이썬 -> 파이썬 검색 결과 창 보여줌 (uri)
	     * dynamic web : 재가공해서 우리에게 보여줌
	결과 : html 문서
```

