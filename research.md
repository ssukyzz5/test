# 자기소개 사이트 v2 리서치

> 2026-11-21, Aside로 실제 사이트를 열어 확인한 내용입니다.
> **[확인]** = 직접 열어 본 것, **[추측]** = 해석입니다.

## 한눈에 보기

| 질문 | 답 |
|---|---|
| 우리 사이트에 가장 부족한 것 | 얼굴(프로필 사진), 말 거는 방법(연락 버튼), 링크 공유 시 미리보기(OG) |
| 가장 효과가 큰 추가 | "요즘 하는 것(Now)" 한 단락 + 날짜 |
| 셀피쉬클럽 느낌을 내는 최소 조건 | 검정 `#0A0A0A` + 라임 옐로 `#E9ED12`, Pretendard 900 제목, 직각, 번호 붙은 섹션 |
| 가져오지 말 것 | 셀피쉬클럽 로고·레터링(상표일 수 있음), 복잡한 일러스트 |

---

## 1. 우리 사이트에서 부족한 부분과 보완할 점

지금 구성: 이름 + 한 줄 소개 → 내 이야기 4문단 → (채널 링크, 비어 있어 숨김)

| 우선순위 | 보완할 것 | 레퍼런스 | 왜 |
|---|---|---|---|
| **필수** | 공유 미리보기 (제목·설명·OG 이미지) | [Justin Schueler](https://justinschueler.com/), [Paco Coursey](https://www.paco.me/), [Josh Puckett](https://joshpuckett.me/) 모두 설정됨 | 링크를 카톡·슬랙에 붙였을 때의 첫인상입니다. 같은 조건의 비개발자 사례 [Dina](https://dina-profile.vercel.app/)는 없었습니다. 워크숍에서 서로 링크를 주고받으면 바로 차이가 보입니다 |
| **필수** | 프로필 사진 | [Felix Haas](https://felixhaas.io/) (큰 인물 사진) | "읽고 나를 더 알게 된다"는 목표에 얼굴이 가장 빠릅니다 |
| **필수** | 연락 버튼 하나 | [김강주(리틀리)](https://litt.ly/thinkling), [정희수(리틀리)](https://litt.ly/heesoojung), [Dina](https://dina-profile.vercel.app/) | 다 읽은 사람이 할 다음 행동이 없습니다. thinkling은 "여기까지 읽으셨다면 비슷한 결일 거예요… 소통하기"로 마무리합니다 |
| 높음 | 요즘 하는 것 (Now) + 날짜 | [Derek Sivers /now](https://sive.rs/now) (원조), [Justin Schueler](https://justinschueler.com/), [Paco Coursey](https://www.paco.me/) | 날짜 한 줄로 "살아 있는 사이트"가 됩니다. 지금 "AI를 배우는 중"인 이야기와 잘 맞고, 워크숍이 끝나도 갱신할 이유가 생깁니다 |
| 높음 | 이야기에 소제목 | [Felix Haas](https://felixhaas.io/) ("The beginning → … → To be continued") | 폰으로 읽는 구독자가 흐름을 잡기 쉽습니다 |
| 중간 | 관심사 키워드 태그 | [김강주](https://litt.ly/thinkling), [Dina](https://dina-profile.vercel.app/) | 다 읽기 전에 "어떤 사람인지"를 3초 안에 보여줍니다. 예: `#정보보안` `#AI활용` |
| 중간 | 채널마다 한 줄 설명 | [참깨(인포크링크)](https://link.inpock.co.kr/sesame.home), [정희수](https://litt.ly/heesoojung) | 링크만 나열한 [Linktree 예](https://linktr.ee/selenagomez)보다 클릭 이유가 분명합니다 |
| 낮음 | 타임라인·이력, 다크모드 토글, 최신 글 자동 표시 | [Brittany Chiang](https://brittanychiang.com/) 등 | 구독자용에는 이야기 문단이 같은 역할을 합니다. 시간 대비 효과가 낮습니다 |

### 레퍼런스별로 가져올 점

| 사이트 | 가져올 것 | 이유 |
|---|---|---|
| [Felix Haas](https://felixhaas.io/) | 좁은 읽기 단, 이야기 소제목, 큰 인물 사진 | 우리 구성(긴 이야기 한 장)과 가장 비슷합니다 · [설명](https://onepagelove.com/felix-haas) |
| [김강주 · 리틀리](https://litt.ly/thinkling) | 키워드 태그 + 마지막 "말 걸기" 한 줄과 버튼 | 목표가 "읽고 알게 되기"로 같습니다 |
| [정희수 · 리틀리](https://litt.ly/heesoojung) | 한 줄 소개를 "무엇을 하는지"보다 "무엇을 믿는지"로 쓰기 | 한 줄 소개에 결이 생깁니다 |
| [Justin Schueler](https://justinschueler.com/) | 이름 바로 아래 짧은 "Now" | 사이트가 살아 있는 인상 · [설명](https://onepagelove.com/justin-schuler) |
| [Derek Sivers /now](https://sive.rs/now) | "업데이트: 2026년 11월 21일" 날짜 표기 | 날짜만으로 신뢰가 생깁니다 |
| [Paco Coursey](https://www.paco.me/) | 마지막을 Connect(연락)로 닫는 순서 | 우리 순서와 그대로 맞습니다 |
| [Josh Puckett](https://joshpuckett.me/) | 정보가 적어도 완성돼 보이는 구성 | 분량이 적어도 괜찮다는 기준점 · [설명](https://onepagelove.com/josh-puckett) |
| [Dina](https://dina-profile.vercel.app/) | 비개발자 + AI + Vercel로 만든 현실적 기준 | 우리와 같은 조건 · [제작 후기](https://www.gpters.org/dev/post/just-talked-ai-created-d3SFvbIlQ38vm1E) · OG 미설정은 반면교사 |
| [참깨 · 인포크링크](https://link.inpock.co.kr/sesame.home) | 채널마다 한 줄 설명 | 숫자 자랑은 구독자용에 불필요, 설명 방식만 |

---

## 2. 셀피쉬클럽 디자인 반영

확인한 곳: [selfishclub.xyz 홈](https://www.selfishclub.xyz/) · [이기적워크샵 상세](https://www.selfishclub.xyz/workshop/claude-code-site4) · [About](https://www.selfishclub.xyz/about) · [스폰지클럽](https://www.selfishclub.xyz/spongeclub) · [인스타그램](https://www.instagram.com/selfishclub.official/)

### 브랜드 특징 [확인]

| 요소 | 셀피쉬클럽 |
|---|---|
| 색 | 검정 `#0A0A0A` + 라임 옐로 `#E9ED12` 가 거의 전부. 밝은 섹션 `#FAFAF8`, 본문 `#171717`, 포인트 블루 `#2E6BFF` 아주 조금 |
| 글꼴 | Pretendard. 제목 굵기 900, 자간 약 -0.025em. 본문 16~18px |
| 강조 | 굵은 제목 안에서 **한 단어만 옐로** (예: "나누는 **사람들**") |
| 모양 | 둥근 모서리 없음(직각), 1~2px 검정 가로선, 01·02·03 번호 |
| 소제목 | 작은 영문 대문자(Programs, Reviews) 위 + 한글 큰 제목 아래 |
| 배경 리듬 | 검정 → 밝은 색 → 검정 → 흰색 → 옐로 → 검정으로 섹션마다 교차 |
| 말투 | 해요체. "통째로", "날것 그대로", "시행착오까지". 완성보다 **과정 공유** |
| 이미지 | 실제 결과물·화면 캡처를 1px 회색 테두리, 직각으로 |

### 우리 사이트에 가져올 것

| 가져올 것 | 구체안 | 이유 |
|---|---|---|
| 검정 + 옐로 두 색 | 첫 화면(이름) 검정 배경, 이름 아래 한 단어 옐로, 연락 버튼 옐로 | 색 두 개만 지켜도 셀피쉬클럽 느낌이 납니다. AI에게 HEX만 주면 됩니다 |
| 굵은 제목 | 이름을 Pretendard 900으로 크게 | 이미 Pretendard를 쓰고 있어 굵기만 바꾸면 됩니다 |
| 영문 소제목 + 번호 | `01 · ABOUT`, `02 · NOW`, `03 · CONTACT` | 한 장 스크롤을 정리해 주고, 브랜드 문법을 가장 적은 요소로 보여줍니다 |
| 직각 + 가로선 | 카드·버튼 둥근 모서리 제거, 섹션 사이 검정 선 | 지금의 둥근 카드는 흔한 템플릿 느낌입니다 |
| 과정 공유 문장 | "이 페이지는 이기적워크샵에서 처음 만든 결과물이에요" | 브랜드의 핵심 가치이고, 이미 이야기 4번째 문단과 같은 결입니다 |
| 소속 표시 | 맨 아래 "이기적워크샵에서 만들었어요 →" + [selfishclub.xyz](https://www.selfishclub.xyz/) 링크 | 로고 대신 글과 링크로 안전하게 |

### 워크숍에 주는 의미 [추측]

[이기적워크샵 일정](https://www.selfishclub.xyz/workshop/claude-code-site4)에 "자기소개 PR 올리기"(STEP 2)와 "PRD대로 사이트 만들고 배포하기"(STEP 4)가 있습니다. 참여자들이 같은 색·글꼴·규칙을 쓰면 서로의 사이트가 **한 커뮤니티의 페이지들**처럼 보입니다. 색과 글꼴 값을 한 파일에 모아 두면 참여자가 그대로 복사해 쓸 수 있습니다.

### 가져오지 않을 것

- **셀피쉬클럽 로고·"SELFISH CLUB" 레터링**: 상표나 저작물일 수 있습니다
- **와이어프레임 일러스트, 종이 오린 컷아웃 포스터**: 하루 안에 만들기 어렵고, 한 장 사이트에는 옐로 면 + 큰 글자로 충분합니다
- **파스텔 보조색**: 브랜드 핵심 색이 아니라 빼는 게 선명합니다

---

## 3. 더 참고할 곳

| 곳 | 용도 |
|---|---|
| [One Page Love · Personal](https://onepagelove.com/genre/personal) | 해외 한 장짜리 개인 사이트 모음 |
| [Minimal Gallery · personal](https://minimal.gallery/tag/personal/) | 미니멀한 개인 사이트 모음 |
| [포폴](https://pofol.works/) | 국내 포트폴리오 약 1,700개 (대부분 취업용이라 참고 범위 제한) |
| [지피터스 · 리틀리 프로필 제작기](https://www.gpters.org/wealth/post/create-your-own-profile-rTqxbSvsdOUPEi7) | 목적·대상을 먼저 정하고 만든 과정 |
| [지피터스 · 비개발자 Vercel 자기소개 제작기](https://www.gpters.org/dev/post/just-talked-ai-created-d3SFvbIlQ38vm1E) | 우리와 같은 조건의 시행착오 (메일 링크 문제 등) |

## 한계

- 스크린샷 캡처가 실패해 일부 디자인 설명은 갤러리 설명과 페이지 구조 확인에 의존했습니다
- 셀피쉬클럽 공식 브랜드 가이드는 찾지 못했습니다. 색·글꼴 값은 사이트에서 측정한 값입니다
- 인스타그램은 로그인 없이 상단 피드만 확인했습니다
