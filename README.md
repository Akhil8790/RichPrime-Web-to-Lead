# RichPrime Motors – Book a Test Drive (Salesforce Web-to-Lead)

A "Book a Test Drive" form styled to match richprimemotors.com. Submitting it posts to Salesforce Web-to-Lead and creates a Lead with Lead Source `Website - Book Test Drive`.

Live page: `https://akhil8790.github.io/RichPrime-Web-to-Lead/`

## Field mapping

| Form field | Salesforce Lead field |
|---|---|
| First Name / Last Name | FirstName / LastName |
| Email | Email |
| Phone Number | MobilePhone |
| Best Way to Reach You | Preferred_Contact_Method__c |
| Desired Vehicle Model | Model_of_Interest__c |
| Preferred Dealership | Branch__c |
| Purchase timeframe | Purchase_Timeframe__c |
| Vehicle Comment + Message | Description |
| (hidden) | LeadSource = Website - Book Test Drive |
| (built from name) | Company |

This is a demo form connected to a Salesforce Developer Edition org. reCAPTCHA is not turned on, so anyone who opens the page can create Leads.
