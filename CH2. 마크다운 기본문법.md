# CH2. 마크다운 기본문법

<br>  
<br>  

```
# 제목(Header)

# 제목 H1
## 제목 H2
### 제목 H3
#### 제목 H4
##### 제목 H5
###### 제목 H6

---
   
# 문장   

마크다운은 기본문법만 알고있다면 일반 텍스트편집기에서도 손쉽게 작성이 가능한 마크업언어다.  
현재 다양한 도구와 플랫폼에서 지원하고 있기 때문에 더욱 손쉽게 스타일적용된 문서를 작성할 수 있어 점점 널리 사용되고 있다.   

---

# 줄바꿈(Line Break)
줄바꿈 처리1 - 띄워쓰기 두번을 하면 줄바꿈 처리가 됩니다.  
줄바꿈 처리2 - <br /> 태그를 사용해서 줄바꿈 처리를 할수도 있습니다.  

---   

# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

--- 
# 목록  

1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록  

- 순서가 필요없는 목록
- 순서가 필요없는 목록
- 순서가 필요없는 목록

* 빨강
  * 녹색
    * 파랑  

* 1단계
  - 2단계
    + 3단계
      + 4단계  

---  
# 링크(Links)  

<a href="https://google.com">Google</a>   
[Google](https://google.com)   
   
<a href="https://naver.com">naver</a>   
[naver](https://naver.com, "Naver Link")  
<a href="https://naver.com" title="네이버로 이동" target="_blank">naver</a> 

--- 

# 이미지(Image)   

![Placeholder Image](https://picsum.photos/300/200)   
   
[![Placeholder Image](https://picsum.photos/300/200)](https://picsum.photos/)  

--- 

# 인용문(Image)  

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.   
> (네이버 국어 사전)
>> 중첩된 인용문1
>>> 중첩된 인용문2

--- 

# 인라인(Inline) 코드  강조

CSS에서 `background` 혹은   
`backgrpound-image` 속성으로 요소에 배경  
이미지를 삽입할 수 있습니다.  

--- 

# 블록(Block) 코드  강조
   
```html  
<a href="https://google.com">Google</a>   
``` 

<br>  

```css  
.box{
  position: absolute;
  top: 40px;
}  
``` 

<br>  

```javascript  
function func(){
  let a = 'AAA';
  return a;
}
``` 
<br>  

```bash  
$ git commit -m 'Study Markdown'
``` 

<br>  

```plaintext  
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세 
``` 

<br>  

```bash 

# 표(Table)
  
position 속성
  
값 | 의미 | 기본값
--|--|--
static | 배치기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모요소 | X
fixed | 뷰포트 기준 | X
   
값 | 의미 | 기본값
--|:--:|--:
static | 배치기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모요소 | X
fixed | 뷰포트 기준 | X

---  

# 원시 HTML(Row HTML)
  
동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세

--- 

# 수평선(hr)
  
--- 
*** 

```