# 제작 기록

- 도구: 내장 image_gen
- 참고: `../../settings/references/team-lineup.png` (캐릭터), `../016-공정한-추첨/comic.png` (그림체·구성)
- 아래는 실제 사용한 생성 프롬프트입니다.

```text
Use case: illustration-story. Create next episode of the Korean office comic series in these references, title exactly "한 장으로 정리했습니다". Reference 1 is drawing style and page layout only, NOT its lottery plot. Reference 2 is character identity sheet. Replace all previous dialogue and props with the new script below.
Deliver one finished landscape approximately 4:3 comic image, exactly FOUR panels in a 2x2 grid, reading top left, top right, bottom left, bottom right. Bold black hand-ink cartoon outlines, expressive cute ADULT faces, slight warm skin tones and muted outfits, lightly shaded grayscale modern office. Match references closely. Thick clean black borders, thin gutters, white speech balloons with large very legible Korean hand lettering. Title above panels, no subtitle. Small boxed panel headings as specified. No extra captions, moral, slogans, speech, or inset panels.

Five established characters, never confuse or duplicate them:
팀장: male team leader, black center-parted hair, NO glasses, dark polo.
나: male narrator and report author, voluminous tight curly black hair, ROUND GLASSES, dark shirt.
보현: woman, long wavy dark hair, NO glasses, cream knit top.
수경: woman, long straight dark hair with bangs, NO glasses, pale inner top and dark pinafore.
하림: woman, tied-back dark hair, ROUND GLASSES, dark collared shirt.
Keep faces, hair, glasses and outfits consistent in every panel.

STORY: Boss requests a one-sheet summary rather than endlessly turning pages. The literal-minded author keeps normal font size and prints everything on one absurdly LONG CONTINUOUS SHEET. The finale must reveal a many-meter paper strip going from the meeting table through the doorway and along the corridor, turning right at the far end. Not separate sheets; no seams, no stack in the finale, no toilet-paper imagery. Text marks on paper are ordinary paragraphs/charts, not microscopic lettering. Do not reveal the long paper before panel 3; do not reveal its full absurd length until panel 4.

PANEL 1 top left heading "1. 분명한 요청":
Team leader has stopped flipping through the author's thick multi-page report and sets it down with many unread pages clearly remaining. Curly-haired glasses author listens attentively.
Team leader exact balloon: "이번에는 한 장으로만 정리해주세요. 계속 넘겨가며 읽는 거 말고요."
Author exact reply: "네. 한 장이면 되시는 거죠?"
No rolled paper or long sheet in this panel.

PANEL 2 top right heading "2. 자신 있습니다":
Curly-haired glasses author edits report at computer, adding and removing content. Sugyeong (bangs, no glasses, pale shirt with dark pinafore) and Harim (tied hair, round glasses, dark collared shirt) stand behind watching his screen. Screen shows an ordinary document editing interface with readable-sized lines, avoid revealing the final extreme paper length.
Three balloons in clear reading order, first and THIRD both belong to SUGYEONG:
Sugyeong: "그 많은 내용이 한 장에 다 들어가요?"
Author: "네. 글씨도 작게 안 했습니다."
Sugyeong again: "오, 어떻게 하셨어요?"
Harim observes silently with no balloon. Accurate balloon tails essential.

PANEL 3 bottom left heading "3. 결과물 제출":
All five coworkers gathered in meeting room. Author proudly puts a SINGLE LARGE tightly rolled sheet of printed report paper on the table, like a scroll with visible concentric paper roll edge and a short uncurled end, no wooden scroll handles. The paper is rolled because it is unusually long, it is not a normal pile of pages. Others look at it.
Author exact balloon: "요청하신 한 장입니다. 필요한 내용은 전부 들어 있습니다."
Team leader exact balloon: "…그런데 왜 말려 있어요?"
Do not yet show the full length outside the room.

PANEL 4 bottom right heading "4. 걸어서 읽는 요약본":
Crucial wide establishing view with deep perspective: ONE absurdly LONG continuous paper sheet now unrolled, starts ON the meeting table in foreground, falls gently over its edge to the floor, crosses the open meeting-room doorway and visibly continues far down an outside CORRIDOR, making a RIGHT TURN at the distant end. Use a wide doorway and clear architectural perspective so the corridor beyond the room is unmistakable and the uninterrupted paper path is visually traceable. The printed report forms a long white ribbon with two consistent edges narrowing in perspective, NOT a blank carpet. The length and coworkers spread out along it are the visual punchline. Avoid a close-up composition here; the distant corridor needs real space.
Team leader in room foreground silently dumbfounded. Curly-haired glasses author nearby points matter-of-factly toward far corridor. Sugyeong is partway along the sheet, leaning over to read middle paragraphs. Harim is walking THROUGH the doorway following the paper, tied hair and glasses identifiable. BOHYEON, cream knit top and wavy hair, is a small distant figure far down the corridor near its end, calls back with a balloon connected to HER distant position.
Bohyeon exact balloon: "결론은 어디 있어요?"
Author exact answer, last in reading order: "복도 끝에서 오른쪽이요."
Do NOT place Bohyeon's question on Sugyeong or Harim. No extra sound effects or additional commentary. Keep all five people unique, at five positions, no duplicates. Make the corridor and right-turning continuous sheet conspicuous.

All quoted dialogue and headings must be exact Korean, not shortened or paraphrased. White clean speech balloons must fit text without covering faces or the continuous paper path. Style fidelity plus exact speech plus final spatial gag are priorities.
```

## 1차 수정

```text
Edit this comic image with targeted corrections. Preserve the title, four-panel layout, art style, all panel 1 artwork and exact text, and the excellent long-paper corridor composition in panel 4. Preserve all dialogue text verbatim.
CRITICAL PANEL 2 top right: currently TWO lookalike women with bangs were drawn, and balloons point to wrong speakers. Redraw ONLY this panel to show exactly THREE people, not four: curly-haired ROUND-GLASSES male author seated at computer on LEFT; ONE Sugyeong (straight long hair with bangs, NO glasses, pale mint inner top with DARK PINAFORE) behind him in CENTER; Harim (tied hair, round glasses, dark collared shirt) at RIGHT. No other people, no duplicated Sugyeong. Harim must be silent.
Assign panel 2 balloons in reading order with unmistakable tails:
1. "그 많은 내용이 한 장에 다 들어가요?" tail to Sugyeong CENTER.
2. "네. 글씨도 작게 안 했습니다." tail travels to curly-haired MALE AUTHOR on LEFT, never Sugyeong.
3. "오, 어떻게 하셨어요?" tail to THE SAME Sugyeong CENTER, never Harim.
Arrange bubbles top and lower if needed, correct speaker ownership matters more than original placements.
PANEL 3 bottom left: remove Sugyeong's white work gloves. Her hands should be ordinary bare hands. Ensure her outfit has dark pinafore over mint shirt. Keep the rolled report and all five original characters. Place author's balloon "요청하신 한 장입니다. 필요한 내용은 전부 들어 있습니다." BEFORE team leader's "…그런데 왜 말려 있어요?" in reading order, with correct tails, same exact text.
PANEL 4 bottom right: keep all art and the single long paper stretching out the door and down the hallway. Improve dialogue reading order: Bohyeon's distant question "결론은 어디 있어요?" should be read first, above the author's reply "복도 끝에서 오른쪽이요." The question tail must point to the distant cream-shirted wavy-haired Bohyeon at the far corridor end. Answer tail points to foreground curly-haired glasses male author. Do not exchange the speakers. Move balloons vertically if needed. Keep faces and long paper unobscured.
No extra dialogue, objects, people, or captions. Do not change panel 1.
```

## 2차 수정 — 현재 comic.png

```text
Make ONLY two small localized corrections to this image. Preserve all other panels, title, dialogue, corridor, style and composition exactly.
1. TOP RIGHT PANEL: currently contains only two speech balloons. Add the missing THIRD speech balloon with exact Korean "오, 어떻게 하셨어요?" at the lower right portion of this panel, with a clearly angled tail pointing to the CENTRAL woman with straight hair and bangs, pale mint shirt and dark pinafore (Sugyeong). This is Sugyeong's second line, not Harim's. Keep the existing two speech balloons and their exact texts unchanged. There must be exactly THREE speech balloons total in panel 2. Keep exactly three people in this panel.
2. BOTTOM LEFT PANEL: the woman immediately to the RIGHT of the curly-haired glasses man (the LEFT of the two young women in the middle) must be BOHYEON: change only this woman's appearance to LONG WAVY DARK HAIR, SIDE PART, NO BANGS, NO GLASSES, CREAM CABLE-KNIT TOP. Keep her surprised expression and bare hands. The next woman to her right must remain SUGYEONG with straight long hair, bangs, NO glasses, PALE MINT SHIRT plus DARK PINAFORE. Far-right woman must remain HARIM with tied hair, glasses, dark collared shirt. This panel must have five UNIQUE people: leader, curly-haired man, Bohyeon, Sugyeong, Harim.
Do not touch any other text or remove existing dialogue. Do not alter panels 1 or 4 at all. No extra people. Maintain the original drawing quality.
```
