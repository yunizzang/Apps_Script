# Digital Lending Partner Web UI Compliance 자동 검증 (Selenium /xPath + CI)
1) 프로젝트 목적 / 배경
파트너 사이트 UI 변경(DOM/XPath 등)으로 인한 규격 위반을 조기 탐지하여 컴플라이언스 리스크(앱스토어 제재 가능성) 및 수동 점검 비용을 감소시키기 위해  자동화 도입
**디지털 렌딩 파트너 사이트에서 당사가 적합하게 표시되는지 확인**
  - Selenium 기반 파트너 사이트 변경 감지 자동화 스크립트 개발
  - DOM 구조 변화 및 XPath 변경 자동 감지 → UI 안정성 및 규격(Compliance) 유지
  - Jenkins CI 파이프라인에 통합하여, 빌드 발생 시 자동 실행되도록 구성
2) 나의 역할 (리드 및 설계)
•	검증 범위/항목 및 실패 기준 정의(표시, 문구, 링크, 위치)
•	Selenium(Python) 기반 구조 설계, 구현 방향 제시 및 코드리뷰 운영가이드 정립
•	Jenkins CI 파이프라인에 통합하여 빌드/스케줄 기반 자동 실행 체계 구축
3) 핵심구현
•	DOM구조 변화 및 XPath 변경을 감지하는 방식으로 하드코딩 최소화
•	실패 시 변경 지점 / 영향범위 중심의 리포트 생성 – 스크린 캡쳐 화면 저장
4) 성과 
•	파트너 UI 변경을 조기에 탐지하여 수동 점검 부담을 감소
•	규격 위반 가능성을 사전에 차단하여 컴플라이언스 리스크 감소


    
<img width="1259" height="720" alt="image" src="https://github.com/user-attachments/assets/e05844fc-7bfc-46b9-8ba5-625986aeace2" />

