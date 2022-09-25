# 2022-Hackathon
2022 KNU SW Hackathon /
Team Member : 김진현 이상희 송우승 주보경
팀명 : 내 퍼스널 컬러는 해커톤
제출 세션 및 주제 : 자유세션 – 행복페이 가맹점 지도
프로젝트 한 줄 설명 : 행복페이 사용가능한 가맹점에 대한 데이터에 접근성을 높이기 위해 안드로이드 스튜디오와 데이터 크롤링 기술을 활용하여 해결
* * *
**프로젝트에 대한 설명** : 행복페이는 대구에서만 가능한 지역화폐로써 선불로 조금 저렴하게 구매 하여 사용할 수 있습니다. 2021년에는 발행한도가 모두 소진될 정도로 행복페이에 대한 수요가 많습니다. 그러나 행복페이가 사용가능한 가맹점에 대한 정보에 대한 접근성은 매우 좋지 않습니다. 사용가능한 지점을 알아보기 위해선 인터넷에서 직접 검색을 해서 해당 지점이 목록에 있는지 확인해야하는 시스템입니다.
 저희 팀은 그 부분에 대한 불편함을 해결하고 수요를 더 늘여 지역경제활성화에 기여할 수 있는 시스템을 개발했습니다. 지도 앱을 활용하여 사용자의 핸드폰 GPS를 이용해 사용자 근처에 위치한 행복페이 가맹점의 위치를 표시합니다. 또한 사용자가 원하는 지점의 위치를 알려줄 수 있는 검색 기능도 추가하였습니다. 더불어 식당/편의시설/편의점, 마트 등 카테고리로 나누어 확인할 수 있어 더욱더 원하는 정보만 효율적으로 얻을 수 있습니다. 
 대구광역시 마스코트인 도달쑤 캐릭터를 활용하여 친근감있고 귀여운 디자인으로 직접 제작하여 사용자들의 만족감을 높일 수 있습니다. 또한 행복페이 카드 충전 및 잔액확인, 지역사랑 상품권 구매 등이 가능한 아임샵과도 연동이 되어 더욱더 편리하게 사용 가능하도록 설계하였습니다. 2022년부터 삼성페이, IC칩이 내장된 카드로 발급되는 등 훨씬 더 많은 수요가 기대되는 만큼 우리 주변에 행복을 알려주는 저희 ‘우주행복’ 서비스는 더 많은 대구 시민들에게 편리함을 제공할 것입니다. 
* * *
**기능구현 설명**
1. 자바-xml 기반 안드로이드 스튜디오로 안드로이드 앱 개발
안드로이드 스튜디오로 어플리케이션의 기본 레이아웃 및 대부분의 기능을 구현하였습니다. 카카오맵 API는 안드로이드내에 시뮬레이터로는 실행이 안돼 안드로이드 기종 기기를 연결하여 실행하였습니다. 
![image](https://user-images.githubusercontent.com/87298145/192125252-32d80359-c538-4bf1-95ce-383384ae25fe.png)
-	로딩화면 디자인
-	마커 및 각종 아이콘 디자인
-	레이아웃 디자인
-	마커 클릭 시 이벤트
-	손가락으로 줌 인/아웃에 따라 지도 조절
-	검색 기능
-	외부 앱으로 연동

2.카카오맵 API
[kakao](https://developers.kakao.com/) 에서 무료배포하는 카카오맵 API를 활용하여 서비스의 주가 되는 지도 기능 구현
-	현재 기기 위치 표시
-	데이터에서 읽어온 위치를 바탕으로 행복페이 가맹점 마커 표시
-	사용자 위치 주변 가맹점만 필터링되어 표시

3.파이썬 기반 데이터 크롤링
파이썬 기반으로 위치와 상호명 사업자 번호 등을 읽어와 엑셀 파일로 저장
-	카테고리 별로 나누어 저장됨
![image](https://user-images.githubusercontent.com/87298145/192125287-1354fa35-30bc-4a95-b9d5-09daa005e4f6.png)

* * *
**시연영상**
[youtube](https://youtu.be/y1lvDlUhan0)
