# 🎓 Enterprise Grad Scheme Retention Study

## 🧠 Project Title
Predicting Educational Engagement: Self-Efficacy, Goal Orientation & Teacher Support  

## 📘 Overview
This project was conducted for **Enterprise Rent-A-Car** as part of their graduate scheme retention research. While the participants were **university students**, the study aimed to provide insights into factors predicting educational engagement, with potential applications for improving graduate retention and development strategies.

The study examined whether **academic self-efficacy**, **goal orientation**, and **perceived teacher support** positively predict education engagement using self-report scales and multiple regression analysis.

## 🔍 Abstract
Education engagement is a key determinant of academic success. Prior research indicates that self-efficacy, goal orientation, and perceived teacher support positively predict engagement.  

In this study, **41 university students** (27 female, 13 male, 1 non-binary) completed an online survey measuring these variables. Multiple regression analysis revealed that **academic self-efficacy** and **perceived teacher support** significantly predicted educational engagement, while goal orientation did not. Collectively, the predictors explained **52.5% of the variability** in engagement (R² = .53, adj. R² = .48). These findings suggest targeted strategies for enhancing engagement could improve outcomes relevant to graduate retention programs.

---

## 🛠 Materials
Scales were administered via an online questionnaire:

1. **Chinese School Support Scale (CSSS)**  
   - Measures perceived teacher support (6 items, 3-point Likert: 1 = false, 2 = I don’t know, 3 = true)  
   - Score range: 6–18, higher scores indicate increased support  
   - Sources: Sun et al., 2006; Trickett & Moos, 1995; Torsheim et al., 2000  

2. **Goal Orientation Scales (GOS)**  
   - Measures task, ability-approach, and ability-avoid orientation (18 items, 5-point Likert: 1 = strongly disagree to 5 = strongly agree)  
   - Score range: 18–90, higher scores indicate increased goal orientation  
   - Sources: Midgley et al., 1998; Nichols, 1989  

3. **New General Self-Efficacy Scale (NGSE)**  
   - Measures academic self-efficacy (8 items, 5-point Likert, with items 4 & 6 negatively keyed)  
   - Score range: 8–40, higher scores indicate increased self-efficacy  
   - Sources: Chen et al., 2001; Schwarzer & Jerusalem, 1995  

4. **School Engagement Scale (SES)**  
   - Measures adaptive cognition/behavior, parent, peer, and teacher support (17 items, 5-point Likert, items 7–9 negatively keyed)  
   - Score range: 17–85, higher scores indicate increased engagement  
   - Sources: Winter et al., 2022; Reininger et al., 2003; Huebner, 2001  

---

## 🧪 Procedure
- Participants were recruited via **university channels** and completed the questionnaire **online via Qualtrics** ([https://www.qualtrics.com/uk/](https://www.qualtrics.com/uk/))  
- Fully informed consent was obtained; participants could withdraw at any time  
- Questionnaire included the four scales plus demographic questions  
- Data were analysed using **multiple regression** to determine predictors of educational engagement  
- Participation was **voluntary and confidential**  

---

## 📊 Results

### Descriptive Statistics & Reliability

| Scale                   | α    | Mean | SD  |
|-------------------------|------|------|-----|
| Academic Self-Efficacy  | .87  | 3.69 | .62 |
| Goal Orientation        | .84  | 3.49 | .57 |
| Perceived Teacher Support| .69 | 2.38 | .45 |
| Education Engagement    | .74  | 3.66 | .41 |

- Standard deviations indicate relatively normal distributions across all scales  
- Cronbach’s alpha demonstrates acceptable internal consistency  

### Correlations with Education Engagement

| Scale                   | r       |
|-------------------------|---------|
| Academic Self-Efficacy  | 0.65*** |
| Goal Orientation        | -0.01   |
| Perceived Teacher Support| 0.41** |

\* **p<.01; ***p<.001  

### Multiple Regression Analysis

| Predictor                | β    | p    |
|--------------------------|------|------|
| Academic Self-Efficacy   | .60  | <.01 |
| Goal Orientation         | -.06 | .62  |
| Perceived Teacher Support | .33  | <.01 |

- Model: F(3,35) = 12.91, p < .01  
- Explained variance: R² = .53, Adjusted R² = .48  
- Academic self-efficacy and teacher support positively predicted engagement, goal orientation did not  
- Multicollinearity was not a concern (VIF: Support = 1.03, Self-Efficacy = 1.02, Goal Orientation = 1.00)  

---

## 📈 Key Insights
- Increased academic self-efficacy and teacher support relate to higher educational engagement  
- Goal orientation may be less influential in predicting engagement in this sample  
- These findings could inform **Enterprise graduate scheme retention strategies**, highlighting the importance of support and self-efficacy in early career development  

---

## 🛠 Built With
- **R** for statistical analysis  
- `tidyverse` for data cleaning and wrangling  
- Multiple regression modeling  
- Likert-scale survey instruments  

---

## 📜 Citation
If referencing this project, please cite as:  

> Jarvis, M. (2025). Predicting Educational Engagement: Self-Efficacy, Goal Orientation & Teacher Support. GitHub. https://github.com/maryjarvis/psychology_research_projects/
