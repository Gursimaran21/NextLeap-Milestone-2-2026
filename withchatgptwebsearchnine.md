## Milestone 2 - ChatGPT : Why Users are Not using Voice Input on ChatGPT Mobile, especially in India

### Solution to ChatGPT Problem Framing, Ideation & Validation + Metrics: Why Users are Not using Voice Input on ChatGPT Mobile, especially in India

#### Task 9 - Insights from user research (quantitative and qualitative) — pain points, blockers

### User Research Insights: Pain Points & Blockers

For the chosen segment — **Indian students aged 18–24 using ChatGPT primarily on mobile** — the research points to a key distinction:

**The problem is not simply lack of awareness. The bigger issue is that Voice has not yet become a trusted, contextually appropriate alternative to typing.**

OpenAI's own India data shows that 18–24-year-olds generate **just under half of ChatGPT messages in India**, making this a high-impact segment. India also has the largest student population on ChatGPT globally.

### Quantitative + qualitative evidence

| Finding                             | Evidence                                                                                                                                                                                                  | What it tells us                                              |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| **Awareness/discoverability**       | One 34-response + 6-interview India study reported 60% didn't know Voice existed and 50% found the mic difficult to spot. ([LinkedIn][1])                                                                 | Some users don't reach the first Voice experience             |
| **Low regular usage despite trial** | Independent India research reports high trial/awareness but much lower regular usage. ([LinkedIn][2])                                                                                                     | **Retention/adoption is more important than awareness alone** |
| **Accuracy/trust**                  | Indian student research reports concerns around transcription accuracy; multilingual research found frequent ASR errors with proper nouns, Hindi loanwords and non-standard accents. ([DOI][3])           | One bad transcription can cause users to revert to typing     |
| **Hinglish/code-switching**         | CHI 2026 research found inconsistent handling of Hindi/Hinglish inputs disrupted conversation and caused frustration. ([DOI][3])                                                                          | Natural Indian speech isn't always the same as formal English |
| **Privacy/social comfort**          | India-focused student research identifies discomfort using Voice in hostels/shared/public spaces. ([LinkedIn][2])                                                                                         | Voice is **context-dependent**                                |
| **Typing feels easier**             | Independent research identifies typing preference/ease as a major barrier. ([NextLeap][4])                                                                                                                | Users need a compelling reason to change behavior             |
| **Academic workflow mismatch**      | Students often need to formulate prompts, attach material and inspect outputs; Indian higher-ed research also finds prompt formulation and uncertainty around output quality challenging. ([Springer][5]) | Voice needs to complement—not replace—text/image workflows    |

[1]: https://www.linkedin.com/posts/indoo_voice-input-user-research-deep-dive-activity-7370858568813678592-C5S5?utm_source=chatgpt.com "Understanding Voice Input Adoption in ChatGPT among Indian Users | Indoo Yadav posted on the topic | LinkedIn"
[2]: https://www.linkedin.com/posts/shantanu-singh-bisht-940624159_chat-gpt-voice-input-research-activity-7383780111512330240-OQC_?utm_source=chatgpt.com "Understanding why Indian students avoid voice input in ChatGPT | Shantanu Singh Bisht posted on the topic | LinkedIn"
[3]: https://doi.org/10.1145/3772318.3791266?utm_source=chatgpt.com "Voice-Based Chatbots for English Speaking Practice in Multilingual Low-Resource Indian Schools: A Multi-Stakeholder Study | Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems"
[4]: https://assets.nextleap.app/submissions/Milestone3_PRD-fbe59a57-9a2f-4ddb-a6c7-cd7f912dec01.pdf?utm_source=chatgpt.com "Boosting Voice Input Adoption in ChatGPT Mobile (India)"
[5]: https://link.springer.com/article/10.1007/s44217-026-01300-8?utm_source=chatgpt.com "Perceptions challenges and ethical concerns of ChatGPT use in Indian higher education institutions | Discover Education | Springer Nature Link"

**1. Pain Point: "Will Voice understand me?"** 🔴

**User anxiety**

**"If ChatGPT misunderstands what I said, I have to repeat everything."**

This is especially relevant for:

- Indian accents
- regional languages
- Hinglish
- technical terminology
- names/proper nouns

The strongest external evidence comes from the 2026 CHI study of multilingual Indian learners: researchers observed ASR errors for **nearly all students**, particularly with proper nouns, Hindi loanwords, non-standard English pronunciation and code-switching. These errors disrupted conversational flow and caused frustration.

**Behavioral consequence**

**Voice fails once → user switches to typing → typing becomes the default.**

**Blocker**

**Low trust in speech recognition.**

**2. Pain Point: "I don't want everyone hearing me."** 🔴

A student may use ChatGPT in:

- hostel
- classroom
- library
- PG
- family home
- public transport

Typing is silent.

Voice is audible.

One India-focused qualitative study specifically reported:

"**Voice feels awkward in hostels – everyone can hear my questions.**"

This creates an important behavioral pattern:

**Same user + different context = different input method.**

| Context            | Likely behavior |
| ------------------ | --------------- |
| Alone in room      | Voice           |
| Walking alone      | Voice           |
| Hostel common area | Typing          |
| Library            | Typing          |
| Classroom          | Typing          |
| Family room        | Typing          |

**Blocker**

**Social + privacy anxiety.**

**3. Pain Point: "Typing gives me more control."** 🟠

Students can:

**Think → type → edit → review → send**

Voice feels more like:

**Think → speak → submit**

For academic questions, users may want to carefully formulate:

"Explain the difference between supervised and unsupervised learning with three examples..."

They may feel more comfortable **seeing and editing that prompt before sending it**.

This is consistent with broader Indian higher-education research, where students report difficulty with prompt formulation and uncertainty about whether their inputs will produce appropriate outputs.

**Blocker**

**Perceived loss of control.**

**4. Pain Point: "Why should I use Voice?"** 🟠

This is potentially the deepest blocker.

If the experience is:

**Typing → answer**

versus:

**Voice → same answer**

then Voice has no compelling behavioral advantage.

The user asks:

**"Why change what already works?"**

This explains why simply adding a microphone button is unlikely to create sustained adoption.

**Blocker**

**Weak Voice-specific value proposition.**

**5. Pain Point: Voice doesn't fit every study task**

Students don't just ask questions.

They also:

- upload PDFs
- share screenshots
- paste assignment questions
- copy code
- work with formulas
- reference notes
- compare documents

Therefore, Voice alone cannot replace the complete study workflow.

OpenAI's Study Mode already supports **voice dictation for asking questions**, alongside broader interactive learning functionality.

**Blocker**

**Voice is perceived as an additional input mode rather than an integrated learning workflow.**

**6. Pain Point: Voice may feel "casual," while typing feels "academic."**

This emerged strongly in independent India-focused research:

**"Typing feels more serious for studying."**

That's a fascinating **mental-model blocker.**

Students may unconsciously categorize:

**Typing = study/productivity**

**Voice = casual conversation**

This means even perfect speech recognition wouldn't necessarily solve the problem.

The product needs to demonstrate:

**Voice can actually make learning better.**

**7. Pain Point: Language switching is natural; Voice may not feel natural**

An Indian student might speak:

"Can you explain this concept thoda simple way mein?"

That's normal conversational behavior.

The user doesn't want to consciously decide:

"Should I speak English now?"

"Will Hindi work?"

"Should I avoid this word?"

Research with multilingual Indian learners found that such code-switching could lead to inconsistent system processing.

**Blocker**

**Users adapt their language to the technology instead of technology adapting to the user.**

### Pain-point hierarchy

I'd consolidate the research into **five major blockers:**

<img width="392" height="597" alt="withchatgptwebsearchnine" src="https://github.com/user-attachments/assets/ab6e63b9-a099-4d06-ae36-462dcebe58c2" />

### Quantitative vs qualitative insight

This distinction will make your PM presentation stronger.

**Quantitative evidence tells us:**

**WHAT is happening**

- Voice awareness can be low for some cohorts.
- Trial is higher than regular use.
- Typing remains the dominant behavior.
- Privacy/usability/awareness appear repeatedly as barriers in independent India studies.

**Qualitative evidence tells us:**

**WHY it happens**

"I don't want people hearing me."

"It doesn't understand when I mix Hindi and English."

"Typing feels more serious."

"I tried it and it got my question wrong."

These quotes and themes are reported in independent India-focused research, not OpenAI's official user research, so they should be labelled accordingly.

### 🎯 Core research insight

Putting everything together:

**Students aren't rejecting Voice—they are rejecting the uncertainty around Voice.**

Typing gives them:

**Accuracy + privacy + control + predictability**

Voice currently offers:

**Speed + conversational interaction**

But for many students:

**The perceived risk of Voice > perceived benefit of Voice.**

Therefore, the real product challenge is:

**Make Voice feel as trustworthy as typing while preserving the speed and conversational advantage of speaking.**

That gives us a much sharper path to the next step:

**Pain points → root causes → opportunity areas → solution ideas → prioritization → MVP → KPIs.**

## Go back to [README](README.md) **or** **Click on** **[Task 10](withchatgptwebsearchten.md)**
