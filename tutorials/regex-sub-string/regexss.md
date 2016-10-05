---
title: regex sub string check for me пп teeeeeets
description: test page for several rules 
tags: [ products>sap-hana-cloud-platform, topic>cloud, topic>java, tutorial>intermediate]
---

## Prerequisites  
 - [End-to-End Weather App Scenario Part 8](http://go.sap.com/developer/tutorials/hcp-java-weatherapp-part8.html)

## Next Steps
 - [End-to-End Weather App Scenario Part 10](http://go.sap.com/developer/tutorials/hcp-java-weatherapp-part10.html)

## Details
### You will learn  
In this tutorial you will implement a simple responsive, mobile-compatible user interface using OpenUI5.

### Time to Complete
**15 min**

---
[ACCORDION-BEGIN [STEP 1](Create a folder)]
1. Create a `weather_app` folder underneath the `webapp` folder.

![image] (font ie.jpg)

[VALIDATE_10]
[VALIDATE_11]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 2](Create a view folder)]
2. In that `weather_app` folder create another sub-folder called `view`.

[VALIDATE_1]
[ACCORDION-END]
[ACCORDION-BEGIN [STEP 3](Create JavaScript and XML files)]
3. Next create the following JavaScript and XML files:

    - `/weather_app/view/App.view.xml`
    - `/weather_app/view/Details.controller.js`
    - `/weather_app/view/Details.view.xml`
    - `/weather_app/view/List.controller.js`
    - `/weather_app/view/List.view.xml`
    - `/weather_app/Component.js`
    - `/weather_app/util/formatter.js`
 
>Note that `Component.js` is in the `weather_app` directory, not the `weather_app/view` directory, and you must create the `util` directory for the `formatter.js` file.
 
![Project explorer for UI5 view](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-java-weatherapp-part9/e2e_09-3.png)
 
[VALIDATE_2]

test content

[VALIDATE_5]
[VALIDATE_9]
[ACCORDION-END]
[ACCORDION-BEGIN [STEP 4](Copy and paste the content from GitHub)]
4. Copy and paste the content from GitHub into the respective files and familiarize yourself with the content of the individual files.

    - `/weather_app/view/`[`App.view.xml`](https://raw.githubusercontent.com/SAP/cloud-weatherapp/4c6c4ca78a680042fda82ab1d413e520608b581c/src/main/webapp/weather_app/view/App.view.xml)
    - `/weather_app/view/`[`Details.controller.js`](https://raw.githubusercontent.com/SAP/cloud-weatherapp/4c6c4ca78a680042fda82ab1d413e520608b581c/src/main/webapp/weather_app/view/Details.controller.js)
    - `/weather_app/view/`[`Details.view.xml`](https://raw.githubusercontent.com/SAP/cloud-weatherapp/4c6c4ca78a680042fda82ab1d413e520608b581c/src/main/webapp/weather_app/view/Details.view.xml)
    - `/weather_app/view/`[`List.controller.js`](https://raw.githubusercontent.com/SAP/cloud-weatherapp/4c6c4ca78a680042fda82ab1d413e520608b581c/src/main/webapp/weather_app/view/List.controller.js)
    - `/weather_app/view/`[`List.view.xml`](https://raw.githubusercontent.com/SAP/cloud-weatherapp/4c6c4ca78a680042fda82ab1d413e520608b581c/src/main/webapp/weather_app/view/List.view.xml)
    - `/weather_app/`[`Component.js`](https://raw.githubusercontent.com/SAP/cloud-weatherapp/4c6c4ca78a680042fda82ab1d413e520608b581c/src/main/webapp/weather_app/Component.js)
    - `/weather_app`[`/util/formatter.js`](https://raw.githubusercontent.com/SAP/cloud-weatherapp/master/src/main/webapp/weather_app/util/formatter.js)

[DONE]
[ACCORDION-END]
[ACCORDION-BEGIN [STEP 5](Replace the content of the `index.html` file)]
5. Replace the content of the `index.html` file to match this [version in Github](https://raw.githubusercontent.com/SAP/cloud-weatherapp/4c6c4ca78a680042fda82ab1d413e520608b581c/src/main/webapp/index.html).

[VALIDATE_6]

[VALIDATE_7]

[VALIDATE_8]
[ACCORDION-END]
[ACCORDION-BEGIN [STEP 5/2](test button)]
test content here

[DONE]
[ACCORDION-END]
[ACCORDION-BEGIN [STEP 6](Publish/deploy your updated app)]
6. Publish/deploy your updated app and navigate your browser to the root URL: <http://localhost:8080/weatherapp>. After successful authentication you should see a fully operational UI.

    ![App example showing weather info for a specific city](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-java-weatherapp-part9/e2e_09-6.png)

    >Note: Feel free beautify the UI by applying formatters and respective icons etc.

[VALIDATE_3]
test content is here

[VALIDATE_4]
[ACCORDION-END]

## Next Steps
 - [End-to-End Weather App Scenario Part 10](http://go.sap.com/developer/tutorials/hcp-java-weatherapp-part10.html)
