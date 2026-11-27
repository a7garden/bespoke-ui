# bespoke-ui

과업이 시작되는 자리부터 완료까지 살펴 화면 뼈대와 입력 흐름을 고른다. UI 문구, 타이포, 색, 간격, 렌더 검수까지 한 스킬에서 다룬다. 대담함은 구조에, 절제는 표면에.

A self-contained skill for task-specific interface design, implementation, and visual review.

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
| `build` | 채택한 구조와 시각 방향을 구현한 뒤 렌더와 실제 과업을 확인한다 |
| `review` | 구조·조작·문구·시각의 실제 문제를 보고 대체안을 낸다 |

## 파일

- `SKILL.md` 스킬 본문
- `references/data-shapes.md` 데이터 모양별 형태
- `references/patterns.md` 배치 비교와 입력 흐름 예시
- `references/visual-craft.md` 시각 방향, 문구, 렌더 검수

## License

MIT
