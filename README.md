# FFBE JP 한글 패치

현재 배포: **한글 0.17 / 패처 2.2 / 원본 26112414**.

[최신 패처 다운로드](https://github.com/2stainer2-byte/ffbe-jp-korean-releases/releases/latest/download/ffbe-jp-korean-patcher.apk) · [업데이트 내역](https://github.com/2stainer2-byte/ffbe-jp-korean-releases/releases/latest)

## 설치

1. [원본 미러](https://gofile.io/d/dkgtqEi8)에서 `FFBE-JP-11.0.0-lapis-26112414.apk`를 준비합니다. 기존 원본을 그대로 쓰면 됩니다.
2. 패처 2.2를 설치하거나 업데이트하고 원본 APK를 선택합니다.
3. 생성된 한글판을 기존 우리 JP 한글판에 **업데이트 설치**합니다.

0.16에서 로딩 오류가 났더라도 앱 삭제나 데이터 초기화는 필요하지 않습니다.

원본: 1,938,443,286바이트, SHA-256 `c58a4d8e824beee35b9b3bfa145e834913bdca430d98d1e3bdf7ac647e1f2978`.

[원작자 소개](https://www.reddit.com/r/FFBraveExvius/comments/1xv8s6y/ffbe_jp_1100_a_standalone_fully_english_offline/) · [원작자 배포 폴더](https://drive.google.com/drive/folders/1j-Req0tDZWt9wizYOyrXr1AYeiGFB93a)

## 이번 수정

- 마을 소개 파일 로딩 오류의 원인인 내부 암호화 패딩 누락을 복구했습니다.
- 전체 마스터를 검사하여 같은 문제가 있던 9개 테이블149행을 수정했습니다. 번역 내용과 게임 수치는 그대로입니다.
- 잘못된 설치 캐시가 교체되도록 해당 마스터 버전도 올렸습니다.
- 0.16의 지역명·마을 소개·아레나 대사·메뉴·콜로세움·확률창 수정과 트마·슈퍼트마 옵션을 유지했습니다.

원본 업데이트는 없습니다. 미번역 전체를 해소한 릴리스가 아니라, 0.16의 로딩 오류를 고친 긴급 수정입니다.

## 검증과 공개 범위

실제 DEX의 Java 복호화 코드를 격리된 JVM에서 실행해 원본149행 정상·0.16의149행 오류·수정149행 정상을 재현했습니다. 수정본53마스터295,200행 전체의 해독 결과도 JSON 바이트 SHA-256과 일치했습니다. 원본→한글판 전체 복원·해시·서명·16KiB 정렬도 검사했습니다.

실제 휴대폰의 전체 로딩·모든 화면·스토리 완주를 실행한 것은 아닙니다.

공개 첨부는 `ffbe-jp-korean-patcher.apk`와 `release.json` 두 개입니다. 원본·완성 게임 APK 전체와 개인 소스·서명키·세이브는 공개하지 않습니다.
