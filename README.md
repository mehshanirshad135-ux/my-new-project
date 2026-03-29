# Smart Health Assistant

Final project for the Building AI course

## Summary

Smart Health Assistant is an AI-powered tool that helps users track their daily health metrics, provides personalized health tips, and predicts potential health risks using data from wearable devices.  
Building AI course project.

## Background

Many people struggle to maintain a healthy lifestyle due to lack of guidance, monitoring, or timely advice. Health issues often go unnoticed until they become serious.  
* Difficulty in tracking personal health metrics consistently  
* Lack of personalized health advice  
* Early detection of health risks is often missed

## How is it used?

Users wear health tracking devices (like smartwatches) that collect daily data like heart rate, sleep, and activity. The AI analyzes patterns and sends personalized recommendations to improve health.  
It is used daily by anyone who wants to improve lifestyle habits and prevent health risks.  

Example image (replace with your own or public domain image):
![Health Tracker](https://upload.wikimedia.org/wikipedia/commons/3/3e/Fitbit_Smartwatch.jpg)

Example code snippet:
```python
def predict_health_risk(user_data):
    # Dummy AI logic
    if user_data['sleep_hours'] < 5:
        return "High risk of fatigue"
    return "Normal risk"

user_data = {'sleep_hours': 4, 'steps': 3000}
print(predict_health_risk(user_data))
