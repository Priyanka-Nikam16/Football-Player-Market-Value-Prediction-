# Football-Player-Market-Value-Prediction-

Overview
 - This project explores a dataset of 5,679 football players, analyzing country and club representation, age distribution, and market value. Using Exploratory Data Analysis (EDA) and Principal Component Analysis (PCA), the study identifies the key drivers of player performance and valuation.

 Project Flow
1. Data Preparation
    - Imported dataset and handled missing values.
    - Standardized numerical features for PCA.
    - Applied log transformation to market values to reduce skewness.
      
2. Exploratory Data Analysis (EDA)
    - Country Representation: Top 5 nations contribute ~29% of players, confirming dominance by a few countries.
    - Club Representation: River Plate, Liverpool, and Lanús lead, but no single club dominatrs the dataset.
    - Age Distribution: Peak at 24 years, smaller cluster at 30, sharp decline after 35.
    - Market Value: Log-transformed distribution shows near-normal shape, improving modeling reliability.
3. Principal Component Analysis (PCA)
    - Extracted principal components to reduce dimensionality.
    - PC1 (~60% variance) driven by attacking/technical skills (dribbling, finishing, ball control, vision, shot power).
    - PC2 (~20%) and PC3 (~10%) add moderate variance.
    - First 2–3 PCs explain ~90% of dataset variability.
      
4. Insights & Interpretation
    - Attacking skills are the strongest drivers of market value.
    - Age in prime career stage (mid‑20s) boosts valuation.
    - Country & club reputation amplify visibility and demand.
    - PCA confirms dimensionality reduction is possible without major information loss.
      
5. Business Implications
    - Scouting: Focus on prime‑age players with strong attacking attributes.
    - Recruitment: Target dominant nations but explore smaller markets for diversity.
    - Valuation: Use log-transformed values for fair benchmarking.
    - Modeling: Retain top PCs for efficient predictive analysis.

Technologies Used
- 	Python: pandas, scikit-learn, seaborn, matplotlib
- 	Machine Learning: PCA, regression modeling
- 	EDA Tools: visualization

 Conclusion
The dataset highlights how attacking skills, prime-age players, and representation in top countries/clubs drive market value. PCA shows that a few components capture most of the variance, enabling efficient modeling and actionable insights for scouting and transfers.
