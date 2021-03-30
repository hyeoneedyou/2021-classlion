## HTML(Hyper Text Markup Language)

- 이해가 쉬움, 정현화된 문법, 쓰이는 문법만 맨날 쓰임
- Hyper Text = Link, Markup Language = 컴퓨터가 알아들을 수 있는 언어
- HTML 코드
    1. 글
    2. 태그(글을 감싸는 틀)
    3. 속성(틀에 붙는 부가설명)
대원칙! HTML로 꾸미려 들지 말자. HTML은 꾸미는 언어가 아니다. 꾸미는 언어는 CSS.

확장-live server 설치

## HTML 코드

- “이거 HTML 문서야~”를 알려주는태그
    ```
    <!DOCTYPE html><html>~</html>
    ```

- 직접 화면에 등장하진 않지만 이문서를 설명하는 태그
  ```
  <head>~</head>
  ```

- 직접적으로 화면에 등장하는, 문서에보이는 태그

  ```
  <body>~</body>
  ```

⇒ 단축키: ! + tab

## form 태그

-사용자로부터 정보를 입력받고 그 값을 프로그램으로 넘겨준다.

```html
<form action="전송받을 대상">
	아이디 : <input type="text" name="myid"> # name으로 이 값을 인식해라!
	비밀번호 : <input type="password" name="mypw"> # type이 password면 텍스트 숨겨짐
	<input type="submit">

</form>
```

## select  태그

```html
<select>
	<option value="goodday">좋은날</option> # value로 이 값을 인식해라!
	<option value="sadday">슬픈날</option>
	<option value="soso">그저그런날</option>
</select>
```

## ol, li, a 태그

⇒단축키:ul>li*5 + tab (*뒤의 개수만큼 리스트가 만들어짐)

```html
<ol>
	<li><a href="1.html">유년기</a></li>
  <li><a href="2.html">질풍노도의 시기</a></li>
  <li><a href="3.html">방황기</a></li>
  <li><a href="4.html">지금</a></li>
</ol>
```

우클릭-페이지소스보기: html코드 확인 가능

F12길게 : 개발자도구