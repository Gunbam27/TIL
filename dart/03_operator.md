## Dart 기초 문법

### 1. 산술연산자
```
+ : 더하기
- : 빼기
* : 곱하기
/ : 나누기
~/ : 몫
% : 나머지
```

### 2. 증감연산자

```
var a=0;
print(a++); //나중에 계산하므로 0출력
// num= 1이 됨
 print( ++a); //먼저 계산하므로 1출력
// num = 2가 됨
```


### 3. 비교연산자
```
== : 같다
!= : 다르다
> : 더 크다
< : 더 작다
>= : 크거나 같다
<= : 작거나 같다
```

### 4. 논리연산자
```
&& : 그리고
|| : 또는
== : 같다
! : 부정
!= : 다르다
```

### 5. 타입검사
```
is => 같은 타입이면 true
is! => 다른 타입이면 true

int a = 10;

if(a is int){
  print(‘정수’);
}

String text = ’hello’;
if(text is! int){
  print(‘숫자가 아님’);
}
```
### 6. 형변환
as 컴파일 타임에 오류를 알 수 없기에 잘 쓰지 않는다. if문으로 타입검사 후에 쓴다.
```
bool bb = num as bool; 
```
### 7. 삼항연산
```
var todo = isRainy ? ‘빨래를 하지 않는다’ : ‘빨래를 한다’;
```
### 8. compile 언어 vs interpreter 언어
- 컴파일 언어(compiled language)는 코드가 실행되기 전 컴파일러를 거쳐서 기계어로 모두 변환되어 실행되는 프로그래밍 언어이다.
- 인터프리트 언어(interpreted language)는 실행 즉시 인터프리터를 거쳐서 실행되는 프로그래밍 언어이다.

### 9. 매개변수(parameter) vs 인자(arguments)
- 변수로 가정하여 받는 값 = 매개변수
- 실제로 받는 값 = 인자 <br/>

![return paraml + param2;](https://github.com/Gunbam27/TIL/assets/95085649/ee2d941d-963c-4df9-b8df-d0b3348e921d)


