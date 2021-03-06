# Python-apriori
This repository is Apriori presentation materials and source code for hackfest in February 21-21, 2017.

## Apriori Algorithm
### Introduction to Apriori Algorithm
The Apriori Algorithm is an association rule learning algorithm, which is an algorithm for finding a frequently selected item set.  

### Development environment
In this Hackfest, hackfest team used OSS that implemented Apriori algorithm in python.
* Development Language: python
* Virtual Environments (env): 2.7
* Reference link: https://github.com/asaini/Apriori

### Example of execution
	Python apriori.py -f tesco.csv -s 0.17 -c 0.68

This command extract data with a support of 0.17 and a confidence of 0.68 or higher by using the apiori.py code and the tesco.csv data.

### Performance result
![result](./images/result.PNG)
  
  
***

# python-apriori
2017년 2월 21~23일간 진행된 호갱노노 Hackfest에서 발표한 Apriori 발표자료 및 소스코드를 제공합니다.  

## Apriori Algorithm
### Apriori Algorithm 소개
Apriori Algorithm은 연관규칙 알고리즘(association rule learning)의 일종으로 자주 선택되는 item 집합을 찾기위한 알고리즘 입니다. 

### 개발 환경
이번 Hackfest에서는 python으로 Apriori 알고리즘을 구현한 오픈소스를 이용했습니다. 
* 개발언어 : python
* 가상환경(env) : 2.7
* 참고링크 : https://github.com/asaini/Apriori

### 실행예시
    python apriori.py -f tesco.csv -s 0.17 -c 0.68

apriori.py 라는 파이선 코드와 tesco.csv 데이터 파일을 이용하여 지지도 0.17 및 신뢰도 0.68 이상의 데이터를 추출하는 명령어 입니다.  

### 수행결과
![result](./images/result.PNG)
 