# TimeTracking Sync 배포

Redmine에 기록한 작업시간을 TT 업무관리에 옮겨 주는 데스크톱 앱 "TimeTracking Sync"의
설치파일을 배포하는 저장소입니다. 소스 코드는 비공개 저장소에 있습니다.

## 설치

[최신 릴리스](../../releases/latest)에서 운영체제에 맞는 파일을 받습니다.

| 운영체제 | 받을 파일 |
|---|---|
| Windows | `TimeTracking.Sync_<버전>_x64-setup.exe` |
| macOS (Apple Silicon) | `TimeTracking.Sync_<버전>_aarch64.dmg` |

- macOS는 서명되지 않은 앱이라 첫 실행 때 앱을 우클릭 → 열기 해야 합니다.
- 릴리스의 "Source code (zip / tar.gz)"는 GitHub이 자동으로 붙이는 파일이며 이 안내문만 들어 있습니다. 받지 않아도 됩니다.
- 현재는 지정된 테스터만 로그인할 수 있습니다.

## 업데이트

한 번 설치하면 앱을 켤 때마다 새 버전을 확인해 자동으로 설치합니다.
버전별 변경 내용은 [릴리스 목록](../../releases)에서 볼 수 있습니다.

## 그 밖의 파일

| 파일 | 용도 |
|---|---|
| `latest.json` | 앱이 새 버전을 확인할 때 읽는 정보 |
| `*.sig` | 설치파일 위변조 확인용 서명 |
| `*.app.tar.gz` | macOS 자동 업데이트용 파일 |