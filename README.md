
# 🎬 Netflix Thumbnail Genre Prediction Dashboard

Deep Learning-Based CNN Classifier | Performance & Business Insights

---

## 📌 Project Overview
- This project explores how well a CNN-based deep learning model can classify Netflix poster thumbnails into genres like Action, Comedy, Drama, Romance, and Thriller.

- A dataset of 1,201 poster images was used, and predictions were visualized via a fully interactive Tableau dashboard.

- The project evaluates not just prediction accuracy but also genre-specific confusion, dominant patterns, and business value risks or opportunities.

- The goal is to help streaming platforms automate and optimize poster tagging workflows for better viewer targeting, reduced cost, and higher content discoverability.

---

## ❗ Business Challenge
- Global streaming platforms like Netflix, Amazon Prime, and Disney+ often rely on manual tagging or rule-based systems to categorize content posters into genres.

- Misclassified or inconsistently tagged posters can mislead viewers, reduce click-through rates, and negatively affect content recommendations.

- There's a pressing need for automated, accurate, and explainable genre classification models that can scale across thousands of titles without manual intervention.

- Business stakeholders need clear, actionable insights into model behavior — not just raw predictions.

---

## 📂 Dataset Information

- A balanced dataset of 1,201 posters across 5 genres was created and used to train and evaluate the model.
- **TMDB Dataset Source**: [The Movie Database API](https://developer.themoviedb.org/reference/discover-movie)

---

## 📊 Results & Insights

- 📦 Total Posters Evaluated: 1,201

- 🎯 Overall Model Accuracy: 20.23% (243 posters correctly classified)

- ❌ Misclassification Rate: 79.77% (958 posters misclassified)

- 🔎 Accuracy by Genre:
    
    - ✅ Drama: 92.0% — the only genre with high classification accuracy

    - ⚠️ Thriller: 8.2%

    - ⚠️ Action: 2.7%

    - ❌ Romance: 0.5%

    - ❌ Comedy: 0.0% — model failed to classify any poster as Comedy

- 🔁 Top Confused Genres: Most posters from other genres were wrongly classified as Drama.

- 📌 Dominant Top-3 Prediction Pattern:
      
  - “Drama > Thriller > Romance” appeared 1,094 times, accounting for 91.1% of all predictions, showing a severe bias toward Drama.                                                        

---

## 💼 Business Impact

- Let’s assume Netflix uses this model to tag 100,000 poster thumbnails annually.

- 📌 Manual tagging cost/poster = $1.25

- 💸 Annual manual tagging cost = 100,000 × $1.25 = $125,000

**📉 Without the model:**
  
  - All posters would need manual labeling.

  - This leads to high operational costs and manual workload.

**📉 With the current model (Accuracy = 20.23%):**
  
  - Only 20,230 posters would be correctly classified.

  - ~79,770 posters (≈ 80%) would still require manual correction.

  - 💰 Estimated savings = 20,230 × $1.25 = $25,287

  - ❗ Uncovered cost (manual correction) = $99,713

**⚠️ Revenue Loss Due to Misclassification:**
  
  - Misleading thumbnails reduce CTR (Click-Through Rate) by 4–8%.

  - If a title earns $1,000,000/year, a 4% drop = $40,000 loss/title

  - Scaled to 1,000 titles/year, that’s $40M/year in opportunity loss

***🔥 Final Insight:***
  
  - Deploying the model as-is yields $25K in tagging savings but risks up to $40M in annual revenue loss.

  - Without improvement, this model would be counterproductive financially and should not be adopted in its current state.

---

## 🧠 Business Recommendations

If enhanced and adopted by streaming companies like:

  - Netflix

  - Amazon Prime Video

  - Disney+

  - HBO Max

  - Hulu

... the following strategies are essential:

**✅ Actionable Fixes**

- Retrain the model with:

    - More balanced and diverse samples — especially for Comedy, Romance, Action

    - Use more advanced deep learning architectures like EfficientNetV2 or Vision Transformers

- Augment inputs with metadata such as title, synopsis, release tags, etc.

- Use SHAP or LIME explainability to detect genre boundary confusion and biases

- Incorporate the model as a QA tool, not yet as a fully autonomous classifier

- Use Tableau insights to retrain only the most misclassified genre clusters iteratively

**📈 Business Potential**

Once model accuracy improves to 80%+, the platform can:

  - Save $100,000+ annually in manual tagging costs

  - Improve CTR and content match, leading to millions in additional revenue uplift

  - Reduce misclassification impact and increase viewer satisfaction and retention

---

## 📁 Project Dashboard Links

- [Github Dashboard Repo](https://github.com/sweetyseelam/Netflix-Thumbnail-Posters-Prediction-Dashboard)

- [Github Dashboard PDF Report](https://github.com/SweetySeelam2/Netflix-Thumbnail-Posters-Prediction-Dashboard/blob/main/Netflix%20Thumbnail%20Poster%20Genre%20Prediction.pdf)

- [Live Streamlit App](https://netflixthumbnailclassifier-dl.streamlit.app/)

---

## 👩‍💼 About the Author    

**Sweety Seelam** | Business Analyst | Aspiring Data Scientist                             

> Passionate about building end-to-end ML solutions for real-world problems in media and entertainment                                                                                                            
                                                                                                                                           
Email: sweetyseelam2@gmail.com                                                   

🔗 **Profile Links**                                                                                                                                                                                          
- [My Portfolio](https://sweetyseelam2.github.io/SweetySeelam.github.io/)

- [LinkedIn](https://www.linkedin.com/in/sweetyrao670/)       

- [GitHub](https://github.com/SweetySeelam2)     

- [Medium](https://medium.com/@sweetyseelam)                                                        

---

## 🔐 Copyrights & Licensing

© 2025 Sweety Seelam. All rights reserved.

This project, including its source code, trained models, datasets (where applicable), visuals, and dashboard assets, is protected under copyright and made available for educational, research, and demonstrative purposes only.

Unauthorized commercial use, redistribution, or duplication of any part of this project is strictly prohibited without explicit written permission.