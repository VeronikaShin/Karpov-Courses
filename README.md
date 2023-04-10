# Karpov-Courses

## Automation of basic reporting with Airflow. 
 Sending an analytical summary to telegram. A script was written to build the report (DAU, views, likes, CTR) for the last  7 days.

## Alert system
The system periodically checks key metrics every 15 minutes, such as active users in the feed / messenger, views, likes, CTR, the number of messages sent.

A statistical method was chosen for detecting anomalies (interquartile range).

If an abnormal value is detected, an alert should be sent to the chat - a message with the following information: metric, its value, deviation value, additional information.
