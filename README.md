# omwm-release

[오늘 뭐 먹었어?](https://github.com/aoetori-ctrl/omwm-food-log) 앱이 "새 버전 나왔나?" 하고
물어보는 곳입니다. **버전 번호와 링크만** 들어 있습니다.

앱 소스와 APK 는 여기 없습니다 — 비공개 저장소에 있습니다. APK 안에 API 키가 평문으로
들어 있어서 공개된 곳에 두면 안 되기 때문입니다.

## latest.json

| 항목 | 뜻 |
|---|---|
| `versionCode` | 앱이 자기 것과 비교하는 번호. 이게 더 크면 새 버전이 있는 것 |
| `versionName` | 사람이 읽는 버전 (`1.0.0`) |
| `url` | "받으러 가기" 를 눌렀을 때 열리는 곳 |
| `notes` | 무엇이 바뀌었는지 한 줄 |

갱신은 소스 저장소의 `tools/make_manifest.py` 로 만듭니다.
