# AIFFEL Campus Online 4th Code Peer Review Templete
- 코더 : 코더 1인의 이름을 작성하세요.
- 리뷰어 : 본인의 이름을 작성하세요.


# PRT(PeerReviewTemplate)
각 항목을 스스로 확인하고 토의하여 작성한 코드에 적용합니다.
- [ ] 1.코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
        코드의 결과값이 없고, 정상적으로 동작하지 않을 것 같습니다.
  ```python
   def first_check(first_input):
        o_to_t = 10/self.total
        e_to_n = 18/self.total
        t_to_t = 11/self.total

        if 0 < first_input <= 10:

        elif 11 <= first_input <= 19:

        else:  
        ### 내용의 부재 ###
  ```        
      
- [ ] 2.주석을 보고 작성자의 코드가 이해되었나요?
  > 위 항목에 대한 근거 작성 필수
        완성된 코드가 아니어서 주석을 보고 코드를 이해할 수 없었습니다.

- [X] 3.코드가 에러를 유발할 가능성이 있나요?
  > 위 항목에 대한 근거 작성 필수
  ```python
   def first_check(first_input):
        o_to_t = 10/self.total
        e_to_n = 18/self.total
        t_to_t = 11/self.total

        if 0 < first_input <= 10:

        elif 11 <= first_input <= 19:

        else:  
  
  ```
    해당 부분에서 else 밑에 부분의 내용이 없기에 코드가 오류가 날 것 같습니다.
  
- [ ] 4.코드 작성자가 코드를 제대로 이해하고 작성했나요?
  > 위 항목에 대한 근거 작성 필수
  ```python
   def distance(not_zero, input):
        not_zero.append(input).sort()
        if len(not_zero) >= 3:
            self.pre_num = abs(not_zero[not_zero.index(input)-1] - not_zero[not_zero.index(input)])
            self.next_num = abs(not_zero[not_zero.index(input)+1] - not_zero[not_zero.index(input)])
  
  ```
    거리 기반의 알고리즘을 활용하여 코드를 완성하고 싶으셨던 것 같은데, 완성까지는 되지 못했습니다.

- [X] 5.코드가 간결한가요?
  > 위 항목에 대한 근거 작성 필수
     클래스로 구현하여 코드가 간결합니다.
```python
   class streams:
    def __init__(self):
        self.score_dict = {1:0, 2:1, 3:3, 4:5, 5:7, 6:9, 7:11, 8:15, 9:20, 10:25, 
                  11:30, 12:35, 13:40, 14:50, 15:60, 16:70, 17:85, 18:100, 19: 150, 20:300}
        self.result = [0]*20
        self.total = 39
        self.pre_num = 0
        self.next_num = 0  

```

# 예시
1. 코드의 작동 방식을 주석으로 기록합니다.
2. 코드의 작동 방식에 대한 개선 방법을 주석으로 기록합니다.
3. 참고한 링크 및 ChatGPT 프롬프트 명령어가 있다면 주석으로 남겨주세요.
```python
# 사칙 연산 계산기
class calculator:
    # 예) init의 역할과 각 매서드의 의미를 서술
    def __init__(self, first, second):
        self.first = first
        self.second = second
    
    # 예) 덧셈과 연산 작동 방식에 대한 서술
    def add(self):
        result = self.first + self.second
        return result

a = float(input('첫번째 값을 입력하세요.')) 
b = float(input('두번째 값을 입력하세요.')) 
c = calculator(a, b)
print('덧셈', c.add()) 
```

# 참고 링크 및 코드 개선
```python
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
