### 🎧 Perceptual Load & Music Tempo: Impact on Reaction Times

🧠 **Project Title**  
The Effects of Perceptual Load and Background Music Tempo on Reaction Times in a Visual Search Task

📘 **Overview**  
This experimental study investigates how **perceptual load** and **music tempo** interact to influence cognitive performance in a visual search task.  

Key focus:  
- Whether high perceptual load slows reaction times  
- Whether music tempo affects reaction times  
- Whether tempo effects depend on perceptual load level  

---

🔍 **Abstract**  
Perceptual load is a well-studied factor in cognitive psychology, known to impact attention and task performance. This study explores its interaction with another factor — background music tempo. It was hypothesised that:  
1. Higher perceptual load would slow reaction times  
2. Higher music tempo would slow reaction times  
3. The effect of music tempo would be greater under low perceptual load  

**Participants:** 42 (28 females, 14 males)  
**Task:** Visual search task, pressing ‘J’ if an orange ‘L’ was present, ‘F’ if absent  
**Design:** Two-way repeated measures ANOVA with perceptual load (high vs. low) and music tempo (high, low, none)  

Results showed:  
- **Significant** main effect of perceptual load (*p* < .001) — slower reaction times in high-load conditions  
- **Non-significant** effect of music tempo  
- **Non-significant** interaction between perceptual load and tempo  

Implications: Findings reinforce the impact of perceptual load on processing speed and suggest music tempo has minimal influence in this task context.

---

🛠 **Built With**  
- **R**  
  - tidyverse  
  - psyntur  
  - afex  
  - emmeans  
  - janitor  
- CSV & Excel input  
- ggplot2 for visualisation  
- Two-way repeated measures ANOVA  

---

📊 **Key Results**  

| Effect | F-value | p-value | Interpretation |
|--------|--------:|--------:|----------------|
| Perceptual Load | 46.37 | < .001 | Significant — slower under high load |
| Music Tempo | 1.07 | .35 | Not significant |
| Interaction (Load × Tempo) | 0.60 | .55 | Not significant |

**Descriptive Statistics (Reaction Time in ms):**

| Condition | Mean | SD |
|-----------|------|----|
| High Load + High Tempo | 1571 | 822 |
| High Load + Low Tempo | 1591 | 888 |
| High Load + No Music | 1490 | 899 |
| Low Load + High Tempo | 1208 | 740 |
| Low Load + Low Tempo | 1258 | 786 |
| Low Load + No Music | 1325 | 795 |

---

🧪 **Method Summary**  
- Online experiment hosted on Gorilla.sc  
- 6 randomised trials per participant  
- Participants rested eyes between trials (20s suggested)  
- Excluded reaction times > 5000 ms (outliers)  
- Only correct responses included in analysis  
- Analysis: Two-way repeated measures ANOVA using `afex`  

---

📜 **Citation**  
If you use this study or code, please cite:  

Jarvis, M. (2025). *The Effects of Perceptual Load and Background Music Tempo on Reaction Times in a Visual Search Task*. GitHub. https://github.com/maryjarvis/psychology_research_projects/PerceptualLoadMusicTempo
