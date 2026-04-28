# 🎵 What Makes a Song Popular?

## Predicting Hit Songs with R & Machine Learning Using Spotify Data

Can we predict whether a song will become a hit using Spotify audio features?

This project explores thousands of Spotify tracks using **R** to analyze what characteristics are commonly associated with popular songs, then builds a **machine learning model** to classify hit songs vs non-hit songs.

---

## 📖 Full Project Story

Read the full article on Medium:  
🔗 [What Makes a Song Popular?](YOUR_MEDIUM_LINK)

---

## Project Objective

This project was built to answer one core question:

> What makes a song popular?

Using Spotify track-level data, I explored whether features such as:

- Danceability  
- Energy  
- Loudness  
- Valence  
- Acousticness  
- Speechiness  
- Tempo  

have any relationship with song popularity.

Then I used **Random Forest Classification** to predict whether a track could be labeled as a **Hit Song**.

---

## Tools & Technologies

- **R**
- **Kaggle Notebook (R Environment)**
- **tidyverse**
- **ggplot2**
- **randomForest**
- **corrplot**

---

## Dataset

Spotify Tracks Dataset containing:

- Track Name  
- Artist  
- Genre  
- Popularity Score (0–100)  
- Audio Features  

Source: Kaggle Spotify Dataset

---

## 🔍 Project Workflow

## 1. Data Cleaning

- Selected relevant columns
- Checked missing values
- Removed incomplete rows

## 2. Exploratory Data Analysis

Analyzed:

- Popularity distribution
- Energy vs Popularity
- Valence vs Popularity
- Danceability vs Popularity
- Loudness vs Popularity
- Speechiness vs Popularity

## 3. Popular vs Non-Popular Comparison

Created popularity groups:

- High Popularity (70+)
- Low Popularity (<70)

Compared feature averages and distributions.

## 4. Correlation Analysis

Checked which features had strongest relationship with popularity.

## 5. Machine Learning Model

Built a **Random Forest classifier** to predict:

- Hit Song
- Not Hit

Also improved model using **class weighting** to handle imbalance.

---

## 📈 Key Findings

### Popular songs tended to be:

- More danceable  
- Slightly more energetic  
- Louder  
- Less acoustic  
- More polished for mainstream listening  

### Important Reality Check:

No single feature strongly explained popularity.

Meaning:

> Hits are usually driven by combinations of signals, not one magic formula.

### Most Important Features in Model:

- Acousticness  
- Energy  
- Loudness  
- Valence  

---

## 🤖 Model Performance

### Baseline Model

- Accuracy: **97.7%**

But class imbalance made this misleading.

### Improved Model (Weighted Classes)

- Accuracy: **96.6%**
- Better at catching real hit songs

This tradeoff is often more useful in business scenarios.

---

## 💼 Business Recommendations

For artists, labels, and agencies:

- Use data as guidance, not formula  
- Focus on replay value  
- Consider release timing  
- Build artist branding  
- Use predictive models as decision support tools  

---

## 🚀 Future Project (Part 2)

Next step:

### Music Recommendation System 🎧

Using the same dataset to recommend songs based on:

- Audio similarity  
- Mood matching  
- Genre preference  
- Listening behavior  

---

## 📁 Repository Structure

```bash
├── data/
├── notebook/
├── README.md
```
---

## 👩‍💻 Author

Created by **Jihan (2026)**
