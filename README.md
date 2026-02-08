# Digital-Wellbeing-Modeling-Social-Medias-Impact-on-Mental-Health
This study uses data science to analyze how social media affects student mental health. With a dataset of 500 students, we apply PCA, Lasso, Naive Bayes, and other models to identify key behavioral drivers and propose actionable insights for digital wellbeing.

## 📊 Project Overview
This project analyzes social media usage patterns among 500 university students to understand their impact on mental health. Using multiple machine learning approaches, we identify key behavioral predictors, build interpretable models, and provide data-driven recommendations for healthier digital habits.

## 🔍 Key Findings
### 1. Screen Time is the Dominant Predictor
- **Finding**: Daily screen time is the strongest behavioral predictor of mental wellbeing

- **Threshold**: ~5.6 hours/day separates high and low wellbeing groups

- **Significance**: Provides a clear, actionable limit for healthy social media use

### 2. Three-Pillar Model of Happiness
- **Finding**: Stress level, sleep quality, and screen time explain most variance in happiness

- **Accuracy**: 70% accuracy in classifying low/medium/high happiness levels using just these three features

- **Interpretation**: LDA shows 99.2% variance explained by the first discriminant function

### 3. Simple Models Can Be Effective
- **Finding**: Naive Bayes achieves competitive performance (87% ROC-AUC) for risk screening

- **Advantage**: Higher recall for detecting at-risk students compared to more complex models

- **Implication**: Simple, interpretable models are suitable for initial screening applications

### 4. Lifestyle-Wellbeing Correlation
- **Finding**: Moderate positive correlation (r ≈ 0.59) between lifestyle and wellbeing scores

- **PCA Results**: 77.9% variance explained for wellbeing composite score

- **Insight**: Healthier digital/physical habits co-occur with better wellbeing, but individual differences remain important

## 🛠️ Technical Implementation
### Data Source

- **Dataset**: Mental Health and Social Media Balance Dataset

- **Sample**: 500 university students

- **Features**: Age, gender, screen time, sleep quality, stress levels, exercise frequency, social media platforms

- **Source**: Kaggle Dataset

### Core Technologies Used
```python
pandas           # Data manipulation
numpy            # Numerical computing
scikit-learn     # Machine learning models
matplotlib       # Data visualization
seaborn          # Statistical visualization
```

### Models Applied
| Model | Purpose | Performance |
|-------|---------|-------------|
| **PCA** | Dimensionality reduction | 77.9% variance explained |
| **LASSO** | Feature selection | Identifies 3 key predictors |
| **Logistic Regression** | Binary classification | 77% accuracy |
| **Naive Bayes** | Baseline screening | 87% ROC-AUC |
| **Gradient Boosting** | Advanced classification | 88% accuracy |
| **LDA** | Multi-class separation | 70% accuracy |
| **SVM** | Non-linear classification | Enhanced LDA results |

##  Analysis Features

- **Composite Scoring**: PCA-based wellbeing and lifestyle scores

- **Multi-model Comparison**: Systematic evaluation of 7 different ML approaches

- **Feature Importance**: LASSO for identifying key predictors

- **Visualization**: ROC curves, confusion matrices, LDA projections

- **Interpretability**: Clear decision boundaries and thresholds

## 🚀 Quick Start
[**Open Notebook in GitHub**](https://github.com/PopJoy-geek/Digital-Wellbeing-Modeling-Social-Medias-Impact-on-Mental-Health/blob/main/Digital%20Wellbeing%20Modeling%20Social%20Media's%20Impact%20on%20Mental%20Health%20(Final%20Project%20Report)%20copy.ipynb)

*GitHub will render the complete Jupyter notebook with all analyses and visualizations*

## 💡 Practical Implications
- **For Students**:
  
Limit daily social media use to under 5-6 hours

Prioritize sleep quality and stress management

Combine digital breaks with regular exercise

- **For Institutions**:

Implement screen time awareness programs

Use simple screening models for early intervention

Focus on sleep hygiene education

- **For Researchers**:

LASSO + LDA provides good balance of prediction and interpretation

Behavioral thresholds offer actionable intervention points

Multi-model comparison reveals trade-offs between complexity and performance

---
**Conclusion**: This project demonstrates that social media's impact on mental health is measurable, predictable, and modifiable. By identifying specific behavioral patterns and thresholds, we provide evidence-based guidance for promoting digital wellbeing among university students.



