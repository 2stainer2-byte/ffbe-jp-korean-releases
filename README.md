# FFBE JP 한글 패치

현재 배포: **한글 0.15 / 패처 2.0 / 원본 26112414**.

[최신 패처 다운로드](https://github.com/2stainer2-byte/ffbe-jp-korean-releases/releases/latest/download/ffbe-jp-korean-patcher.apk) · [업데이트 내역](https://github.com/2stainer2-byte/ffbe-jp-korean-releases/releases/latest)

## 설치

1. [원본 미러](https://gofile.io/d/dkgtqEi8)에서 `FFBE-JP-11.0.0-lapis-26112414.apk`를 준비합니다.
2. 최신 패처를 설치하거나 업데이트합니다.
3. 패처에서 원본 APK를 선택해 한글판을 생성합니다.
4. 기존 우리 JP 한글판에 **업데이트 설치**합니다. 기존 앱은 삭제하지 마세요.

원본: 1,938,443,286바이트, SHA-256 `c58a4d8e824beee35b9b3bfa145e834913bdca430d98d1e3bdf7ac647e1f2978`.

[원작자 소개](https://www.reddit.com/r/FFBraveExvius/comments/1xv8s6y/ffbe_jp_1100_a_standalone_fully_english_offline/) · [원작자 배포 폴더](https://drive.google.com/drive/folders/1j-Req0tDZWt9wizYOyrXr1AYeiGFB93a)

## 이번 변경

- 원본의 APK 전용 마스터 누락 전송, 콜로세움 편성 자료, 스토리 재생 연결 등 수정 사항을 반영했습니다.
- 새 스토리 맵 개방 옵션과 시즌별 어빌리티 조정 4개 항목을 한글화했습니다. 원본의 새 맵 옵션 기본값은 모든 프로필에서 OFF입니다.
- 기존 한글 대사를 유지하고 영어로 남아 있던 부분에는 새 GL 대사 개선을 반영했습니다.
- 콜라보 장비·효&판테라 울티무스 표기와 소환 자막 연결을 보완했습니다.
- 트마·슈퍼트마 전투1회 개별 옵션과 선택 소환의 시대·출시일 검사를 유지했습니다.

어빌리티 조정의 이전 연도별 선택은 원본 정책에 따라 기본값으로 돌아갑니다. 새 맵 옵션의 첫 클리어 보상·OFF 시 동작은 설정 도움말을 확인하세요.

## 자동 업데이트·검증

공개 릴리스 첨부는 `ffbe-jp-korean-patcher.apk`와 `release.json` 두 개입니다. 패처는 저장소·패키지·서명 인증서·크기·해시를 검사해 업데이트를 확인합니다.

실제 원본에서 최대 힙32MiB의 Android용 Java 엔진으로 전체 APK를 복원하고 최종 크기·해시·서명·16KiB 정렬을 확인했습니다. 마스터 데이터와 설정의 비표시 값은 원본과 대조했습니다.

게임 동작 검사는 격리된 실제 함수와 메모리 SQLite를 이용했습니다. 실제 휴대폰의 전체 화면·전체 스토리 완주 검증은 아닙니다. 기존 영문 대사를 전부 새로 번역했다는 의미도 아닙니다.

원본·완성 게임 APK 전체와 개인 번역 소스·서명키·비밀번호·세이브는 이 저장소에 공개하지 않습니다.
