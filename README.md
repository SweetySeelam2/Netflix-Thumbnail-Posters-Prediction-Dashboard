# 🎬 Netflix Thumbnail Genre Prediction Dashboard

> Deep Learning-Based CNN Classifier | Performance & Business Insights

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

## 🚀 App Demo

You can interactively test the model here:

👉 [**Live Streamlit App**](https://netflixthumbnailclassifier-dl.streamlit.app/)

Features:
- 📤 Upload your own poster image
- 📁 Use sample posters from our dataset
- ⚡ Instant prediction with genre + confidence
- 📊 Model architecture and overview

---

## 🧠 Recommendations for Future Work

- 🔄 **Multi-label Classification** (movies often belong to more than one genre)
- 🧩 **Multi-modal Learning**: Combine poster with movie metadata (title, synopsis)
- 🔍 **Model Upgrade**: Explore Vision Transformers (ViT, Swin Transformer)
- 📈 **Dataset Expansion**: Grow to 10,000+ posters using TMDB/IMDb

---

## 👩‍💼 About the Author    

**Sweety Seelam** | Business Analyst and aspiring Data Scientist                             

| Passionate about building end-to-end ML solutions for real-world problems in media and entertainment                                                                                                            
                                                                                                                                           
Email: sweetyseelam2@gmail.com                                                   

🔗 **Profile Links**                                                                                                                                                                       
[Portfolio Website](https://sweetyseelam2.github.io/SweetySeelam.github.io/)                                                         
[LinkedIn](https://www.linkedin.com/in/sweetyrao670/)                                                                   
[GitHub](https://github.com/SweetySeelam2)                                                             

---

## 📜 License

This project is licensed under the **MIT License**.

© 2025 Sweety Seelam