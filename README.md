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
 >포함관계로 되어있는 목록
> 설명목록(description List) - dl
```
<dl>
  <dt>html</dt> (dt: description title)
  <dd>표준 마크업 언어</dd> (description data)
</dl>

```
### HTML Hyper link
>하이퍼링크 a(anchor)

>attribute(속성): href(hypertext reference): 연결되는 웹문서의 URL
<a href="http://www.naver.com">naver</a>
```
>북마크 기능
>외부 페이지 연결이 아닌 같은 페이지에서 특정위치로 이동할 수 있게 해주는 기능
>도착지점에 id attribute를 사용하여 이름을 지정
```
<a href="#t1"></a>
```
<h2 id="t1">제목</h2>
```

###Table Element
https://www.tablesgenerator.com/

>기본사용태그: table, thead,tbody,tr,th,td

>열 제목: thead(table head), th(table heading

>표 내용:tbody(table body), td(table data)

>행:tr(table row)

### Image element
> Tag:img

> Attribute: src(image 위취,파일명),alt(대체텍스트)

`:backtick
```
<img src="image.jpg" alt="대체텍스트">
```

###video Element
>비디오 및 오디오 콘탠츠는 용량이 크기떄문에 서버에 저장을 해서 제공하면 많은 트래픽이 발생한다.

>트래픽 과부하를 해결하기 위해서 유튜브서비스를 사용하기도 함
>attribute

>controls:컨트롤 버튼 표시

>autoplay:자동재생(*muted와 같이 사용해도 됨)

>muted:음소거

>loop:반복재생

##Youtube (유튜브 파라미터)
>비디오 컨텐프 제공시 트래픽 과부하를 해결하기 위해서 유튜브서비스를 사용하기도 함

>매개변수

>controls=1,0

>auto[lay=1,0(mute와 같이 사용)

>mute=1,0

>loop=1,0(playlist와 같이 사용)

>텍스트는 html문서에 직접 입력되는 콘텐츠

>이미지와 동영상, 오디오 콘텐츠는 외부에서 만들어지는 콘텐츠

>이미지,동영상,오디오는 직접 입력하는 것이 아니고 외부 파일을 삽입 =>임베드(embed) 콘텐츠


vimeo.com (유료지만 고화질)



###개발자 도구보기

F12 클릭->상단화살표->파란색영역으로 마우스 이동 소스 확인



###
웹 포토샵:https://www.photopea.com/

###container

웹사이트 템플릿 디자인
https://freebiesbug.com/psd-freebies/minimo-minimal-blog-template/

###Container Element(단순 영역 구분 요소)

div(division)

span
Block, Inline

모든 element는 각각의 고유 영역을 가지고 있음

block element, Inline Element 구분은 이들 영역의 화면 표시 방식에 따른 구분

block element는 줄바꿈 되어 표시 - block element 영역의 가로 너비가 부모요소에 100% 채워짐 (** 포함하는 요소 : 부모요소, 포함되는 요소 : 자식요소)

block element에는 위,아래 여백을 적용할 수 있음

inline element는 같은 줄에 나란히 표시 - inline element 영역의 가로 너비가 콘텐츠 크기만큼만 정해짐

inline element는 위,아래 여백을 적용할 수 없음
Parent Element(부모요소), Child Element(자식요소)

포함관계에서 포함하는 요소가 부모요소, 포함되는 요소가 자식요소

직계 포함관계에서만 부모요소, 자식요소

직계가 아닌 포함관계에서는 조상요소(Ancestor), 자손요소(decendant)
CSS

CSS 기본 개념

선택자는 스타일을 지정할 HTML 요소를 가리킵니다.
선언 블록에는 세미콜론으로 구분 된 하나 이상의 선언이 포함됩니다.
각 선언에는 콜론으로 구분된 CSS 속성(Property)이름과 값(value)이 포함됩니다.
여러 CSS 선언은 세미콜론으로 구분하고 선언 블록은 중괄호로 묶습니다.
id, class

HTML element에 특정 이름을 사용할 때 id, class attribute를 사용해서 이름을 붙여줄수 있음.

id는 동일한 이름이 사용된 HTML element가 여러개이면 논리적 오류가 발생

id는 HTML 문서내에서 고유해야함

class는 동일한 이름이 여러 개의 element에 사용되어서 공통 디자인 요소나 공통 기능을 적용할 수 있음

id는 주로 서버에서 불러오는 데이터를 표시하는 위치에 고유하게 사용 => 백엔드 개발에서 주로 사용

class는 주로 css 스타일 적용, javascript 인터랙션 적용할때 사용 => 프론트엔드 개발에서 주로 사용

id는 하나의 HTML Element에 대해서 하나의 이름만 존재, HTML 문서내에서 고유해야 함

class는 하나의 HTML Element에 대해서 여러개의 이름을 지정할 수 있고, HTML 문서내에서 여러 곳에서 공통 사용 가능함
CSS 작성방법

External CSS : 파일 분리

Internal CSS : 같은 HTML 문서내에 head 태그 영역에 style 태그를 사용하여 입력

Inline CSS : 시작태그에 style attribute를 사용해서 입력 => javascript에서 css를 제어할때 사용
naming할 때 표기방식

id/class naming, 변수/함수/클래스 naming, 파일/폴더 naming의 경우 가독성을 높이기 위해 사용

표기방식을 사용하는 이유

naming할 때 두단어 이상으로 구성되는 경우 단어와 단어 사이를 구분하기 위해 사용

단어의 시작부분에 첫글자를 대문자로 변경, 특수기호를 사용

표기방식 종류

snake case : gnb_depth1 => 파일/폴더

kebab case : gnb-depth1 => id/class

camel case : gnbDepth1 => javascipt의 변수/함수

Pascal case : GnbDepth1 => javascript의 클래스
OOCSS(Object Oriented CSS)

HTML Element를 대상화시키는 과정에서 Element 하나하나를 모두 객체화 시키는 이론

HTML Element 모두 각각 id,class attibute를 사용해서 이름을 지정해줌
web color

color mode

가산혼합(빛의혼합) : RGB 컬러모드
표현할 수 있는 색의 개수

1byte = 8bit = 256개(0~255)

RGB => 3byte => 24bit 트루컬러 : 16777216가지 색
색 표현 코드값

16진수(hex code) : #AABA01

10진수 : (255, 255, 255)


