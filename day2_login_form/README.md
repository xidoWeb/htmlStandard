# 웹표준/접근성 day2
## 접근성 고려시 명도대비
- 배경색, 전경색에대한 명도대비  
- 4.5:1이상의 조건을 가져야 한다~!  
- 3:1이상의 조건일때에는 글씨 18pt이거나, 14pt bold조건을 갖춰야 한다!!!


## login만들기
> form 태그의 의미와, 접근성 기본내용을 참고로 작성

1. form태그에는 action, method 속성이 필요하다.
	- action: 서버언어(php, asp, jsp)연동
	- method: 보안처리 방식(get, post)
2. form내부에는 fieldset, legend 태그가 있다.
	- fieldset: 영역을 만드는것
	- legend: 영역별 제목
3. input, label 태그가 있다.
	- input에는 여러속성중 현재 로그인에 필요한 기능은 type(text, password, submit)
	- label은 접근성을 고려해야 하므로 반드시 input id속성과 연동(for)해야한다.
	- 이외에도 input에는 name, value 속성을 담아내야 한다~~











