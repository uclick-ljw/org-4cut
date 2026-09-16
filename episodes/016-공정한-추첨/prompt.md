# 제작 기록

- 도구: 내장 image_gen
- 참고: `../../settings/references/team-lineup.png` (캐릭터), `../015-구매-승인/comic.png` (그림체·구성)
- 아래는 실제 사용한 생성 프롬프트입니다.

```text
Use case: illustration-story. Create the next episode of the Korean office comic series in the reference images, titled exactly "공정한 추첨". Image 1 is the previous comic for consistent drawing style and 2x2 layout; replace the previous plot and ALL its text with this new story. Image 2 is the character identity reference. No chair squeaks or reused old dialogue.
OUTPUT: one finished landscape 4:3 comic, exactly FOUR panels in 2 rows and 2 columns, read top-left, top-right, bottom-left, bottom-right. Large black brush-lettered title "공정한 추첨" above the grid. Small boxed Korean panel headings. Bold hand-ink outlines, expressive cute adult characters, subtle warm skin and muted clothing against lightly shaded grayscale office, matching the previous episode. White speech balloons with large exceptionally legible accurate Korean. Clear black panel borders, narrow white gutters. No additional inset panels or extra commentary.

IDENTITIES (stable faces, hairstyles and clothes in all panels):
팀장: adult man, black center-parted hair, NO glasses, dark polo.
나: adult man, voluminous tightly curly dark hair, ROUND GLASSES, dark collared shirt. He is the program's creator, not the team leader.
보현: adult woman, long wavy dark hair, NO glasses, cream knit top.
수경: adult woman, straight long dark hair with bangs, NO glasses, pale top with dark pinafore.
하림: adult woman, dark hair tied back, ROUND GLASSES, dark collared shirt. She delivers the last line.
Only these five coworkers; never duplicate a person. Main joke: the manager and developer praise randomness until the two of them are selected for warehouse cleaning, then suddenly demand software verification. Harim firmly closes the laptop and gives them gloves. Preserve this entire sequence.

PANEL 1 top-left, heading "1. 아무도 눈을 마주치지 않는다":
Office corner with a clearly visible large stack of equipment cardboard boxes. Team leader addresses the other four coworkers.
Exact leader balloon: "창고 정리, 두 분만 맡아주시면 좋겠는데요."
Everyone avoids his gaze: curly-haired glasses man looks at his monitor, Bohyeon looks down at her fingernails, Sugyeong checks her schedule, Harim is already half hidden behind the boxes (recognizable glasses and tied hair peeking out).
Exact Sugyeong balloon, tail to woman with bangs and NO glasses: "그냥 공정하게 추첨할까요?"
Do NOT show gloves yet.

PANEL 2 top-right, heading "2. 기술로 해결하겠습니다":
Curly-haired glasses man confidently turns an OPEN laptop toward the group and viewer. Its screen must visibly show the FIVE names exactly "팀장", "나", "보현", "수경", "하림", and a single button labeled exactly "두 명 뽑기". NO result yet.
Three speech balloons in clear reading order:
Curly-haired man: "제가 만들었습니다. 직급이나 순서와 상관없이 완전 무작위예요."
Team leader (no glasses): "좋네요. 결과에 이의 제기 없기입니다."
Bohyeon (wavy hair, cream shirt): "네. 다 들으셨어요."
Readable laptop screen with sensible perspective, do not obscure faces.

PANEL 3 bottom-left, heading "3. 공정한 결과":
The curly-haired man clicks. Open laptop screen faces the reader in foreground and displays VERY LARGE BOLD EXACT TEXT: "당첨: 팀장 / 나".
No additional dialogue in this panel. Behind the laptop, the manager and curly-haired glasses man freeze simultaneously, stunned, rigid, blank expressions and tiny sweat drops. These are clearly two different men, one without glasses and one with curly hair AND glasses.
Bohyeon beams happily. Sugyeong takes out work gloves, practical and cheerful. Harim quietly observes. Keep the winning result unmistakably readable and do not change the winning names.

PANEL 4 bottom-right, heading "4. 갑작스러운 품질 검증":
The two men have leaned in solemnly to inspect the laptop, suddenly very serious.
Exact team leader balloon (tail to center-parted man with NO glasses): "그런데 이 프로그램, 충분히 검증된 건가요?"
Exact curly-haired glasses man balloon: "저도 방금 오류 가능성을 발견했습니다."
Show the immediate interruption in this SAME panel: Harim (tied-back hair, round glasses, dark collared shirt) has snapped the laptop COMPLETELY SHUT on the desk; her hand is still at the lid. Bold sound effect "탁" beside the closing edge and short motion lines. The screen is now hidden, laptop lid horizontal.
TWO PAIRS OF WORK GLOVES (four gloves, arranged as two clear pairs) rest ON TOP of the CLOSED laptop lid, offered for the TWO selected men. Not just one pair. Keep gloves separate from hands and physically coherent.
Harim's exact punchline balloon, clearly pointing to her, last in reading order: "검증은 다녀오셔서 하세요."
Men gaze down at the abruptly closed laptop and gloves, visibly caught out; their earlier balloons express their interrupted inspection. Background women may smile quietly, no extra dialogue.

Constraints: reproduce ALL dialogue verbatim without shortening, including polite speech and punctuation. No narrator captions beyond the four panel headings. No extra labels on people, no motivational wall posters, no subtitles, no watermarks. Allocate enough space to the long panel-2 and panel-4 dialogue; text must not collide with characters. Match established faces and illustration quality.
```
