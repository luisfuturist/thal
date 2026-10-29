# TODO — thal

- [ ] T-001 Refactor code that is only app, server and shared (keep code in the right folders) · created:2026-10-29
- [ ] T-002 Fix tsconfig on nuxt v4 - typecheck not working properly · created:2026-10-29

## 0.2.0-2 - Focus mode message analysis

- [ ] T-003 Improve analysis prompting (it's not working for fantasy, not considering politeness as well) · created:2026-10-29
  - [ ] T-192 Summary should not focus on "remove this, add that" but on the actual changes in a generic/overview way, like "found typos..."
- [ ] T-004 Summary should not focus on "remove this, add that" but on the actual changes in a generic/overview way, like "found typos..." · created:2026-10-29
- [ ] T-005 Improve the explanation prompting · created:2026-10-29
- [ ] T-006 Add focus mode to the message analysis modal · created:2026-10-29
  - [ ] T-193 Focus in that particular wavy underline part of the message and pass it to the assistant (it will be able to understand if the that part is associated with other parts as well!)
  - [ ] T-194 Explain the mistake and why it's wrong
  - [ ] T-195 Add "Ignore this mistake" button
- [ ] T-007 Focus in that particular wavy underline part of the message and pass it to the assistant (it will be able to understand if the that part is associated with other parts as well!) · created:2026-10-29
- [ ] T-008 Explain the mistake and why it's wrong · created:2026-10-29
- [ ] T-009 Add "Ignore this mistake" button · created:2026-10-29

## 0.2.0-3

- [ ] T-010 Fix (translation) prompt injection · created:2026-10-29
- [ ] T-011 Fix double message listening · created:2026-10-29
- [ ] T-012 How to modify analysis based on future messages? · created:2026-10-29
- [ ] T-013 Perf: implement virtual and infinite scrolls · created:2026-10-29
- [ ] T-014 Perf: ignore too far way messages in the past (cut the history to most recent messages) · created:2026-10-29
- [ ] T-015 Add more features to the chat bubble inside the message analysis modal, such as speech, copy, etc. · created:2026-10-29

## 0.3.0

- [ ] T-016 Add feature to generate (more) examples of the incorrect-correct pairs · created:2026-10-29
- [ ] T-027 Save translations in the database (it will be useful for analytics and be used to improve the translation quality) · created:2026-10-29
  - [ ] T-196 Refactor translate endpoint into /api/message/translate with messageId param?
- [ ] T-028 Refactor translate endpoint into \`/api/message/translate\` with \`messageId\` param? · created:2026-10-29
- [ ] T-029 Add \[hint mode]\(./notes/hint.md) · created:2026-10-29
- [ ] T-030 Allow users to see the translation on a popover by selecting a text/word on the message, also below the translation the user can COPY, LISTEN · created:2026-10-29
- [ ] T-031 Implement basic analytics to track user engagement and app performance · created:2026-10-29

## 0.2.1 — Issues related

- [ ] T-017 Force test with ton of characters, chats, contacts and messages · created:2026-10-29
- [ ] T-018 Virtual scroll for chats, messages and discover · created:2026-10-29
- [ ] T-019 Improve SEO, robots.txt, meta tags, etc · created:2026-10-29
  - [ ] T-197 Fix character seo tags
- [ ] T-020 Fix character seo tags · created:2026-10-29
- [ ] T-021 Add infinite queries to lists (specially chat) · created:2026-10-29
- [ ] T-022 Deal with long history on translate · created:2026-10-29
- [ ] T-023 Fix listening to long messages · created:2026-10-29
- [ ] T-024 Handle longer contexts · created:2026-10-29

## 0.2.1 — Post-release tasks

- [ ] T-025 Create characters · created:2026-10-29
- [ ] T-026 Share Thal with friends, family, colleagues, etc. · created:2026-10-29

## 0.4.0 - Language Assistance Improvements

- [ ] T-032 Add text input correction confirmation popover · created:2026-10-29
  - [ ] T-198 Diffing
  - [ ] T-199 Actions: "Regenerate", "Explain", "Apply", "Ignore"
- [ ] T-033 Diffing · created:2026-10-29
- [ ] T-034 Actions: "Regenerate", "Explain", "Apply", "Ignore" · created:2026-10-29
- [ ] T-035 Consider userId in query keys · created:2026-10-29
- [ ] T-036 Fix error page not showing translation · created:2026-10-29
- [ ] T-037 Ensure the app note is up to date · created:2026-10-29
- [ ] T-038 Add conversation starters for users · created:2026-10-29
- [ ] T-039 Add follow up message suggestions · created:2026-10-29

## 0.5.0

- [ ] T-040 Language Practice Reminders: Send notifications encouraging users to engage in language practice with their saved characters. · created:2026-10-29
  - [ ] T-200 Daily/week reminders to keep users practicing
  - [ ] T-201 Push Notifications: Reminders and encouragement to practice regularly
  - [ ] T-202 Add to terms that we can send email notifying messages of characters (after off-line daily)
- [ ] T-041 Daily/week reminders to keep users practicing · created:2026-10-29
- [ ] T-042 Push Notifications: Reminders and encouragement to practice regularly · created:2026-10-29
- [ ] T-043 Add to terms that we can send email notifying messages of characters (after off-line daily) · created:2026-10-29
- [ ] T-044 After days not used the app, the character sends a message (powered by character memory to create a persuasive but with the character persnality). The idea is t ouse 1–2 facts of the user or them (e.g. name, hobby, last topic). Drop them naturally like “So, how’s your guitar practice going?” Boom—instant connection. (This improves Retention) · created:2026-10-29
- [ ] T-045 Continue backlog · created:2026-10-29
- [ ] T-046 Look for TODOS inside the codebase · created:2026-10-29
