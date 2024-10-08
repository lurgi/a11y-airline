# ✈️ 누구나 접근할 수 있는 항공사 웹사이트

항공사 웹사이트 컴포넌트의 스크린 리더 접근성 높이기

1. 컴포넌트 접근성 개선 - 이미지 캐로셀
   항공사 홈페이지 메인 화면에 아래와 같이 지금 프로모션 진행 중인 노선과 가격 정보를 제공해주려 합니다.
   프로모션 정보를 제공해주기 위한 이 섹션을 스크린 리더가 읽을 수 있게 개선해 주세요.

   - [x] 스크린 리더가 캐로셀의 전체 아이템 수를 읽을 수 있어야 합니다.
   - [x] 스크린 리더가 이미지 캐로셀 내 각 아이템 정보를 읽을 수 있어야 합니다.
     - [x] 여행지, 좌석 유형, 가격 정보를 한번에 읽을 수 있어야 합니다.
     - [x] 이전/다음 아이템으로 이동하고 현재 보이는 아이템의 정보를 읽을 수 있어야 합니다.
   - [x] 각 아이템을 선택하면 각각에 맞는 링크로 이동할 수 있어야 합니다.

2. 페이지 접근성 개선
   사전 미션과 본 미션에서 구현한 내용을 합쳐서 하나의 페이지를 구성합니다.
   완성한 페이지의 접근성을 점검하고 개선해 주세요.

   - [x] 페이지를 하나의 문서로 읽을 수 있어야 합니다.
     - [x] 페이지에 적절한 제목(title)을 제공하세요. 제목은 페이지의 주요 내용을 간결하게 설명해야 합니다.
     - [x] 페이지의 주요 영역을 시맨틱 태그를 사용해 명확히 구분해 주세요
     - [x] 헤딩을 논리적인 순서로 사용해 페이지 구조를 명확히 해주세요
   - [x] 키보드 사용자를 위해 페이지 최상단에 '본문으로 바로가기' 링크를 제공해 반복되는 메뉴를 건너뛸 수 있게 해주세요

3. 🚚 추가 도전 과제
   필수 요구 사항을 다 완료한 뒤, 접근성 개선을 더 연습해보고 싶다면 아래 선택 요구 사항에도 도전해 보세요.

   선택 요구 사항) 팝업 모달 포커스 트랩
   항공사 앱을 새로 론칭하여 홍보하는 팝업 모달을 띄우기로 하였습니다.

   - [x] 스크린 리더로 진입했을 때에도 현재 팝업이 떴다는 것을 인지할 수 있게 개선해 주세요.
   - [x] 팝업이 열려있는 동안에는 포커스 이동이 팝업 내에서만 이루어져야 합니다.
   - [x] 스크린 리더로 팝업을 닫을 수 있어야 합니다.
   - [x] 키보드 접근성을 함께 고려합니다. (키보드만으로도 팝업으로 바로 진입해서 팝업을 닫을 수 있어야 합니다)
