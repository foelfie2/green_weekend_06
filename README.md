# green_weekend_06
HTML.CSS,js기초 주말반
## HTML
> HTML : Hyper Text Markup Language - 마크업(표시) 언어
> 
> 웹페이지의 구조를 표시
> 
> 웹페이지의 콘텐츠를 표시

### HTML Elements

>Element: 요소-의미적
>
>Tag: 태그- 기술적

>문법(Syntax)
>
><>로 감싸줌
>
>소문자 사용
>
>시작태그와 종료태그 세트로 구성됨.
```
<tagname><contents></tagname>
```

>예외) 시작태그만 존재하는 경우: 빈 요소(Empty Element)

>포함관계(Nested)
```
<body>
  <div>
    test
  </div>
</body>
```

### HTML Attribute

>HTML 속성

>HTML 요소의 부가 정보

>속성name="속성value" 속성이름="속성값" 
```
<a href="http://www.naver.com">naver</a>
```

### 제목 태그
>heading->h

>h1~h5

>h1 가장 큰 제목

### HTML 기본 구조
```
<!DOCTYPE html> -1
<html> -2
<head> -3
    <meta charset="UTF-8"> -4
    <title>TEST PAGE</title> -5
</head>
<body> -6

    <p>This is a test page.</p>

</body>
</html>
```

1. 웹 문서의 버전: HTML5
2. html문서의 가장 바깥쪽 요소
3. 웹 문서를 설명하는 정보가 담기는 영역 요소
4. 웹 문서의 정보를 표시하는 요소
5. 웹문서의 제목을 표시하는 요소
6. 웹문서의 콘텐츠 요소들이 담기는 영역 요소

### 단락 태그
>단락을 표시

><p>(Paragraph): 단락을 표시
>
>
>단락과 단락사이를 구분하는 수평선
```
<hr> - Horizontal Rule
```
>단락을 구분하지 않고 줄 바꿈
```
<br> - Break
```

### 목록태그

> 순서없는 목록 ul(Unordered List)

> 순서있는 목록 ol(Ordered List)

> 목록 항목List(list item)

```
<ul>
  <li>html</li>
  <li>css</li>
 </ul> 
 
 <ol>
  <li>html</li>
  <li>css</li>
 </ol> 
 ```
> 설명목록(description List) - dl
```
<dl>
  <dt>html</dt> (dt: description)
  <dd>표준 마크업 언어</dd>
</dl>

```
