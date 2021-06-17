# HTML 기본 문서 구조
## Tag 법칙
1. `<` 와 `>`를 이용해 구분한다.
2. 소문자로 쓴다.
3. 여는 태그와 닫는 태그를 정확히 입력한다.<br />
ex) 
```html
<h1>HTML 공부</h1>
```
4. 적당히 들여쓰자!<br />
ex)
```html
<ul>
  <li>메뉴1</li>
  <li>메뉴2</li>
</ul>
```
5. 속성과 함께 사용할 수 있다.
```html
<태그 속성="속성 값" 속성="속성 값" ...>
```

6. 포함 관계를 명확히 하자.
- 한 태그 안에 다른 태그를 포함시킬 수 있다.
- 여는 태그와 닫는 태그 쌍을 정확히 맞추자!

## Tag 설명
### `<!doctype>` - 문서 유형을 지정하는 선언문
> 이제부터 처리할 문서는 HTML 문서이고 어떤 유형을 사용했으니 그 버전에 맞는 방법으로 해석하라.

### `<html>` - 웹 문서 시작을 알리는 태그
> 문서 유형을 선언한 후 실제 문서 정보와 내용이 시작되는 끝나는 것을 표시
<br/> `lang`이라는 속성을 사용해 사용할 언어 지정 가능

#### 주요 국가별 언어 코드
<table>
  <tr>
    <th>코드</th>
    <th>de</th>
    <th>en</th>
    <th>fr</th>
    <th>ja</th>
    <th>ko</th>
    <th>zh</th>
  </tr>
  <tr>
    <td><b>언어</b></td>
    <td>독일어</td>
    <td>영어</td>
    <td>프랑스어</td>
    <td>일본어</td>
    <td>한국어</td>
    <td>중국어</td>
  </tr>
</table>

### `<head>` - 브라우저에게 정보를 주는 태그
> 웹 브라우저 화면에는 보이지 않지만 웹 브라우저가 알아야 하는 정보들을 입력한다.

1. `<title>` : 문서 제목
- 웹 브라우저의 제목 표시줄에 표시되는 제목
```html
<title>문서 제목</tltle>
```

### `<meta>` - 문자 세트를 비롯한 문서 정보
> 웹 브라우저 화면에는 보이지 않지만 웹 문서와 관련된 정보들을 지정한다.

1. 문자 세트 지정
```html
<meta charset="UTF-8">
```
2. 모바일 기기 고려
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
3. 인터넷 익스플로러 브라우저 고려
```html
<meta http-equiv="X-UA-Compatible" content="ie=edge">
```
4. 검색 엔진 고려
```html
<meta name="keywords" content="html 기본"> // 해당 문서의 키워드
<meta name="description" content="210617 공부한 것"> // 해당 문서의 설명
<meta name="author" content="Yeonlisa"> // 해당 문서의 소유자 또는 제작자
```

### `<body>` - 실제 브라우저에 표시될 내용
> 실제 브라우저에 표시될 내용을 입력한다.



