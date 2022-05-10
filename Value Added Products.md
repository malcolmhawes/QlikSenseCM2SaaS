# From Client-Managed to SaaS: **Value Added Products**

## Introduction
This guide is designed to help OEM partners with a Qlik Sense Client-managed deployments that are thinking or willing to move to SaaS.

There are a number of "Add On" capabilities with Client Managed products such as alerting, reporting and chat bots that Qlik refer to as "Value Added Products" in the Client  Managed product set. These tools and capabilities haven't been converted directly "as is" to Qlik Cloud SaaS and this will not be a "Gap Analysis" between Client Managed and SaaS but rather a guide to describe these tools in Client managed, then describe aspects of Qlik Cloud SaaS which are available currently to achieve similar capabilities. Qlik is building new features in Qlik Cloud continuously, to provide similar, and in many cases additional, capabilities in these areas.

Essentially, functionality is different from one to the other so it is important that you consult your OEM Presales specialist team to understand these differences and implications in more depth.


&nbsp;
___
## Value Added Products and Similar Qlik Cloud SaaS Capabilities

The differences between relevant Client Managed tools (CM) and Similar Qlik Cloud SaaS (SaaS) capabilities are subtle but important to describe - however this is not a Gap Analysis excercise.

The Client managed tools are delivered via stand-alone "value add" products that requires a full-stack implementation. 

The following describes the functionality in both CM and SaaS to help guide your understanding between the two.

**Client Managed tools that are relevant here include** :

Qlik NPrinting :

- Qlik NPrinting is a reporting platform that lets you create reports using your QlikView and Qlik Sense data, and then distribute them automatically in a range of standard formats.

Qlik Alerting :

- Qlik Alerting provides enterprise alerting for your Qlik Sense deployment. It offers self-service capabilities for users to create their own alerts on the data they have access to in Qlik Sense. It also provides the capability for users, often power users, to create and manage alerts for others with managed shared and broadcast alerts.

Qlik Insight Bot :

- Qlik Insight Bot offers a fast and easy way to ask questions and discover insights using natural language. It’s available right in Qlik Sense and through popular tools such as Slack, Skype, and Microsoft Teams. With each question, it instantly surfaces relevant charts and insights, including key drivers, comparisons, predictions and more. And its self-learning AI makes the system progressively smarter.

- Insight Advisor Chat is Qlik's next-generation of Qlik Insight Bot, fully conversational analytics experience native to Qlik Sense. It is driven by our cognitive engine and uses natural-language processing and generation (NLP and NLG) to understand user intent and generate both narrative and visual responses to questions. Insight Advisor Chat works across Qlik Sense apps and allows users to transition directly to in-app, search-based visual analysis for deeper exploration. It is now offered as a licensed, value-added product for Qlik Sense Enterprise on Windows, replacing Qlik Insight Bot. Insight Advisor Chat supports integrations with Microsoft Teams and Slack.

Information note - These above are on-premise tools for Qlik Sense Enterprise on Windows and/or QlikView on Windows.

In Qlik Cloud SaaS (SaaS) these capabilities are integrated experiences that are supporting various customer use cases - Qlik are not trying to directly replicate the Client Managed functionality into Qlik Cloud SaaS.



**Qlik Cloud SaaS Capabilities that are relevant here include** :

Reporting from Qlik Cloud :

- Qlik reporting tools let you summarize and share insights with other users using exported documents.

Automated reporting using the Qlik Reporting Service :

- You can create automated multi-page PDF reports based on a Qlik Sense app using the Qlik Reporting Service and Qlik Application Automation. Recipients can receive complex, scheduled reports, even if they do not have access to Qlik Sense. Get started with a report template, or create a fully custom automation.

Creating a Qlik Reporting Service report :

- The Qlik Reporting Service connector blocks let you quickly and easily build customized, multi-page reports based on app sheets. This topic shows you how to use each of the reporting blocks to build reports. By the end of this topic, you'll be able to generate single-page reports based on an app sheet, generate multi-page reports, and generate customized reports with different selections applied to different sheets.

You should be familiar with Qlik Application Automation to create a Qlik Reporting Service report.

Monitoring data with alerts :

- Detect outliers and anomalies in your data quickly with alerts, without the need to open the app. You define conditions based on measures or dimensions of the data that you want to monitor. When the conditions are met, a notification with a preview of the data is sent to you.

Scheduling reports with subscriptions :

- Subscription reports let you schedule recurring emails containing a PDF of your preferred sheets or chart. You can set your desired filters and have a PDF report with the newest data delivered to your inbox at a scheduled time. For example, you could receive overnight order information in an email every morning. You can edit subscriptions you own at any time.


Exploring apps with conversational analytics :

- Insight Advisor Chat is a chat-based interface for conversational analytics. Insight Advisor Chat lets you search for insights in any app you can access.

In Qlik Cloud SaaS be aware that Insight Advisor has many aspects that inlcuded :

Insight Advisor :

- Insight Advisor comprises the following Qlik Sense features:

Insight Advisor Search: 

- Insight Advisor Search is available from Sheet in the Analyze tab of an app. Insight Advisor Search creates visualizations based on natural language searches or selections of fields and master items. Insight Advisor Search can also generate charts of potential interest.

Insight Advisor Analysis Types: 

- Insight Advisor Analysis Types is available from Sheet in the Analyze tab of an app. Insight Advisor Analysis Types allows you to select an analysis type and the data to include. Insight Advisor then generates charts based on your parameters.

Insight Advisor Chat: 

- Insight Advisor Chat is a chat-based interface for conversational analytics. Insight Advisor Chat enables you to make natural language searches from the hub to apps to which you have access. Insight Advisor Chat then returns relevant visualizations.

Associative insights: 

- Associative insights helps you uncover blind spots and reveal relationships you may have missed. Associative insights compares the contributions of your selections and excluded values against your measures.

Chart suggestions: 

- Chart suggestions enable you to select data fields when editing a sheet and let Qlik Sense choose the dimensions, measures, and visualization types. The suggested chart adjusts itself based on your changes. You can customize a suggested visualization with a focused set of properties.

Recommended associations: 

- Insight Advisor can recommend associations between your data tables in the Associations view in Data manager. The Recommended associations panel lets you view and apply these recommendations.


&nbsp;
___
## Key Resources for Qlik Cloud SaaS Capabilities described above


Qlik Reporting

1. [Reporting from Qlik Cloud](https://help.qlik.com/en-US/cloud-services/Subsystems/Hub/Content/Sense_Hub/Reporting/SaaS-reporting-intro.htm)
2. [Self Service Reports with Subscription](https://youtu.be/GydNMmIK4cs) (3:30 min)
3. [Automated Reporting with Qlik Reporting Services](https://youtu.be/tXyuT_1S23o) (22:12 min)

Qlik Alerting

1. [Monitoring Changes with Alerts](https://help.qlik.com/en-US/cloud-services/Subsystems/Hub/Content/Sense_Hub/Alerting/monitoring-changes-with-alerts.htm)
2. [Setting up Data Alerts](https://youtu.be/AbFTcpzvsfc) (1:15 min)
3. [Monitoring Changes with Alerts](https://youtu.be/4nd_02efDCg) (2:23 min)


Qlik Insight Advisor

1. [Creating Viz with Insight Advisor](https://help.qlik.com/en-US/cloud-services/Subsystems/Hub/Content/Sense_Hub/Insights/insight-advisor-create-visualizations.htm)
2. [Insight Advisor Chat and Business Logic](https://youtu.be/PO7GwxfdfFQ) (1:34 min)
3. [Insight Advisor Chat](https://youtu.be/1ewjXxZygBE) (5:42 min)







