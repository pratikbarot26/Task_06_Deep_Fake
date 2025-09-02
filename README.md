# 📘 Syracuse University iSchool OPT Research Task 06

This project extends **Task 05** by transforming the football narrative (2021 → 2024) into an **AI-generated “deep fake” interview**.  

The workflow has three parts:

1. **🎤 Scriptwriting** — Using verified Task 05 stats, I developed two distinct video-ready interview scripts:
   - *Analyst Desk Style* (SportsCenter tone)  
   - *Street Interview Style* (campus vox-pop)  
   Scripts were drafted and refined with help from **ChatGPT** and **Google Gemini** to ensure factual accuracy and conversational flow.

2. **🤖 AI Video Generation** — Multiple tools were explored:
   - **Google Flow (Veo 3 model)** → gave the most realistic-looking results, but limited by free credits (sample video created).  
   - **Sora** → lacked integrated audio, limiting full interview generation.  
   - **EasyVid** → produced complete interview-style videos with audio, but free-tier outputs contained watermarks and were clearly identifiable as AI-generated.  
   Final videos included here were generated with **EasyVid**.

3. **💻 Transparency & Verification** — All narrative content ties directly back to Task 05’s descriptive stats and notebook validation.

---

## 📦 What’s Included

- **Scripts** (`script1.md`, `script2.md`)  
- **Prompts** (`prompts/`) for natural speech rewriting and captions  
- **Final Videos** (EasyVid, watermark present)  
- **Summary Report** (`summary_task06.pdf`)  
- **README.md** (this file)

---

## 🗂 Data Notes

- **Source**: Syracuse 2021 & 2024 cumulative stats (page 1 only):contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}  
- **Scope**: Offense, defense, efficiency, turnovers, sacks, penalties, attendance, and record splits.  
- **Verification**: All claims validated in `Task_05_Syracuse_Football.ipynb` against typed dictionaries.

---

## 🧠 LLM → Media Flow

**Process Overview**  
1. Start with Task 05 verified stats.  
2. Drafted conversational scripts with **ChatGPT** and **Google Gemini**.  
3. Tested AI video generation across platforms (Google Flow, Sora, EasyVid).  
4. Final EasyVid outputs retained for submission.

**Tool Comparisons**  
- **Google Flow (Veo 3)** → Best realism, but free tier restrictive.  
- **Sora** → Promising visuals, but lacked audio integration.  
- **EasyVid** → Complete videos (with audio + interview format), but free tier adds watermark and outputs are easily detected as synthetic.

---

## 📈 Summary of Key Facts (Task 05 → Scripts)

- 2021: run-first (213 rush, 153 pass, 5 wins)  
- 2024: pass-first (98 rush, 370 pass, 10 wins)  
- Offense: +100 yds/g, +9 pts/g, +12 plays/g  
- Efficiency: 3rd-down ↑, red-zone TDs ↑, TOP ↑  
- Weakness: rushing O/def both slipped  
- Impact: attendance +20%  
- Recommendation: improve run defense to add +2 wins

---

## ▶️ Running Alternatives

- **Google Flow**: set up multi-agent flow (HOST/COACH), attach TTS voices, render outputs.  
- **Free local pipeline** (optional):  
  - *Coqui TTS* for audio  
  - *ffmpeg* for mixing  
  - *SadTalker or Wav2Lip* for video sync  

---

## 🙋 Acknowledgments

This project is for **Syracuse University iSchool OPT Research Task 06**.  
Scripts drafted and polished with **ChatGPT** and **Google Gemini**.  
AI-video generation tested with **Google Flow (Veo 3)**, **Sora**, and **EasyVid**.  
Final outputs generated in **EasyVid (free-tier)**.  
All stats grounded in Task 05 verification.  
