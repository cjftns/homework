# 마크다운 문법

<br>

## <헤더>

- #의 개수로 제목 크기 조절(H1~H6)
- #이 늘어날 수록 작아짐

<br>마크다운

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

<br>미리보기

# H1

## H2

### H3

#### H4

##### H5

###### H6

<br><br>

## <수평선>

- 기호 \*, -, \_ 중 한 종류만 3개 이상 작성

<br>마크다운

```
* * * * *
---
- - - - -
____
```

<br>미리보기

---

---

---

---

<br><br>

## <줄바꿈>

- 텍스트 중간에 &lt;br&gt;을 입력

<br>마크다운

```
동해물과 백두산이 마르고 닳도록<br>하느님이 보우하사 우리나라 만세<br>무궁화 삼천리 화려 강산<br>대한 사람 대한으로 길이 보전하세
```

<br>미리보기

동해물과 백두산이 마르고 닳도록<br>하느님이 보우하사 우리나라 만세<br>무궁화 삼천리 화려 강산<br>대한 사람 대한으로 길이 보전하세

<br><br>

## <강조문>

- 이탤릭체 : \* 또는 \_로 감싸기
- 볼드체 : \*\* 또는 \_\_로 감싸기
- 취소선 : ~~로 감싸기
- 밑줄 : &lt;u&gt;, &lt;/u&gt;로 감싸기

<br>마크다운

```
*이탤릭체*
_이탤릭체_
**볼드체**
__볼드체__
~~취소선~~
***이탤릭체+볼드체***
___이탤릭체+볼드체___
*~~이탤릭체+취소선~~*
**~~볼드체+취소선~~**
<u>밑줄</u>
```

<br>미리보기

_이탤릭체_<br>
_이탤릭체_<br>
**볼드체**<br>
**볼드체**<br>
~~취소선~~<br>
**_이탤릭체+볼드체_**<br>
**_이탤릭체+볼드체_**<br>
_~~이탤릭체+취소선~~_<br>
**~~볼드체+취소선~~**<br>
<u>밑줄</u>

<br><br>

## <인용문>

- &gt;로 시작하는 텍스트

<br>마크다운

```
> 인용문1
>> 인용문2
>>> 인용문3
>>>> 인용문4
>>>>> 인용문5
```

<br>미리보기

> 인용문1
>
> > 인용문2
> >
> > > 인용문3
> > >
> > > > 인용문4
> > > >
> > > > > 인용문5

<br><br>

## <목록>

### 순서가 없는 목록

- \*, +, - 를 이용
- 들여쓰기 하면 모양 바뀜

<br>마크다운

```
* 월
+ 화
  - 수
  * 목
    + 금
      - 토
        * 일
```

<br>미리보기

- 월

* 화
  - 수
  * 목
    - 금
      - 토
        - 일

<br><br>

### 순서가 있는 목록

- 숫자를 기입
- 어떤 숫자를 입력하든 상관 없이 순서대로 번호를 매김
- 들여쓰기 하면 모양 바뀜

<br>마크다운

```
1. 1번 기입
2. 2번 기입
4. 4번 기입
6. 6번 기입
```

<br>미리보기

1. 1번 기입
2. 2번 기입
3. 4번 기입
4. 6번 기입

<br><br>

- 리스트 안 리스트를 사용하려면 탭과 함께 1번부터 나열해야 적용 가능

<br>마크다운

```
1. 1번
   1. 1-1번
2. 2번
3. 3번
   1. 3-1번
   2. 3-2번
      1. 3-2-1번
```

<br>미리보기

1. 1번
   1. 1-1번
2. 2번
3. 3번
   1. 3-1번
   2. 3-2번
      1. 3-2-1번

<br><br>

- 두 리스트 종류를 혼합해서 사용 가능

<br>마크다운

```
1. 음료
   * 콜라
   * 사이다
2. 패스트푸드
   - 햄버거
      - 맘스터치
    - 피자
        1. 도미노
        2. 미스터
```

<br>미리보기

1. 음료
   - 콜라
   - 사이다
2. 패스트푸드
   - 햄버거
     - 맘스터치
   - 피자
     1. 도미노피자
     2. 미스터피자

<br><br>

## <특수 문자 표현>

- 표시될 특수 문자 앞에 \ 기입

<br>마크다운

```
* 특수 문자 출력 안 됨

- 특수 문자 출력 안 됨

\* 특수 문자 출력

\- 특수 문자 출력
```

<br>미리보기

- 특수 문자 출력 안 됨

* 특수 문자 출력 안 됨

\* 특수 문자 출력

\- 특수 문자 출력

<br><br>

## <링크>

- \[링크 설명](링크)

<br>마크다운

```
[여기](https://www.google.com/)를 클릭하여 이동
```

<br>미리보기

Google - [여기](https://www.google.com/)를 클릭하여 이동

<br><br>

## <이미지>

- \!\[이미지 설명](링크)

<br>마크다운

```
![강아지](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyNTAyMjRfMjk5%2FMDAxNzQwMzkzNTI5ODk2.OYjQmDgt7jWzItkd1Idmsxi5poY1M_VvoTk4KioGqsAg.rfdper6LO6yEm_NpxApYhQaBfOt3U9_kOlLnTcMCHa4g.PNG%2F%25B0%25AD%25BE%25C6%25C1%25F6%25B8%25E9%25BF%25AA%25B7%25C210.png&type=sc960_832)
```

<br>미리보기

![강아지](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyNTAyMjRfMjk5%2FMDAxNzQwMzkzNTI5ODk2.OYjQmDgt7jWzItkd1Idmsxi5poY1M_VvoTk4KioGqsAg.rfdper6LO6yEm_NpxApYhQaBfOt3U9_kOlLnTcMCHa4g.PNG%2F%25B0%25AD%25BE%25C6%25C1%25F6%25B8%25E9%25BF%25AA%25B7%25C210.png&type=sc960_832)

<br><br>

## <테이블>

- | 기호와 - 기호로 테이블 생성
- 가장자리는 | 생략 가능

<br>마크다운

```
헤더1|헤더2|헤더3
-|-|-
셀1|셀2|셀3
셀4|셀5|셀6
```

<br>미리보기

| 헤더1 | 헤더2 | 헤더3 |
| ----- | ----- | ----- |
| 셀1   | 셀2   | 셀3   |
| 셀4   | 셀5   | 셀6   |

<br>

- : 기호로 내용 정렬 가능

<br>마크다운

```
왼쪽 정렬|가운데 정렬|오른쪽 정렬
:-|:-:|-:|
왼쪽|가운데|오른쪽
왼쪽정렬|가운데정렬|오른쪽정렬
```

<br>미리보기

| 왼쪽 정렬 | 가운데 정렬 | 오른쪽 정렬 |
| :-------- | :---------: | ----------: |
| 왼쪽      |   가운데    |      오른쪽 |
| 왼쪽정렬  | 가운데정렬  |  오른쪽정렬 |
