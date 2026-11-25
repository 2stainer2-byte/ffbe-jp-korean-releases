# FFBE JP 한글 패치

현재 배포: **한글 0.16 / 패처 2.1 / 원본 26112414**.

[최신 패처 다운로드](https://github.com/2stainer2-byte/ffbe-jp-korean-releases/releases/latest/download/ffbe-jp-korean-patcher.apk) · [업데이트 내역](https://github.com/2stainer2-byte/ffbe-jp-korean-releases/releases/latest)

## 설치

1. [원본 미러](https://gofile.io/d/dkgtqEi8)에서 `FFBE-JP-11.0.0-lapis-26112414.apk`를 준비합니다.
2. 최신 패처를 설치하거나 업데이트합니다.
3. 패처에서 원본 APK를 선택해 한글판을 생성합니다.
4. 기존 우리 JP 한글판에 **업데이트 설치**합니다. 기존 앱은 삭제하지 마세요.

0.15와 동일한 원본 APK가 대상입니다. 원본 크기: 1,938,443,286바이트, SHA-256 `c58a4d8e824beee35b9b3bfa145e834913bdca430d98d1e3bdf7ac647e1f2978`.

[원작자 소개](https://www.reddit.com/r/FFBraveExvius/comments/1xv8s6y/ffbe_jp_1100_a_standalone_fully_english_offline/) · [원작자 배포 폴더](https://drive.google.com/drive/folders/1j-Req0tDZWt9wizYOyrXr1AYeiGFB93a)

## 이번 변경

- 콜로세움 편성 검색에 한글 표시 이름이 섞이던 문제를 수정했습니다. 70개 라운드의 편성을 원본과 대조하고 기존 한글 몬스터 이름은 유지했습니다.
- 소환 확률 화면의 주소를 한글판 로컬 서버 포트에 맞췄습니다. 소환 확률 수치는 변경하지 않습니다.
- 지역별 뒤쪽 전투명 79곳과 기존 지역명 재사용 97곳, 도전과제 표시 409셀을 보완했습니다.
- 지역 소개문 83개, 아레나·모그리성 대사 54행, NPC 화자와 이름·스킬의 기존 번역 재사용을 추가했습니다.
- 입장 확인창·순위 등에 노출되던 잘못된 `%s` 서식 4키를 수정했습니다. 순위표의 자동 생성 상대 이름과 아레나 이미지 라벨 8개도 한글화했습니다.
- 기존 스토리·스킬·메뉴 번역, 소환 자막, 트마·슈퍼트마 전투1회 개별 옵션과 선택 소환 제한을 유지했습니다.

이번에는 새 원본을 도입하지 않았습니다. 원본 26112414의 변경 내용은 [이전 0.15 릴리스](https://github.com/2stainer2-byte/ffbe-jp-korean-releases/releases/tag/v2.0-jp-ko.15-build26112414)에 정리되어 있습니다.

## 자동 업데이트·검증

공개 첨부는 `ffbe-jp-korean-patcher.apk`와 `release.json` 두 개입니다. 패처는 저장소·패키지·서명 인증서·크기·해시를 검사해 업데이트를 확인합니다.

실제 원본에서 최대 힙32MiB의 Android용 Java 엔진으로 전체 APK를 복원하고 최종 크기·해시·서명·16KiB 정렬을 확인했습니다. 이번 변경의 편성·추가 번역·확률 페이지 연결을 검사하고, 기존 변경 없는 범위는 같은 원본의 0.15 검증 기록을 이어받았습니다.

실제 휴대폰 전체 화면·전체 스토리 완주와 모든 배너 터치 동작을 검증한 것은 아닙니다.
새 번역이 필요한 이름·적 스킬·이벤트 대사와 일부 이미지 문구는 남아 있습니다. 이번 릴리스는 모든 미번역이 해소됐다는 의미가 아닙니다.

원본·완성 게임 APK 전체와 개인 번역 소스·서명키·비밀번호·세이브는 이 저장소에 공개하지 않습니다.
