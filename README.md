# prophet_test

시계열 예측 라이브러리 Prophet을 사용해

http://ncov.mohw.go.kr/ 

에서 제공하는 코로나 일일 환자수로 미래의 환자수를 예측해본다.(2021년8월26일 기준)
![file](https://user-images.githubusercontent.com/52062016/131106273-76491f56-488e-4610-a21e-ee4db49d3c58.PNG)

제공되는 데이터는

![image](https://user-images.githubusercontent.com/52062016/131105832-b89071ca-1a2f-488a-b2c5-32775972b511.png)

이런식인데

Prophet에서는 컬럼이 ds, y 로 되어있어야 해서
필요없는 부분은 지우고, 날짜를 ds, 확진자를 y로 바꿔준다.
그리고 천 단위가 쉼표로 구분돼서 쉼표도 지워준다.

![data](https://user-images.githubusercontent.com/52062016/131105738-38bf254d-ee6a-45de-a55d-c2cba8989b5e.PNG)

<사용환경>

윈도우10

아나콘다 4.10.1 & 주피터노트북

prophet 1.0.1

