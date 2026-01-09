# 마크다운 문법

> 마크다운 문법에 대해 조사하고 정리한 파일입니다.

- 마크다운이란?
  - 마크다운 문법은 주로 README, 문서, 블로그, 노트, Notion에서 사용되는 문법입니다.

---

## 1. 제목

**#**의 개수로 제목의 크기를 조절할 수 있다.

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

...

---

## 2. 강조, 기울림, 취소선

- **이름**

---

> 마크다운 문법에 대해 조사하고 정리한 파일입니다.

- 마크다운이란?
  - 마크다운 문법은 주로 README, 문서, 블로그, 노트, Notion에서 사용되는 문법입니다.

---

## 1. 제목

**#**의 개수로 제목의 크기를 조절할 수 있다.

```md
# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5
```

...

---

## 2. 강조, 기울림, 취소선

- 내용 양쪽에 \* 2개를 사용하여 강조할 수 있습니다.

```md
**내용**
```

**결과물**
**내용**

- 내용 양쪽에 \* 1개를 사용하여 기울림을 사용할 수 있습니다.

```md
_내용_
```

**결과물**
_내용_

- 내용 양쪽에 ~ 2개를 사용하여 취소선을 사용할 수 있습니다.

```md
~~내용~~
```

**결과물**
~~내용~~

---

## 3. List 목록

### 순서없는 항목

-를 사용해서 순서없는 항목을 만들 수 있습니다.

```md
- 내용1
  - 부내용1
    - 부내용1
  - 부내용2
    - 부내용2
      - 부부내용1
- 내용2
```

**결과물**

- 내용1
  - 부내용1
    - 부내용1
  - 부내용2
    - 부내용2
      - 부부내용1
- 내용2

### 숫자 순서 있는 항목

1.2.3.을 사용해서 순서를 만들 수 있습니다.

```md
1. 내용1
2. 내용2
3. 내용3
```

**결과물**

1. 내용1
2. 내용2
3. 내용3

---

## 4. 링크나 파일연결

```md
[내용](링크)
```

- 결과물
  - [djsy01 github](https://github.com/djsy01)

## 5. 이미지 연결

```md
![이미지 설명](이미지 주소)
```

**결과물**
![djsy 아이콘](https://lh3.googleusercontent.com/rd-d/ALs6j_HGfrpYuoEoKdNrTJcor_prV46DBrFKPWzONrC3TKjiKt5MlWmu_BHb34BxZUAKaX_4XKiFvGIVP9jEsNFH78vF5QWK1PXNV9oVhyRyyUdoUtNr-gyM9KYzSK4frLxz9FbdAaxAfnCT26vhT2zjya0gAtn3lX3VE0zVs4D8ufBv0DCBT2jBsIkzQhilQbyRdqiHKoQuLxiqaIylP8iCuiZ5FUhRoQW_Ez-zsMdfbUSXRl8gex9t5rTtHX1bICfyfSufPc2YjO7iYv1k0wxu6d5Z9JfoCgcv4G-MaMaCnrUZBaN-mdCZ3A54UQbHnpxS83dqGqXXXYDqK1vv006gTwrhXuLo7BNpU6aLzA7z0JDtXg7NsK-JfBKLldXZB45pkjTt-2NFa3oANyxbsw98-wXefZTwDjS343d8ho93iwodFQgiuk9JSldhUUcD0I6w0tismPYxo4ZX1bOqG5gCQJSh0JbIYYQzYXApZcsxEOjqKzcc-OfONtEUk_WgXkK6jyobw2MmmoVhqPfKwCnyqISb0knI_C8BsPuLY12IAwwL9H4srjPRyLEUv_392BfBAhHVoXF9yLrTAx41LArtksd84StQ2-3fWobG86p8DBXRjycme2BLwTJNalhJpQpwAWwO_Hi4V37fRZsj5pRXLf6rFAJWh7E3Kp6huX_copFE9g-BGb7gL_oGIRFermZvrDskHTWIn4Ac4gIwI7s43cyZVMJoliyoA_v8LRQP0UtpRYJWtExkLM9P4uASuM242HdBji9YWXN47DZHZ9QBQ44-qMD2wLyRDDMI3Qi2ki2Pz0ZwHjeU0-GLatJVnLlcXAlim8pVXdawnHDHktNeNrZlZZOHThjIAF1NwvbQZDMByitKjnjanI-BXzlO2RMMOXFxC0GM6soICmNaY1HACqLgHE9fvVx-iJ7gNKSgrYD8f8ne_IGD_oxycj9LK_HfbX9cX5Cwz7PTng4T0vSbeYtJmv0ROI3XLENsalU4psTNtvU8zSpJkbMevPChOzVDbezKKN1iEEvhQ8tIPfd_opjRMPADGi1PLEoZnwP2wYHogZb1=w3584-h1810?auditContext=prefetch)

## 6. 코드 블록

터미널에 console.log("내용")을 적어 내용을 출력할 수 있습니다.

```js
function hello() {
  console.log('Hello World');
}
```

**결과물**
Hello world

## 7. 인용문

\> 를 사용하여 인용문을 작성할 수 있습니다.

```md
> 이것은 인용문입니다
```

> 이것은 인용문입니다

---

## 8. 구분선

/--- 를 사용해서 구분선을 만들 수 있습니다

```md
---
```

## **결과물**

## 9. 표

**실행 방법**

```md
| 내용 | 내용 |
| ---- | ---- |
| 내용 | 내용 |
```

**결과물**
| 내용 | 내용 |
| ----- | ----- |
| 내용 | 내용 |
