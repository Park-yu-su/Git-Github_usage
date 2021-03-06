# **마크다운 기본 문법 (Markdown Basic Syntax)**

-  **아래 문서는 Markdown에서 주로 사용되는 기본 문법을 정리했습니다!**

---

## 1) **제목 (Headings)**

---

### 1.1) **제목 생성하기 1**

---

- 제목으로 사용하고 싶은 문장 앞에 파운드 기호( `#` )를 입력한다.

- (1 ~ 6)개의 `#`를 입력하여 크기가 다른 제목을 만들 수 있다.

```
<입력>

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
####### Heading level 7
```

> <출력>
>  
> # Heading level 1
> ## Heading level 2
> ### Heading level 3
> #### Heading level 4
> ##### Heading level 5
> ###### Heading level 6
> ####### Heading level 7 (7개 이상부터는 더 이상 만들어지지 않는다.)

### 1.2) **제목 생성하기 2**

---

- 레벨 1 또는 레벨 2의 제목을 붙이는 경우에는 `#` 없이 아래와 같은 방법 역시 사용이 가능하다.

```
<입력>

Heading level 1
================
```

> <출력>  
>
> Heading level 1
> ================

```
<입력>

Heading level 2
----------------
```

> <출력>
>
> Heading level 2
> ----------------

### 1.3) **주의할 점**

---

- `#` 를 입력한 다음에는 꼭 띄어쓰도록 한다.

```
# Hello world!  (O)
#Hello wolrd!   (X)
```

## 2) **단락 (Paragraph)**

---

### 2.1) **단락 만들기**

---

- 새로운 단락을 만들려면 한 줄을 공백으로 두도록 한다.

```
<입력>

Hello my name is
Park yu su.

Nice to meet you.
Thank you.  
```

> <출력>
>
> Hello my name is
> Park yu su.
>
> Nice to meet you.
> Thank you.  

- **위와 같이 한 줄을 비우지 않으면 문장이 이어지니 꼭 한 줄을 비우거나 공백을 두 개 이상 입력하는 습관을 가지자. (3절 후술)**

### 2.2) **주의할 점**

---

- 새 단락을 만들 때에는 문장 앞에 TAP을 하거나 SPACE로 공백을 만들지 않도록 한다.

```
Don't use TAB        (O)
Don't use space      (O)


    Don't use TAB    (X)
    Don't use space  (X)
```


## 3) **줄 바꾸기 (Line Breaks)**

---

### 3.1) **줄 바꾸는 방법**

---

- 줄을 바꾸기 위해서는 두 개 이상의 공백(　　)으로 줄을 끝내면 된다.
```
<입력>

이것은 첫 번째
줄입니다.  
이것은 두 번째
줄입니다.  
```

> <출력>
>
> 이것은 첫 번째
> 줄입니다.  
> 이것은 두 번째
> 줄입니다.  

- 앞에서 후술한 단락 만들기랑 헷갈릴 수 있다. 차이점은 아래와 같다.
```
<입력>

이것은 문장 끝에 space를
2번 입력한 것입니다.  
이것은 문장을 끝내고 공백 한 줄을
만든 것입니다.

마지막 문장입니다. 단락의 차이가 느껴지십니까?  
```

> <출력>
>
> 이것은 문장 끝에 **space를**
> **2번 입력한** 것입니다.  
> 이것은 문장을 끝내고 **공백 한 줄을**
> **만든** 것입니다.
>
> 마지막 문장입니다. 단락의 차이가 느껴지십니까?  

### 3.2) **주의할 점**

---

- 줄을 바꾸는 과정에서 역슬래쉬( `\` )를 이용하지 않도록 한다.

```
First line with two spaces
after.  
And the next line.    (O)


First line with a backslash
after. \
And the next line.    (X)
```

## 4) **강조하기 (Emphasis)**

---

### 4.1) **굵게 표시하기**

---

- 굵게 표현하고 싶은 문장 앞에 두 개의 별표( `**` )나 밑줄( `__` )을 추가한다.
- 문장 중간에 특정 단어를 굵게 표시하려면 공백없이 두 개의 별표( `**` )를 입력한다.

```
<입력>

나는 **굵게 쓰는 것을 좋아해!**  
나는 __굵게 쓰는 것을 좋아애!__  
Love**is**bold  
```

> <출력>
>
> 나는 **굵게 쓰는 것을 좋아해!**  
> 나는 __굵게 쓰는 것을 좋아해!__  
> Love**is**bold  

#### 4.1.1) **주의할 점**

---

- 호환성을 위해 문장 중간에 공백 없이 밑줄(`__`)을 쓰는 것을 지양하도록 한다.
```
아버지가**방에**들어가신다.  (O)
아버지가__방에__들어가신다.  (X)
```

### 4.2) **이탤릭체(기울이기)**

---

- 기울이게 표현하고 싶은 문장 앞에 한 개의 별표( `*` )나 밑줄( `_` )을 추가한다.
- 문장 중간에 특정 단어를 기울이고 싶으면 공백없이 한 개의 별표( `*` )를 입력한다.

```
<입력>

나는 *기울여 쓰는 것을 좋아해!*  
나는 _기울여 쓰는 것을 좋아애!_  
A*cat*meow  
```

> <출력>
>
> 나는 *기울여 쓰는 것을 좋아해!*  
> 나는 _기울여 쓰는 것을 좋아애!_  
> A*cat*meow  

### 4.2.1) **주의할 점**

---

- 호환성을 위해 문장 중간에 공백 없이 밑줄( `_` )을 쓰는 것을 지양하도록 한다.
```
아버지가*방에*들어가신다.  (O)
아버지가_방에_들어가신다.  (X)
```

### 4.3) **굵고 기울이기**

---

- 표현하고 싶은 문장 앞에 별표 또는 밑줄 세 개를 추가한다. (**꼭 통일할 필요는 없다!**)
- 문장 중간에 특정 단어를 굵고 기울이게 표시하려면 공백없이 세 개의 별표( `***` )를 입력한다.

```
<입력>

이것은 매우 ***중요한 문장*** 이다.  
이것은 매우 ___중요한 문장___ 이다.  
이것은 매우 __*중요한 문장*__ 이다.  
이것은 매우 **_중요한 문장_** 이다.  
This is really***very***important text.   
```

> <출력>
>
> 이것은 매우 ***중요한 문장*** 이다.  
> 이것은 매우 ___중요한 문장___ 이다.  
> 이것은 매우 __*중요한 문장*__ 이다.  
> 이것은 매우 **_중요한 문장_** 이다.  
> This is really***very***important text.   

### 4.3.1) **주의할 점**

---

- 호환성을 위해 문장 중간에 공백 없이 밑줄( `___` )을 쓰는 것을 지양하도록 한다.
```
아버지가***방에***들어가신다.  (O)
아버지가___방에___들어가신다.  (X)
```


## 5) **인용, 들여쓰기 (Blockquotes)**

---

### 5.1) **인용구 만들기**

---

- 인용하고 싶은 문장 앞에 꺽쇠( `>` )를 추가한다.

```
<입력>

> 나는 이 문장을 인용했습니다.  
```

- 출력 결과는 아래와 같다.  

> 나는 이 문장을 인용했습니다.  

### 5.2) **여러 단락이 있는 인용구 만들기**

---

- 빈 단락에도 꺽쇠( `>` )를 추가한다.

```
<입력>

> 나는 이 문장을 인용했습니다.  
>
> 이 문장도 인용했습니다.  
```

- 출력 결과는 아래와 같다.  

> 나는 이 문장을 인용했습니다.  
>
> 이 문장도 인용했습니다.  

### 5.3) **중첩이 있는 인용구 만들기**

---

- 중첩하려는 단락 앞에 꺽쇠를 두 번( `>>` ) 추가한다.

```
<입력>

> 이 문장을 인용하려고 합니다.  
>
>> 문장 안에 중첩으로 인용하려고 합니다.  
>
> 다시 돌아왔습니다.  
```

- 출력 결과는 아래와 같다.  

> 이 문장을 인용하려고 합니다.  
>
>> 문장 안에 중첩으로 인용하려고 합니다.  
>
> 다시 돌아왔습니다.  

### 5.4) **다른 요소가 있는 인용구 만들기**

---

- 인용구 안에 제목( `#` ), 글머리번호( `-` ), 강조( `*` ), 코드 입력 등을 사용할 수 있다.

```
<입력>

> ## **명언을 사용해 보도록 합시다!**
>
> - 좋은 소프트웨어 기능이란 복잡한 것을 간단하게 보이도록 만드는 것이다. (Grady Booch, UML 개발자)
> - 먼저 문제를 풀고 그 다음에 개발을 하라. (John Johnson, 미국의 유명한 소프트웨어 강사)
>
>       printf("Hello world!\n");
>
> 신기한 **명언**들이 많네요.  
```

- 출력 결과는 아래와 같다.  

> ## **명언을 사용해 보도록 합시다!**
>
> - 좋은 소프트웨어 기능이란 복잡한 것을 간단하게 보이도록 만드는 것이다. (Grady Booch, UML 개발자)  
> - 먼저 문제를 풀고 그 다음에 개발을 하라. (John Johnson, 미국의 유명한 소프트웨어 강사)  
>
>        printf("Hello world!\n");
>
> 신기한 **명언**들이 많네요.  



## 6) **목록 (Lists)**

---

### 6.1) **순서 있는 목록(번호)**

---

- 순서 있는 목록은 숫자와 점을 사용한다.

```
<입력>

1. First  
2. Second  
3. Third  
4. Fourth  
```

> <출력>
>
> 1. First  
> 2. Second  
> 3. Third  
> 4. Fourth  

- **첫 숫자는 1로 시작해야 하고 순서를 어떻게 해도 내림차순으로 표시된다.**

```
<입력>

1. First
1. Second
1. Third
1. Fourth
```

> <출력>
>
> 1. First  
> 1. Second  
> 1. Third  
> 1. Fourth  

```
<입력>

1. First
3. Second
7. Third
5. Fourth
```

> <출력>
>
> 1. First  
> 3. Second  
> 7. Third  
> 5. Fourth  

- **들여 써서 번호를 표시한 경우 다시 처음부터 번호가 매겨진다.**

```
<입력>

1. First
1. Second
    1. Indented one
    1. Indented two
    1. Indented three
1. Third
1. Fourth
```

> <출력>
>
> 1. First
> 1. Second
>     1. Indented one
>     1. Indented two
>     1. Indented three
> 1. Third
> 1. Fourth

### 6.1.1) **주의할 점**

---

- 번호를 매길 때 호환성을 위해 `1)` 이런 형식으로 괄호( `)` )를 사용하지 않는다.

```
1. First item   (O)
2. Second item  (O)

1) First item   (X)
2) Second item  (X)
```

### 6.2) **순서 없는 목록(정렬 X)**

---

- 순서 없는 목록은 대시( `-` )나 별표( `*` ) 또는 더하기( `+` ) 기호를 사용한다.
- 중첩된 목록은 들여쓰기(TAB)를 사용한다.

```
<입력>

- First item  
- Second item  

* First item
* Second item

+ First item
+ Second item

- First item
    - Indented one
    - Indented two
- Second item
```

> <출력>
>
> - First item  
> - Second item  
> 
> * First item
> * Second item
> 
> + First item
> + Second item
>
> - First item
>     - Indented one
>     - Indented two
> - Second item

### 6.2.1) **주의할 점**

---

- 호환성을 위해 동일한 목록에서는 같은 기호를 사용한다.

```
(옳은 사용)

- First
- Second
- Third
- Fourth

(잘못된 사용)

- First
* Second
+ Third
- Fourth
```

### 6.3) **목록에 다양한 것 추가하기**

---

- 목록를 쓰는 도중에 단락이나 인용구, 코드( \` 사용의 경우 ) 등을 출력할 수 있다.
- **공백을 4개** 입력하거나 **탭**을 해 들여 쓰면 된다.


단락의 경우  

```
<입력>

1. 첫 번째 문장입니다.
2. 두 번째 문장입니다.

    문장을 나누겠습니다.

3. 세 번째 문장입니다.

```

> <출력>
>
> 1. 첫 번째 문장입니다.
> 2. 두 번째 문장입니다.
>
>     문장을 나누겠습니다.
>
> 3. 세 번째 문장입니다.


인용의 경우  
```
<입력>

1. 첫 번째 문장입니다.
2. 두 번째 문장입니다.

    > 잠시 인용문을 사용하겠습니다.

3. 세 번째 문장입니다.

```

> <출력>
>
> 1. 첫 번째 문장입니다.
> 2. 두 번째 문장입니다.
>
>     > 잠시 인용문을 사용하겠습니다.
>
> 3. 세 번째 문장입니다.

코드의 경우  
```
<입력>

1. 첫 번째 문장입니다.
2. 두 번째 문장입니다.

    `printf("코드를 사용하겠습니다.\n");`

3. 세 번째 문장입니다.

```

> <출력>
>
> 1. 첫 번째 문장입니다.
> 2. 두 번째 문장입니다.
>
>     `printf("코드를 사용하겠습니다.\n");`
>
> 3. 세 번째 문장입니다.

### **중요 : 코드블럭** 의 경우
- 코드블럭는 원래 **공백 4칸이나 탭**으로 들여 쓰기 때문에, 목록에서 사용하는 경우 **공백 8칸이나 탭 2칸**을 들여 쓴다.  
```
<입력>

1. 첫 번째 문장입니다.
2. 두 번째 문장입니다.

        printf("Hello world!\n");
    printf("Hello world!\n");         (잘못된 들여쓰기)

3. 세 번째 문장입니다.

```

> <출력>
>
> 1. 첫 번째 문장입니다.
> 2. 두 번째 문장입니다.
>
>        printf("Hello world!\n");
>    printf("Hello world!\n");        (잘못된 들여쓰기)
>
> 3. 세 번째 문장입니다.

- **그 외 이미지나 목록 역시 들여쓰기가 가능하다.**  
- **이미지에 관련된 내용은 10절에서 자세히 다루도록 하겠다.**

## 7) **코드 입력 (Code)**

---

### 7.1) **코드 표현**

---

- 코드로 표시하고 싶은 내용을 백틱( \` ) 으로 감싸서 표현한다.

```
<입력>

프로그래밍에서 가장 유명한 문장은 `printf("Hello world!\n");` 이다.
```

> <출력>
>
> 프로그래밍에서 가장 유명한 문장은 `printf("Hello world!\n");` 이다.

### 7.2) **코드 블럭 표현**

---

- 6.3절에서 미리 언급했듯이 4개의 공백 or 탭을 이용한다.

```
<입력>

    printf("Hello world!\n");
    for(int i = 0; i < 10; i++)
        printf("Number : %d\n", i);


```

> <출력>
>
>     printf("Hello world!\n");
>     for(int i = 0; i < 10; i++)
>         printf("Number : %d\n", i);
>

### 7.2.1) **코드 블럭 표현 TIP**

---

- **분리 코드 블럭**을 이용해 탭 없이 코드 블럭 표현이 가능하다.  
- ( "\```" )와 ( "\~~~" )을 이용해 코드 블럭 표현이 가능하다. 

<pre>
<code>
<입력>

```
printf("Hello world!\n");
printf("Nice to meet you!\n");
```

~~~
printf("Hello world!\n");
printf("Nice to meet you!\n");
~~~
</code>
</pre>

> <출력>
>
> ```
> printf("Hello world!\n");
> printf("Nice to meet you!\n");
> ```
>
> ~~~
> printf("Hello world!\n");
> printf("Nice to meet you!\n");
> ~~~



## 8) **수평선 (Horizontal Rules)**

---

### 8.1) **수평선 그리기**

---

- 3개 이상의 별표( `***` ), 대시( `---` ), 밑줄( `___` )을 그으면 동일한 수평선이 그려진다.

```
<입력>

***

---------

_________________
```

> <출력>
>
> ***
>
> ---------
>
> _________________
>

### 8.2) **주의할 점**

---

- 호환성을 위해 앞뒤에 빈 줄을 넣는다.

```
(옳은 사용)

Try this!

---

OK!


(잘못된 사용)

Don't try this!
---
NO! 
```


## 9) **링크 (Links)**

---

### 9.1) **링크 만들기**

---

- 링크로 표시할 텍스트를 대괄호( `[ ]` )로 묶은 다음 바로 뒤에 주소를 괄호( `( )` )로 묶는다.
- ex ) `[대체 문자](URL)` - `[네이버](https://www.naver.com/)`

```
<입력>

제가 다니는 학교는 [숭실대학교](https://ssu.ac.kr/)입니다.
```

> <출력>
>
> 제가 다니는 학교는 [숭실대학교](https://ssu.ac.kr/)입니다.

### 9.2) **링크 미리보기 텍스트 만들기 (제목 추가)**

---

- URL을 입력한 바로 뒤에다가 **따옴표( `""` )** 로 타이틀을 적으면 링크 제목을 추가할 수 있다.
- 제목을 추가한 뒤 링크에 마우스를 가져가면 추가한 링크 제목이 보인다.

```
<입력>

제가 재학중인 학교는 [숭실대학교](https://ssu.ac.kr/ "숭실대학교")입니다.
```

> <출력>
>
> 제가 재학중인 학교는 [숭실대학교](https://ssu.ac.kr/ "숭실대학교")입니다.

### 9.3) **간단하게 URL / Email주소 표시하기**

- 꺽쇠( `< >` )를 사용하여 빠르게 링크를 만들 수 있다.

```
<입력>

<https://ssu.ac.kr/>  
<asdf@example.com>  
```

> <출력>
>
> <https://ssu.ac.kr/>  
> <asdf@example.com>  

### 9.3) **링크에 변화 주기**

---

- 링크를 강조하거나 기울이고 싶을 때는 링크 앞뒤에 별( `*` )을 추가한다.

```
<입력>

제가 다니는 학교는 **[숭실대학교](https://ssu.ac.kr/)**입니다.  
학교의 공지사항은 *[여기서](https://scatch.ssu.ac.kr/ "SSU:catch")* 확인 가능합니다.  
```

> <출력>
>
> 제가 재학중인 학교는 **[숭실대학교](https://ssu.ac.kr/)** 입니다.  
> 학교의 공지사항은 *[여기서](https://scatch.ssu.ac.kr/ "SSU:catch")* 확인 가능합니다.  

### 9.4) **참조 스타일 링크**

---
- 참조 스타일 링크를 사용하면 코드 작성 중 **좀 더 깔끔하게 문장 사이에 링크를 삽입**할 수 있다.

<사용법>
1. 대괄호( `[ ]` )사이에 레이블을 넣고 `:`을 입력한 뒤 한 칸 공백을 삽입한다.　(ex. `[1]:` )
2. 공백 뒤로 URL를 삽입한다.
3. 링크 미리보기 텍스트를 삽입하고 싶은 경우 괄호( `()` ), 따옴표( `""`, `''` ) 를 삽입한다. 


```
<사용 예시>

[1]: https://ssu.ac.kr/
[1]: https://ssu.ac.kr/ "숭실대학교"
[1]: https://ssu.ac.kr/ '숭실대학교'
[1]: https://ssu.ac.kr/ (숭실대학교)

2-4 번째는 출력 시 같게 표시된다.
```

- 실제로 사용하면 아래와 같다. (띄어쓰기에 유의하자!)

```
<입력>

안녕하세요 저는 [숭실대학교][1]에 재학중인 학생입니다.  
만나서 반갑습니다.

[1]: https://ssu.ac.kr/ "숭실대학교"
```

> <출력>
>
> 안녕하세요 저는 [숭실대학교][1]에 재학중인 학생입니다.  
> 만나서 반갑습니다.
> 
> [1]: https://ssu.ac.kr/ "숭실대학교"

### 9.5) **주의할 점**

---

- URL은 중간에 빈칸이 없어야 하며 빈칸인 부분은 `%20`으로 채운다.
```
[link]: https://www.example.com/my%20great%20page  (O)
[link]: https://www.example.com/my great page      (X)
```


## 10) **이미지 (Images)**

---

### 10.1) **이미지 삽입하기**

---

- `![대체 택스트](이미지 경로 또는 URL "URL 미리보기 텍스트")` 방식을 통해 이미지를 추가할 수 있다.

```
<입력>

![card](https://user-images.githubusercontent.com/57581969/110939259-79572300-8378-11eb-836a-5313ab82ffed.jpg  "card")



![eagle](https://user-images.githubusercontent.com/57581969/110938958-02ba2580-8378-11eb-9bb7-2fd39306a6c6.jpg)
```
> <출력>
>
> ![card](https://user-images.githubusercontent.com/57581969/110939259-79572300-8378-11eb-836a-5313ab82ffed.jpg "card")
>
> ![eagle](https://user-images.githubusercontent.com/57581969/110938958-02ba2580-8378-11eb-9bb7-2fd39306a6c6.jpg)


### 10.2) **이미지에 링크 삽입하기**

---

- 이미지에 링크를 추가할 수 있다!
- 링크를 만드는 코드의 `[대체 문자](이미지 URL)` **대체 문자** 부분에 이미지 연결 코드를 연결하면 된다.

- ex ) `[![대체 택스트](이미지 경로 또는 URL "URL 미리보기 텍스트")](이미지 URL)`

```
<입력>

[![card](https://user-images.githubusercontent.com/57581969/110939259-79572300-8378-11eb-836a-5313ab82ffed.jpg  "card")](https://youtu.be/LjLLPe5ZhFo)

```

> <출력>
>
> [![card](https://user-images.githubusercontent.com/57581969/110939259-79572300-8378-11eb-836a-5313ab82ffed.jpg  "Card magic video")](https://youtu.be/LjLLPe5ZhFo)


## 11) **이스케이프 문자 (Escaping characters)**

---

- Markdown에서 사용하는 리터럴 문자들을 표시하려면 문자 앞에 백슬래쉬(`\`)를 사용한다.

<사용할 수 있는 종류는 아래와 같다.>
```
백슬래쉬(\)  -  \\  
백틱(`)      -  \`  
별표(*)      -  \*   
밑줄(_)      -  \_  
괄호(())     -  \(  　\)
중괄호({})   -  \{  　\}
대괄호([])   -  \[  　\]
꺽쇠(<>)     -  \<  　\>
파운드(#)    -  \#
더하기(+)    -  \+
빼기(-)      -  \-
점(.)        -  \.
느낌표(!)    -  \!
```

실제로 출력하면 아래와 같다.  

> 백슬래쉬( \\ )　-  　( \\ )  
> 백틱( \` )　　　-  　( \` )  
> 별표( \* )　　　-  　( \* )   
> 밑줄( \_ )　　　-  　( \_ )  
> 괄호( `()` )　　-  　( \(  \) )  
> 중괄호( `{}` )　-  　( \{  \} )  
> 대괄호( `[]` )　-  　( \[  \] )  
> 꺽쇠( `<>` )　　-  　( \<  \> )  
> 파운드( \# )　　-  　( \# )  
> 더하기( \+ )　　-  　( \+ )  
> 빼기( \- )　　　-  　( \- )  
> 점( \. )　　　　-  　( \. )  
> 느낌표( \! )　　-  　( \! )  


## 12) **HTML**

---

- Markdown 형식의 텍스트에 HTML 코드를 사용할 수 있다.
- 사람에 따라 차이는 선호되는 코드가 있기에 취향대로 사용하면 **GOOD!**

```
<입력>

This **word** is bold. This <em>word</em> is italic.
```

> <출력>
> 
> This **word** is bold. This <em>word</em> is italic.

--- 


### 이상으로 Markdown에서 사용하는 기본 문법 사용을 마치도록 하겠습니다.  

### 아래 링크를 통해 GitHub Flavered Markdwon (GFM)에 대한 추가 문법을 볼 수 있습니다!

## [GitHub Flavered Markdwon (GFM)](https://github.com/Park-yu-su/Markdown_usage "Park-yu-su의 GitHub")