# 📊 Digital Engagement Communication Scale (DECS)

## 🧠 Project Title  
**The Impact of Digital Interactions and Engagement on Confidence, Self-Esteem, Social Anxiety, and Perceived Social Support**

## 📘 Overview

This project introduces and validates a 36-item scale to measure psychological dimensions of digital communication, including:

- Confidence & Self-esteem  
- Social Anxiety  
- Perceived Social Support  

Using Exploratory Factor Analysis (EFA) in **R**, the study identifies a reliable three-factor structure. The findings are validated using the Internet Self-efficacy Scale (ISS).

---

## 🔍 Abstract

With social media use increasingly prevalent, especially among young adults, there is a lack of measures exploring the impact of confidence and self-esteem, social anxiety, and perceived social support within online interactions. This study introduces a new 25-item scale, developed based on prior research, to measure Digital Engagement Communication.

An exploratory factor analysis (EFA) was conducted to examine the structure of the newly developed scale, using a sample of 87 participants aged 18 to 56. The EFA revealed a three-factor solution, demonstrating good internal consistency and reliability. The findings were validated by the Internet Self-efficacy Scale (Kim & Glassman, 2013) to underscore its relevance for understanding the factors influencing digital engagement.

The study provides valuable insights for assessing how confidence and self-esteem, social anxiety, and perceived social support shape online interactions, offering a tool for further exploration of digital communication engagement behaviours.

---

## 🛠 Built With

- **R**
  - tidyverse  
  - psych  
  - GPArotation  
  - lavaan  
  - MVN  
  - car  
  - lmtest  

- **CSV** input
- **ggplot2** for visualization
- **Exploratory Factor Analysis (EFA)**
- **Validation** using ISS (Internet Self-efficacy Scale)

---

## 📊 Key Results  

**Three Factors Identified:**  
1. **Perceived Social Support**  
2. **Social Anxiety in Digital Settings**  
3. **Online Confidence & Engagement**  

**Model Fit:**  
| Fit Index | Value | Interpretation |
|-----------|-------|----------------|
| RMSEA | .06 (90% CI [.037, .075]) | Acceptable |
| RMSR | .06 | Acceptable |
| TLI | .87 | Below ideal, potential improvement |

**Reliability (Cronbach’s α):**  
- Factor 1: **.87**  
- Factor 2: **.87**  
- Factor 3: **.84**

---

## 🧪 Method Summary  
- EFA with **minimum residual estimation** & **direct oblimin rotation**  
- KMO = .78, Bartlett’s χ²(325) = 1055.10, *p* < .001  
- 10 items removed for low KMO, cross-loading, or loadings < .30  
- Final model: **25 items across 3 factors**  
- Reliability analysis: Cronbach’s Alpha  
- Construct validity: correlations with ISS  
  - F1 (Perceived Social Support): r = .58  
  - F3 (Confidence & Engagement): r = .56  
  - F2 (Social Anxiety): r = .40  

---

📈 Factor Correlations  
|        | F1 | F2   | F3   |
|--------|----|------|------|
| **F1** | —  | -0.18 | 0.33 |
| **F2** |    | —    | 0.08 |
| **F3** |    |      | —    |
---

## 📜 Citation

If you use this scale or project in your work, please cite it as:

> Jarvis, M. (2025). *The Impact of Digital Interactions and Engagement on Confidence, Self-Esteem, Social Anxiety, and Perceived Social Support*. GitHub. https://github.com/maryjarvis/psychology_research_projects

Additionally, when referencing the Internet Self-efficacy Scale, please cite:

> Kim, Y., & Glassman, M. (2013). Beyond search and communication: Development and validation of the Internet Self-efficacy Scale (ISS). *Computers in Human Behavior*, 29(4), 1421–1429. https://doi.org/10.1016/j.chb.2013.01.018

---

## 🔒 License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).  
© Mary Jarvis, 2025

See the [LICENSE](LICENSE) file for full details.


