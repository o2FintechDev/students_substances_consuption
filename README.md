# Students' Addictive Behaviors Analysis — Inquiry & BI Dashboard

📊 **Real survey data (n=208) → Power BI analytics dashboard**

## 📋 Project Summary

A quantitative research study analyzing addictive behaviors and academic stress management strategies among **208 French university students**. The project combines survey data collection, statistical analysis, and interactive visualization to provide actionable insights on substance consumption patterns in higher education.

**Keywords:** Behavioral addictions, academic stress, university students, BI visualization, data-driven research

**Technologies:** Python/Excel (data cleaning) | Power BI (visualization, custom visuals) | Quantitative methodology (OFDT-aligned)

**Duration:** January–April 2026 (Master's level project)

---

## 🎯 Research Objectives

- ✅ **Identify** the most prevalent addictive behaviors among French university students  
- ✅ **Analyze** links between consumption patterns and academic stress, lifestyle variables  
- ✅ **Measure** frequency, intensity, and perceived addiction across multiple substances  
- ✅ **Produce** actionable recommendations for university-level prevention strategies  

---

## 📊 Key Findings

### Behavioral Landscape

- **~70%** of respondents report regular sugary snacking (2–4+ times/week)
- **~75%** consume caffeine regularly; **63%** increase intake during exam periods
- **~77%** report alcohol consumption, primarily in social contexts (not stress-related)
- **~48%** of students perceive sugar as addictive; **84.6%** recognize tobacco as addictive

### Stress Adaptation Strategies

- **64%** increase sweet food consumption during exams (primary coping mechanism)
- **73%** report increased medication use for sleep/stress during high-pressure periods
- **51%** cite stress management as a primary motivation for consumption
- **54%** prioritize pleasure-seeking; **46%** highlight social integration

### Critical Insight

Behaviors are **context-dependent**. Students deploy differentiated strategies:
- **Functional** (coffee, medication) → ramped up during exams
- **Social/recreational** (alcohol) → stable across academic periods, driven by socializing
- **Emotional regulation** (snacking) → intensified under pressure

---

## 📁 File Structure

```
├── Livrable_Enquete_-_Addictions.pdf
│   ├── Part 1: Methodology (44 pages)
│   │   ├── Research context, objectives, scope
│   │   ├── Questionnaire design & distribution
│   │   └── Data collection & cleaning protocols
│   │
│   ├── Part 2: Results
│   │   ├── Descriptive analysis (consumption frequencies, demographics)
│   │   ├── Stress–behavior correlations (correlation matrices)
│   │   ├── Cross-tabular analysis (exam periods, substance types)
│   │   └── Comparative analysis vs. national datasets (OFDT)
│   │
│   └── Part 3: Discussion & Recommendations
│       ├── Methodological limitations & validity
│       └── Prevention strategies for university settings
│
├── Réponses_questionnaire_etudiant.xlsx
│   ├── [Sheet 1] Demographics: respondent profiles (n=208)
│   ├── [Sheet 2] Raw Responses: all 45 survey questions × respondents
│   └── [Sheet 3] Data Dictionary: question codebook & response encoding
│
└── resultats_sondage.pbix  [Power BI Dashboard]
    ├── Page 1: Executive Summary & KPIs
    │   ├── Total respondents, gender split, study levels
    │   ├── Overall addiction perception rates
    │   └── Top 5 substances perceived as addictive
    │
    ├── Page 2–3: Addiction Analysis by Substance Type
    │   ├── Consumption frequency (snacking, alcohol, tobacco, cannabis, medication)
    │   ├── Trend evolution since start of studies
    │   ├── Exam-period intensity increases (comparative bars)
    │   └── Custom visuals (Advanced Card, KPI Viz, cluster charts)
    │
    ├── Page 4–5: Stress × Behavior Linkages
    │   ├── Correlation heatmap (stress ↔ 10 substance types)
    │   ├── Motivation breakdown (pleasure, stress mgmt, socialization, etc.)
    │   ├── Exam-period shifts by substance
    │   └── Segment profiles (high-stress vs. low-stress cohorts)
    │
    └── Drill-through capability: click a substance → detailed breakdowns
```

---

## 🔧 Technical Stack & Skills Demonstrated

### Data Engineering

- **Collection:** Quantitative survey via Google Forms (multi-channel distribution)
- **Cleaning:** Excel data validation, duplicate detection, missing-value handling
- **Structuring:** Pivot tables, cross-tabulation matrices, correlation analysis

### Business Intelligence

- **Visualization:** Power BI Desktop (6.1 MB file, 5 interactive pages)
- **Custom Visuals:** Advanced Card, KPI Indicators, custom tooltips
- **DAX Calculations:** stress-indexed KPIs, conditional aggregations
- **Interactivity:** slicers, drill-through, dynamic filters by demographic/substance

### Quantitative Research

- **Questionnaire Design:** 45-item survey (Likert scales, frequency matrices, open-ended questions)
- **Sampling:** 208 respondents across French universities (stratified by study level & gender)
- **Analysis Methods:** Descriptive statistics, correlation matrices, cross-tabulation, comparative analysis vs. OFDT national benchmarks

### Communication

- **Academic Reporting:** Methodology → Results → Discussion (44-page formal report)
- **Data Storytelling:** Transformed raw frequencies into actionable insights (narratives in each section)
- **Multi-format Delivery:** PDF report + Excel data + Interactive dashboard

---

## 📈 Methodology Overview

**Population:** French university students (Bachelor + Master levels, N=208)

**Survey Design:**
- **45 items** covering:
  - Demographic profile (age, gender, study level)
  - Substance consumption (frequency, quantities, perceived addiction)
  - Contextual factors (exam periods, motivations, coping strategies)
  - Academic stress (perceived levels, management techniques)

**Data Quality:**
- **Response rate:** 209 initial responses → 208 valid after data cleaning
- **Temporal frame:** 12-month retrospective (past year's consumption patterns)
- **Comparability:** Indicators aligned with OFDT (French drug observatory) standards for benchmarking

**Validation:**
- Questionnaire pre-tested with target population
- Data consistency checks (non-contradictory responses)
- Comparison with national surveys (Santé publique France, OMS datasets)

---

## 🎓 Learning Outcomes & Competencies

This project demonstrates:

✅ **End-to-end data pipeline** (collection → cleaning → analysis → visualization)  
✅ **Real-world survey design** with methodological rigor  
✅ **Advanced Power BI** beyond template dashboards (custom visuals, DAX, interactivity)  
✅ **Statistical literacy** (correlation, distributions, hypothesis testing frames)  
✅ **Stakeholder communication** (academic rigor + visual clarity + actionable insights)  
✅ **Contextual awareness** (understanding addiction as multi-factorial, stress-influenced phenomenon)  

---

## 🔗 Key Insights for Recruiters (Data/Analytics Roles)

**What This Proves:**

- 🎯 Can **collect & structure real data** from messy sources (not academic exercises)
- 📊 Can **design BI solutions** that communicate complexity without oversimplifying
- 🔍 Can **balance rigor with clarity** (methodology-driven but stakeholder-friendly)
- 💡 Can **identify patterns** that inform real prevention strategies (not just dashboards for dashboards' sake)

**Relevant Roles:**

- Analytics Engineer / Data Analyst (proof of BI maturity)
- Data Consultant (combines technical + strategic thinking)
- Business Intelligence Developer (custom visuals, DAX, data modeling)

---

## 🚀 How to Use This Repository

### 1. Read the Report

Start with `Livrable_Enquete_-_Addictions.pdf`

- **Executive Summary:** Key findings & recommendations (2–3 pages)
- **Methodology:** Research design, questionnaire, sampling (6 pages)
- **Results:** Descriptive analysis, correlations, cross-tabs (12+ pages)
- **Discussion:** Limitations, implications, prevention strategies (4 pages)

### 2. Explore the Data

Open `Réponses_questionnaire_etudiant.xlsx`

- **Sheet 1 (Demographics):** Respondent profiles — age, gender, study level distribution
- **Sheet 2 (Raw Responses):** All 45 survey questions across 208 respondents (master data)
- **Sheet 3 (Data Dictionary):** Question text, response options, encoding scheme

### 3. Interact with the Dashboard

Open `resultats_sondage.pbix` in **Power BI Desktop** (free download: https://powerbi.microsoft.com/en-us/desktop/)

- **Page 1:** Overview KPIs & demographic breakdowns
- **Pages 2–3:** Substance-by-substance consumption patterns & trends
- **Pages 4–5:** Stress correlations & behavioral segment profiles
- **Use slicers** to filter by study level, gender, or substance type
- **Drill-through** individual substances for granular analysis

### 4. Ask Questions

Key questions the dashboard answers:

- *Why do sugary snacks spike during exams but alcohol doesn't?*  
  → Functional vs. social consumption patterns differ
- *Are high-stress students more likely to use medication?*  
  → Yes; r ≈ 0.29 (modest but significant correlation)
- *How do these results compare to national OFDT data?*  
  → Largely aligned; see "Mise en perspective" section in report
- *What prevention strategies work for university settings?*  
  → Report Part 3 outlines context-specific recommendations

---

## 📋 Survey Scope & Limitations

**What's Covered:**

- Behavioral addictions (food, caffeine, nicotine, alcohol, cannabis, medication)
- Academic stress perception and coping strategies
- Demographic factors (age, gender, study level)
- Temporal patterns (baseline vs. exam periods)

**Limitations (Acknowledged in Report):**

- **Sample size:** 208 respondents (not nationally representative; primarily advanced Master students)
- **Geographic concentration:** Majority from one university basin (Montpellier region)
- **Self-reported data:** No clinical assessments; relies on respondents' honesty
- **Recall bias:** 12-month retrospective (memory effects possible)
- **Snapshot in time:** Conducted January–April 2026 (French context, Spring semester conditions)

**Generalizability:** Results reflect patterns in French higher education; care needed when extrapolating to other geographies/populations.

---

## 👥 Project Team

| Role | Name | Contribution |
|------|------|--------------|
| **Data Lead** | Aude Bernier | Data cleaning, statistical analysis, pivot tables, visualization design |
| **Questionnaire Lead** | Justine Reiter-Guerville | Survey design, question formulation, testing & refinement |
| **Project Coordination** | Clara Pierreuse | Planning, report writing, synthesis of results |

**Supervisor:** Vanessa Cucurullo, Université de Montpellier (Master SIEF)

---

## 📄 Citation & Usage

**Academic Context:**

- Master's project, Université de Montpellier (2026)
- Confidential data (CNIL-compliant; respondents anonymous)
- **Recommended for:** Educational/portfolio purposes only

**If Citing:**

```
Bernier, A., Pierreuse, C., & Reiter-Guerville, J. (2026). 
Comportements addictifs chez les étudiants: Stress académique et stratégies de gestion 
[Addictive behaviors among students: Academic stress and management strategies]. 
Master's thesis, Université de Montpellier.
```

---

## 🔍 Detailed Results Summary

### Consumption Patterns by Substance

| Substance | % Consumers | Primary Motivation | Exam-Period Increase | Key Finding |
|-----------|-------------|-------------------|----------------------|-------------|
| **Sugar** | 70% | Pleasure + Stress | +64% | Strongest functional response to pressure |
| **Caffeine** | 75% | Performance boost | +63% | Integrated into daily routine; spikes exams |
| **Alcohol** | 77% | Socialization | +3% | NOT stress-driven; contexts matter |
| **Tobacco** | 33% | Habit formation | +50% | Polarized use (many non-users, regular users) |
| **Cannabis** | 50% | Experimentation | +13% | Occasional; limited regular use cohort |
| **Medication** | 40% | Medical relief | +73% | Highest exam-period proportional increase |

### Motivation Hierarchy

Students attribute consumption to (ranked by frequency):

1. **Pleasure-seeking** (54%)
2. **Stress management** (51%)
3. **Socialization** (46%)
4. **Boredom** (25%)
5. **Curiosity** (17%)
6. **No identified reason** (11%)
7. **Work/study pressure** (0.5%)

*Note: The minimal mention of direct academic pressure suggests students rationalize consumption through intermediate mechanisms (stress → need pleasure → snacking) rather than academic demand → direct response.*

### Demographic Insights

- **Study level:** 63% from Bachelor +4 or +5 (advanced students experience more pressure)
- **Gender split:** Balanced (50% female, 48% male, 1% prefer not to specify)
- **Consumption increases at university entry:** 42% report increased sugar consumption since higher education began

---

## 💡 Strategic Recommendations (from Report)

### For University Administration

1. **Strengthen accessible stress-management alternatives:**
   - Subsidized gym memberships, mindfulness workshops, peer support groups
   - Target: Counter reliance on consumables for stress relief

2. **Environmental design:**
   - Reduce vending machine presence or shift to healthier options
   - Increase access to free water, herbal tea in study areas

3. **Academic workload audit:**
   - Exam-period intensity correlates with medication/snacking spikes
   - Stagger deadlines, provide flexible exam scheduling where feasible

### For Student Services

1. **Screening & outreach:**
   - Low-burden addiction perception check (e.g., simple 3-item screener)
   - Normalize conversations around consumption habits

2. **Targeted interventions:**
   - High-stress populations: proactive referral to counseling
   - Medication users: brief clinician check-in on appropriateness

3. **Peer education:**
   - Leverage social motivation (46% cite socialization)
   - Frame healthy alternatives as social: group fitness, club activities

### For Future Research

- Longitudinal tracking: Do patterns stabilize post-graduation?
- Intervention pilot: Test alternative stress-management strategies
- Qualitative follow-up: Why do some behaviors cluster?

---

## 📊 Technical Details: Power BI Dashboard

**File Size:** 6.1 MB (optimized with compression)

**Custom Visuals Used:**
- Advanced Card (KPI display with trend icons)
- KPI Indicators (gauge-style visualizations)
- Cluster charts (substance groupings by correlation)
- Heatmaps (stress × consumption correlations)
- Slicers (dynamic filtering by study level, gender, substance type)

**DAX Measures (Examples):**
- Stress Percentile: `PERCENTRANK.INC(…)` for relative positioning
- Exam-Period Delta: `[Consumption During Exams] − [Baseline]` as % change
- Addiction Perception Rate: `COUNT(IF([Addiction] = "Yes")) / COUNTA(…)`

**Performance Optimization:**
- Aggregated data tables reduce query load
- Drill-through limited to 2 levels (dashboard → substance detail)
- Separate tables for demographics, consumption, stress (normalized schema)

---

## 🔗 External References & Standards

**Methodology Standards:**
- OFDT (Observatoire français des drogues et des tendances addictives): Addiction definitions & measurement frameworks
- OMS (Organisation mondiale de la Santé): Alcohol use classification; stress assessment protocols
- Haute Autorité de Santé (HAS): Standardized addiction screening tools (Fagerström for tobacco, etc.)

**Comparative Data Sources:**
- Santé publique France: National consumption prevalence rates
- INSERM studies: Stress effects on eating behavior in young adults
- WHO Global Health Observatory: International benchmarking

All cited in Appendix B (Bibliographie et Webographie).

---

## 🎯 Portfolio Positioning

**For Data Engineering roles:**
- ✅ Demonstrates end-to-end pipeline (collect → clean → analyze → visualize)
- ✅ Real messy data (208 survey responses → 208 clean records after validation)
- ✅ Data quality consciousness (dropped 1 invalid response, documented cleaning decisions)

**For Analytics Engineer roles:**
- ✅ Advanced BI beyond dashboards (custom visuals, DAX, interactivity)
- ✅ Attention to user experience (logical page flow, intuitive slicers)
- ✅ Metadata management (data dictionary, clear measure names)

**For Data Consultant roles:**
- ✅ Business context understanding (academic stress ≠ clinical addiction)
- ✅ Actionable insights (prevention strategies tailored to university setting)
- ✅ Stakeholder communication (formal report + visual dashboard + README for accessibility)

---

## ❓ FAQ

**Q: Can I use this data for my own research?**

A: Data is confidential (CNIL-compliant, anonymized); use restricted to educational/portfolio review. For research purposes, contact the project authors.

**Q: Why is Power BI file proprietary (.pbix) instead of open-source?**

A: Power BI is standard in enterprise analytics. Alternative: dashboard could be recreated in Tableau, Apache Superset, or Metabase upon request.

**Q: How current are these findings?**

A: Study conducted Jan–Apr 2026. Results reflect spring semester pressures in French higher education. Seasonal & context-specific patterns may differ in other periods/regions.

**Q: Where's the Python code for analysis?**

A: Analysis performed in Excel pivot tables & Power BI DAX. Raw Python scripts not archived; focus was on output accessibility. Code can be reconstructed if needed for reproducibility.

---

## 📞 Contact & Collaboration

**For recruiters / hiring managers:**  
This portfolio piece demonstrates **bridging technical rigor with strategic insight**—ideal for Analytics Engineer, Data Consultant, or BI Developer roles. Check back for updates!

**For academic collaborators:**  
Methodology & findings available for citation in peer-reviewed research. Reach out for methodological details, questionnaire, or data-sharing agreements.

---

## 📜 License & Attribution

This project is **educational** (Master's work, Université de Montpellier, 2026).

- **Report & analysis:** Open for review & citation (non-commercial)
- **Data:** Confidential; restricted to project team & supervisors (CNIL compliance)
- **Dashboard & code:** Available for educational purposes; commercial use requires permission

**Attribution required:** Cite as per section above.

---

## ✨ Key Takeaway

**This is not just a dashboard.** It's a proof of capability across the full analytics spectrum:

📊 Can **collect real data** (not Kaggle datasets)  
🧹 Can **clean & validate** rigorously  
📈 Can **analyze & find patterns** with statistical confidence  
🎨 Can **visualize** for non-technical audiences  
📝 Can **communicate insights** that drive decisions  

**Perfect for:** Analytics Engineer, Data Consultant, Business Intelligence Developer, or Data Analyst roles in tech/consulting.

---

*Last updated: October 2026 | For questions, see report Appendix or contact project team.*
