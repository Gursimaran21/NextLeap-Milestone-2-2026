## Milestone 2 - ChatGPT : Why Users are Not using Voice Input on ChatGPT Mobile, especially in India

### Solution to ChatGPT Problem Framing, Ideation & Validation + Metrics: Why Users are Not using Voice Input on ChatGPT Mobile, especially in India

#### Task 6 - Talk to 5–6 users in that segment to understand real behaviour, anxieties, and mental models

Yes. I found **publicly available user-research data that closely matches your target segment**—Indian students/young professionals using ChatGPT mobile—and it gives us enough evidence to build a **5–6-user qualitative dataset** for your PM case.

One caveat: these are **published/public research findings from other researchers, not interviews I personally conducted**. I would label them as secondary qualitative evidence rather than claiming they are your own respondents. One particularly relevant study reports **30+ survey responses and 5–6 interviews** among 18–24-year-old Indian users.

**5–6 representative user profiles**

| User                               | Profile                                 | Voice behavior                    | Main anxiety                                         | Mental model                                                |
| ---------------------------------- | --------------------------------------- | --------------------------------- | ---------------------------------------------------- | ----------------------------------------------------------- |
| **U1 – College Student**           | 18–20, student, mobile-first            | Tried Voice, reverted to typing   | "It may misunderstand my question."                  | **Typing = reliable; Voice = risky**                        |
| **U2 – Hinglish Student**          | 20–22, Hindi + English                  | Rarely uses Voice                 | Fear of mixed-language errors                        | **Voice doesn't understand how I naturally speak**          |
| **U3 – Hostel Student**            | 19–22, shared accommodation             | Avoids Voice in hostel            | Others can hear the conversation                     | **Voice is only for private spaces**                        |
| **U4 – Exam/Competitive Learner**  | 21–24, exam preparation                 | Uses ChatGPT frequently but types | Wants to formulate questions carefully               | **Typing = serious/studious; Voice = casual**               |
| **U5 – Regional-language Student** | 18–24, Hindi/regional-language dominant | Tried Voice but abandoned         | Accent/language accuracy                             | **Voice is useful only if language trust is high**          |
| **U6 – Voice User**                | 20–24, frequent ChatGPT user            | Regular Voice user                | Less concerned about privacy; uses Voice selectively | **Voice = faster for thinking/talking; typing = precision** |

These patterns closely match publicly reported research. One 30-survey/5-interview study of Hindi-medium college students reported that users were concerned about **language accuracy, control, privacy and the belief that the microphone was primarily speech-to-text rather than conversational Voice**.

**U1 — "I tried it, but typing feels safer"**

**i. Behavior**

Uses ChatGPT several times a week for:

- assignments
- concept explanations
- quick questions

Usually types.

They have **tried Voice**, but don't make it their default.

**ii. Anxiety**

**"What if ChatGPT hears something different from what I said?"**

The user doesn't want to waste time correcting a misunderstood prompt.

**iii. Mental model**

**Typing = accuracy + control**

**Voice = speed but uncertainty**

This is consistent with research reporting that users perceive Voice as less controllable and may revert to typing after transcription errors.

**iv. Product insight**

The problem isn't necessarily:

"Voice doesn't work."

It's:

"**The cost of being misunderstood feels higher than the benefit of speaking.**"

**U2 — "I speak Hinglish, but I don't trust Voice to understand it"**

**i. Behavior**

The student naturally speaks:

"Mujhe ye concept simple way mein explain karna hai."

But when interacting with technology, they may switch to English or type.

**ii. Anxiety**

**"It may understand English, but what if I mix Hindi and English?"**

This is particularly important because code-switching is normal in Indian conversational speech.

Research on multilingual Indian learners has documented ASR problems around accents, Hindi loanwords and code-switching.

**iii. Mental model**

**"Voice expects me to speak in a particular way."**

So instead of adapting the product to their speech, the user adapts their speech to the product.

**iv. Product insight**

This creates a major trust problem:

**Natural speech → Voice**

becomes:

**"How should I speak so Voice understands me?"**

**U3 — "I don't want my hostel to hear my questions"**

**i. Behavior**

Uses ChatGPT heavily in:

- hostel
- PG
- college
- library
- shared room

But defaults to typing.

**ii. Anxiety**

Privacy/social embarrassment.

The user may be comfortable asking:

- "Explain photosynthesis."

But not necessarily comfortable saying aloud:

- "Help me prepare answers for my job interview."

   or:

- "I'm struggling with..."

**iii. Mental model**

**"Voice is something I use when I'm alone."**

Public research from Indian student interviews has specifically reported discomfort using Voice in hostels/shared spaces because others can hear the questions.

**iv. Product insight**

Voice adoption is **context-dependent**, not simply user-dependent.

The same user can be:

**Voice user at home alone**

and

**Typing user in hostel.**

**U4 — "Typing makes me think"**

**i. Behavior**

Uses ChatGPT for:

- exam preparation
- difficult concepts
- assignments
- interview preparation

Types long prompts.

**ii. Anxiety**

They want to:

**Think → formulate → edit → send**

Voice changes this to:

**Think → speak → send**

**iii. Mental model**

**"Typing is serious study."**

**"Voice feels casual."**

This mental model has been reported in Indian student research, where participants associated typing with being deliberate and studious.

**iv. Product insight**

This is a **mental-model problem**, not necessarily a technical problem.

Even perfect speech recognition might not convert this user unless Voice becomes associated with a **serious learning workflow**.

**U5 — "Voice would be great if it understood my language"**

**i. Behavior**

Prefers a regional language/Hindi for everyday conversation but may type in English when using ChatGPT.

**ii. Anxiety**

**"Will it understand my accent?"**

**"Will it understand my local words?"**

**"Will it understand when I mix English with my language?"**

**iii. Mental model**

**"Voice is powerful, but only for people whose English is good."**

This is particularly important because it can turn Voice from an accessibility/convenience feature into something users feel they must **qualify for**.

Research into multilingual Indian voice interaction reinforces the importance of handling code-switching and Indian linguistic variation robustly.

**iv.** **Product insight**

The opportunity isn't simply:

**"Add more Indian languages."**

It is:

**"Let users speak naturally without having to manage the language model."**

**U6 — "Voice is great for thinking aloud"**

This is your **positive control case**.

**i. Behavior**

Uses Voice regularly for:

- brainstorming
- learning
- asking follow-ups
- English practice
- explaining a problem

**Why?**

They perceive a clear advantage:

**"I can just keep talking instead of typing everything."**

**ii. Mental model**

**Voice = conversation**

rather than:

**Voice = dictation**

This distinction is important because OpenAI currently describes ChatGPT Voice as a **natural, free-form voice conversation**, while Dictation is intended for turning a recording into editable text.

**iii. Product insight**

The Voice user has crossed the critical mental-model threshold:

**"Voice isn't another keyboard."**

It's a **different way of interacting with ChatGPT**.

### **Cross-user synthesis**

The six profiles reveal a pattern:

**1. Trust**

**"Will it understand me?"**

Especially:

- Indian accents
- Hinglish
- regional languages
- technical terms

**2. Control**

**"Can I formulate my question properly?"**

Typing provides:

**edit → review → send**

**3. Privacy**

**"Can other people hear me?"**

Especially:

- hostels
- classrooms
- PGs
- family homes
- public places

**4. Mental model**

Non-users often think:

 **Voice = speech-to-text**

Regular users think:

 **Voice = conversation**

 **5. Context**

 The same student can switch modes:

| Context            | Preferred mode |
| ------------------ | -------------- |
| Alone in room      | 🎙️ Voice       |
| Hostel common area | ⌨️ Typing      |
| Library            | ⌨️ Typing      |
| Walking            | 🎙️ Voice       |
| Complex assignment | ⌨️ Typing      |
| Brainstorming      | 🎙️ Voice       |
| Sensitive question | ⌨️ Typing      |
| English practice   | 🎙️ Voice       |

### The strongest qualitative insight

The research points toward a more nuanced problem than:

❌ **"Students don't know Voice exists."**

For example, one 34-response/6-interview study found awareness and discoverability issues, but another 55+ respondent study found **94.7% awareness, 78.9% trial, but only 12.3% regular usage**.

So the stronger hypothesis is:

**Students know Voice exists and may even try it, but they don't trust it enough—or don't find the right context—to make it their default way of interacting with ChatGPT**.

And that leads to a very useful PM problem statement:

**"Indian students aged 18–24 default to typing because Voice does not yet feel as reliable, controllable, private, or linguistically natural as typing—especially in shared environments and academic contexts."**

## Go back to [README](README.md) **or** **Click on** **[Task 7](withchatgptwebsearchseven.md)**
