# EV-charging-station-location-analysis-in-YonginSi

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [METHOD](#METHOD)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
<분석 배경>
최근 화석연료의 가격 상승과 환경 문제의 심화로 인해 정부에서도 전기차 보급 정책을 마련해 실행하고 있고, 이에 따라 국내 전기차 보급대수는 2014년 1075대 판매를 시작으로 2022년 현재 누적 30만대를 돌파 하게 되었다. 또한 xEV TREND KOREA 2022의 조사 결과에 의하면 전기차 구매 의향을 묻는 질문에 95%가 긍정적인 의사를 밝혔으며, 이 중 59%가 3년 이내에 구입하겠다고 응답했다. 하지만 수 년이 지난 현재에도 늘어난 전기차 보급과 수요에 비해 아직 전기 자동차 인프라는 부족한 실정이다. 특히 충전기 설치 속도가 전기차 보급 확산 추세에 따라가지 못하는 점이 내연기관 자동차 운전자들이 전기차 구매를 주저하는 주요 요인이 되고 있다. 따라서 정부의 전기차 보급 확대를 위해서는 무엇보다도 적절한 전기차 충전소 설치가 필요하다.
경기도와 용인시 또한 정부의 정책과 동일하게 보조금 등의 보급 정책을 시행하며 충전 인프라 확충에 나서고 있다. 이에 발맞춰 행정동별 수요지수 개발, 설치장소별 수요점수 스코어링과 수익성 계산을 통해 데이터를 분석해서 입지를 선정하여 용인시 내에서 최고의 수익성을 충족할 수 있는 최적의 완속 충전소 최종 입지를 추천함으로써 최종적으로는 전기차 보급과 충전 인프라 최적화에 기여하고자 한다.

## Technologies Used
- python
- QGIS


## METHOD

![image](https://user-images.githubusercontent.com/113409289/196112279-61d6c785-3081-4b32-89c2-48fbb3312dd0.png)

평균 충전시간이 7~8시간으로 긴 완속충전의 특성상, 효율적인 입지 선정을 위해서 주거지와 직장과 같은 생활거점에 집중적으로 완속 충전소를 설치할 필요가 있다. 따라서 입지는 아파트, 공동주택, 업무시설, 공공기관, 주차장 등으로 한정되어 있다. 각 목적지의 정확한 기종점 수요를 분석하기 위해 위 입지를 거주지, 활동지로 나누어 해당하는 유형의 건물로 특정했다. 또한 현재 전기차 보급이 많이 운행되고 있는 지역뿐만 아니라 신규 충전 인프라 구축에 따라 증가할 신규 전기차 수요에 대응하기 위해 각 입지의 수요를 현재수요와 잠재수요로 나누어 분석했다. 도출된 거주지/활동지의 행정동별 수요지수와 건물별 현재/잠재수요를 결합하고 최대수요와 비용의 최소화를 고려하기 위해 기설치된 충전기 수를 활용하여 최종 입지를 선정하였다.


## Project Status
Project is: _complete_ / _no longer being worked on_


## RESULT

<img width="500" alt="Screenshot 2022-10-17 at 4 16 47 PM" src="https://user-images.githubusercontent.com/113409289/196113243-24f23b61-4374-49fc-b258-bf8b596aac2f.png">

<img width="500" alt="Screenshot 2022-10-17 at 4 16 54 PM" src="https://user-images.githubusercontent.com/113409289/196113222-0b33e586-28c8-4ea9-91ac-cd85e0a425a3.png">

<img width="500" alt="Screenshot 2022-10-17 at 4 17 15 PM" src="https://user-images.githubusercontent.com/113409289/196113419-98ae4382-710a-4851-9168-23d1a034c60d.png">



## Contact
Created by (summercheriy@gmail.com) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
