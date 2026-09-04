# Cybersecurity 2026

전북대학교 DAS Lab의 **사이버보안 2026** 강의 홈페이지입니다.

## 페이지 구성

- `index.html`: 강의 홈 및 공지
- `syllabus.html`: 강의 개요와 평가 방식
- `lectures.html`: 주차별 YouTube 강의 링크
- `exams.html`: 중간고사와 기말고사 안내

## 강의 영상 추가

`lectures.html`의 `.lecture-row` 항목을 복사하고 제목과 설명을 수정합니다. `업로드 예정` 요소를 다음 링크로 교체하면 됩니다.

```html
<a class="video-button" href="https://youtu.be/VIDEO_ID" target="_blank" rel="noopener">▶ YouTube</a>
```

## GitHub Pages 게시

이 저장소에는 GitHub Pages 배포 워크플로가 포함되어 있습니다. GitHub 저장소의 **Settings → Pages → Build and deployment → Source**를 **GitHub Actions**로 설정하면, `main` 브랜치에 push할 때 자동으로 게시됩니다.
