# 모각공 스터디

혼자 또는 함께 공부한 내용을 꾸준히 남기는 저장소입니다.

## 기록 방법

1. **[스터디 기록 템플릿](STUDY_TEMPLATE.md)**을 열어 코드 블록을 복사합니다.
2. `_posts` 폴더에 `YYYY-MM-DD-제목.md` 형식으로 저장합니다.
3. 공부한 내용, 막힌 점, 다음 할 일을 작성합니다.
4. 변경 내용을 GitHub에 올립니다.

파일 이름 예시: `_posts/2026-09-21-알고리즘-스터디.md`

템플릿에는 기본 정보, 오늘 할 일, 실제로 한 일, 공부 방법, 배운 내용, 결과, 문제 해결 과정, 회고 및 다음 계획을 기록하는 항목이 준비되어 있습니다.

## 폴더 구조

```text
.
├─ _posts/       # 날짜별 스터디 기록
├─ _templates/   # 새 글 작성용 템플릿
├─ STUDY_TEMPLATE.md # GitHub에서 바로 복사할 기록 양식
├─ assets/       # 글에 넣을 이미지 등의 자료
├─ _config.yml   # GitHub Pages 설정
└─ index.md      # 블로그 첫 화면
```

## GitHub Pages로 공개하기

GitHub 저장소의 **Settings → Pages**에서 다음과 같이 설정합니다.

- Source: `Deploy from a branch`
- Branch: `main` / `/(root)`

저장하면 잠시 후 GitHub Pages 주소에서 기록을 블로그처럼 볼 수 있습니다.
