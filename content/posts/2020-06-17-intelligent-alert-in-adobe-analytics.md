---
template: post
title: Intelligent Alert in Adobe Analytics
slug: intelligent-alert-adobe-analytics
draft: false
date: 2020-06-17T12:08:10.087Z
description: The new Intelligent Alerts system in Adobe Analytics allows for
  more granular control over alerts and integrates anomaly detection with the
  alert system. The new Alert Builder and Alert Manager replace the existing
  alert functionality in Adobe Analytics. Read more.
category: adobe analytics
tags:
  - adobe analytics
  - development
---
More often than not, business puts forward a question to you as an Analyst. What is the ROI on our analytics investment? How can you tell me what is going up and what has gone down? Do I need to open for e.g. a pages report every week to analyze any anomalies?

Presenting Intelligent Alerts from Adobe Analytics. Intelligent alerts helps you create alerts that get triggered when a condition gets satisfied. As per the official documentation, Intelligent Alerts let you

* Build alerts based on anomalies (90%, 95%, 99%, 99.75%, and 99.9% thresholds; % change; above/below).
* Preview how often an alert will trigger.
* Send alerts by e-mail or SMS with links to auto-generated Analysis Workspace projects.
* Create "stacked" alerts that capture multiple metrics in a single alert.

Intelligent alert is a part of the Adobe AI fueled system designed to help an Analyst analyze the customer more deeply and perform his job better. 

To set an Alert, there are three different options available within the Adobe Analytics UI:

1. Setting Alert from the Components tab in Adobe Analytics

![Alert in Adobe Analytics via Components Tab](/media/screen-shot-2020-07-08-at-5.15.14-pm.png)

2. Using the Right Click context menu in Analysis Workspace

![Alert in Adobe Analytics via Right Click context menu](/media/screen-shot-2020-07-08-at-5.16.06-pm.png)

3. Alert via Report Suite > More

![Alert via Report Suite > More ](/media/screen-shot-2020-07-08-at-5.18.21-pm.png)

I prefer the Workspace tool to set my alerts as I need not worry about dragging dimensions and metrics within the UI. The data points are pre-filled within the UI and all I need to do is adjust the threshold limit, fill in the details and voila my alerts are ready to be triggered. Here are the steps involved after selecting the Workspace option:

Step 1: Fill in the Title, Description, Granularity of Alerts, Recipient (Email or SMS) and the Expiry 

![Step 1 : Fill the necessary details](/media/screen-shot-2020-07-08-at-5.33.59-pm.png)

Step 2:  

Adjust the alert trigger using a combination of the actual trigger

![Step 2 : Set the alert](/media/screen-shot-2020-07-08-at-5.35.11-pm.png)

And the threshold limit

![Step 2 : Set the threshold](/media/screen-shot-2020-07-08-at-5.36.39-pm.png)

Step 3: Get a preview of the number of times the alert would have triggered in the last 30 days based on the current settings of the trigger and the threshold

![](/media/screen-shot-2020-07-08-at-5.38.49-pm.png)

Once you are satisfied with the Intelligent Alert set up, please save the Alert. And you are done.

Alerts are a great way to showcase a quick view into the power of Adobe Analytics. Alerts help business  / marketing get continuous feedback on their activities and not be caught unaware. I believe it is a great tool to sustain the interest of the company in the power of Adobe Analytics as no one can resist opening up an email or view an alert that talks about their favorite metrics either spiking up or coming down.

Go ahead and set up your alerts. For a video tutorial, please click this link: 

<https://www.youtube.com/watch?v=UVH9xr_2REA>