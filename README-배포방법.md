# LiftLog 휴대폰 배포 방법

이 폴더 전체를 웹에 올리면 됩니다. 시작 파일은 `workout-log.html`입니다.

## 가장 쉬운 방법: Netlify Drop

1. 휴대폰과 PC에서 같은 주소로 쓰려면 [Netlify Drop](https://app.netlify.com/drop)에 로그인합니다.
2. 이 `outputs` 폴더를 페이지에 끌어 놓습니다.
3. 만들어진 `https://...` 주소를 휴대폰에서 엽니다.
4. iPhone은 Safari 공유 버튼 → **홈 화면에 추가**, Android는 Chrome 메뉴 → **앱 설치**를 선택합니다.

## GitHub Pages

GitHub 저장소에 이 폴더의 파일을 올린 뒤, 저장소의 **Settings → Pages**에서 배포 브랜치와 폴더를 선택하세요. 생성된 주소에서 `/workout-log.html`을 열면 됩니다.

## 알아둘 점

- 설치 뒤에는 인터넷이 없어도 앱 화면을 열 수 있습니다.
- 운동 기록은 현재 각 기기의 브라우저에 따로 저장됩니다. PC와 휴대폰을 자동 동기화하려면 다음 단계에서 온라인 데이터 저장소를 연결해야 합니다.
