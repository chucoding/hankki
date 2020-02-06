# 한끼줍Show(hankki)

한신대학교 종합설계 3조 투플러스원팀

프로젝트명 : 카카오톡 자동응답 시스템과 GPS를 연동한 챗봇 구현  
팀장 : 서현석  
팀원 : 한유태, 심원형

1. 문제 및 목적
   1. 현재 많이 사용되고 있는 순위권 맛집 어플들의 불편한 접근성
   2. 메신저 카카오톡 플러스 친구의 특별함 없는 기능
   3. 현존하는 챗봇들은 GPS기능이 없는 단순 자동 응답 시스템 혹은 결제시스템

2. 관련 연구
   1. http 서버 - node.js, npm, express 프레임워크(body-parser, express-handlbars)
   2. 응용 프로그램1(인터페이스) - 카카오톡 (Home Keyboard API, 메시지 수신 및 자동응답 API)
   3. 응용 프로그램2(인터페이스) - 웹 홈페이지(Google Maps Javascript API, Geolocation)
 
3. 설계 내용
   시스템 기능 및 기대 효과 - GPS를 이용한 다양한 서비스 창출
   비기능 요구 - 포트포워딩을 통한 외부 IP 접속 허용
   비즈니스 이익 기술 - 음식점 길찾기를 통한 상업용 이익 창출
   시스템 구조(아키텍처)
   <img src="/system-architecture"></img>
   시스템 설계도
   <img src="/system-design"></img>
   
4. 구현 결과

5. 문제점 및 해결책

6. 수행 계획

7. 참고 문헌
   1. LG CNS 강석태, "부상하는 비즈니스 마케팅 채널! 챗봇(ChatBot)", http://blog.lgcns.com/1318, 2017.
   2. 플러스친구 관리자 센터, "API Document", https://center-pf.kakap.com
   3. plusfriendteam, "플러스친구 자동응답 API", https://github.com, 2018.04.19
   4. 나스모에, "ipTime 공유기 포트포워딩", https://nas.moe/archives/93
   5. Google Maps API, "마커가 있는 Google 지도를 웹사이트에 추가", https://developers.google.com
   6. PoiemaWeb, "Node.js"와 MySQL 연동", https://poiemweb.com/nodejs-mysql
