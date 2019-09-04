---
title: Setting up Google Analytics search tracking
description: "Measure your store's main searched terms and learn more about user behavior by setting up the Google Analytics search tracking."
date: "30/08/2019"
tags: ["google-analytics", "search", "track", "tracking"]
version: "0.x"
git: "https://github.com/vtex-apps/io-documentation/blob/master/docs/en/Recipes/store/SettingUpGoogleAnalyticsSearchTracking.md"
---

# Setting up Google Analytics search tracking

The charts and graphs generated by Google Analytics’ search tracking help retailers analyze user queries, measuring the store’s main searched terms.

To add this tracking tool, you’ll need to ensure that your Analytics is properly configured to translate search URLs into relevant data on user behavior. 

Follow the steps below and configure your store’s tracking:

**1.** Accessing Google Analytics in the desired account, click on **Admin** (gear button) in the lower left corner of your screen. 

**2.** Access **View Settings**.

**3.** Enable **Site search Tracking** and fill out the **Query parameter** field with `_q,rest`.

**4.** Enable **Site search categories** and fill out the **Category parameter** field with `_c`.

<img width="392" alt="parameter-fields-analytics" src="https://user-images.githubusercontent.com/52087100/63990605-ff738780-caba-11e9-8f99-ca7ba6751d59.png">

**5.** Click on **Save**.