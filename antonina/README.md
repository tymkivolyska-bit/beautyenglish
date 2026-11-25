# Antonina's Beauty English (A2)

Antonina's page (owner of OKO lash & brow studio), published with GitHub Pages:
https://tymkivolyska-bit.github.io/beautyenglish/antonina/

Tabs: About & homework, This autumn (from the Miro board), Flashcards (British voice), Test, Progress.

- `index.html`: the page. Homework tasks and the autumn lessons are written in it.
- `cards.js`: all flashcards, as `window.LESSONS` (topic → groups → `[English, Ukrainian, note]`). Add new words at the end of a group. Don't rename existing words, topic ids or group names: her saved progress is keyed on them.
- `img/`: the make-up photo and the wavy pink frame.

## Saving her answers
- Every answer, card rating, test and homework tick is saved in the browser Antonina uses.
- With her personal link, each finished test, each homework tick and the "Send my progress to my teacher" button send a Telegram message to the teacher (same setup as Alyona's page).
- Make the link at `antonina/#teacher` (link at the bottom of the page): paste the bot token, find the chat, send a test message, copy the link and send it to Antonina. If Telegram is offline, messages wait on her device and are sent next time.
