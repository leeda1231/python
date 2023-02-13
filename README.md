**목차**

- [join](#join)
- [특수문자 출력](#특수문자-출력)
- [sys.stdin.readline](#sysstdinreadline)
- [반올림](#반올림)



# Join

**Definition and Usage**

The `join()` method takes all items in an iterable and joins them into one string.

A string must be specified as the separator.

**Syntax**

`string.join(iterable)`

**Example**

따라서, int형 리스트 같은 경우 아래와 같이 써주어야 한다.

```python
print(''.join(map(str,num_list)))
```





# 특수문자 출력

| 문자 | 설명         |
| ---- | ------------ |
| \n   | 줄바꿈       |
| \t   | 수평 탭(tab) |
| \\\\ | \            |
| \\'  | '            |
| \\"  | "            |





# sys.stdin.readline

한 두줄 입력받는 문제들과 다르게, 반복문으로 여러줄을 입력 받아야 할 때

- `input()`으로 입력 받는다면 시간초과가 발생할 수 있다.
- `sys.stdin.readline()`을 쓰자.

```python
import sys
input = sys.stdin.readline
```

- `sys.stdin.readline()`은 문자열로 입력을 받기 때문에 개행 문자 "\n"을 같이 입력받는다.
  - ex) 문자열\n 
  - `rstrip()`을 쓰자.

```python
import sys
sys.stdin.readline().rstrip()
```



[참고]

https://yeomss.tistory.com/120





# 반올림

- round 함수

```python
print(round(result,3)) # 40.0
```

- % 서식 문자

```python
print("%0.3f"%result) # 40.000
```

