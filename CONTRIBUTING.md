# 기여 안내 / Contributing Guide

---

## 한국어

이 프로젝트는 『제주4·3사건 진상조사보고서』의 영문 번역을 공개하고, 번역의 정확성을 높이며 더 많은 언어로 접근 가능하게 만들기 위한 열린 협업을 환영합니다.

### 기여 방법

#### 1. 번역 오류 수정 (Translation Corrections)

번역 오류, 용어 불일치, 문맥 오해 등을 발견하셨다면 다음 방법으로 기여해 주세요:

**GitHub Issues를 통한 신고**
- [Issues 탭](../../issues)에서 새 이슈를 열어 주세요
- 제목 형식: `[오류] Chapter III, p.231 — "토벌대" 번역 오류`
- 내용에 다음을 포함해 주세요:
  - 해당 파일명과 페이지 번호 (`**[p. N]**` 마커 기준)
  - 현재 번역된 내용
  - 제안하는 번역 또는 수정 내용
  - 수정 이유 (참고 문헌이 있다면 함께 제시)

**Pull Request를 통한 직접 수정**
1. 이 리포지토리를 Fork하세요
2. 해당 `.md` 파일을 수정하세요
3. PR 제목에 수정 내용을 명시해 주세요: `[수정] Chapter II, p.95 — 군정장관 직책명 통일`

#### 2. 다른 언어로의 번역 (Localization)

이 보고서를 일본어, 중국어, 그 외 언어로 번역하는 작업에 참여하고 싶으신 분을 환영합니다.

- 먼저 [Issues](../../issues)에 번역 언어와 계획을 알려 주세요
- 언어별 폴더를 생성하여 관리합니다 (예: `ja/`, `zh/`, `de/`)
- 영문 번역본(`*_Jeju43Report_ENG.md`)을 원본으로 사용합니다
- 번역 원칙은 아래 **용어 및 표기 기준**을 참고해 주세요

### 용어 및 표기 기준

- 주요 용어는 [GLOSSARY.md](./GLOSSARY.md)를 기준으로 합니다
- 로마자 표기: 맥쿤-라이샤워(McCune-Reischauer) 방식
  - 1960년 이전 조직명의 '제주' → *Cheju*
  - 지명 및 1960년 이후 명칭의 '제주' → *Jeju*
- 인명: 이미 국제적으로 통용되는 표기가 있는 경우 해당 표기 우선 (예: Syngman Rhee)

### 문의

질문이나 제안이 있으시면 Issues를 통해 연락해 주세요.

---

## English

This project welcomes open collaboration to improve the accuracy of the English translation and make it accessible in additional languages.

### How to Contribute

#### 1. Translation Corrections

If you find translation errors, inconsistent terminology, or misreadings of the original Korean, please contribute in one of the following ways:

**Report via GitHub Issues**
- Open a new issue in the [Issues tab](../../issues)
- Title format: `[Error] Chapter III, p.231 — mistranslation of "토벌대"`
- Please include:
  - File name and page number (based on the `**[p. N]**` inline markers)
  - The current translation as written
  - Your suggested correction
  - Reason for the correction (with references if available)

**Direct correction via Pull Request**
1. Fork this repository
2. Edit the relevant `.md` file
3. Submit a PR with a descriptive title: `[Fix] Chapter II, p.95 — standardize title of Military Governor`

#### 2. Localization (Translation into Other Languages)

Contributions translating this report into Japanese, Chinese, or other languages are very welcome.

- Please first open an [Issue](../../issues) to announce the target language and your plan
- Translations should be organized in language-specific folders (e.g., `ja/`, `zh/`, `de/`)
- The English translation files (`*_Jeju43Report_ENG.md`) serve as the source for localization
- Please follow the terminology and romanization principles in [GLOSSARY.md](./GLOSSARY.md)

### Terminology and Romanization Standards

- Key terms follow the [GLOSSARY.md](./GLOSSARY.md)
- Romanization: McCune-Reischauer system
  - 제주 in pre-1960 organization names → *Cheju*
  - 제주 as a place name and in post-1960 entities → *Jeju*
- Personal names: use internationally established romanizations where they exist (e.g., Syngman Rhee)

### Contact

For questions or suggestions, please open an Issue.
