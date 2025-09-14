---
title: "Chat Melody — Assistant Chatbot for Music Education"
date: 2024-09-10
aliases: []
tags: ["AI","Education","Music Theory","Teachable Agent","LLM","Chatbot"]
author: "Mengze Hong"   # or "Mengze Hong" if you prefer personal credit
description: "An assistant chatbot that teaches music theory through dialogue—improving learning gains and lowering cognitive load."
summary: "LLM-powered teachable agent for music theory. Students teach the bot while analyzing scores with playback, leading to higher post-test scores and reduced cognitive load."
cover:
  image: "music.png"
  alt: "Chat Melody — assistant chatbot for music education"
  relative: true
editPost:
  URL: "https://github.com/mengze-hong/ChatMelody"   # update if your repo differs
  Text: "Project Repo"
showToc: false
disableAnchoredHeadings: true

---

{{< figure src="music2.jpg" alt="Chat Melody Interface Design"
           width="900" >}}

### Overview

Chat Melody is an assistant chatbot for music education. Students learn music theory by teaching the assistant how they hear and see a piece. The assistant behaves like a curious learner and keeps the conversation focused on musical reasoning instead of shortcuts. The experience pairs score viewing with audio so learners connect notation, harmony, and form with what they hear.
<br>

### Why it matters

Many learners memorize rules without building a stable sense of why chords and phrases work the way they do. One-to-one coaching is rare and feedback often comes late. Chat Melody gives structured guidance in the moment. It nudges students to justify choices, compare alternatives, and connect symbols on the page with sound in the ear. This helps turn facts into understanding.
<br>

### How students learn

A student opens a short piece or excerpt and can view the score and play audio. The assistant asks a simple focus question that matches the task for example identify the cadence or outline the phrase. The student explains what they see and hear. The assistant reflects the explanation back, highlights gaps, and asks for specific evidence such as pitch content, position in the measure, or voice leading. When the student proposes a chord or label, the assistant requests a brief justification and a check against context. If the student is stuck, the assistant suggests the next small step rather than giving a full answer. At the end the assistant summarizes the reasoning chain so the student leaves with a clear record of how they reached the result.
<br><br>

{{< figure src="music3.png" alt="Chat Melody"
           caption="Figure: Interface design of the LLM-powered Teachable Agent."
           width="900" >}}
<br>

### Technology and architecture

Chat Melody is an LLM driven dialog system with domain scaffolding for tonal analysis. The conversation engine runs a small policy that turns student messages into intents such as identify, justify, compare, and reflect. Prompts are modular and draw on a bank of musical moves so the assistant can request evidence about pitch sets, inversion cues, harmonic function, and cadential patterns without revealing solutions.

The score and audio layer presents notation and playback in the browser and supports note selection and section looping. The assistant can reference student selections through lightweight metadata so questions feel grounded in the page the learner is viewing. Common formats such as MusicXML and MIDI are supported to keep import simple.

Session state keeps a compact memory of claims and evidence so the assistant can say what has already been established and what still needs support. A rubric store defines what good reasoning looks like for tasks such as roman numeral analysis or phrase labeling. That rubric drives hints, checks, and end summaries.

Safety and quality controls keep the assistant on task. The system limits the model to pedagogical actions, strips out requests for solutions, and logs unclear prompts for later tuning. Analytics capture only what is needed to improve coaching prompts and measure engagement. The service is deployable behind a school or studio account and can run against different model providers.
<br>

### What this enables

Instructors can assign practice that looks like real studio coaching and still scale to a full class. Learners get immediate guidance and a trace of their reasoning that they can review later. The same framework can support ear training, counterpoint, and form study by swapping the rubric and prompt bank while keeping the conversation engine and score layer the same.


