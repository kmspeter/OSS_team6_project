
# 📚 오픈소스 도서 소개 프로젝트 - Git 협업 실습

---

## 📝 소개 (Description)

본 프로젝트는 **Git 및 GitHub 기반 협업 기능 실습**을 위한 텍스트 중심 프로젝트입니다.  
주요 학습 내용은 다음과 같습니다:

- 브랜치 생성 및 전략 수립
- 커밋 메시지 작성 규칙
- Pull Request 생성 및 리뷰
- 충돌 유도 및 해결
- 이슈 및 마일스톤 기반 협업
- 태그 관리 및 최종 배포

> 코드가 아닌 텍스트 파일(`book_list.txt`, `markdown_guide.txt`)을 통해 실습합니다.

---

## 🖼️ 스크린샷 (Screenshots)

> 📷 작업 예시, PR 충돌 상황, 태그 생성 화면 등을 여기에 첨부예정입니다.  
> 예: `pull_request_conflict_example.png`, `milestone_overview.png` 등

---

## ⚙️ 설치 방법 (Installation)

```bash
# 저장소 클론
git clone https://github.com/kmspeter/OSS_team6_project.git
cd OSS_team6_project.git
```

---

## 🚀 사용법 (Usage)

```bash
# 브랜치 생성 및 변경
git switch -c feature/booklist-KW

# 텍스트 문서 작업
vim book_list.txt

# 커밋
git add book_list.txt
git commit -m "Add: 도서 목록 작성 (Resolves: #1)"

# 푸시 및 PR 생성
git push origin feature/booklist-KW
```

---

## 🤝 기여 방법 (Contributing)

> ⚠️ 팀원들은 아래 규칙을 반드시 따라야 합니다.

- **브랜치 네이밍**: `type/파일명-작업자이니셜` (예: `feature/booklist-KW`)
- **커밋 메시지 형식**:  
- 한 줄 커밋
```
[제목]:[내용](Resolves: #이슈번호)
```

```
[제목: 50자 이내 요약]  

본문: 문제의 원인, 해결 방법, 추가적인 변경 사항 기술  
Resolves: #이슈번호
```

- **작성 원칙**
- 제목 첫 글자는 대문자로 시작, 마침표 X
- **명령형** 사용 (예: "Add", "Fix", "Refactor" 등)
- 한 커밋은 한 작업 목적만 포함
- 커밋 내용이 분명할 시, 한 줄 커밋을 주로 사용
- 본문 작성 시, 본문에서는 **무엇을**, **왜**, **어떻게** 수정했는지를 기술

📄 자세한 협업 규칙은 [`team_rules.md`](./team_rules.md)를 참고하세요.

---

## 🧭 실습 흐름

1. 저장소 초기화, 역할 분담
2. `README.md` 및 `team_rules.md` 작성
3. 브랜치 생성, 이슈 등록, 마일스톤 설정
4. 파일 작성 → 커밋 → PR → 충돌 유도 및 해결
5. 병합 → 태그 생성(`v1.0.0`) → 회고 작성

---

## 📁 주요 파일 구조

| 파일명 | 설명 |
|--------|------|
| `book_list.txt` | 추천 오픈소스 도서 목록 |
| `markdown_guide.txt` | 마크다운 문법 정리 가이드 |
| `team_rules.md` | 팀 협업 규칙 (커밋/브랜치/PR 등) |
| `README.md` | 프로젝트 소개 및 실습 흐름 안내 |

---

## 📌 마일스톤 / 이슈 관리

- 마일스톤: OSS 도서 소개 프로젝트 완성
- 이슈 템플릿 사용 권장
- 라벨 예시: `documentation`, `enhancement`, `bug`, `question`
- 모든 PR은 반드시 이슈 및 마일스톤에 연결되어야 함

---

## 🏷️ 태그 및 버전 관리

- 병합 완료 후 태그 생성
```bash
git tag v1.0.0
git push origin --tags
```

---

## 📬 제출 안내

- 팀장은 `.txt` 형식 작업 스크립트를 수합하여 ZIP 압축 후 LMS에 업로드
- GitHub 저장소 주소는 `mjjang@kau.ac.kr`로 이메일 제출
- 저장소에 교수님 계정(`mjjang@kau.ac.kr`)을 Collaborator로 등록할 것

---

## 🛡️ 라이선스 (License)

> 본 프로젝트는 학습용으로만 사용되며, 별도의 라이선스는 포함되어 있지 않습니다.  
> 필요시 [MIT License](https://opensource.org/licenses/MIT) 또는 [Creative Commons](https://creativecommons.org/) 추가 가능

---

## 🔗 참고 자료 / 링크 (Optional)

- [Git 공식 문서](https://git-scm.com/doc)
- [GitHub 협업 가이드](https://docs.github.com/en/pull-requests)
- [Markdown 문법 참고](https://www.markdownguide.org/basic-syntax/)
- 교수 강의자료: Git 기초 I~V PDF

---

## ✍️ 작성자 / 크레딧 (Credits)

- 민수 (팀장): 저장소 초기화, 태그 생성, 최종 병합
- 지윤 (기획자): 이슈/마일스톤/라벨 기획, 팀 규칙 정리
- 견우 (개발자 A): `book_list.txt` 리뷰 작성
- 건하 (개발자 B): `markdown_guide.txt` 작성, 리뷰 및 회고
