# org-4cut · 팀 만화 아카이브

4컷만화 — 팀장 · 나 · 보현 · 수경 · 하림이 등장하는 만화와 캐릭터 참고 이미지를 모았습니다.

## 보관 범위
현재 **에피소드 54편·생성 이미지 75개**를 보관합니다. 최초 복원본은 주요 에피소드 14편의 이미지 15개(단체사진의 이전 버전 1개 포함), 초기 만화 2개, 캐릭터·직업 참고 이미지 7개와 원고 14개입니다. 이후 제작한 015 「구매 승인」, 016 「공정한 추첨」, 017 「한 장으로 정리했습니다」, 018 「뜻밖의 재능」, 019 「귀한 몸」, 020 「완벽한 집중 환경」, 021 「아무도 건드리지 마세요」, 022 「블루투스의 배신」, 023 「간식의 대가」, 024 「존재 증명」, 025 「뜻밖의 지원군」, 026 「회사어 통역」, 027 「확실한 분실 방지」, 028 「원격 기술 지원」, 029 「보안 교육의 빈틈」, 030 「성공적인 발표 연습」, 031 「한 글자의 무게」, 032 「전부 사용 중입니다」, 033 「신입의 업무 능력」, 034 「완벽한 비밀 작전」, 035 「오랜 동료와의 이별」, 036 「퇴근 신호」, 037 「놀라운 친화력」, 038 「좋은 이웃」, 039 「잠깐만 확인할게요」, 040 「역시 좋은 건 다르네요」, 041 「종이 한 장도 소중하게」, 042 「뜻밖의 운동왕」, 043 「마지막 남은 일」, 044 「문제 해결 전문팀」, 045 「철저한 출장 준비」, 046 「전화는 어려워요」, 047 「무음 모드」, 048 「말 없는 협상」, 049 「설명을 듣는 쪽」, 050 「무소음 업데이트」, 051 「화면 없는 휴식」, 052 「좋은 소식도 들려주세요」, 053 「긴장 푸는 법」, 054 「매일 듣는 설명」의 이미지·원고·생성 프롬프트를 추가했습니다. 017과 042의 수정 전 이미지 각 2개, 043의 초안 1개, 049의 수정 전 이미지 2개, 050~053의 초안 각 1개도 해당 에피소드의 `versions/`에 보관합니다.

이미지는 재압축·리사이즈·대사 수정 없이 복사했습니다. 원본 파일명과 새 위치, SHA-256 검증값은 `manifest.json`에 기록되어 있습니다. 폴더의 회차 번호는 이번 정리를 위한 관리 번호이며, 원본 그림 안의 번호와 다를 수 있습니다.

이 아카이브는 대화 작업 공간에서 만들어졌으며, 2026-09-16에 `team-comics.zip`에서 사용자 PC의 로컬 작업 폴더로 복원했습니다. `manifest.json`의 저장 안내와 검증값은 최초 아카이브 생성 시점의 기록입니다.

## 로컬 작업 환경
- 별도 패키지 설치나 빌드 없이 `index.html`을 열어 갤러리를 봅니다.
- 이 폴더를 Git 저장소로 관리하며 기본 브랜치는 `main`입니다.
- GitHub 공개 저장소: [uclick-ljw/org-4cut](https://github.com/uclick-ljw/org-4cut). 기본 브랜치 main에 반영합니다.
- 새 만화는 기존 마지막 번호 다음으로 저장합니다. 제작 기준과 파일 보존 방식은 [작업 안내](AGENTS.md)를 따릅니다.

## 열어보기
압축을 풀고 `index.html`을 브라우저로 열면 전체 이미지를 볼 수 있습니다. 갤러리에는 외부 스크립트, 외부 폰트, 분석 도구 또는 네트워크 요청이 없습니다. Markdown 원고와 설정은 텍스트 편집기에서 볼 수 있습니다.

## 폴더 구조
```text
team-comics/
├── README.md
├── index.html                 # 로컬 이미지 갤러리
├── manifest.json              # 원본 파일명·저장 위치·해시
├── ideas.md                   # 대화에서 제안된 미제작 후보
├── settings/
│   ├── characters.md          # 이름, 외형, 성격, 존댓말 기준
│   ├── style.md               # 그림체·패널·보존 기준
│   └── references/            # 캐릭터·직업 참고 이미지 7개
├── episodes/
│   ├── 001-퇴근-1등/
│   │   ├── comic.png
│   │   └── story.md
│   ├── 003-단체사진-대작전/
│   │   ├── comic.png
│   │   ├── story.md
│   │   └── versions/comic-v1.png
│   └── ...054-매일-듣는-설명/
└── archive/                   # 캐릭터 설정 전의 초기 만화 2개
```

## 에피소드 목록
| 번호 | 제목 | 이미지 | 원고 |
|---|---|---|---|
| 001 | 퇴근 1등 | [이미지](episodes/001-퇴근-1등/comic.png) | [원고](episodes/001-퇴근-1등/story.md) |
| 002 | 아무거나 먹자는 사람들 | [이미지](episodes/002-아무거나-먹자는-사람들/comic.png) | [원고](episodes/002-아무거나-먹자는-사람들/story.md) |
| 003 | 단체사진 대작전 | [이미지](episodes/003-단체사진-대작전/comic.png) / [이전 버전](episodes/003-단체사진-대작전/versions/comic-v1.png) | [원고](episodes/003-단체사진-대작전/story.md) |
| 004 | 마지막 쿠키 사건 | [이미지](episodes/004-마지막-쿠키-사건/comic.png) | [원고](episodes/004-마지막-쿠키-사건/story.md) |
| 005 | 칭찬 스티커의 위력 | [이미지](episodes/005-칭찬-스티커의-위력/comic.png) | [원고](episodes/005-칭찬-스티커의-위력/story.md) |
| 006 | 오늘 회의, 사람은 왜 왔죠? | [이미지](episodes/006-오늘-회의-사람은-왜-왔죠/comic.png) | [원고](episodes/006-오늘-회의-사람은-왜-왔죠/story.md) |
| 007 | 진짜 리더가 드러나는 순간 | [이미지](episodes/007-진짜-리더가-드러나는-순간/comic.png) | [원고](episodes/007-진짜-리더가-드러나는-순간/story.md) |
| 008 | 복장의 최소한의 선 | [이미지](episodes/008-복장의-최소한의-선/comic.png) | [원고](episodes/008-복장의-최소한의-선/story.md) |
| 009 | 하림의 장점 세 가지 | [이미지](episodes/009-하림의-장점-세-가지/comic.png) | [원고](episodes/009-하림의-장점-세-가지/story.md) |
| 010 | 그를 부르는 주문 | [이미지](episodes/010-그를-부르는-주문/comic.png) | [원고](episodes/010-그를-부르는-주문/story.md) |
| 011 | 수경 씨의 또 다른 직장 | [이미지](episodes/011-수경-씨의-또-다른-직장/comic.png) | [원고](episodes/011-수경-씨의-또-다른-직장/story.md) |
| 012 | 답장이 빨라지는 공지 | [이미지](episodes/012-답장이-빨라지는-공지/comic.png) | [원고](episodes/012-답장이-빨라지는-공지/story.md) |
| 013 | 철저한 익명 보장 | [이미지](episodes/013-철저한-익명-보장/comic.png) | [원고](episodes/013-철저한-익명-보장/story.md) |
| 014 | 질문부터 끝까지 | [이미지](episodes/014-질문부터-끝까지/comic.png) | [원고](episodes/014-질문부터-끝까지/story.md) |
| 015 | 구매 승인 | [이미지](episodes/015-구매-승인/comic.png) | [원고](episodes/015-구매-승인/story.md) · [생성 프롬프트](episodes/015-구매-승인/prompt.md) |
| 016 | 공정한 추첨 | [이미지](episodes/016-공정한-추첨/comic.png) | [원고](episodes/016-공정한-추첨/story.md) · [생성 프롬프트](episodes/016-공정한-추첨/prompt.md) |
| 017 | 한 장으로 정리했습니다 | [이미지](episodes/017-한-장으로-정리했습니다/comic.png) · [초안](episodes/017-한-장으로-정리했습니다/versions/comic-v1.png) · [1차 수정](episodes/017-한-장으로-정리했습니다/versions/comic-v2.png) | [원고](episodes/017-한-장으로-정리했습니다/story.md) · [생성 프롬프트](episodes/017-한-장으로-정리했습니다/prompt.md) |
| 018 | 뜻밖의 재능 | [이미지](episodes/018-뜻밖의-재능/comic.png) | [원고](episodes/018-뜻밖의-재능/story.md) · [생성 프롬프트](episodes/018-뜻밖의-재능/prompt.md) |
| 019 | 귀한 몸 | [이미지](episodes/019-귀한-몸/comic.png) | [원고](episodes/019-귀한-몸/story.md) · [생성 프롬프트](episodes/019-귀한-몸/prompt.md) |
| 020 | 완벽한 집중 환경 | [이미지](episodes/020-완벽한-집중-환경/comic.png) | [원고](episodes/020-완벽한-집중-환경/story.md) · [생성 프롬프트](episodes/020-완벽한-집중-환경/prompt.md) |
| 021 | 아무도 건드리지 마세요 | [이미지](episodes/021-아무도-건드리지-마세요/comic.png) | [원고](episodes/021-아무도-건드리지-마세요/story.md) · [생성 프롬프트](episodes/021-아무도-건드리지-마세요/prompt.md) |
| 022 | 블루투스의 배신 | [이미지](episodes/022-블루투스의-배신/comic.png) | [원고](episodes/022-블루투스의-배신/story.md) · [생성 프롬프트](episodes/022-블루투스의-배신/prompt.md) |
| 023 | 간식의 대가 | [이미지](episodes/023-간식의-대가/comic.png) | [원고](episodes/023-간식의-대가/story.md) · [생성 프롬프트](episodes/023-간식의-대가/prompt.md) |
| 024 | 존재 증명 | [이미지](episodes/024-존재-증명/comic.png) | [원고](episodes/024-존재-증명/story.md) · [생성 프롬프트](episodes/024-존재-증명/prompt.md) |
| 025 | 뜻밖의 지원군 | [이미지](episodes/025-뜻밖의-지원군/comic.png) | [원고](episodes/025-뜻밖의-지원군/story.md) · [생성 프롬프트](episodes/025-뜻밖의-지원군/prompt.md) |
| 026 | 회사어 통역 | [이미지](episodes/026-회사어-통역/comic.png) | [원고](episodes/026-회사어-통역/story.md) · [생성 프롬프트](episodes/026-회사어-통역/prompt.md) |
| 027 | 확실한 분실 방지 | [이미지](episodes/027-확실한-분실-방지/comic.png) | [원고](episodes/027-확실한-분실-방지/story.md) · [생성 프롬프트](episodes/027-확실한-분실-방지/prompt.md) |
| 028 | 원격 기술 지원 | [이미지](episodes/028-원격-기술-지원/comic.png) | [원고](episodes/028-원격-기술-지원/story.md) · [생성 프롬프트](episodes/028-원격-기술-지원/prompt.md) |
| 029 | 보안 교육의 빈틈 | [이미지](episodes/029-보안-교육의-빈틈/comic.png) | [원고](episodes/029-보안-교육의-빈틈/story.md) · [생성 프롬프트](episodes/029-보안-교육의-빈틈/prompt.md) |
| 030 | 성공적인 발표 연습 | [이미지](episodes/030-성공적인-발표-연습/comic.png) | [원고](episodes/030-성공적인-발표-연습/story.md) · [생성 프롬프트](episodes/030-성공적인-발표-연습/prompt.md) |
| 031 | 한 글자의 무게 | [이미지](episodes/031-한-글자의-무게/comic.png) | [원고](episodes/031-한-글자의-무게/story.md) · [생성 프롬프트](episodes/031-한-글자의-무게/prompt.md) |
| 032 | 전부 사용 중입니다 | [이미지](episodes/032-전부-사용-중입니다/comic.png) | [원고](episodes/032-전부-사용-중입니다/story.md) · [생성 프롬프트](episodes/032-전부-사용-중입니다/prompt.md) |
| 033 | 신입의 업무 능력 | [이미지](episodes/033-신입의-업무-능력/comic.png) | [원고](episodes/033-신입의-업무-능력/story.md) · [생성 프롬프트](episodes/033-신입의-업무-능력/prompt.md) |
| 034 | 완벽한 비밀 작전 | [이미지](episodes/034-완벽한-비밀-작전/comic.png) | [원고](episodes/034-완벽한-비밀-작전/story.md) · [생성 프롬프트](episodes/034-완벽한-비밀-작전/prompt.md) |
| 035 | 오랜 동료와의 이별 | [이미지](episodes/035-오랜-동료와의-이별/comic.png) | [원고](episodes/035-오랜-동료와의-이별/story.md) · [생성 프롬프트](episodes/035-오랜-동료와의-이별/prompt.md) |
| 036 | 퇴근 신호 | [이미지](episodes/036-퇴근-신호/comic.png) | [원고](episodes/036-퇴근-신호/story.md) · [생성 프롬프트](episodes/036-퇴근-신호/prompt.md) |
| 037 | 놀라운 친화력 | [이미지](episodes/037-놀라운-친화력/comic.png) | [원고](episodes/037-놀라운-친화력/story.md) · [생성 프롬프트](episodes/037-놀라운-친화력/prompt.md) |
| 038 | 좋은 이웃 | [이미지](episodes/038-좋은-이웃/comic.png) | [원고](episodes/038-좋은-이웃/story.md) · [생성 프롬프트](episodes/038-좋은-이웃/prompt.md) |
| 039 | 잠깐만 확인할게요 | [이미지](episodes/039-잠깐만-확인할게요/comic.png) | [원고](episodes/039-잠깐만-확인할게요/story.md) · [생성 프롬프트](episodes/039-잠깐만-확인할게요/prompt.md) |
| 040 | 역시 좋은 건 다르네요 | [이미지](episodes/040-역시-좋은-건-다르네요/comic.png) | [원고](episodes/040-역시-좋은-건-다르네요/story.md) · [생성 프롬프트](episodes/040-역시-좋은-건-다르네요/prompt.md) |
| 041 | 종이 한 장도 소중하게 | [이미지](episodes/041-종이-한-장도-소중하게/comic.png) | [원고](episodes/041-종이-한-장도-소중하게/story.md) · [생성 프롬프트](episodes/041-종이-한-장도-소중하게/prompt.md) |
| 042 | 뜻밖의 운동왕 | [이미지](episodes/042-뜻밖의-운동왕/comic.png) · [초안](episodes/042-뜻밖의-운동왕/versions/comic-v1.png) · [1차 수정](episodes/042-뜻밖의-운동왕/versions/comic-v2.png) | [원고](episodes/042-뜻밖의-운동왕/story.md) · [생성 프롬프트](episodes/042-뜻밖의-운동왕/prompt.md) · [수정 기록](episodes/042-뜻밖의-운동왕/revision.md) · [2차 수정](episodes/042-뜻밖의-운동왕/revision-2.md) |
| 043 | 마지막 남은 일 | [이미지](episodes/043-마지막-남은-일/comic.png) · [초안](episodes/043-마지막-남은-일/versions/comic-v1.png) | [원고](episodes/043-마지막-남은-일/story.md) · [생성 프롬프트](episodes/043-마지막-남은-일/prompt.md) · [수정 기록](episodes/043-마지막-남은-일/revision.md) |
| 044 | 문제 해결 전문팀 | [이미지](episodes/044-문제-해결-전문팀/comic.png) | [원고](episodes/044-문제-해결-전문팀/story.md) · [생성 프롬프트](episodes/044-문제-해결-전문팀/prompt.md) |
| 045 | 철저한 출장 준비 | [이미지](episodes/045-철저한-출장-준비/comic.png) | [원고](episodes/045-철저한-출장-준비/story.md) · [생성 프롬프트](episodes/045-철저한-출장-준비/prompt.md) |
| 046 | 전화는 어려워요 | [이미지](episodes/046-전화는-어려워요/comic.png) | [원고](episodes/046-전화는-어려워요/story.md) · [생성 프롬프트](episodes/046-전화는-어려워요/prompt.md) |
| 047 | 무음 모드 | [이미지](episodes/047-무음-모드/comic.png) | [원고](episodes/047-무음-모드/story.md) · [생성 프롬프트](episodes/047-무음-모드/prompt.md) |
| 048 | 말 없는 협상 | [이미지](episodes/048-말-없는-협상/comic.png) | [원고](episodes/048-말-없는-협상/story.md) · [생성 프롬프트](episodes/048-말-없는-협상/prompt.md) |
| 049 | 설명을 듣는 쪽 | [이미지](episodes/049-설명을-듣는-쪽/comic.png) · [초안](episodes/049-설명을-듣는-쪽/versions/comic-v1.png) | [원고](episodes/049-설명을-듣는-쪽/story.md) · [생성 프롬프트](episodes/049-설명을-듣는-쪽/prompt.md) · [수정 기록](episodes/049-설명을-듣는-쪽/revision.md) |
| 050 | 무소음 업데이트 | [이미지](episodes/050-무소음-업데이트/comic.png) · [초안](episodes/050-무소음-업데이트/versions/comic-v1.png) | [원고](episodes/050-무소음-업데이트/story.md) · [생성 프롬프트](episodes/050-무소음-업데이트/prompt.md) · [수정 기록](episodes/050-무소음-업데이트/revision.md) |
| 051 | 화면 없는 휴식 | [이미지](episodes/051-화면-없는-휴식/comic.png) · [초안](episodes/051-화면-없는-휴식/versions/comic-v1.png) | [원고](episodes/051-화면-없는-휴식/story.md) · [생성 프롬프트](episodes/051-화면-없는-휴식/prompt.md) · [수정 기록](episodes/051-화면-없는-휴식/revision.md) |
| 052 | 좋은 소식도 들려주세요 | [이미지](episodes/052-좋은-소식도-들려주세요/comic.png) · [초안](episodes/052-좋은-소식도-들려주세요/versions/comic-v1.png) | [원고](episodes/052-좋은-소식도-들려주세요/story.md) · [생성 프롬프트](episodes/052-좋은-소식도-들려주세요/prompt.md) · [수정 기록](episodes/052-좋은-소식도-들려주세요/revision.md) |
| 053 | 긴장 푸는 법 | [이미지](episodes/053-긴장-푸는-법/comic.png) · [초안](episodes/053-긴장-푸는-법/versions/comic-v1.png) | [원고](episodes/053-긴장-푸는-법/story.md) · [생성 프롬프트](episodes/053-긴장-푸는-법/prompt.md) · [수정 기록](episodes/053-긴장-푸는-법/revision.md) |
| 054 | 매일 듣는 설명 | [이미지](episodes/054-매일-듣는-설명/comic.png) | [원고](episodes/054-매일-듣는-설명/story.md) · [생성 프롬프트](episodes/054-매일-듣는-설명/prompt.md) |

## 캐릭터·스타일
현재 이름을 반영한 [단체 캐릭터 이미지](settings/references/team-lineup.png), [캐릭터 설정](settings/characters.md), [스타일 및 말투 기준](settings/style.md)을 함께 보존했습니다.

**다섯 인물은 서로 존댓말을 사용합니다.** 기존 원고·이미지에 남은 일부 반말 표현은 이번 아카이빙에서 수정하지 않았습니다. 새 제작이나 수정판에서는 이 기준을 우선 적용합니다.

## 원본과 버전 처리
`comic.png`는 해당 이야기에서 이 대화에 가장 나중에 생성된 그림입니다. 최종 승인 여부를 새로 부여하지 않았습니다. 단체사진의 이전 버전과 초기 캐릭터 이미지도 삭제하지 않고 보존했습니다.

대화 원고와 실제 그림 속 대사는 일부 다를 수 있습니다. 원고를 이미지에 맞춰 새로 만들어 쓰거나 기존 PNG를 편집하지 않았습니다. 원고 출처는 각 `story.md`에 표시했습니다.

이름이 일반적인 `imagegen.png`는 ‘마지막 쿠키’ 원본과 파일 내용이 같고, `image.png`는 이름 변경 전 단체 캐릭터와 RGB 픽셀이 같아 중복 사본을 넣지 않았습니다. 생성 결과물이 아닌 실사 사진은 패키지에 포함하지 않았습니다. 원래 작업 공간의 파일은 삭제하지 않았습니다.

## 검증
모든 복사 이미지의 SHA-256이 대응하는 원본과 일치하는지 확인했습니다. 압축 파일 내 파일 내용도 생성 후 검사했습니다. 파일별 검증값은 `manifest.json`을 참고하세요.
