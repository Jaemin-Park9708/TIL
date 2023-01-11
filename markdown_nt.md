빽킷을 활용해서 인라인 코드 만들 수 있음

# markdown 문법 필기

## asd;jlkf



h1 → `#` → html: <h1>내용물></h1>

h2 → `##`

h3 → `###`

h4 → `####`

h5 → `#####`

h6 → `######`

`ctrl` + 숫자 → 전환 단축키



## list

### unordered list(순서가 없는 리스트)

`-` / `*` 

- ㅁㄴㅇㄹ 
  - ㅁㄴㅇㄹ
    - ㅁㅇㄴㄹ
      - ㅁㄴㅇㄹ
        - ㅁㄴㅇㄹ
          - ㅁㅇㄻㄴ
- 바꿀 수 없음

html: <ul>내용물</ul>

### ordered list(순서가 있는 리스트)

`숫자` + `.` 

1. 순서가 있는 리스트 1
2. ㅁㅇㄴ;ㅣㅏㅓㄻㄴㅇㄹ
3. ㅁ;ㅏㅣ얾ㄴ;ㅣㅇ
4. ㅇㅁㄴ;ㄹ이
   1. 4-1
      1. ㅁ;ㄴ이ㅏ러
         1. ㅁㄴ;ㅇ럼;
         2. ㅁ;ㅣ나럼;니ㅏㅇ러
         3. ㅁ;ㅏㅓㅇㄴㄹ;

html: <ol>내용물</ol>



## text style

### bold

`**` 내용물 `**`

안녕하세요 **박재민**입니다.

단축키: `ctrl` + `b` 

### italic

`*` 내용물 `*`

단축키: `ctrl` + `i`

안녕하세요 *박재민*입니다.



- bold + italic

  - 안녕하세요 ***서울 8반***입니다.

    → 앞뒤로 `*` 3개씩 쓰면 됨

## hyperlink

### link

`[텍스트](내가 가고싶은 url)`

`[`구글`]` `(`www.google.com`)`

[구글](www.google.com)

### img

`![텍스트](내가 보여주고 싶은 이미지 url)'

![아따맘마](C:\Users\SAFY\Desktop\TIL\assets\scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.png)

이미지 크기 조정이 안됨 어쩔 수 없음

## Code Block

### inlince code block

빽킷을 활용해서 인라인 코드 만들 수 있음

글1, 글2, 글3, `코드` 

#### code block

빽킷을 세번 입력하고 엔터 누르면 

```java
// C://USER/SSAFY/Desktop/intro1.java 주석
class Sample{
    public static void main(String args[]){
        System.out.pritnln("Hello Java");
    }
}
```

## Table

`| | | | |`

| 사이에 스페이스바 넣어야 함





