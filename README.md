# stopwatch

Claude Code로 만든 HTML 결과물 모음입니다. (스탑워치, AI 뉴스 클리핑)

## 실행 방법

`output/` 폴더의 HTML 파일을 브라우저로 열면 바로 동작합니다.

GitHub Pages에서 모든 결과물을 탭으로 볼 수 있습니다: https://sk37025.github.io/stopwatch/

탭을 추가하려면 `index.html`의 `OUTPUTS` 목록에 한 줄을 추가하세요.

## 폴더 구조

```
.
├── index.html                  # 오늘의 아웃풋을 탭으로 보여주는 페이지
├── README.md
├── .claude/skills/ai-news-clipping/
│   ├── SKILL.md                # 뉴스 클리핑 스킬 (Role·Rubric·Context·Tools·Workflow·Guardrail)
│   ├── template.html           # Linear 스타일 HTML 템플릿
│   └── questions.md            # 스킬 요구사항 & 확인 질문
└── output/
    ├── ai-news-2026-10-15.html
    ├── stopwatch.html
    └── digital-stopwatch.html
```

## 결과물

| 파일 | 이름 | 주요 기능 |
| --- | --- | --- |
| `output/stopwatch.html` | 크로노 스탑워치 | 크로노그래프 시계 디자인, 시작·정지·랩·초기화, 슬롯 릴 숫자, 랩 기록·비교 막대, 단축키(Space·L·R), 다크 모드 |
| `output/digital-stopwatch.html` | 디지털 스탑워치 | LCD 스탑워치 디자인, 시작·정지·초기화, 7세그먼트 숫자, 손가락 누르기 모션, 단축키(Space·R) |
| `output/ai-news-2026-10-15.html` | AI 뉴스 클리핑 | 2026-10-15 이코노미스트·뉴욕 타임즈 AI 기사 10선 한국어 요약, 왼쪽 목록 + 오른쪽 원문 패널(너비 드래그 조절), 단축키(J·K·Esc), Linear 스타일, 다크/라이트 모드 |
