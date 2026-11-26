# bespoke-ui

과업이 시작되는 자리부터 완료까지 살피고, 화면 뼈대와 입력 흐름을 비교하는 스킬이다. 폴딩·드롭다운·일괄 입력 폼·대시보드형 배치는 사용자가 정보를 보고 판단하는 순서와 맞는지 확인한 뒤 선택한다. 대담함은 구조에, 절제는 표면에.

A skill for comparing task-specific layouts and input flows before choosing controls. Use `impeccable` for visual direction and polish where available.

## 설치

```sh
git clone https://github.com/a7garden/bespoke-ui ~/.claude/skills/bespoke-ui
```

## 쓰는 법

```
/bespoke-ui [대상 화면 · 파일 · 기능] [explore | build | review]
```

| 모드 | 하는 일 |
| - | - |
| `explore` (기본) | 과업을 해부하고 구조가 다른 2~3안을 스케치해 하나를 고른다 |
| `build` | 채택 이유를 남기고 구현한 뒤 실제 과업을 따라가며 확인한다 |
| `review` | 습관으로 깐 컴포넌트와 배치를 찾아 대체안을 낸다 |

## 파일

- `SKILL.md` 스킬 본문
- `references/data-shapes.md` 데이터 모양별 형태
- `references/patterns.md` 배치 비교와 입력 흐름 예시

## License

MIT
