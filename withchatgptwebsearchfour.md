## Milestone 2 - ChatGPT : Why Users are Not using Voice Input on ChatGPT Mobile, especially in India

### Solution to ChatGPT Problem Framing, Ideation & Validation + Metrics: Why Users are Not using Voice Input on ChatGPT Mobile, especially in India

#### Task 4 - Write down hypotheses on why this segment is not using voice input

For the chosen segment — **Indian students/early-career learners aged 18–24 using ChatGPT primarily on mobile** — I would frame the hypotheses as **testable explanations**, not established facts.

OpenAI says India has the world's largest student population on ChatGPT, with millions using it for homework, exam preparation and exploring ideas. Study Mode now explicitly supports voice dictation/conversations for learning, making this a particularly relevant segment for a Voice-adoption strategy.

| #       | Hypothesis                                                        | Why we believe it                                                                                                                                                                                                                                           | What to validate                                                          |
| ------- | ----------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| **H1**  | **Students don't know Voice exists**                              | Voice may not be sufficiently discoverable; small India-focused user studies report awareness/discoverability gaps. ([LinkedIn][1])                                                                                                                         | % who know Voice exists; % who can locate it without help                 |
| **H2**  | **Typing feels more accurate than speaking**                      | Students worry ChatGPT will misinterpret accents, technical terminology or mixed-language speech. Indian voice research identifies accent/native-language understanding as a significant barrier. ([Academy of Management Journals][2])                     | Transcription error rate; perceived accuracy; retry rate                  |
| **H3**  | **Hinglish/code-switching reduces trust**                         | Indian speech frequently mixes languages; recent India voice-AI research highlights code-switching as a fundamental challenge. ([Hindustan Times][3])                                                                                                       | Voice success rate for English vs Hindi vs Hinglish vs regional languages |
| **H4**  | **Students don't feel comfortable speaking in shared spaces**     | Hostels, classrooms, libraries, homes and public transport make spoken queries audible to others. India-focused student research reports privacy/social-comfort concerns. ([LinkedIn][4])                                                                   | Usage by environment; % avoiding Voice because others can hear            |
| **H5**  | **Typing gives students greater control**                         | Students can formulate, edit and review a question before sending it; speaking feels harder to correct once uttered.                                                                                                                                        | Edit/retry behavior; perceived control score                              |
| **H6**  | **Voice isn't perceived as faster for real study tasks**          | Although speech can be faster than typing, errors, corrections and waiting can erase the perceived speed advantage. India research identifies "value barriers" as adoption inhibitors. ([Taylor & Francis Online][5])                                       | Task completion time: Voice vs typing                                     |
| **H7**  | **Voice doesn't fit students' dominant study workflows**          | Students frequently need to paste questions, upload PDFs/images, read formulas, inspect code or work from notes. Voice alone doesn't replace these workflows. Study Mode already supports images, PDFs and other study materials. ([OpenAI Help Center][6]) | Voice usage by task type; Voice → text/image switching                    |
| **H8**  | **Students don't trust Voice for technical/academic terminology** | Engineering/science students may use specialized terms, names, formulas and abbreviations that are more easily typed or pasted.                                                                                                                             | Error rate on STEM/technical prompts                                      |
| **H9**  | **Poor network/device conditions discourage repeat use**          | Voice is more sensitive to streaming, microphone and environmental conditions than simple text input.                                                                                                                                                       | Voice failure rate by network/device tier                                 |
| **H10** | **Students don't have a compelling Voice-specific use case**      | If Voice provides the same experience as typing, users have little reason to change an established behavior.                                                                                                                                                | Ask: "What task would make you choose Voice over typing?"                 |
| **H11** | **Students perceive typing as the "serious study" mode**          | Some student research suggests typing is associated with deliberate/academic work, while Voice feels casual. This is a behavioral/mental-model hypothesis that needs stronger validation. ([LinkedIn][4])                                                   | Qualitative interviews + task-mode preference                             |
| **H12** | **Voice lacks a strong habit loop**                               | Students may try Voice once but return to typing because the experience doesn't create a recurring trigger.                                                                                                                                                 | First Voice session → 7-day repeat rate                                   |

[1]: https://www.linkedin.com/posts/md-arif-khan-a1054b207_user-research-activity-7359903500090134528-r-HL?utm_source=chatgpt.com "Uncovering Voice Input Barriers for Indian Students on ChatGPT | MD ARIF KHAN posted on the topic | LinkedIn"
[2]: https://journals.aom.org/doi/10.5465/AMPROC.2025.12755abstract?utm_source=chatgpt.com "Namaste Alexa, Siri, and Google: Voice Assistants and Communication Accommodation Problems of India | Academy of Management Proceedings"
[3]: https://www.hindustantimes.com/ht-insight/future-tech/why-ai-voice-agents-break-in-india-101785150773089.html?utm_source=chatgpt.com "Why AI voice agents break in India | Hindustan Times"
[4]: https://www.linkedin.com/posts/shantanu-singh-bisht-940624159_chat-gpt-voice-input-research-activity-7383780111512330240-OQC_?utm_source=chatgpt.com "Understanding why Indian students avoid voice input in ChatGPT | Shantanu Singh Bisht posted on the topic | LinkedIn"
[5]: https://www.tandfonline.com/doi/full/10.1080/08874417.2024.2312858?utm_source=chatgpt.com "Full article: Assessing Factors Influencing Customers’ Adoption of AI-Based Voice Assistants"
[6]: https://help.openai.com/en/articles/11780217-study-mode?utm_source=chatgpt.com "Using Study Mode in ChatGPT | OpenAI Help Center"

### I would prioritize these 5

For a PM case, **don't present 12 hypotheses as equally important.** I'd prioritize five.

🔴 **H1 — Discoverability**

**Students don't use Voice because they don't notice or understand that Voice is available.**

**Test:** Show the current mobile UI and ask users to start a voice interaction.

**Metric:**

Voice discoverability rate = users who successfully locate Voice / users tested

🔴 **H2 — Indian speech recognition**

**Students try Voice but abandon it because ChatGPT misunderstands Indian accents, Hinglish and technical terms.**

This is particularly credible because research on Indian voice assistants identifies language/accent accommodation as a distinct challenge, while current reporting highlights multilingual and code-mixed speech as baseline Indian conditions.

**Test:** Compare:

- English
- Hindi
- Hinglish
- Tamil/other regional language
- Technical vocabulary

**Metrics:**

Speech recognition accuracy

Correction/retry rate

Successful task completion

🔴 **H3 — Privacy/social comfort**

**Students avoid Voice when studying around other people because they don't want their questions or conversations overheard.**

This is especially relevant to **hostels, classrooms, libraries, family homes and public transport.** Student-focused research has surfaced this exact concern, although the cited studies are small and should be treated as directional rather than population estimates.

**Test:**

Ask:

"Where do you normally use ChatGPT?"

Then:

"Would you use Voice in that location?"

🟠 **H4 — Typing feels more controllable**

**Students prefer typing because they can think, edit and verify their question before sending it.**

This is particularly important for academic questions where wording matters.

**Test:** Give users the same difficult study task using Voice and typing.

Measure:

- corrections
- retries
- abandoned prompts
- perceived control
- task completion time

🟠 **H5 — No compelling Voice-first learning use case**

**Students understand Voice but don't perceive enough incremental value over typing.**

This may ultimately be the **biggest product hypothesis.**

If the experience is:

**Typing → answer**

versus

**Voice → same answer**

then why change behavior?

But:

**Voice → conversational tutor → asks follow-up → listens → quizzes → corrects**

is a fundamentally different experience.

OpenAI's Study Mode is already designed around this interactive learning model and supports voice dictation/conversations, which strengthens this product hypothesis.

### The hypothesis tree

I'd present your PM case like this:

**Why aren't Indian students using ChatGPT Voice?**

→ **They don't know about it**

- H1: Low awareness
  
- H1a: Poor discoverability

→ **They tried it but didn't trust it**

- H2: Accent recognition
  
- H3: Hinglish/code-switching
  
- H8: Technical terminology

→ **They don't feel comfortable using it**

- H4: Privacy
  
- H11: Social/cultural discomfort

→ **They prefer typing**

- H5: Greater control
  
- H6: Typing perceived as faster
  
- H7: Existing text/image study workflows

→ **They don't see enough incremental value**

- H10: No Voice-specific JTBD
  
- H12: No habit loop

### 🎯My core hypothesis

If I had to reduce everything to one hypothesis for the case, I'd choose:

**"Indian students don't adopt ChatGPT Voice because they don't yet perceive it as more reliable, private, or useful for studying than typing."**

And break that into three dimensions:

**Trust** → "Will it understand me?"

**Context** → "Can I use it here?"

**Value** → "Why should I speak instead of type?"

That gives you a very clean path into the next PM step:

**Hypotheses → User interviews/survey → Prioritization → Root cause → Product solution → KPI.**

## References

1. [Using study mode in ChatGPT](https://help.openai.com/en/articles/11780217-using-study-mode-in-chatgpt?utm_source=chatgpt.com).

2. [Why AI voice agents break in India](https://www.hindustantimes.com/ht-insight/future-tech/why-ai-voice-agents-break-in-india-101785150773089.html?utm_source=chatgpt.com).

3. [Signals individual data](https://openai.com/signals/data/?utm_source=chatgpt.com).

4. [The Efficacy of ChatGPT “Voice” Mode in AI-Assisted Language Learning: EFL Students’ Viewpoints](https://rsisinternational.org/journals/ijriss/view/the-efficacy-of-chatgpt-voice-mode-in-ai-assisted-language-learning-efl-students-viewpoints).
   
5. [ChatGPT — ಬಿಡುಗಡೆ ಟಿಪ್ಪಣಿಗಳು](https://help.openai.com/kn-in/articles/6825453-chatgpt-%E0%B2%AC%E0%B2%A1%E0%B2%97%E0%B2%A1-%E0%B2%9F%E0%B2%AA%E0%B2%AA%E0%B2%A3%E0%B2%97%E0%B2%B3?utm_source=chatgpt.com).

## Go back to [README](README.md) **or** **Click on** **[Task 5](withchatgptwebsearchfive.md)**
