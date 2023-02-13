**목차**

- [join](#join)
- [특수문자 출력](#특수문자-출력)



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

