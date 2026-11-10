# bespoke-ui

Claude Code 스킬. 기본 컴포넌트(카드 · 배지 · 탭 · KPI 타일 · 모달 · 스텝퍼)와 기본 배치(헤더 + 사이드바 + KPI 줄 + 카드 그리드)를 습관으로 깔지 않고, 과업과 데이터의 모양에서 컴포넌트 형태와 화면 뼈대를 새로 짓는다. 대담함은 구조에, 표면은 미니멀하게.

A Claude Code skill for designing task-specific component forms and layout skeletons instead of stock card/badge/tab/dashboard patterns. Visual world and polish are left to `impeccable`.

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
| `explore` (기본) | 과업 해부, 결정 메모, 2~3안 스케치. 코드는 고치지 않는다 |
| `build` | 결정 메모를 짧게 남기고 구현한 뒤 그려서 확인한다 |
| `review` | 습관으로 깐 컴포넌트와 배치를 찾아 대체안을 낸다 |

## 파일

- `SKILL.md` 스킬 본문
- `references/data-shapes.md` 데이터 모양별 형태
- `references/patterns.md` 패턴 모음

## License

MIT
