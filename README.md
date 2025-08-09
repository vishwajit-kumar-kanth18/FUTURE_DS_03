# 🎯 Task 3 – College Event Feedback Analysis

## 📌 Project Overview
This project is part of the **Future Intern** internship program.  
**Objective:** Analyze student event feedback to uncover satisfaction trends and suggest improvements using survey data.

**Key Skills Practiced:**
- Data Cleaning
- Sentiment Analysis (NLP)
- Data Visualization
- Survey Insights Extraction

## 📂 Dataset
The dataset (`event_feedback.csv`) contains feedback from students for different college events.

**Columns:**
- `Event Name` – Name of the event (e.g., Tech Fest, Cultural Night, Sports Day)
- `Rating` – Rating given by the participant (1–5 scale)
- `Likes` – Positive feedback text
- `Dislikes` – Negative feedback text
- `Suggestions` – Suggestions for improvement

## 🛠 Tools & Libraries
- **Python**
- **Google Colab**
- **Pandas** – Data cleaning and manipulation
- **TextBlob** – Sentiment analysis
- **Seaborn** & **Matplotlib** – Data visualization

## 📜 Steps Performed
1. **Data Loading**
   - Imported CSV data into Google Colab.
2. **Data Cleaning**
   - Filled missing text fields with empty strings.
3. **Insights Extraction**
   - Calculated average rating for each event.
4. **Sentiment Analysis**
   - Used `TextBlob` to calculate polarity for Likes, Dislikes, and Suggestions.
5. **Visualization**
   - Bar chart of average ratings by event.
   - Sentiment distribution chart for Likes.


## 📊 Example Visuals
**Average Rating by Event**
