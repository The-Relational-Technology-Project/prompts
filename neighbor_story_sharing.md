# Neighbor Story Sharing – Builder Prompt

Build a local web platform for **Neighbor Story Sharing**: a lightweight, emotionally warm tool for collecting and sharing personal stories from community members to build trust, connection, and belonging. It should balance **simplicity, consent, and relational design** with a UI that feels welcoming, calm, and human — not like social media.

---

## Core Features

### 1. Homepage
- **Tagline (centered, bold):** “The shortest distance between two people is a story.”
- **Neighborhood Label:** prominent pill-shaped button with neighborhood name (e.g. “Outer Sunset”).
- **Call-to-Action:** “Express interest in stories below! You can select multiple. We’re covering coffee for the first 5 gatherings in our neighborhood.”
- **Filters:** collapsible “Show Filters” button for searching/sorting (by language, topic, recency).
- **Story Grid:** display story cards in a 2–3 column layout, scrollable.

---

### 2. Story Cards
Each story card should include:
- **Title** (short, bold).
- **Intro snippet** (first 1–2 lines of the story).
- **Language tags:** e.g., “English,” “Mandarin.” If translation support exists, add a tag: “Translator available.”
- **Author line:** e.g., “by Maria S.” (allow pseudonyms).
- **Interest counter:** shows how many neighbors clicked “Interested.”
- **Primary Button:** “Express Interest.”
- **State Change:** when selected, card border highlights (blue) and button changes to “Selected.”
- **Optional Badges:** e.g., “We’re organizing a gathering soon.”

---

### 3. Express Interest Flow
**Step 1: Confirmation modal (Join Multiple Story Circles).**
- List all selected stories with title + author.
- Explain how it works:
  1. We’ll notify authors of interest.
  2. When 2–3 neighbors express interest, authors may choose to organize a meetup.
  3. Meet at a local coffee shop/library to share and connect.
- Button: **Next.**

**Step 2: Your Information.**
- First name field.
- Contact preference toggle (Email or Text).
- Input field for email or phone number.
- Button: **Next.**

**Step 3: Privacy & Consent.**
- Checkbox: “Keep my identity private (story will show as Anonymous).”
- Checkbox: “Notify me when people want to hear my full story.”
- Contact method confirmation.
- Button: **Submit.**

---

### 4. Share a Story Flow
**Trigger:** “+ Share Story” button in top-right nav.

**Step 1: Inspiration Modal.**
- Prompts with icons:
  - Share something you want others to know about our neighborhood.
  - Tell us about your family’s journey.
  - Share something surprising about your life.
- Button: **Start Writing.**

**Step 2: Story Basics.**
- Title field.
- Short intro (1–2 sentence) field.
- Button: **Next.**

**Step 3: About You.**
- Name field (text).
- Story language (dropdown).
- Checkbox: “I can help translate for non-English speakers.”
- Translation language (dropdown).
- Button: **Next.**

**Step 4: Privacy & Meetups.**
- Checkbox: “Keep my identity private (show as Anonymous).”
- Checkbox: “Notify me when people want to hear my full story.”
- Contact method (Email/Text) + field for address/phone.
- Button: **Submit Story.**

---

### 5. Admin & Steward Features
- Dashboard for stewards to:
  - See submitted stories (with or without attribution).
  - Track interest counters.
  - Export contact list of people who opted in for meetups.
- Option to **pin or feature** certain stories on the homepage.
- Localization controls: easily swap in neighborhood name, copy, and visuals.

---

## UX / UI Design Guidelines
- **Tone:** warm, approachable, neighborly — not corporate or transactional.
- **Color palette:** soft pastels and gradients (like Outer Sunset sky). Use warm orange/pink for CTA buttons, calm blue for selections.
- **Typography:** large, friendly headers (sans-serif), clean body text. Avoid overly sleek or “techy” fonts.
- **Spacing:** generous padding, breathing room between cards. Focus on legibility.
- **Buttons:** rounded, tactile, with hover/selection states that feel alive.
- **Accessibility:** support for multilingual text entry and RTL scripts.

---

## Copy Guidelines
- Always frame participation as an **invitation, not extraction.**
- Examples:
  - Instead of “Submit Content,” say: “Share Your Story.”
  - Instead of “Register Interest,” say: “Express Interest.”
  - Remind people: “Stories are acts of care. Share only what feels safe.”
- Include community-specific hooks like: “We’re covering coffee for the first 5 gatherings.”

---

## Relational Design Principles
- **Consent & Care:** optional anonymity, clear opt-ins, emotional safety emphasized.
- **Low Barrier:** no login required to read or share.
- **Multilingual Respect:** language tags + translator available badges.
- **Bridge to Offline:** digital platform is a tool for **sparking real-world gatherings** — not an end in itself.
- **Community Memory:** stories serve as connective tissue, not just content.

---

## Automation Notes
Set up **email and/or SMS automations** for:
- Story submission confirmation (“Thanks for sharing your story”).
- Express interest confirmation.
- Meetup reminders: 1 week before, 1 day before, 1 day after.
- Story owner notification when neighbors express interest.

---
