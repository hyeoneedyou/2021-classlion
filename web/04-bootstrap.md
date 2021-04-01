## Bootstrap

- CSS/javascript 기반의 웹 프레임워크
- 오픈소스! 가져다 쓰기만 하면 됨
- 반응형 웹 지원 ( 모바일에서도 화면 자동 조정)
- 브라우저 호환성
- 하지만 성능이 다소 떨어짐

-웹 프레임워크 = 웹을 만드는 재료들의 모임

## Bootstrap 사용법

- 부트스트랩 검색 후 이동>시작하기>CDN을 head태그에 붙여넣기
- https://code.jquery.com 에 접속> 최신 버전의 uncompressed링크 클릭> 코드 복사> head 태그 맨 위에 붙여넣기

또는

- CSS CDN을 head 태그에 붙여넣기
- js CDN을 body 종료태그 바로 위에 붙여넣기

## container 사용해보기

-css>개요>콘테이너

```html
<div class="container">
  ...
</div>
```

## 버튼 바꿔보기

-css>버튼

```html
<input type="submit" class="btn btn-primary">
```

## 폼 기본예제 사용해보기

-css>폼>기본예제

```html
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">이메일 주소</label>
    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="이메일을 입력하세요">
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">암호</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="암호">
  </div>
  <div class="form-group">
    <label for="exampleInputFile">파일 업로드</label>
    <input type="file" id="exampleInputFile">
    <p class="help-block">여기에 블록레벨 도움말 예제</p>
  </div>
  <div class="checkbox">
    <label>
      <input type="checkbox"> 입력을 기억합니다
    </label>
  </div>
  <button type="submit" class="btn btn-default">제출</button>
</form>
```

## 네비게이션 사용하기

-컴포넌트>네비게이션>탭형

```html
<ul class="nav nav-tabs">
  <li role="presentation" class="active"><a href="#">Home</a></li>
  <li role="presentation"><a href="#">Profile</a></li>
  <li role="presentation"><a href="#">Messages</a></li>
</ul>
```

## 그래프 사용해보기

-컴포넌트>진행바>맥락적인 의미

```html
<div class="progress">
  <div class="progress-bar progress-bar-success" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%">
    <span class="sr-only">40% Complete (success)</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100" style="width: 20%">
    <span class="sr-only">20% Complete</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%">
    <span class="sr-only">60% Complete (warning)</span>
  </div>
</div>
<div class="progress">
  <div class="progress-bar progress-bar-danger" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%">
    <span class="sr-only">80% Complete (danger)</span>
  </div>
</div>
```

## 부트스트랩 CSS 변경할 때
- 부트스트랩의 스타일 적용 방식은 .class
- 따라서 부트스트랩보다 상위 우선 순위인 !important, #id, div.class를 이용해야 CSS를 변경할 수 있다.

## 그리드 시스템(.contatiner)
- 전체를 12개의 col로 나눈다.
- col-4, col-3, col-5면 12개를 4, 3, 5로 나눠갖는 것.
- .col-lg-4 : lg: 기준의 되는 화면의 사이즈, 4: 12등분 중 차지할 비율
![](https://images.velog.io/images/hyeoneedyou/post/674aa07a-08f9-4edc-888f-576752e42fdf/image.png)
