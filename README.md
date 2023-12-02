# EarnMoney

## 필요 라이브러리
* pandas
* FinanceDataReader
* matplotlib
* requests
* datatime
* bs4(beautifulsoup)
* mplfinance
* numpy

## 동작 과정
Dow Jones와 KOSPI의 상관 관계를 보여주는 산점도 그래프가 출력된다.
![image](https://github.com/Yorushiku0v0/EarnMoney/assets/152679231/30c303ff-1dda-4478-9e04-5873051436cb)

위 둘의 상관 계수 계산하여 출력한다.
![image](https://github.com/Yorushiku0v0/EarnMoney/assets/152679231/8d6e672d-df60-4fb3-ac66-d39a2c411e1a)

웹 크롤링을 통해 KRX로부터 상장 법인 목록을 불러온다.
![image](https://github.com/Yorushiku0v0/EarnMoney/assets/152679231/c9090824-6db7-4823-a888-4e326a50e0ff)

사용자로부터 위 법인 목록을 참고하여 인덱스를 입력받는다.
![image](https://github.com/Yorushiku0v0/EarnMoney/assets/152679231/1650aa49-179b-4765-b73c-a2cc93e5d05d)

사용자가 입력한 인덱스에 해당하는 종목의 주가 데이터프레임, 변동 그래프, 캔들차트 등 다양한 정보를 출력한다
![image](https://github.com/Yorushiku0v0/EarnMoney/assets/152679231/aaa5cafb-91bb-4d0f-b9be-6bdb786f58d7)
![image](https://github.com/Yorushiku0v0/EarnMoney/assets/152679231/45d5fc55-47e0-41f2-8b87-c2269f361e48)
![image](https://github.com/Yorushiku0v0/EarnMoney/assets/152679231/84be6214-d850-466e-aa5a-cf066170820c)

마지막으로 종목 매수, 매도 타이밍의 지표인 볼린저 밴드를 출력한다
![image](https://github.com/Yorushiku0v0/EarnMoney/assets/152679231/55346e02-9c2d-4b0f-9e29-5c8bdf80ca0c)

## 개인적인 견해
얼핏 보면 나무, 영웅문S와 같은 주식 매매 어플리케이션에서 지원하는 작은 기능들이다. 하지만 누군가가 만들어놓은 것을 단순 사용하는 것과 직접 구현하는 것은 큰 차이가 있다고 생각한다.
해당 기능들의 구현을 통해, 웹 크롤링의 구현에 대해 공부할 수 있었고, 데이터프레임의 접근 방식과 구조에 대해서 알 수 있었다. 이를 기반으로 더 나아간다면, 뉴스 내용 토큰화를 통한 내용 분석과 같은 고난도의 기능도 구현할 수 있을 것이다.

## 참고 자료
웹 크롤링과 데이터프레임 분석 참고
https://wikidocs.net/book/8434
