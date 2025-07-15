### **TRAJECTORY OF BLOOD PRESSURE WITH AGE**
### **Introduction**

This project investigates the relationship between age and systolic blood pressure (SBP) using nationally representative data from the National Health and Nutrition Examination Survey (NHANES). The primary objective was to determine how SBP changes across the adult lifespan and whether these age-related changes differ based on sociodemographic and health-related factors such as sex, race/ethnicity, income level, insurance status, and use of antihypertensive medication.

---

### **Study Population and Variable Definitions**

The analysis was restricted to adults aged 18 years and older. Income was categorized using the Income Poverty Ratio (IPR) into:

* Low income: IPR < 1
* Middle income: 1 ≤ IPR < 4
* High income: IPR ≥ 4

---

### **Blood Pressure Distributions**

Blood pressure distributions were examined descriptively:

* **Systolic BP (SBP)** showed a right-skewed distribution, peaking between 120 and 130 mmHg, with a long tail beyond 200 mmHg—suggesting a mix of normotensive and hypertensive individuals.
* **Diastolic BP (DBP)** had a more symmetric, bell-shaped distribution centered around 70–80 mmHg.

---

### **Age and SBP: Overall Trends**

Exploratory data analysis revealed a positive relationship between age and SBP, with older adults generally exhibiting higher SBP. Individuals on antihypertensive medication had higher average SBP than those not on medication, likely reflecting more severe baseline conditions. However, the age-by-medication interaction was not statistically significant, indicating similar age-related SBP increases across both groups.

---

### **Sex Differences in Age-Related SBP Increase**

The analysis found a sex-based difference in the rate of SBP increase:

* Males: \~0.38 mmHg/year
* Females: \~0.68 mmHg/year
  This difference was statistically significant (p < 0.001), showing a steeper rise among women.

---

### **Insurance Status and SBP Trajectories**

Although the overall difference in SBP between insured and uninsured adults was not statistically significant (p = 0.064), the rate of SBP increase with age was steeper in the uninsured group:

* Insured: 0.52 mmHg/year
* Uninsured: 0.64 mmHg/year
  This may reflect disparities in access to long-term care and hypertension management.

---

### **Income-Level Disparities in SBP Trends**

Income was also associated with SBP patterns:

* Middle-income individuals had significantly higher average SBP than low-income individuals (β = 3.9 mmHg, p = 0.037).
* The rate of SBP increase with age was slower in the middle- and high-income groups, suggesting a possible crossover effect at older ages where low-income individuals eventually surpass in SBP.

---

### **Racial and Ethnic Variations**

Differences in age-related SBP trends by race/ethnicity were limited:

* Only individuals categorized as “Other Race – Including Multi-Racial” had significantly higher average SBP and a flatter slope compared to Mexican Americans.
* No other significant differences were observed after adjustment.

---

### **Modeling Non-Linear Relationships with GAM**

To explore potential non-linear relationships, a Generalized Additive Model (GAM) was fitted:

* The model found a highly significant non-linear effect of age on SBP (p < 0.001).
* GAM outperformed the linear model, capturing varying rates of SBP increase across the lifespan and underscoring the importance of flexible modeling techniques in aging research.

---

### **Conclusion**

This analysis of NHANES data confirms that systolic blood pressure increases with age and that this increase is influenced by sex, income level, and insurance status. These findings highlight the need for targeted public health interventions and policies that consider both age and social determinants in the prevention and management of hypertension.

