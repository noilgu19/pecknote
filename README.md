# 콕!노트(PeckNote) 시험판

화면의 일부나 선택한 글에 메모를 붙이고, 여러 메모·주변 맥락을 하나의 요청으로 정리하는 설치형 앱입니다. 저장하거나 AI 대화의 초안을 준비하며 최종 전송은 사용자가 합니다.

게시자: **noilgu19**. **소스는 공개하지 않습니다. 개인적·비상업적 용도에 한해 무료로 사용할 수 있으며, 현재 재배포와 상업적 사용은 허용하지 않습니다.** [이용 조건](LICENSE.md)을 확인하세요. 이 저장소는 설치 파일·공개 안내·문제 신고를 위한 곳입니다.

## 다운로드

[macOS Apple Silicon / Windows x64 최신 릴리스](https://github.com/noilgu19/pecknote/releases/latest)에서 Mac ZIP 또는 Windows setup.exe를 받으세요. 이름에 ‘시험판’을 표시한 일반 릴리스로 게시합니다. 이전 버전은 [전체 릴리스 목록](https://github.com/noilgu19/pecknote/releases)에서 확인하세요. Intel Mac 빌드는 없습니다.

## 처음 실행

- **Mac:** ZIP을 풀고 PeckNote.app을 응용 프로그램 폴더로 옮깁니다. Finder와 시스템 설정의 권한 목록에는 한국어 시스템에서 콕!노트, 영어 시스템에서 PeckNote로 표시됩니다. Apple 공증을 받지 않은 시험판이므로 첫 실행이 차단되면 시스템 설정 › 개인정보 보호 및 보안 › **그래도 열기**에서 허용합니다. 화면 기록은 화면 캡처, 손쉬운 사용은 다른 앱의 선택 글 읽기와 사용자가 요청한 붙여넣기에 필요합니다. macOS 자체 화면 기록 알림이 반복될 수 있습니다.
- **Windows:** 현재 사용자 계정에 설치합니다. 서명되지 않은 설치 파일의 ‘Windows의 PC 보호’ 안내는 **추가 정보 › 실행**에서 진행합니다. **Smart App Control이 켜져 있으면 실행할 수 없습니다.** WebView2가 없으면 설치 중 bootstrapper를 인터넷으로 내려받습니다. 조직 보안 정책을 따르세요.

## 사용 방법

1. **콕 짚기:** 다른 앱 위에서 화면 메모 단축키(Mac ⌥+Shift+M, Windows Alt+Shift+M)를 누르고 화면의 한 부분을 드래그한 뒤 말풍선에 메모를 적어 저장합니다. Mac에서는 ⌥+Shift+T로 글 메모 모드를 켜고 다른 앱의 문장을 드래그해 메모할 수도 있습니다.
2. **메모 모으기:** 같은 방법으로 메모를 모읍니다. 모은 메모는 ‘메모 모음’ 창에서 고르고 **프롬프트 만들기**로 하나의 요청 글로 묶습니다.
3. **AI에 넘기기:** Mac은 **붙여넣기 준비**를 누르고 AI 입력창을 클릭한 뒤 ⌥+Shift+V를 누릅니다. Windows는 **경로와 함께 복사**를 누르고 같은 PC의 터미널 에이전트 입력창에 붙여넣습니다(웹 채팅에는 **다른 방법**의 **화면+요청 복사**). 전송은 직접 합니다.

처음 따라 하는 과정은 앱 화면 그림으로 된 [그림으로 따라 하기](https://noilgu19.github.io/pecknote/tutorial.html)에, 단축키 표, 가리기, 다른 컴퓨터로 넘기기, 문제 해결은 [사용 방법](https://noilgu19.github.io/pecknote/guide.html)에 있습니다.

## 범위와 업데이트

Windows는 영역 캡처를 제공하며 글 메모는 아직 없습니다. 앱별 글 선택·다중 모니터·배율과 Windows 실제 설치는 추가 확인이 필요합니다. AI에 자동 전송하지 않습니다. 앱은 시작 시 하루에 한 번까지 업데이트를 확인하며 설정에서 수동 확인할 수 있습니다. ‘지금 업데이트’를 누르면 리뷰를 저장하고 다운로드·서명 검증 뒤 다시 시작합니다.

## 개인정보와 의견

리뷰·캡처·선택 글은 컴퓨터에 보관합니다. 사용자가 보관함 전송이나 의견 보내기를 선택하면 해당 내용이 전송됩니다. 업데이트 확인 시 호스트는 네트워크 주소를 볼 수 있습니다. [개인정보 안내](PRIVACY.md)와 [오픈소스 고지](THIRD-PARTY-NOTICES.md)를 읽어 주세요. [안내 사이트](https://noilgu19.github.io/pecknote/)에도 같은 안내가 있습니다.

앱 설정의 ‘제작자에게 의견 보내기’ 또는 이 저장소의 [이슈](https://github.com/noilgu19/pecknote/issues)를 이용하세요. 공개 이슈에는 비밀·접속 키·개인 화면·개인정보를 올리지 마세요. 의견 삭제 요청도 접수 ID가 있다면 ID만 적어 이슈에 남길 수 있습니다.

## 개발 후원

개발을 응원하고 싶다면 [Buy Me a Coffee](https://buymeacoffee.com/pecknote)(해외 카드)나 [카카오페이 송금](https://qr.kakaopay.com/FI0dPSyXu)(국내)으로 후원할 수 있습니다. 카카오페이 송금은 휴대폰에서만 열리므로 PC에서는 [안내 사이트](https://noilgu19.github.io/pecknote/)의 QR 코드를 휴대폰으로 찍어 주세요. 후원은 선택이며 앱 기능은 달라지지 않습니다.

## English

PeckNote is a trial for collecting screen and text annotations and preparing a prompt for an AI conversation. It is free for personal, non-commercial use only; redistribution and commercial use are not permitted for now. The source is not published. Publisher: noilgu19. See [Terms of use](LICENSE.md).

A step-by-step how-to (in Korean) is at the [guide](https://noilgu19.github.io/pecknote/guide.html).

Download the Apple Silicon Mac ZIP or Windows x64 installer from [latest release](https://github.com/noilgu19/pecknote/releases/latest), or [all releases](https://github.com/noilgu19/pecknote/releases) for earlier versions. Trial builds are published as regular releases titled 시험판. No Intel Mac build; Windows text annotations are not available yet. Nothing is sent to an AI automatically.

On Mac, the app is not Apple-notarized: allow it in System Settings › Privacy & Security › Open Anyway. Screen Recording captures the screen; Accessibility reads selected text and supports requested pasting. macOS may repeat its recording reminder. On Windows, use More info › Run anyway on SmartScreen; the app cannot run with Smart App Control enabled. Installation is per user and downloads WebView2 if needed.

Reviews stay locally; sending to your configured inbox or sending product feedback is your choice. Update hosts see your network address. Read [privacy](PRIVACY.md) and [third-party notices](THIRD-PARTY-NOTICES.md). Send feedback from app settings or [public issues](https://github.com/noilgu19/pecknote/issues); never include secrets or private screenshots.

If you would like to support development: [Buy Me a Coffee](https://buymeacoffee.com/pecknote), or [KakaoPay](https://qr.kakaopay.com/FI0dPSyXu) within Korea (opens on a phone only; the site shows a QR code). It is optional and changes nothing in the app.
