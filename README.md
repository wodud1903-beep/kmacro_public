# A1Auto 배포 저장소

[A1Auto](https://github.com/wodud1903-beep/kmacro) 의 **자동 업데이트 배포 전용** 공개 저장소입니다.
소스 코드는 비공개 저장소에 있으며, 여기에는 실행 파일과 버전 정보만 올라갑니다.

## 파일
| 파일 | 용도 |
|---|---|
| `version.txt` | 프로그램이 시작 시 조회하는 최신 버전 정보 |
| `A1Auto-<버전>.exe` | 해당 버전의 실행 파일 |

## version.txt 형식
```
version=1.1.0
url=https://raw.githubusercontent.com/wodud1903-beep/kmacro_public/main/A1Auto-1.1.0.exe
notes=변경 내용 요약
```

프로그램은 `version` 을 자신의 버전과 비교해, 더 높으면 `url` 에서 내려받아 교체 후 재실행합니다.
버전마다 파일명을 다르게 두어 캐시 문제를 피합니다.
