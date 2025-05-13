# Sixth Project 
## Sentiment Analysis
### First pic 
![Screanshot (495).](https://github.com/Mahmoud0019/oibsib_taskno6/blob/main/1.png)

###Description:

This image displays a dashboard focused on the sentiment analysis of user reviews for applications on the Google Play Store. It provides an overview of app ratings, categories, and the relationship between app size, price, and ratings. The dashboard includes the following elements:
Title: "Play Store: Sentiment Analysis Of Users Reviews" clearly indicates the dashboard's focus.

###cKey Metrics:

Total Apps: Displays the total number of apps in the dataset (9638).
Cnt. Category: Shows the total number of app categories (33).
Count by Rating Histogram: A bar chart showing the distribution of app ratings (from 1 to 5 stars) and the count of apps receiving each rating. The distribution is heavily skewed towards higher ratings (4 and 5 stars).
Size and Rating Scatter Plot: A scatter plot visualizing the relationship between the size of the app (on the x-axis) and its rating (on the y-axis). The density of points might indicate common app sizes and their corresponding ratings. There doesn't appear to be a strong linear correlation visible at first glance.
Count of Apps by Category Bar Chart: A bar chart displaying the number of apps in each category. "FAMILY" and "GAME" categories have significantly higher counts compared to others.
Price and Rating Scatter Plot: A scatter plot showing the relationship between the price of the app (on the x-axis) and its rating (on the y-axis). Most apps appear to be priced below 100, and there's no clear visual correlation between price and rating.

### Analysis:

The dashboard provides a high-level understanding of app ratings, categories, and their relation to size and price in the Google Play Store. Key observations include:
Positive Rating Bias: The majority of apps have high ratings (4 and 5 stars), suggesting a positive bias in user reviews or app quality.
Dominant Categories: The "FAMILY" and "GAME" categories have the highest number of apps, indicating their popularity or the breadth of offerings in these areas.
Weak Correlation between Size/Price and Rating (Visual): The scatter plots don't immediately reveal a strong linear relationship between app size or price and their ratings. However, further statistical analysis might uncover subtle correlations.
Concentration of Free/Low-Priced Apps: The "Price and Rating" scatter plot shows a high concentration of apps with lower prices.

### Insights:

Focus Areas for Developers: Understanding the dominant categories can inform developers about potential market opportunities or areas with high competition.
User Rating Tendencies: The positive rating bias might suggest that users are more likely to leave reviews for apps they like, or that the Play Store environment encourages higher-quality apps.
App Size and Performance: While no direct correlation with rating is immediately visible, developers should still consider app size for downloadability and user experience.
Pricing Strategies: The prevalence of free or low-priced apps suggests that this might be the dominant monetization strategy on the Play Store.
Further Investigation: It would be beneficial to further analyze the sentiment of the text reviews associated with these ratings to gain a deeper understanding of user opinions and identify specific aspects driving positive or negative feedback.
### Second pic 
![Screanshot (495).](https://github.com/Mahmoud0019/oibsib_taskno6/blob/main/2.png)

### Description:

This image presents a more detailed view of the Google Play Store app data, focusing on installs by category, app content rating, app type (free/paid), and the Android versions supported. The dashboard includes the following elements:
Title: "Play Store: Sentiment Analysis Of Users Reviews -- Details" indicates a more granular level of analysis.
Key Metrics (Repeated for Context):
Total Apps: 9638
Cnt. Category: 33
Installs by Category Bar Chart: Shows the total number of installs for apps within each category. "GAME" and "COMMUNICATION" categories have significantly higher total installs compared to others.
Count of App by Content Rating Pie Chart: Displays the distribution of apps based on their content rating (Everyone, Teen, Mature 17+, Everyone 10+). "Everyone" is the dominant content rating.
Average of Installs and Count of App by Type Pie Chart: Shows the distribution of installs and the count of apps between free and paid. While free apps constitute the vast majority of the app count, they also account for the vast majority of installs.
Sentiment Distribution Bar Chart: Shows the count of apps categorized by their overall sentiment derived from user reviews (Positive, Negative, Neutral). The majority of apps have a positive sentiment.
Count of App by Android Ver Bar Chart: Displays the number of apps supporting different Android versions. Older versions like "4.1 and up" and "4.0 and up" have a high number of supported apps, but newer versions are also well-represented.

### Analysis:

This detailed view provides insights into app popularity (based on installs), content rating demographics, the prevalence of free vs. paid apps, overall sentiment, and platform compatibility. Key observations include:

Install Leaders: While "FAMILY" had the highest number of apps, "GAME" and "COMMUNICATION" categories lead in terms of total installs, indicating higher user engagement or broader appeal.
Broad Audience: The dominance of the "Everyone" content rating suggests that a large portion of apps targets a general audience.
Free-to-Install Model: The data strongly indicates that the free-to-install model is the most prevalent, driving the majority of downloads, even though paid apps exist.
Positive User Sentiment: The majority of apps have a positive sentiment based on user reviews, aligning with the rating distribution in the first dashboard.
Wide Android Compatibility: A significant number of apps support older Android versions, likely to reach a wider user base. However, newer versions are also well-supported, indicating ongoing platform updates.

### Insights:

Monetization Strategies: The overwhelming dominance of free apps in terms of installs suggests that in-app purchases, advertisements, or freemium models might be more effective monetization strategies than upfront payment for many app categories.
Target Audience Considerations: The content rating distribution helps developers understand the demographics they are reaching and the guidelines they need to follow.
Platform Support Decisions: The Android version distribution informs developers about the minimum and target SDK versions to support based on the current ecosystem.
Sentiment as a Key Indicator: The predominantly positive sentiment highlights the overall quality or user satisfaction with the apps in this dataset. Analyzing the negative sentiment in more detail could reveal areas for improvement.
Category-Specific Strategies: The differences in app count versus install count across categories suggest that different strategies might be needed for success in different areas (e.g., focusing on user acquisition in highly popular but crowded categories).
