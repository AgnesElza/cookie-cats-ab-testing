# Mobile Game A/B Testing (Cookie Cats)

This project analyzes an **A/B test from Cookie Cats**, a popular mobile puzzle game.  
The experiment tested whether moving the level gate earlier in the game affected **player retention**.  

The goal is to demonstrate **end-to-end A/B testing skills**: from experiment design checks to outcome analysis, survival analysis, Bayesian inference, and business recommendations.

---

## Project Workflow
1. **Experiment Design**
   - Define hypotheses (Day 1 & Day 7 retention).
   - Sanity checks: SRM (Sample Ratio Mismatch), covariate balance.
   
2. **Frequentist Analysis**
   - Difference in proportions (z-test).
   - Confidence intervals for Day 1 and Day 7 retention.
   
3. **Survival Analysis**
   - Kaplan-Meier curves to compare player lifetimes.
   - Long-term engagement insights beyond single retention points.
   
4. **Power Analysis**
   - Minimum Detectable Effect (MDE).
   - Achieved power vs observed effect size.
   
5. **Bayesian Analysis**
   - Beta-binomial model for retention.
   - Posterior distributions and probability that treatment is better.
   
6. **Business Recommendations**
   - Interpret results in the context of player engagement and monetization.

---

## Dataset
Source: Cookie Cats A/B Testing dataset (mobile gaming).  

- **Group A:** Original version (gate at level 30).  
- **Group B:** Treatment version (gate at level 40).  
- **Outcome:** Player retention at Day 1 and Day 7.  

---

## Key Results
- **Day 1 Retention:** No significant difference.  
- **Day 7 Retention:** Lower in treatment group (≈ –0.8 pp).  
- **Survival Analysis:** Control group shows longer play duration.  
- **Power Analysis:** Experiment was underpowered for small effects.  
- **Bayesian Analysis:** High probability that treatment reduced retention.  

---

## Business Insights
- Moving the gate earlier **hurt long-term retention** without boosting early engagement.  
- For free-to-play games, **retention drives monetization** → recommend **keeping gate at level 30**.  
- Demonstrates importance of **power analysis** in experiment planning.  

---
## Next Steps
- Simulate **sequential testing** or bandit strategies.  
- Extend to **multi-variant testing** (multiple game mechanics).  
- Incorporate **player segmentation** (casual vs heavy users).  

---

**This project showcases statistical experiment design, advanced A/B testing methods, and the ability to translate results into actionable product recommendations.**
