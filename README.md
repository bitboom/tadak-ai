# Tadak AI 사용 가이드

Apple Intelligence를 사용하는 Tadak AI 번역 키의 설정과 사용 방법을 한국어로 안내하는 정적 GitHub Pages 사이트입니다.

## 배포 위치

- GitHub 저장소: `bitboom/tadak-ai`
- GitHub Pages: `https://bitboom.github.io/tadak-ai/`
- 배포 방식: `main` 브랜치의 루트 디렉터리

## 로컬 확인

정적 HTML 사이트이므로 `index.html`을 브라우저에서 바로 열 수 있습니다.

```bash
open /Users/sangwan/dev/tadak-ai/index.html
```

로컬 서버로 확인하려면 다음 명령을 사용합니다.

```bash
cd /Users/sangwan/dev/tadak-ai
python3 -m http.server 4173
```

## 문서 기준

- 모든 본문, 이미지 대체 텍스트, 설명 문구는 한국어 사용자를 기준으로 작성했습니다.
- 스크린샷은 시스템 언어와 Siri 언어를 한국어로 맞춘 iOS 시뮬레이터에서 촬영했습니다.
- Tadak AI는 현재 번역 기능만 설명합니다.
- Apple Intelligence 조건은 Apple 공식 문서를 기준으로 정리했습니다.
- Tadak은 자체 AI 서버로 번역 요청을 보내지 않는다는 설명과 함께, Apple Intelligence가 복잡한 요청에 Private Cloud Compute를 사용할 수 있음을 같이 명시했습니다.

## 스크린샷

실제 화면 캡처만 사용합니다. 주요 파일은 `assets/screenshots/`에 있습니다.

- `apple-intelligence-siri-settings.png`
- `ios-keyboard-settings.png`
- `ios-keyboards-list.png`
- `ios-full-access.png`
- `tadak-ai-settings.png`
- `tadak-ai-language-menu.png`
- `tadak-ai-key-ready.png`
- `tadak-ai-key-processing.png`
- `tadak-ai-key-result.png`

## 참고 링크

- [Lazyweb](https://www.lazyweb.com/)
- [Apple 지원: Apple Intelligence 시작하기](https://support.apple.com/en-euro/121115)
- [Apple 지원: iPhone의 Apple Intelligence와 개인정보 보호](https://support.apple.com/en-ie/guide/iphone/iphe3f499e0e/ios)
- [Apple: iOS 및 iPadOS 기능 지원 여부](https://www.apple.com/ios/feature-availability/)
