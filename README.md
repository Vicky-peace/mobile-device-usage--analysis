# Analyzing Mobile Usage Patterns and User Behavior Classification Across Devices

## 1. Dataset Overview
The **Mobile Device Usage and User Behavior Dataset** provides insights into mobile device usage patterns and user behavior classification. It contains **700 samples** with key metrics such as:
- App usage time
- Screen-on time
- Battery drain
- Data usage
- Device model
- Operating System (OS)
- Number of apps
- User age, gender, and behavior class

## 2. Approach
### Data Loading and Preparation
- Loaded and inspected the dataset to assess its structure and quality for analysis.

### Data Exploration and Visualization
- Analyzed feature distributions, such as operating system, gender, and age brackets, to understand demographic usage patterns.

### Feature Analysis
- Assessed trends in app usage time, screen-on time, and battery drain through visualizations to uncover behavior patterns.

### Modeling
- Developed a predictive model to estimate screen-on time based on app usage time, aiming to provide insights into user engagement.

## 3. Key Findings
### Device and OS Preference
- **Android** devices are more widely used than iOS devices.
- Android models include Google Pixel 5, OnePlus 9, Samsung Galaxy S21, and Xiaomi Mi 11.
- **iPhone 12** represents iOS usage in this dataset.

### Battery Consumption
- The iPhone 12 shows higher average battery drain compared to Android models, suggesting Android devices may offer longer battery life.

### Usage Patterns by Time
- App usage and screen-on time peak in the early hours and gradually decrease throughout the day, with app usage time consistently less than screen-on time.

### Demographics
- Most users fall within the middle-age range (26-55).
- Gender distribution is nearly balanced, with a slight predominance of male users.

### Model Findings
- **Linear Regression Model** performed well but had a slightly higher Mean Squared Error (MSE) of 1.015, indicating some limitations in capturing complex patterns.
- **Random Forest Regression** provided stronger performance with a higher R-squared (0.916) and a lower MSE (0.756), making it more effective for predicting screen-on time based on app usage.

## 4. Product Improvements and Business Insights
### Battery Optimization for iOS Devices
- High battery consumption on iOS devices (e.g., iPhone 12) suggests an opportunity for app functionality optimization to save power, potentially enhancing user satisfaction.

### Usage-Based Notifications
- Usage peaks during early hours indicate an optimal period for sending notifications and promotions to boost engagement.

### Personalized Features by Device Type
- With more Android users, focusing on Android-specific features or optimizations can better serve this larger user segment.

### Data Usage Control Features
- Offering tools to track and manage app data usage could appeal to users concerned about their data consumption.

### Targeted Marketing for Age Demographics
- With a high number of users aged 26-55, marketing efforts tailored to this group could improve engagement, especially with messaging focused on connectivity and productivity.

### Android-Centric Strategy
- Android's popularity suggests prioritizing Android compatibility, feature updates, and marketing could maximize reach and engagement.

### Balanced Gender Engagement
- The nearly equal male-female representation shows minimal gender-based bias, enabling generalized feature updates and marketing without the need for gender-based customization.

---

This project provides a comprehensive analysis of mobile usage patterns, uncovering valuable insights that can drive product improvements and targeted business strategies.

