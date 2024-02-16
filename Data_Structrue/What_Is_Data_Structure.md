# 자료구조란 무엇인가?

-   자료구조에서는 데이터를 표현하고 저장하는 방법에 대해서 설명한다.
    
-   우리는 C언어를 공부하면서 다음과 같은 이야기를 접한적이 있다.
    
-   "프로그램이란 데이터를 표현하고, 그렇게 표현된 데이터를 처리하는 것이다." 위에서 말하는 '데이터의 표현'은 '데이터의 저장'을 포함하는 개념이다. 그리고 이렇듯 '데이터의 저장'을 담당하는 것이 바로 자료구조이다.
    

ex)

1\. "정수를 저장하기 위해서 int형 변수를 선언"

2\. "개인정보를 저장하기 위한 목적으로 구조체 정의"

넓은 의미에서 int형 변수도, 구조체의 정의도 자료구조에 속한다. int형 변수도, ,구조체도 데이터를 표현 및 저장하는 하나의 방법이기 때문이다. 뿐만 아니라 배열도 자료구조의 일종이다.

## 기본적인 자료구조의 분류

-   .선형구조 - 리스트 , 스택, 큐
    
-   .비선형구조 - 트리, 그래프
    
-   .파일구조 - 순차파일, 색인파일, 직접파일
    
-   .단순구조- 정수, 실수, 문자, 문자열
    

\*자료구조 학습법에 대한 분류

\-자료구조 모델 자체에 대한 이해를 강조한 학습법

\-코드 레벨에서 자료구조의 구현을 강조한 학습법

코드레벨 구현도 중요하지만 자료구조 모델자체에 대한 이해가 더 중요하다.

## 알고리즘 성능 분석

## 시간 복잡도(Time Complexity)와 공간 복잡도(Space Complextiry)

알고리즘은 동작여부 뿐 아니라 성능 까지 보장받을 수 있어야 좋은 코드이다. 때문에 자료구조와 알고리즘을 분석하고 평가할 수 있어야한다.

알고리즘 평가 요소 두가지

"어떤 알고리즘이 어떠한 상황에서 더 빠르고 또 느리냐?" -'속도'

"어떤 알고리즘이 어떠한 상황에서 메모리를 적게 쓰고 또 많이 쓰냐?" - '메모리의 사용량'

속도에 해당하는 알고리즘의 수행시간 분석결과를 가리켜 '시간 복잡도'라 하고, 메모리 사용량에 대한 분석결과를 가리켜 '공간 복잡도'라 한다.

\-------------------------------------------------------------------------------------------------------------

출처 : 윤성우의 열혈자료구조