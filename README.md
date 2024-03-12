# Python-1
## Python Home
```언어
print("Hello, World!")
```
## Python Syntax 
Python Indentation
```언어
if 5 > 2:
  print("Five is greater than two!")
```
들여쓰기를 건너뛰면 Python에서 오류가 발생한다.
가장 일반적으로 사용되는 것은 4개이다.
BUT 적어도 하나는 있어야 한다 !
  예
```언어
  if 5 > 2:
 print("Five is greater than two!") 
if 5 > 2:
        print("Five is greater than two!") 
```
## Python Variables
변수에 값을 할당하면 변수가 생성된다.
```언어
x = 1120
y = "Hello, World!"
```
## Comment
주석은 #으로 시작한다 !
Python은 줄의 나머지 부분을 주석으로 렌더링한다.
```언어
print("Hello, World!")
```
## Python Comments
주석은 a로 시작한다.
#Python은 이것을 무시한다.
```언어
print("Hello, World!") #This is a comment
```
Multiline Comments
Python은 변수에 할당되지 않은 문자열 리터럴을 무시한다.
==> 코드에 여러 줄 문자열(삼중 따옴표)을 추가한다.
-> 안에 주석을 넣을 수 있다.
```언어
"""
배고프다
너무 배고프다
격렬하게 배고프다
"""
print("Hello, World!")
```
## Python Variables
변수는 처음 값을 할당하는 순간 생성된다.
```언어
x = 1120
y = "Hee Cheol"
print(x)
print(y)
```
# 변수는 특정 유형으로 선언할 필요가 없다.
설정된 후에 유형을 변경 할 수 있다.
```언어
x = 1120       # x is of type int
x = "Hee Cheol" # x is now of type str
print(x)
```
# 변수의 데이터 유형을 지정하려면 캐스팅을 사용한다.
```언어
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
```
# type() 함수를 사용하여 변수의 데이터 유형을 얻을 수 있다.
```언어
x = 1120
y = "Hee Cheol"
print(type(x))
print(type(y))
```
# 문자열 변수는 작은따옴표나 큰따옴표를 사용하여 선언할 수 있다.
변수의 이름은 대소문자를 구분한다.
### Variable Names
변수 이름은 문자나 밑줄 문자로 시작해야 한다.
변수 이름은 숫자로 시작할 수 없다.
변수 이름에는 영숫자와 밑줄(Az, 0-9 및 _)만 포함할 수 있다.
변수 이름은 대소문자를 구분한다(age, Age 및 AGE는 세 가지 다른 변수).
변수 이름은 Python 키워드 중 하나일 수 없다.
```언어
myvar = "Hee Cheol"
my_var = "Hee Cheol"
_my_var = "Hee Cheol"
myVar = "Hee Cheol"
MYVAR = "Hee Cheol"
myvar2 = "Hee Cheol"
```
# 여러 변수에 대한 많은 값
한 줄로 여러 변수에 값을 할당할 수 있다.
```언어
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
```
# 하나의 값을 여러 변수로
한 줄에 여러 변수에 동일한 값을 할당할 수 있다.
```언어
x = y = z = "Orange"
print(x)
print(y)
print(z)
```
컬렉션 압축 풀기
# 목록 압축 풀기 : 
```언어
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)
```
## Output Variables
# print()함수는 변수를 출력한다.
+ 연산자를 사용하여 여러 변수를 출력 할 수도 있다 .
```언어
x = 1100
y = 20
print(x + y)
```
# 함수에서 print() 문자열과 숫자를 + 연산자와 결합하려고 하면 Python에서 오류를 표시한다.
```언어
x = 1120
y = "Hee Cheol"
print(x + y)
```
함수에서 여러 변수를 출력하는 가장 좋은 방법은 print()변수를 쉼표로 구분하는 것이다. 
이것은 다양한 데이터 유형도 지원한다.
```언어
x = 1120
y = "Hee Cheol"
print(x, y)
```
## Python Data Types

텍스트 유형:	`str`

숫자 유형:	`int`, `float`, `complex`

시퀀스 유형:	`list`, `tuple`, `range`

매핑 유형:	`dict`

세트 유형:	`set`,`frozenset`

부울 유형:	`bool`

바이너리 유형:	`bytes`, `bytearray`, `memoryview`

없음 유형:	`NoneType`

## 데이터 유형 가져오기
type() 함수를 사용해서 데이터 유형을 얻을 수 있다.
```언어
x = 1120
print(type(x))
```
  ## Python Numbers
  
파이썬에는 세 가지 숫자 유형이 있다.

 `int` 정수
 
 `float` 실수 
 
 `complex` 복소수
 
 ## 숫자 유형의 변수는 값을 할당하면 생성된다.
 ```언어
x = 1    # int
y = 2.8  # float
z = 1j   # complex
```
Python에서 객체의 유형을 확인하려면, type()함수를 사용한다.
```언어
print(type(a))
print(type(b))
print(type(c))
```
## 변수 유형 지정
Python에서의 캐스팅은 생성자 함수를 사용하여 수행된다.
int() 
- 정수 리터럴, 부동 소수점 리터럴(모든 소수를 제거하여) 또는 문자열 리터럴(문자열이 정수를 나타낼 때)에서 정수를 생성한다.
float()
- 정수 리터럴, 부동 소수점 리터럴 또는 문자열 리터럴에서 부동 소수점 숫자를 구성한다(문자열이 부동 소수점 또는 정수를 나타낼 때).
str()
- 문자열, 정수 리터럴, 부동 소수점 리터럴을 포함한 다양한 데이터 유형에서 문자열을 구성한다.
```언어
x = int(1)   # x will be 1
y = int(2.8) # y will be 2
z = int("3") # z will be 3
```
## Python Strings
Python의 문자열은 작은따옴표나 큰따옴표로 묶인다.
'안녕하세요' 는 '안녕하세요' 와 같다.

# 변수에 문자열 할당
```언어
a = "배고프다"
print(a)
```
## Strings are Arrays

# 위치 1의 문자를 가져온다 (첫 번째 문자의 위치는 0).
```언어
a = "배고프다, 밥 먹을래?"
print(a[1])
```
#  `for` 문자열은 배열이므로 루프를 사용하여 문자열의 문자를 반복할 수 있다.
```언어
for x in "apple":
  print(x)
```
## 문자열 길이
# `len()` 함수를 사용해서 문자열의 길이를 얻는다.
```언어
a = "배고프다, 밥 먹을래?"
print(len(a))
```
## Check String
`in` 과 `not in`을 사용하여 텍스트에 원하는 단어가 있는지 확인 가능 !
```언어
txt = "배고프다, 밥 먹을래?"
print("배부르다" not in txt)
```

`if` 명령문을 통해 활용 가능 !
```언어
txt = "배고프다, 밥 먹을래?"
if "배부르다" not in txt:
    print("No, '배부르다' is NOT present.")
```
## 슬라이싱
슬라이스 구문을 사용해서, 다양한 문자를 반환할 수 있다.
문자열의 일부를 반환하려면, 시작 인덱스와 끝 인덱스를 콜론으로 구분하여 지정한다.
```언어
b = "Hello, World!"
print(b[2:5])
```
## 처음부터 슬라이스
시작 인덱스를 생략하면, 범위는 첫 번째 문자에서 시작된다.
```언어
b = "Hello, World!"
print(b[:5])
```
## 끝까지 슬라이스
끝 인덱스를 생략하면 범위가 끝으로 이동한다.
```언어
b = "Hello, World!"
print(b[2:])
```
## 네거티브 인덱싱
문자열 끝에서 조각을 시작하려면 음수 인덱스를 사용한다.
```
b = "Hello, World!"
print(b[-5:-2])
```
## 대문자
upper() 메서드는 문자열을 대문자로 반환한다.
```언어
a = "Hello, World!"
print(a.upper())
```
## 소문자
lower() 메서드는 문자열을 소문자로 반환한다.
```언어
a = "Hello, World!"
print(a.lower())
```
## 공백 제거
공백은 실제 텍스트 앞 또는 뒤의 공백이며, 이 공백을 제거하려는 경우가 많다.
이 strip() 메서드는 시작이나 끝에서 공백을 제거한다.
```언어
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"
```
## 문자열 바꾸기
replace() 메서드는 문자열을 다른 문자열로 바꾼다.
```언어
a = "Hello, World!"
print(a.replace("S", "H"))
```
## 문자열 분할
split() 메서드는 지정된 구분 기호 사이의 텍스트가 목록 항목이 되는 목록을 반환한다.
split() 메서드는 구분 기호의 인스턴스를 찾으면 문자열을 하위 문자열로 분할한다.
```언어
a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!']
```
## 문자열 연결
두 문자열을 연결하거나 결합하려면 + 연산자를 사용할 수 있다.
```언어
a = "Hello"
b = "World"
c = a + b
print(c)
```
## 문자열 형식
이 메소드를 사용하면 문자열과 숫자를 결합할 수 있다. format()
```언어
age = 36
txt = "My name is John, and I am {}"
print(txt.format(age))
```
### 부울 값
프로그래밍에서는 표현식이 True 또는 False 인지 알아야 하는 경우가 많다.
if 문에서 조건을 실행하면 Python은 True 또는 False 를 반환한다.
```언어
a = 200
b = 33

if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
```
## 값과 변수 평가
bool() 함수를 사용하면, 모든 값을 평가한다. ==> True 또는 False .
문자열과 숫자를 평가한다.
```언어
print(bool("Hello"))
print(bool(15))
```
두 가지 변수를 평가한다.
```언어
x = "배고프다"
y = 1120

print(bool(x))
print(bool(y))
```
### 파이썬 연산자
연산자는 변수와 값에 대한 연산을 수행하는 데 사용된다.
```언어
print(10 + 5)
```
Python은 연산자를 다음 그룹으로 나눈다.
산술 연산자 - 숫자 값과 함께 사용되어 일반적인 수학 연산을 수행한다.
할당 연산자 - 변수에 값을 할당하는 데 사용된다.
비교 연산자 - 두 값을 비교하는 데 사용된다.
논리 연산자 - 조건문을 결합하는 데 사용된다.
신원 연산자 - 객체가 같은지 비교하는 것이 아니라 실제로 동일한 메모리 위치를 가진 동일한 객체인지 비교하는 데 사용된다.
회원 운영자 - 시퀀스가 ​​객체에 표시되는지 테스트하는 데 사용된다.
비트 연산자 - (이진) 숫자를 비교하는 데 사용된다.
## 연산자 우선순위
연산자 우선 순위는 작업이 수행되는 순서를 설명한다.
괄호의 우선순위가 가장 높다. ==> 괄호 안의 표현식을 먼저 평가해야 한다.
```언어
print((6 + 3) - (6 + 3))
```
곱셈은 *​​덧셈보다 우선순위가 높 +으므로 곱셈은 덧셈보다 먼저 평가된다.
```언어
print(100 + 5 * 3)
```
덧셈 +과 뺄셈 -의 우선순위는 동일하므로 왼쪽에서 오른쪽으로 표현식을 평가된다.
```언어
print(5 + 4 - 7 + 3)
```
### 파이썬 목록
```언어
mylist = ["apple", "banana", "cherry"]
```
## 목록
목록은 단일 변수에 여러 항목을 저장하는 데 사용된다.
목록은 데이터 컬렉션을 저장하는 데 사용되는 Python의 4가지 내장 데이터 유형 중 하나이다.
나머지 3개는 Tuple , Set 및 Dictionary 이며 모두 품질과 용도가 다르다.
목록은 대괄호를 사용하여 생성된다.
```언어
thislist = ["apple", "banana", "cherry"]
print(thislist)
```
## 중복 허용
목록은 색인화되어 있으므로 목록에는 동일한 값을 가진 항목이 있을 수 있다.
```언어
thislist = ["apple", "banana", "cherry", "apple", "cherry"]
print(thislist)
```
## 목록 길이
len()함수를 사용하면, 목록에 포함된 항목 수를 확인할 수 있다.
```언어
thislist = ["apple", "banana", "cherry"]
print(len(thislist))
```
## 목록 항목 - 데이터 유형
목록 항목은 모든 데이터 유형이 될 수 있다.
```언어
list1 = ["apple", "banana", "cherry"]
list2 = [1, 5, 7, 9, 3]
list3 = [True, False, False]
```
## 유형() 
Python의 관점에서 목록은 'list' 데이터 유형을 가진 객체로 정의된다.
<class 'list'>
## list() 생성자
새 목록을 만들 때 사용한다.
```언어
thislist = list(("apple", "banana", "cherry")) # note the double round-brackets
print(thislist)
```
## Python 컬렉션(배열)
Python 프로그래밍 언어에는 네 가지 컬렉션 데이터 유형이 있다.
목록은 순서가 지정되고 변경 가능한 모음이다.중복 회원을 허용한다.
튜플(Tuple) 은 순서가 지정되고 변경할 수 없는 컬렉션이다. 중복 회원을 허용한다.
세트 는 순서가 없고, 변경할 수 없으며 색인이 생성되지 않은 컬렉션이다. 중복된 회원이 없다.
사전은 주문되고 변경 가능한 모음이다. 중복된 회원이 없다.
## 튜플
튜플은 단일 변수에 여러 항목을 저장하는 데 사용된다.
튜플은 순서가 지정되고 변경할 수 없는 컬렉션이다.
튜플은 둥근 ​​괄호로 작성된다.
```언어
thistuple = ("apple", "banana", "cherry")
print(thistuple)
```
## 튜플 항목
튜플 항목은 순서가 지정되고 변경할 수 없으며, 중복 값을 허용한다.
튜플 항목은 색인이 생성되고 첫 번째 항목에는 index가 있고 [0] 두 번째 항목에는 index [1]가 있다.
## 중복 허용
플은 인덱싱되므로 동일한 값을 가진 항목을 가질 수 있다.
```언어
thislist = ["apple", "banana", "cherry", "apple", "cherry"]
print(thislist)
```
## 튜플 길이
len() 함수를 사용해서 튜플에 포함된 항목 수를 확인한다.
```언어
thistuple = ("apple", "banana", "cherry")
print(len(thistuple))
```
## 하나의 항목으로 튜플 생성
항목이 하나만 있는 튜플을 만들려면 항목 뒤에 쉼표를 추가해야 한다. 
```언어
thistuple = ("apple",)
print(type(thistuple))

#NOT a tuple
thistuple = ("apple")
print(type(thistuple))
```
## tuple() 생성자
튜플을 생성한다.
```언어
thistuple = tuple(("apple", "banana", "cherry")) # note the double round-brackets
print(thistuple)
```
## 세트
세트는 단일 변수에 여러 항목을 저장하는 데 사용된다.
세트는 순서가 없고 , 변경할 수 없으며 , 색인이 생성되지 않은 컬렉션이다.
세트 항목은 변경할 수 없지만, 항목을 제거하고 새 항목을 추가할 수 있다.
세트는 중괄호로 작성된다.
```언어
thisset = {"apple", "banana", "cherry"}
print(thisset)
```
중복된 값은 무시된다.
```언어
thisset = {"apple", "banana", "cherry", "apple"}

print(thisset)
```
값 True 과 1세트에서는 동일한 값으로 간주되며 중복 항목으로 처리된다.
```언어
thisset = {"apple", "banana", "cherry", True, 1, 2}

print(thisset)
```
값 False 과 0세트에서는 동일한 값으로 간주되며 중복 항목으로 처리된다.
```언어
thisset = {"apple", "banana", "cherry", False, True, 0}

print(thisset)
```
## set() 생성자
세트를 생성한다.
```언어
thisset = set(("apple", "banana", "cherry")) # note the double round-brackets
print(thisset)
```
### 사전
사전은 키:값 쌍으로 데이터 값을 저장하는 데 사용된다.
사전은 순서가 지정되고, 변경 가능하며 중복이 허용되지 않는 모음이다.
사전은 중괄호로 작성되며 키와 값을 갖는다.
```언어
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)
```
## 사전 항목
사전 항목은 순서가 지정되고 변경 가능하며 중복이 허용되지 않는다.
사전 항목은 키:값 쌍으로 표시되고, 키 이름을 사용하여 참조할 수 있다.
사전의 "브랜드" 값을 인쇄한다.
```언어
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict["brand"])
```
## 중복은 허용되지 않는다
사전에는 동일한 키를 가진 두 개의 항목이 있을 수 없다.
중복된 값은 기존 값을 덮어쓴다.
```언어
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964,
  "year": 2020
}
print(thisdict)
```
## dict() 생성자
사전을 생성한다.
```언어
thisdict = dict(name = "John", age = 36, country = "Norway")
print(thisdict)
```
### Python 조건 및 If 문
Python은 수학의 일반적인 논리적 조건을 지원한다.
같음: a == b
같지 않음: a != b
미만: a < b
작거나 같음: a <= b
보다 큼: a > b
이상: a >= b
```언어
a = 33
b = 200
if b > a:
  print("b is greater than a")
```
## 엘리프
elif 키워드 는 "이전 조건이 true가 아니면 이 조건을 시도해라" 라고 말하는 Python의 방식이다.
```언어
a = 33
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
```
else 키워드는 이전 조건에서 포착되지 않은 모든 항목을 포착한다.
```언어
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")
```
## 중첩된 경우
if명령문 안에 명령문이 있을 수 있고, 이를 중첩된 명령문 if 라고 한다.
```언어
x = 41

if x > 10:
  print("Above ten,")
  if x > 20:
    print("and also above 20!")
  else:
    print("but not above 20.")
```
## 패스 설명
if문은 비워둘 수 없지만, 어떤 이유로 if내용이 없는 문이 있는 경우 pass오류가 발생하지 않도록 문을 입력할 것.
```언어
a = 33
b = 200

if b > a:
  pass
```
### Python While 루프
Python에는 두 가지 기본 루프 명령이 있다.
while 루프 - 조건이 참인 한 일련의 명령문을 실행할 수 있다.
```언어
i = 1
while i < 6:
  print(i)
  i += 1
```
for 루프 - 시퀀스(즉, 목록, 튜플, 사전, 집합 또는 문자열)를 반복하는 데 사용된다.
for 루프 를 사용하면 목록, 튜플, 집합 등의 각 항목에 대해 한 번씩 일련의 명령문을 실행할 수 있다.
```언어
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
```
## break 문
while 조건이 true인 경우에도 루프를 중지할 수 있다.
```언어
i = 1
while i < 6:
  print(i)
  if i == 3:
    break
  i += 1
```
## 계속 진술
continue 문을 사용하면, 현재 반복을 중지하고 다음을 계속할 수 있다.
```언어
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)
```
## else 문
else 문을 사용하면, 조건이 더 이상 참이 아닐 때 코드 블록을 한 번 실행할 수 있다.
```언어
i = 1
while i < 6:
  print(i)
  i += 1
else:
  print("i is no longer less than 6")
```
## 문자열을 통한 반복
문자열도 반복 가능한 객체이므로 일련의 문자를 포함한다.
```언어
for x in "banana":
  print(x)
```
## break 문
break 문을 사용하면 모든 항목을 반복하기 전에 루프를 중지할 수 있다.
```언어
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break
```
## 계속 진술
continue 문을 사용하면 루프의 현재 반복을 중지하고 다음을 계속할 수 있다.
```언어
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue
  print(x)
```
## range() 함수
지정된 횟수만큼 코드 세트를 반복하려면, range() 함수를 사용할 수 있다.
range () 함수는 기본적으로 0부터 시작하여 1씩 증가하고(기본적으로), 지정된 숫자에서 끝나는 일련의 숫자를 반환한다.
```언어
for x in range(6):
  print(x)
```
 ## For 루프의 Else
 else루프 의 키워드는 루프 for가 완료될 때 실행될 코드 블록을 지정한다.
```언어
for x in range(6):
  print(x)
else:
  print("Finally finished!")
```
## 중첩 루프
중첩 루프는 루프 내부의 루프이다.
"내부 루프"는 "외부 루프"가 반복될 때마다 한 번씩 실행된다.
```언어
adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
  for y in fruits:
    print(x, y)
```
## 패스 설명
for루프는 비워둘 수 없지만, 어떤 이유로든 내용이 없는 루프가 있는 경우 오류가 발생하지 않도록 명령문을 for입력한다.
```언어
for x in [0, 1, 2]:
  pass
```
