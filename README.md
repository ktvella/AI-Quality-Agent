# AI Quality Agent
An automated daily pipeline built with n8n that takes real manufacturing recall data from the FDA, runs exploratory data analysis, generates an AI-powered interpretation of the results, and delivers a formatted report to your inbox every morning. Also includes an Excel attachment of the data, named by week number and day. <br>
<br>
Built as a portfolio project to demonstrate end-to-end data analyst workflow automation skills in a manufacturing context. 
<br>
## What it does
1. Fetches the 100 most recent medical device recall records from the FDA public API <br>
2. Cleans and normalizes the raw API response into structured fields <br>
3. Runs exploratory data analysis: trends over time, outlier detection, reason breakdown, and firm breakdown <br>
4. Sends the EDA results to OpenAI GPT-4O-MINI for interpretation <br>
5. Builds an Excel file named with the current week number and day <br>
6. Delivers a formatted HTML email with the AI narrative in the body and the Excel file attached <br>
<br>

## Data Source
FDA Medical Device Recall Database https://www.fda.gov/medical-devices/medical-device-recalls <br>
