<위험자산을 이용한 최소분산포트폴리오 도출>
=============
학과 | 학번 | 성명
---- | ---- | ---- 
경영학과 | 201743143 | 김수민

## 🛠 프로젝트 목적 및 동기
'계란을 한 바구니에 담지 말라.' 투자를 시작한다면 듣게 되는 투자 격언입니다. 계란을 한 바구니에 담으면 쉽게 깨지듯이,하나의 자산에 올인하기보다 포트폴리오를 통한 분산투자로 위험을 최소화하라는 의미입니다. 그렇다면 개개인은 포트폴리오를 구성한 후, 개별 자산의 투자비중을 어떻게 설정해야 가장 효율적이고 최적화된 투자를 할 수 있을까요?  2개의 자산으로 포트폴리오를 구성한다면 각각의 투자비중을 구하기 쉬울 것입니다. A,B 자산으로 구성했을 때,A 기업이 경영난을 겪고 있다고 가정한다면 A 10%, B 90%로 투자비중을 정하면 될 것입니다. 하지만 포트폴리오 구성 자산 수가 5개, 10개, 그리고 150개가 될 경우에는 어떻게 투자비중을 배분하나요? 감과 촉으로만으로는 개개인이 희망수익률에 따른 가장 효율적인 자산 투자비중을 알아내기 어렵습니다. 또한 임의로 투자비중을 정한다면 이에 따른 예상위험을 예측하기도 힘듭니다.   

따라서 저는 fnguide 에서 제공하는 수정주가 데이터를 이용하여 포트폴리오 최적화 자산배분 비율(투자비중)을 구하는 과정 중
최소분산포트폴리오(위험이 최소가 되는 투자비중)를 도출하는 프로그램을 만들어보려고 합니다.
개인이 선택한 포트폴리오에 따라 가장 위험이 최소가 되는 투자비중을 구하고, 그 비중에 따른 수익과 위험을 구할 것입니다.
차입,대출이 가능한 무위험자산은 제외하고 위험자산만 고려할 예정입니다.

## 📊 사용한 공공데이터
* fnguide 수정주가 수익률 데이터
[데이터보기](https://github.com/cybermin/python2019/blob/master/%EB%B6%80%EC%82%B0%EA%B5%90%ED%86%B5%EA%B3%B5%EC%82%AC_%EB%8F%84%EC%8B%9C%EC%B2%A0%EB%8F%84%EC%97%AD%EC%82%AC%EC%A0%95%EB%B3%B4_20190520.csv)

## 소스
* [링크로 소스 내용 보기](https://github.com/cybermin/python2019/blob/master/tes.py) 

* 코드 삽입
~~~python
items = list(range(1,11))

for i in items:
    print(i)
~~~
