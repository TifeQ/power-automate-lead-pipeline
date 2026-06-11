# BlazeSolutions Lead Pipeline
# Automated lead scoring and routing system built entirely on Microsoft 365.
What It Does
Captures leads from Microsoft Forms, scores them automatically across three criteria, routes them to the correct team via Microsoft Teams, stores qualified leads in a SharePoint CRM list, and logs every execution to an Excel audit trail.

# Tech Stack

Microsoft Power Automate
Microsoft Forms
Microsoft Teams
SharePoint Online
Excel Online (OneDrive)

Scoring Logic
# Criteria                      Points
Budget >= $2,000                40 pts
Budget < $2,000                 20 pts
Country = Nigeria               30 pts
Other country                   10 pts
Service = Automation            30 pts
Other service                   10 pts

# Routing

Score 70 and above = Hot Lead
Score 31 to 69 = Cold Lead
Score 30 and below = Invalid

# How to Import

Download the solution ZIP from this repo
Go to make.powerautomate.com
Click Solutions on the left sidebar
Click Import solution
Upload the ZIP and follow the prompts
Reconnect your Microsoft Forms, Teams, SharePoint, and Excel connections after import
