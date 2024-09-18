# Changelog

### May 31, 2024 (2.19.9)

[Ticket Attachments](case-management/case-management/custom-fields-and-attachments.md#ticket-attachments) now available in Case Management

Test [webhook destination](actions/destinations/webhooks.md#webhook-builder) connections

Trigger actions [grouped by column](actions/actions.md#configure-your-action-settings)

### April 29, 2024 (2.19.6)

Added Microsoft Teams as [destination](actions/destinations/microsoft-teams.md)

Attach CSV of query results to [Slack alerts](actions/destinations/slack.md#attach-csv-results)

[AI SQL Copilot](ai/ai-query-helper.md) moved to sidebar

### Apr 15, 2024 (2.19.5)

Support [viewing subticket data](case-management/case-management/ticket-generation.md#view-additional-ticket-data) for grouped tickets

Added [filter by destination](queries/rules/more-rule-options.md#filter-by-destination) on Rules page

UX Filtering improvements

### Apr 1, 2024 (2.19.3)

Display [list of associated alerts](actions/actions.md#view-destination-alerts) below any destination

Added [filter by data source](queries/rules/more-rule-options.md#filter-by-data-source) on Rules page&#x20;

Enabled [Oracle](data-sources/supported-data-sources/oracle.md) as a [data source](data-sources/supported-data-sources/)

Display [list of associated rules](data-sources/data-sources/#view-data-source-rules) below any data source

### Mar 18, 2024 (2.19.1)

Column type support added to [AI Query Helper](ai/ai-query-helper.md)

Extended[ AI Query Fixer](ai/ai-query-helper.md#ai-query-fixer) descriptions for what should be fixed

Support verifying destination connections with [Test Connection](actions/actions.md#test-action-destination)

### Mar 4, 2024 (2.18.7)

Add ACTION\_LOG\_URL to built-in [templating parameters](actions/templating.md)

Show query results in [Ask AI](ai/ask-ai.md)

Form-based input for [Google Sheets data source](data-sources/supported-data-sources/google-sheets.md#reading-your-google-sheet)&#x20;

### Feb 19, 2024 (2.18.5)

Run SQL generated by AI

Expand [PagerDuty destination](actions/destinations/pagerduty.md) with Custom Details

### Feb 12, 2024 (2.18.4)

Added more [databases as destinations](actions/destinations/write-to-database.md): Snowflake, Microsoft SQL Server, BigQuery, sqlite, Redshift, Databricks, RDS mySQL

Added action failure notification

### Jan 19, 2024 (2.18.1)

Rule run and action count stored and displayed on homepage

[Template parameters](actions/templating.md) now available in [Slack messages](actions/destinations/slack.md)

### Dec 28, 2023 (2.17.6)

Increased channel limit for [Slack integrations](teams/integrations/slack.md)

Expanded data available in [LogicLoop Data Source](data-sources/supported-data-sources/logicloop-data-source.md)

### Nov 17, 2023 (2.17.0)

Support for [Advanced Scheduling](queries/rules/more-rule-options.md#advanced-scheduling) live

Upgrade default AI Query Helper to gpt3.5

Add in-app data source customer support

### Oct 13, 2023 (2.16.7)

Support [MySQL data source](data-sources/supported-data-sources/mysql.md) SSL file upload

Add [Azure MySQL](data-sources/supported-data-sources/mysql.md) as data source

### Sep 29, 2023 (2.16.6)

Add run logs table to [LogicLoop Data Source](data-sources/supported-data-sources/logicloop-data-source.md)

Add scheduling to [Action Setup](actions/actions.md)

### Sep 7, 2023 (2.16.4)

Add Query Optimizer to [AI Query Helper](ai/ai-query-helper.md)

Support Athena in [AI SQL API](beta/ai-sql-api.md)

### Aug 18, 2023 (2.16.2)

Added button to insert [template parameters](actions/templating.md) into [action subscriptions](broken-reference)

Increased [Slack integration](teams/integrations/slack.md) channel limit from 1000 channels to 10,000 channels

Added database schema retrieval API for [AI SQL generation](beta/ai-sql-api.md)

Added database schema update API for [AI SQL generation](beta/ai-sql-api.md)

### Aug 6, 2023 (2.16.1)

Added database schema creation API for [AI SQL generation](beta/ai-sql-api.md)

Support table selection from data schema for [AI SQL generation](beta/ai-sql-api.md)

### July 6, 2023 (2.15.6)

Multiple new AI models are avilable in the [AI SQL generation API](beta/ai-sql-api.md) (gpt-4, gpt-3.5-16k, Anthropic Claude)

Additional UI filtering for [Rules](queries/rules/), including author

Additional UI filtering for [Tickets](case-management/case-management/), including creating rule

Ticket row data is now available in [Case Analytics](beta/case-analytics.md)

### June 15, 2023 (2.15.3)

Google Sheets added as an Auth Integration [service](data-sources/supported-data-sources/google-sheets.md)

Add Batch Assign to [Tickets](case-management/case-management/)

Add support for Oracle SQL to the [AI SQL Suite](broken-reference)

### May 25, 2023 (2.15.0)

Additional UI filtering for [Tickets](broken-reference), including searching by rule name and assignee

Additional UI filtering for [Rules](broken-reference), including run schedule and action status

\[BETA] [AI SQL API](beta/ai-sql-api.md)

### April 27, 2023 (2.14.6)

Query Editor added to [AI Query Helper](ai/ai-query-helper.md)

Various UX Improvements (Home page, AI Query Helper, Schedule, Email)

### April 21, 2023 (2.14.4)

[Ask AI](ai/ask-ai.md) released

Query Fixer added to [AI Query Helper](ai/ai-query-helper.md)

Additional data sources supported by [AI Query Helper](ai/ai-query-helper.md)

### April 4, 2023 (2.14.0)

Query Explainer and Query Generator added to [AI Query Helper](ai/ai-query-helper.md)

### March 30, 2023 (2.13.4)

Added [Custom Fields](case-management/case-management/custom-fields-and-attachments.md) to Ticket Action [Destination](case-management/case-management/ticket-generation.md)

Support empty field state for [Custom Fields](case-management/case-management/custom-fields-and-attachments.md)

### March 21, 2023 (2.13.3)

Added common [webhook](actions/destinations/webhooks.md) destinations.

We support [toggling alert subscriptions](actions/actions.md#toggle-action-subscription).

Ticket comments are available in your [LogicLoop data source](beta/case-analytics.md).

### March 9, 2023 (2.13.0)

We now support [Custom Fields](case-management/case-management/custom-fields-and-attachments.md) for tickets. Track specific criteria across your case management.

Your own LogicLoop data can now be [a data source](beta/case-analytics.md). You can to track the success of your workflow and escalate any unresolved issues.

### Feb 20, 2023 (2.11.0)

You can now [chain rules](actions/destinations/chain-rules.md) together in actions. Create an action subscription to trigger a rule and pass your results as parameters.

### Jan 18, 2023 (2.10.0)

You can now batch archive tickets. Instructions on how to do so can be found [here](case-management/case-management/#batch-archiving-tickets).

You can now specify parameters in either UPPER\_CASE or lower\_case in action templates. Previously we required all parameters to be UPPER\_CASE.

### Sept 1, 2022 (2.9.3)

You can now associate an entity ID to [tickets](case-management/case-management/) generated by LogicLoop rules. This is helpful if a single user can generate multiple alerts and you want a way of associating all the alerts to a single user. Entity IDs are searchable so you can search up all tickets that belong to the same entity. &#x20;

<figure><img src=".gitbook/assets/Screen Shot 2022-09-08 at 12.20.06 PM.png" alt=""><figcaption></figcaption></figure>

Additionally, you can choose to "Group items with the same entity ID into a single ticket". This means that if the same user triggers multiple alerts, instead of creating a new ticket for each alert, the alerts will all be grouped into one ticket under "Additional Rules Flagged"&#x20;

<figure><img src=".gitbook/assets/Screen Shot 2022-09-08 at 12.21.33 PM (4).png" alt=""><figcaption></figcaption></figure>

### **June 30, 2022 (2.7.4)**

You can now re-alert on duplicate items after a period of time. For example, let's say you have an alert that runs every hour, but you only want it to alert your team for the same issue at most once per day. You can turn on the deduplication & include a 1 day time period so that it does not alert multiple times in one day, but will alert again the next day.

![](<.gitbook/assets/Screen Shot 2022-07-01 at 2.56.40 PM.png>)

### May 24, 2022 (2.7.0)

Users who don't know SQL can now use LogicLoop's Visual Query Builder to query for data just by choosing a few drop down filters. If your database is Postgres, MySQL, Redshift, Snowflake, or BigQuery, the option to use the Visual Query Builder will automatically show up in the top right corner of your query's page.

![](<.gitbook/assets/Screen Shot 2022-05-24 at 2.48.37 PM.png>)

### May 2, 2022 (2.6.0)

When you sign up for LogicLoop, we now pre-load your account with a sample database and a few rules to help you get started quickly.&#x20;

![](<.gitbook/assets/Screen Shot 2022-05-24 at 2.45.12 PM.png>)

### Mar 2, 2022 (2.5.0)

LogicLoop now provides autocomplete suggestions for [template parameters](actions/templating.md) when editing [action](actions/actions.md#create-an-action-subscription) or [ticket action](case-management/case-management/#ticket-actions) subscriptions. The parameter options will automatically appear below once you type the opening curly braces.

![](.gitbook/assets/template\_autocomplete\_zoomed.png)

You can now view the edit history of a query. While viewing a rule, click on the three dots menu button at the top right corner, and select 'View Edit History'.&#x20;

![](.gitbook/assets/edit\_history\_page\_shipped.png)

### Feb 7, 2022 (2.4.0)

There is now a new home screen with step by step instructions to help you get started with LogicLoop. In addition, check out our [new demo](https://www.loom.com/share/34f79a15487241a79ff743e22eade19d?t=0) and [templates here](broken-reference).&#x20;

![](.gitbook/assets/152441730-3526e4f6-cd00-4adf-a9c6-9f7208332465.png)

You can now write to DynamoDB as an [action](actions/destinations/write-to-database.md). That means you can have your rule insert or update database rows each time it runs.

![](<.gitbook/assets/Screen Shot 2022-02-07 at 1.47.16 PM.png>)

### **Jan 4, 2022 (2.3.0)**

You can now take actions on your tickets! For workflows that involve a human in the loop, you may want to first schedule a LogicLoop rule that [creates a ticket](case-management/case-management/) whenever the rule is triggered. Afterwards, a human can follow up on that ticket and manually execute an action on it e.g. Approve or Deny a user.

To create a Ticket Action, first go to the 'Queues' tab on the left navbar and click on 'Settings' to configure your Ticket Actions. You will be able to select from the same actions you've set up under Action Destinations.&#x20;

![](<.gitbook/assets/ezgif-6-316bed1476 (1).gif>)

Next, you can click on any of your tickets and click 'Take Action' to execute the action on that ticket.

![](.gitbook/assets/ezgif-6-da0d428115.gif)

### **Dec 29, 2021 (2.2.0)**

You can now write to Google Sheets as an action. First, create a Google Spreadsheets Action Destination.&#x20;

![](<.gitbook/assets/Screen Shot 2021-12-29 at 4.44.02 PM (1).png>)

Next, attach an Action Subscription to your rule that will write to a specific Google spreadsheet. All you have to do is paste in the URL of your Google sheet and specify which tab number you wish to write to. When you rule runs, it will write all the rows returned from your SQL query into the spreadsheet.&#x20;

![](<.gitbook/assets/Screen Shot 2021-12-29 at 4.48.00 PM.png>)

### **Nov 3, 2021 (2.1.0)**

You can now write a query that refers to a list of items returned from another query. In this example below, we retrieve all api\_calls whose id belongs to a list of whitelisted ids defined by another query.

![](<.gitbook/assets/Screen Shot 2021-11-12 at 9.59.14 AM.png>)

To make this happen, just insert a parameter into your query using curly brackets like `{{ param }}` and then in the parameter's settings choose 'Query Based Dropdown List', select the query you want to pull from, and choose to automatically select all values.

![](<.gitbook/assets/Screen Shot 2021-11-12 at 9.57.32 AM.png>)

### **Oct 18, 2021 (2.0.0)**

You can now choose to receive an email notification if there has been an error running a query you wrote. To enable this feature, an admin must first go to **Settings > General** and turn on email query owners when scheduled queries fail.

![](<.gitbook/assets/Screen Shot 2021-10-18 at 9.53.10 AM.png>)

![Example of what a failed query email looks like](<.gitbook/assets/Untitled (92).png>)

### **Oct 5, 2021 (1.11.0)**

You can now set up your LogicLoop queries to trigger PagerDuty alerts. Simply create a PagerDuty action destination type, enter your PagerDuty service integration key, and set up your query to trigger a PagerDuty action.

![A PagerDuty action](<.gitbook/assets/Screen Shot 2021-10-05 at 10.11.53 AM.png>)

![What the alert looks like in PagerDuty](<.gitbook/assets/Screen Shot 2021-10-05 at 10.12.28 AM.png>)

### **Sept 3, 2021 (1.10.0)**

You can now set a rate limit on your action to prevent it from triggering downstream actions too quickly. This comes in handy if your rule returns a large number of rows and your action triggers something like a Twilio or Slack API that has a rate limit.

![](<.gitbook/assets/Screen Shot 2021-09-03 at 5.57.18 PM.png>)

We've introduced a more user friendly Webhook Builder action destination type to allow you to construct a webhook request. In addition, a technical user on your team can set up a webhook endpoint once, which your non-technical user can then plug and play where ever necessary. [More info here](actions/destinations/webhooks.md).

![](<.gitbook/assets/Untitled (63).png>)

### **Aug 20, 2021 (1.9.0)**

You can now take action on up to 1000 rows per rule run. Previously, we capped the maximum number of rows you can action upon at 500.

![](<.gitbook/assets/Screen Shot 2021-09-01 at 2.03.54 PM.png>)

You can now include a CSV file of your query results in email destinations.

![](<.gitbook/assets/Screen Shot 2021-09-01 at 12.37.55 PM (1).png>)

![](<.gitbook/assets/Screen Shot 2021-09-01 at 2.09.08 PM.png>)

For API JSON based sources, you can now enter a custom Authorization header when you're configuring the source:

![](<.gitbook/assets/Screen Shot 2021-09-01 at 2.10.48 PM.png>)

### **Aug 10, 2021 (1.8.0)**

In this update, you can now dedup your queries so that actions are not taken on rows whose `id` field has been seen before. All you have to do is turn on the toggle that says **Deduplicate** under your action settings:

{% hint style="info" %}
In order to enable this feature, your SQL query must return an **`id`**field. A clever way of doing so is by naming whichever column you wish to designate as the identifier as **`id`** in your SQL query e.g.`select user_id as id from accounts`
{% endhint %}

![](<.gitbook/assets/Screen Shot 2021-09-01 at 1.48.31 PM.png>)

### **Aug 5, 2021 (1.7.0)**

In this update, you can now see a history of all actions that your rule has taken. Just go to your action and under history, you can click **View Action Logs** to see all the actions that were associated with each rule run, as well as its payload and any errors. In order to enable this feature, go to **Settings > General** and turn on **Record and show history of rule runs** under Logs.\


![](https://lh6.googleusercontent.com/vAcQew2OWn-iH4XWpSa5aaBYS33604iIih0N1Epe5ElGpr06uMh04useBPV2EMQnRoF9yr-aYHW4WerIo2FWEIBl0mclsJdJ0l0EE4EC-h1hnfMiZ2yGM4LFcr--br4QVsasXm7s=s0)

![](<.gitbook/assets/Screen Shot 2021-09-01 at 1.51.51 PM.png>)

### **July 12, 2021 (1.6.0)**

In this update, you can now see a history of every single time your rule ran. Just go to your action and in the history section you will see a log of every rule run with information on: when it ran, what its status was, how it was triggered, and what conditions it ran under.&#x20;

![](https://lh4.googleusercontent.com/\_rE75AEQ5MxFhvp6xUN7tM3EwRz\_9fHrebb4tL2PhcujqqXO-ZujMYlh2GdhGuHE-YSBIirWYXIw4s\_7cP\_Lvi2ZykRFNBKXrS59UFYVR8Ecwp0WchA5UNP4YU0WM4Bdaa10KSUv=s0)

In order to enable this feature, go to **Settings > General** and turn on **Record and show history of rule runs** under Logs.

![](https://lh3.googleusercontent.com/Zw1xWD-SkBjK4gcPatQAQehyqskpvJlPcnJE5mHFfwNfh84tYX86R9jZ8bE1o1yqLmSkEJIkw0dpTw56\_poAYHGZwhmGucCsFKSGAM0rOLybbZjAtfhW3tLhBuTr0JHNCHPK6PDx=s0)

### **June 28, 2021 (1.5.0)**

In this update, you can now write to your Postgres or MySQL database an action. That means you can insert, update, or delete database rows as a result of your rule run. \


![](https://lh6.googleusercontent.com/RzzbeZmQlYMnl88oWDGFTV2efyGATDh\_6vFBGP3EnULKQTCyoeS11TBff986988jHXoVJBaZev0XQ7ZC9XkiPFAO9y5pEVIkjbOHJoyKnCATwDE0AZPn7huVkUGKr9KXVKNLR7fi=s0)

![](https://lh5.googleusercontent.com/QMSsthS4KHqwTood0BW7Z3NrNsGwUCSkD6Uk3Wk0VnSLOsLMDwrlNRBxxMZDMIvAyAUHZvYfKFNYeSnCZ49hLibusrYoTskmWR2uuI66QsCNTI7cw3x7lfmRCA-ZqkjMWXAlYZGf=s0)

![](https://lh5.googleusercontent.com/KIaBinFA8EsPOi2UW4eHwHtWub07Zu9MKp2OsVhP5RBEv2WEW9qAZ8ZceKbTDQOZT4o0sa1d69gjc1ZfAZnJqY0w4Ni6VufKP5ee8y-bFWRuttD1ulPmqq1AIw1AOTE8ITBwyFyZ=s0)

You can also now use Firebase as an action destination. If you want the result of your rule run to send your customers push notifications, all you have to do is enter your Firebase credentials and hook it up as an action destination!&#x20;

![](https://lh3.googleusercontent.com/19v8KATsxI7TipWGucIP5XSevVRtpFqjiXA0EnXUfLwEKwKLvT-aMJluW1c28NaqhFmGZ25dnS4DOoywMz63J2iU\_XOLbv1y\_6Hx4TUHEth18YWmb73\_koKqM1gTvy\_B1tNWRX8p=s0)

![](https://lh5.googleusercontent.com/7zyVIeyQpM846IuY0NFPBtsisuAATGNNb7u5QEG6aTnjsotF7xqllDs-pfzH3CI2Appn0LTbQpFmVlVHbl8x\_EwESVpwBvsYVKHi9DoQ2TZEGh5G08NS7SIvwYGwISg3Y1hJdQL7=s0)

### **May 26, 2021 (1.3.0)**

In this update, you can now specify the To: field when you configure an email subscription. Previously, you could only hardcode the To: field once when you create the email destination, but now you can configure emails to be sent to different recipients (e.g. each of your customers) by embedding their email in the To: field.&#x20;

![](https://lh4.googleusercontent.com/LVJO3s9OCD\_AhNr72aegbYb7WMDhFXyjJzfMiSUFE54m8R48vpQwkb\_9SAi7-8ECOmx-Sx3QGoYBj392TaZntvvHGmNK1OKXBR2z0JmwOAYfAfA7xVch\_ReGmijEMHNBr1\_bgkzb=s0)

### **May 19, 2021 (1.2.0)**

In this release, we introduce LogicLoop’s case management system. You can create, assign, filter, and triage tickets under the **Queues** tab. You can also have your rule runs automatically generate tickets for triage. [You can watch a demo here](https://www.loom.com/share/be2739e974bf49a2adc67426b61e529d) and read more [detailed documentation about the full feature here](case-management/case-management/).

![](https://lh4.googleusercontent.com/WumLSMjmKeXjOXM3MhGWY1Er9o6vPqYHUyPUNR8-YxJGQ2lM4zbAjhgsjK-X\_ql8YprfrQC6FJxqLgZDbbDwWyr5dNRza29I3HIGj6tW\_jcx2sGWuRGcUzvDCsQ9hkNAfz2AY3ai=s0)

![](https://lh5.googleusercontent.com/u2KegzqKlAc-rzRMLXT6BonHn5ULqI22ilhMeFKZDEwSkh9Fa1-81pE3BDAwCCitpxG9YHELynvVV-D\_89zalzGBQ3b6phi6bpVz7cYXJHV14kIowauTSr\_ZpAZV1QduDscymZqp=s0)

### **May 7, 2021 (1.1.0)**

In this release, we’re letting you take more custom and powerful actions on the results of your LogicLoop queries. [You can watch a demo here](https://www.loom.com/share/4e5958ddaf7647999386ecb0de7e7783).

Create actions for each row returned

Instead of triggering one action for the entire result of your rule run, you may want to trigger a separate action for each row. For instance, you may want one Slack message per customer that needs attention, or you may want to call an API endpoint for each new customer returned. Now, you can trigger actions for each row in your Trigger preferences.

![](https://lh6.googleusercontent.com/uaGf-RAT\_YirUZAAniGiR-B-qkuca\_sAyAc06-fcj0cud\_I\_qsqbi3Bx\_aJaqGeNALhgrH68X5mI90SVt5Qjp5SN84Y6iXq2Tw5qgJoblFRijF-hv-0J9mOcFx7YGgeASKfZLUbo=s0)

Customize templates for each action

You may want to send different content in your Slack message and an email alert on the same query. Now, you can customize data sent to each downstream action. You can embed query specific data into your notifications by injecting special variables in curly braces.&#x20;

![](https://lh5.googleusercontent.com/VdiLNdcqCRcqb-MbkJKo72mO5awkLbR1K0jRTwtmPt\_VfipkwH2ExqgWHk0AXb6Sl5stWjR0gI-xE0127GLrHN0sA4q1HS\_ZYVwXdougUqtP2t6Zg3YjoEGA7aglBCICLMX8MXmw=s0)

Advanced webhook support

Invoke more powerful downstream APIs with advanced webhook configurations. Set authorization headers, method type, individual URLs per row returned, headers and JSON payloads.

![](https://lh3.googleusercontent.com/W5lqiHEJ3TBCKiyaKvOauPtZZ7FSZcP8b6bxbv6UuNWoMu\_ZxjyRoj13ZX7sntNojYIJkSEfLBIcsIqGGkUS53wXBI4aeCUBqfhetJhfNwg9Q-MBFXbjUi2ceclWVffSZgw8RvZZ=s0)
