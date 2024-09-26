# Stress Detection Application

## Overview
The Stress Detection Application is a web-based platform designed to assess an individual's stress level based on various physiological signals. This application utilizes machine learning techniques, specifically a Decision Tree Classifier, to analyze data from users and provide insights into their mental health status.


Mental health issues, particularly stress, have become increasingly prevalent in today's society. Early detection and intervention can significantly improve outcomes for individuals suffering from stress
.

The goal of this project was to create a user-friendly application that utilizes physiological data to assess stress
levels, providing users with actionable insights about their mental health. For this we have used different features like:
## Features used in the detection
1. **Galvanic Skin Response (GSR)**: Measures the electrical conductance of the skin, which varies with moisture levels. It serves as an indicator of emotional arousal and can signal stress or anxiety, both of which are closely related to stress.

2. **Respiration Rate (RR)**: Monitors the number of breaths taken per minute. Abnormal respiration rates can reflect psychological stress and contribute to the assessment of stress levels.

3. **Body Temperature (BT)**: Measures the body’s temperature. Changes in body temperature can indicate various health issues, including mental health disorders like stress.

4. **Limb Movement (LM)**: Assesses the physical activity and movement of limbs. Reduced limb movement may indicate a lack of motivation or energy, which are common symptoms of stress.

5. **Blood Oxygen Levels (BO)**: Indicates the amount of oxygen in the blood. Low levels can affect mood and cognitive function, providing valuable information about the user's emotional state.

6. **Rapid Eye Movement (REM)**: Tracks the duration of REM sleep, which is crucial for emotional processing. Disruption in REM sleep patterns can be a sign of stress.

7. **Sleeping Hours (SH)**: Measures the total hours of sleep. Insufficient sleep is linked to a higher risk of stress, making this feature essential for accurate assessment.

To achieve this, we developed a Streamlit application that collects user data through interactive sliders for each feature. The application processes the data using a Decision Tree Classifier, which was trained on a dataset containing various physiological signals. The features include GSR, RR, BT, LM, BO, REM, and SH. Users can input their data, and the model predicts their stress
level, providing feedback on whether they have low, medium, high, or very high stress
levels.

The application effectively detects stress
levels based on physiological signals, offering an accessible tool for individuals to monitor their mental health. By providing insights based on user input, it encourages users to seek help if necessary and promotes awareness of mental health issues.

