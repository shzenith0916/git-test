# git-test
쿠버네티스 6회차 프로그램 강의

# Markdown tutorial 
## readme.md 파일은 어떻게 쓰는지

단락을 바꾸고 싶다면, 스페이스를 두번 누르거나  
아니면 엔터를 쳐서 그 다음 라인으로 넘어갑니다. 

---------------------------------------------------------------

강조에는 *이탈릭* **볼드** 두가지가 있는데요, * 표시 하나는 이탈릭, ** 표시 두개는 볼드 입니다.  
혹은 _이탈릭_ __볼드__ , 이렇게 _ underscore 하나가 이탈릭 __ underscore 두개가 볼드 입니다.  
___구름수업___ 이렇게 ___ 세개의 underscore는 이탈릭 볼드 둘 다 반영됩니다.<br>
섞어서 사용할 수도 있습니다. *__구름__* 수업 튜토리얼  

---------------------------------------------------------------

인용문은 > 표시로 나타냅니다. 
> “The great thing in this world is not so much where we are, but in what direction we are going.” - Oliver Wendall Holmes Jr.
>> reference website: https://www.goodreads.com/author/quotes/432185.Oliver_Wendell_Holmes_Jr_

---------------------------------------------------------------

목록은 - 혹은 * 혹은 numbering 하여 나타냅니다. 
예시로 pro git book 의 목차(공부내용 플로우)를 한번 목록으로 적어볼게요. 

- 시작하기 
  - 버전 관리란
  - git 의 역사
  - git 기초
  - CLI
  - Git 설치/최초 설정

2. Git의 기초  
  2.1 Git 저장소 만들기  
  2.2 수정하고 저장소에 저장하기  
  2.3 커밋 히스토리 조회하기  
  
--------------------------------------------------------------------------

### 코드 블록은 README 파일에서 어떻게 작성할까? 

예시) Scitkit-Learn을 이용하여 linear model 을 이용해 트레이닝하고 새로운 데이터를 넣고 예측한 후, metrics를 살펴보자.  
먼저 설치해야할 라이브러리는 다음과 같다.  

`import numpy as np`   
`from sklearn.linear_model import LinearRegression`  
`from sklearn.metrics import mean_squared_error`   

위와 같이 ` ` 사이에 적으면 된다.  
만약에 python 언어로 적어진 코드를 나타내고 싶다면, ```python 이라고 표기하면 
코드블럭안의 내용이 파이썬 언어네 맞춰서 하이라이트 된다. 
```python
linear_reg = LinearRegression()
linear_reg.fit(X, y)
predicted = linear_reg.predict(X_new)
lin_mse = mean_squared_error(y, predicted)
lin_rmse = np.sqrt(mse)
```

----------------------------------------------------------

링크는 어떻게 마크다운할까?  
첫째로 그냥 웹사이트를 붙여넣으면 파란색깔을 가진다. https://kerbernetes.io

다른 방법은 square brackets과 circle brackets을 사용하는 것이다.  
예시로 [쿠버네티스 공식 사이트]만 하면 하이라이트 되지 않지만,  
[쿠버네티스 공식 사이트](https://kerbernetes.io) 하고 []뒤에()사이에 웹사이트 링크를
넣어주면 링크를 클릭할 수 있게 된다. 

----------------------------------------------------------

이미지는 !마크뒤에 [] 표시안에 이미지 레이블을 적어주고 () 사이에 이미지 링크를 넣어준다. 

아쉽지만, 이미지 사이즈는 조정이 안된다. 

![quote image](http://img.picturequotes.com/2/227/226750/the-best-thing-you-can-do-for-the-poor-is-not-to-be-one-of-them-quote-1.jpg)

---------------------------------------------------------

테이블 

|No.|Name|Seat|
|:-|:-:|-:|
|1|Peter|15A|
|2|Ian|27E|
|3|Sam|8C|

중간 구분자에서 정렬 방법은 아래와 같다.  
:- 좌측 정렬
:-: 가운데 정렬
-: 우측 정렬

-------------------------------------------------------------------

취소선은 ~~ 와 ~~ 사이에 글자를 적으면 취소가 된다. 

~~That's just trouble~~ Silence

-----------------------------------------------------------

작업 목록 To do list 는 - 후에 [ ] 표시한다. [ ] 안에 x 가 있으면 마크, 없으면 마크하지 않음. 

- [x] Review
- [ ] Preview
- [x] Practice
