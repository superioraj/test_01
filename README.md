🐍 Snake Game (HTML / CSS / JavaScript — Single File)
화살표 키로 조작하는 클래식 스네이크 게임입니다.
HTML, CSS, JavaScript가 모두 하나의 HTML 파일 안에 포함되어 있어 바로 실행할 수 있습니다.

  https://img.shields.io/badge/HTML-5E5E5E?logo=html5&logoColor=white
  https://img.shields.io/badge/JavaScript-efd81d?logo=javascript&logoColor=black
  https://img.shields.io/badge/CSS-254BDD?logo=css3&logoColor=white


🎮 Features

화살표 키(↑ ↓ ← →)로 스네이크 조작
먹이를 먹으면 길이 증가
벽 또는 몸 충돌 시 게임 오버
점수 표시
5점마다 자동으로 속도 증가(가속)
모든 코드가 한 HTML 파일에 포함
Enter 키로 게임 재시작
깔끔한 다크 UI + 그리드 + 라운드 스네이크 디자인


📝 How to Play





















조작설명↑ ↓ ← →방향 이동방향키첫 입력 시 게임 시작Enter게임 오버 후 재시작

📁 Project Structure
snake.html   # HTML + CSS + JavaScript가 모두 포함된 단일 실행 파일


🚀 How to Run

이 저장소를 다운로드하거나 클론합니다.
snake.html 파일을 브라우저에서 열기만 하면 바로 실행됩니다!

Chrome
Edge
Safari
Firefox
등 모든 최신 브라우저 지원




📸 Screenshot (Optional)
필요하시면 아래처럼 스크린샷 섹션을 GitHub에 추가해도 좋습니다:
!game screenshot


🔧 Code Overview

Canvas API로 게임판을 렌더링
SetInterval 기반 루프로 게임 진행
먹이 배치는 뱀 몸과 겹치지 않도록 처리
방향 전환은 반대 방향 금지(자기 몸 충돌 방지)
게임 상태는 JS 객체로 관리

snake[]
food
direction
score
tick interval




📦 Future Improvements (Optional)
원하시면 GitHub에 이런 개선 아이디어도 남길 수 있어요:

난이도 선택 메뉴
최고 점수(LocalStorage)
벽 통과(토로이드 맵) 모드
모바일 터치 패드 버튼 추가
더 다양하고 예쁜 스네이크 스킨


📜 License
이 프로젝트는 자유롭게 수정/배포할 수 있습니다.
별도 라이선스가 필요하다면 MIT License 추가를 추천드립니다.
