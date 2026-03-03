<p align="center">
    <img src="https://github.com/Amrita-TIFAC-Cyber-Blockchain/.github/blob/main/profile/img/AVV_CYS_Logo.png" alt ="Amrita TIFAC" width="700" />
</p>

# Standard Operating Procedures

## Cyber Readiness Index (CRI) Rubrics (CRR)

### Table of Contents

-   Version History
-   Introduction
-   Academic Performance (CGPA)
-   CTF Participation and Performance
-   Hackathon Participation and Outcomes
-   Competitive Coding (Rating-based)
-   Final Calculation
-   Recommendation Guideline
-   Example Calculation

### Version History

| Date | Version | Change History | Author |
|------|----------|----------------|--------|
| 17 – June – 2025 | V1.0 | Initial Version<br>- Overview<br>- Proposed Scoring Logic | Mr. Ramaguru Radhakrishnan |
| 21 – June – 2025 | V1.2 | Individual Score Calculation and Final Formula Added | Mr. Ramaguru Radhakrishnan |
| 28 – June – 2025 | V1.5 | - Scoring Logic to CTFs<br>- Recommendation Guidelines<br>- Example Scoring | Mr. Ramaguru Radhakrishnan |   


### Introduction

The **Cyber Readiness Rubrics (CRR)** is a structured evaluation framework developed to assess and quantify the cyber-readiness of students in terms of their academic performance and active engagement in
co-curricular technical activities.
 
It is part of the **Cyber Readiness Index (CRI)** initiative, which aims to encourage holistic development and reward students with relevant opportunities such as internships, fellowships, and research positions.

The CRR consists of four verticals:

1.  Academic Performance (CGPA)
2.  Capture the Flag (CTF) Participation and Performance
3.  Hackathon Participation and Performance
4.  Competitive Coding Practice and Rating

### 1. Academic Performance (CGPA)

**Weightage: 25%**

## Scoring Logic

| CGPA Range   | Score (out of 10) |
|--------------|-------------------|
| 9.0 – 10.0   | 10 |
| 8.5 – 8.99   | 9  |
| 8.0 – 8.49   | 8  |
| 7.5 – 7.99   | 7  |
| 7.0 – 7.49   | 6  |
| 6.5 – 6.99   | 5  |
| 6.0 – 6.49   | 4  |
| Below 6.0    | 0  |

```
CGPA_Score = Scaled value from table (0–10)
```

### 2. CTF Participation and Performance

**Weightage: 25%**

#### Scoring Logic (Per CTF)

-   Participation only → **2 points**
-   Solved at least 1 challenge → **3 points**
-   Top 50% → **5 points**
-   Top 25% → **7 points**
-   Top 10% → **9 points**
-   Podium → **10 points**

```
CTF_Score = (Σ CTF_Scores / Max_CTF_Score) × 10
```
Where:
```
Max_CTF_Score = 100 (can be adjusted based on context)
```

### 3. Hackathon Participation and Outcomes

**Weightage: 25%**

#### Scoring Logic (Per Hackathon)

-   Participation only → **2 points**
-   Intermediate Levels → **4 points**
-   Finalist or Demoed → **6 points**
-   Won Special Mention/Track → **7 points**
-   Runner-up/Winner → **10 points**

```
Hackathon_Score = (Σ Hackathon_Scores / Max_Hackathon_Score) × 10
```

Where:

```
Max_Hackathon_Score = 100 (can be adjusted based on context)
```

### 4. Competitive Coding (Rating-based)

**Weightage: 25%**

#### Platforms Considered

-   Competitive Programming Track: **Codeforces**
-   Regular Programming Track: **LeetCode**

#### Scoring Logic

Convert rating to 10-scale.

#### Normalization Example (for Codeforces)

| Rating Range   | Score (out of 10) |
|----------------|-------------------|
| 2400+          | 10 |
| 2000–2399      | 9  |
| 1800–1999      | 8  |
| 1600–1799      | 7  |
| 1400–1599      | 6  |
| 1200–1399      | 5  |
| 1000–1199      | 4  |
| 800–999        | 3  |
| <800           | 1  |

```
Competitive_Score = max(Normalized_Score_Across_Platforms)
```

### Final Calculation

    CRI = 0.25 × CGPA_Score
        + 0.25 × CTF_Score
        + 0.25 × Hackathon_Score
        + 0.25 × Competitive_Score

### Recommendation Guideline

A threshold will be decided by the committee chaired by the Director,
TIFAC-CORE in Cyber Security based on the performance by students of a
given batch.


### Example Calculation

| Student        | CGPA | CTFs | Hackathons | Comp. Coding | CRI   |
|---------------|------|------|------------|--------------|-------|
| Dinesh Kumar  | 8    | 3.2  | 2.8        | 7            | **5.3** |
| Deepa         | 10   | 0    | 0          | 0            | **2.5** |
| Arul          | 4    | 4.2  | 0          | 0            | **2.6** |
| Rosh          | 7    | 0    | 0.8        | 8            | **4**   |
