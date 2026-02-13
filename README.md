# Contact Center CSAT Analysis Dashboard
## 📝 Project Overview
This project provides a comprehensive analysis of contact center operations for the month of October 2020. The goal was to identify key drivers of Customer Satisfaction (CSAT) and evaluate operational efficiency across different communication channels and response times using data-driven visualizations
## 🛠️ Tools Used
- **Excel**: Data cleaning, initial exploration, and SLA categorization

- **Power BI**: Data modeling, DAX measures, and interactive dashboarding

- **GitHub**: Project documentation and version control
## 📊 Dataset
- Source Data: [Link to your dataset here]

- Description: The dataset contains detailed logs of customer interactions including:

  - Customer Info: Name, City, and State

  - Call Details: Call ID, Duration, Date, Reason, and Call Center City

  - Performance Metrics: Sentiment (Very Negative to Very Positive), CSAT Score (1-10), Communication Channel (Call Center, Web, Email, Chat), and Response Time (Within, Below, or Above SLA)
## ⚙️ Steps Followed
- Data Cleaning (Excel): Handled missing values, formatted date columns, and ensured consistency in sentiment labeling

- Data Loading: Imported the cleaned file into Power BI

- Data Transformation: Created calculated measures for average CSAT, average duration, and SLA compliance percentages

- Visual Development: Built a multi-visual dashboard featuring line charts for trends, scatter plots for correlations, and AI-driven "Key Influencers"

- Analysis: Extracted insights by filtering through different call reasons and response time categories
## 💡 Key Insights
The October 2020 data reveals critical areas where the contact center's performance has plateaued, offering clear opportunities for strategic improvement:

- **Speed is Not the Solution**: CSAT remains stuck at a "moderate" level (approx. 5.5/10) regardless of whether agents meet or miss SLAs. This suggests that **faster response times alone will not improve customer happiness**; the issue likely lies in the quality or depth of the resolution

- **Stagnant Service Quality**: There is no significant variation in CSAT across different call reasons. While the service is consistent, it is **consistently average**, indicating that no single department is excelling. This points to a need for a specialized training overhaul rather than the current "one-size-fits-all" approach

- **The "Duration Fatigue" Effect**: A clear inverse relationship exists between call length and satisfaction. Customers clearly **associate longer calls with frustration** (dropping from 5.55 to 5.38 as time increases), suggesting that agents may be struggling with complex issues or inefficient internal processes

- **Soft Skills as the Growth Lever**: AI analysis confirms that **Sentiment—not speed or reason—is the only factor that significantly moves the needle**. A "Very Positive" interaction yields a **+4.37** CSAT boost, proving that the current "Average" scores are likely due to a lack of emotional engagement and empathy during calls

- **The "Neutral" Trap**: Neutral sentiment only provides a marginal **+1.26** lift to CSAT. This highlights a missed opportunity where agents are technically "resolving" the issue but failing to create a positive brand experience, leaving the customer feeling indifferent
