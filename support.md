---
lang: ko
title: 지원
permalink: /support/
alt: /en/support/
description: Easy NAS Player(LG TV 앱) 사용 도움말과 문의 방법입니다.
---
# 지원

## 문의
이메일: [jjlab-support@googlegroups.com](mailto:jjlab-support@googlegroups.com)

문제를 알려 주실 때는 무엇을 했는지, 무엇을 기대했는지, 실제로 어떻게 됐는지와 함께 앱 버전(설정 › About), TV 모델, webOS 버전, NAS 모델과 DSM 버전을 적어 주세요. **NAS 비밀번호 · 인증 코드 · 인증 앱 키는 절대 보내지 마세요.**

## 시작하기
1. 앱을 열고 NAS 목록에서 **+**(NAS 추가)를 누릅니다.
2. NAS 주소(IP · 도메인) 또는 QuickConnect ID, 포트, HTTPS 여부, 계정 이름과 비밀번호를 넣고 **저장 후 연결**을 고릅니다.
3. 공유 폴더를 열어 사진과 동영상을 봅니다. 설정(톱니바퀴)에서 테마 · 보기 방식 · 재생 방식 · 자막 스타일을 바꿀 수 있습니다.

필요한 것: DSM 이 설치된 Synology NAS 와 File Station 을 쓸 수 있는 계정. Video Station 스트리밍은 NAS 에 Video Station 이 설치되어 있어야 합니다.

## 자주 묻는 질문

### 비밀번호는 어디에 저장되나요?
TV 안에만 저장됩니다. 비밀번호와 인증 앱 키는 이 앱만 쓸 수 있는 키로 암호화해 저장하고, 개발자에게 보내지 않습니다. 폴더 화면의 **로그아웃**은 프로필을 남기고 저장된 비밀번호 · 인증 앱 키 · 신뢰 기기 토큰을 지웁니다. 자세한 내용은 [개인정보처리방침]({{ '/privacy/' | relative_url }})을 보세요.

### 2단계 인증을 쓰는 계정도 되나요?
됩니다. 로그인할 때 인증 코드를 입력하고, **이 TV 신뢰**를 고르면 다음부터 묻지 않습니다. 프로필에 인증 앱 키를 넣으면 코드를 자동으로 입력합니다.

### 집 밖의 NAS 에 접속할 수 있나요?
NAS 의 외부 주소(도메인) 또는 QuickConnect ID 로 접속할 수 있습니다. QuickConnect ID 를 쓰면 NAS 주소를 찾기 위해 그 ID 를 Synology 의 QuickConnect 서버에 보냅니다.

### 인증서 오류가 나요.
자체 서명 인증서를 쓰는 NAS 라면 프로필에서 **인증서 오류 무시**를 켜고 접속할 수 있습니다. 믿을 수 있는 내 NAS 에만 켜 주세요.

### 재생되지 않는 동영상이 있어요.
직접 재생은 TV 가 지원하는 코덱(예: H.264 · HEVC, AAC · AC3 · MP3)만 재생할 수 있습니다. NAS 에 Video Station 이 있으면 설정의 **재생 방식**을 Video Station 으로 바꿔 NAS 에서 변환한 스트림으로 재생해 보세요.

### 자막이 나오지 않아요.
자막 파일을 동영상과 같은 폴더에 같은 이름으로 두세요(예: `movie.mp4` 와 `movie.srt`). .srt · .smi · .vtt 를 지원합니다.

### 폴더 표지는 어떻게 정하나요?
폴더 안에 `cover.jpg` 또는 `folder.jpg`(.png 도 가능)를 두면 그 사진을 폴더 표지로 보여 줍니다.

### 파일을 올리거나 지울 수 있나요?
아니요. 앱은 보기 전용이라 NAS 의 파일을 올리거나 고치거나 지우지 않습니다.

### 앱이 무료인가요?
무료이며 광고와 인앱 구입이 없습니다.

Easy NAS Player 는 Synology Inc. 와 제휴 관계가 없는 독립 앱입니다. Synology, DSM, QuickConnect 는 Synology Inc. 의 상표입니다.
