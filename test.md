# 매크로적발
## 배경
대부분의 애플리케이션은 **권한**이 매우 없기에 사용자가 동시에 무슨 어플리케이션을 사용하고 있는지 알 수가 없음

## 적발방법
- 키 입력시간간격,정밀도를 감지 후 기준치와 비교
- 난수처리로 빠져나갈 수도 있지만 난수값의 분포패턴을 분석해서 정교한 정규분포 그래프가 그려지면 매크로로 판정 


but 이중난수화(난수사이에 독립된 값들 10%정도 투입)를 이용하다면 적발이 어려움


=>의심이 가는 유저에게 튜링테스트 실시

[출저](https://gall.dcinside.com/board/view/?id=gfl&no=1196535)


