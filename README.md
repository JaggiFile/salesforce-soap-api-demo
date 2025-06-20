# Salesforce SOAP API Demo

This project demonstrates how to connect to Salesforce using the **SOAP API** via **SOAP UI**, including login and querying Account records.

##  Tools Used

- Salesforce Developer Edition Org  
- Enterprise WSDL  
- SOAP UI (Open Source)  
- GitHub (for version control)

##  Included Files

| File Name                   | Description                                          |
|----------------------------|------------------------------------------------------|
| `enterprise.wsdl.xml`      | Enterprise WSDL downloaded from Salesforce Setup     |
| `login-request.xml`        | Sample SOAP request to log in using username + token |
| `account-query-request.xml`| Sample SOAP request to query Account records         |

##  What This Project Covers

- Authenticating with Salesforce using **SOAP login**
- Receiving and using `sessionId` and `serverUrl`
- Querying data using the SOAP `query()` operation

## 📈 Sample Query Performed

```sql
SELECT Id, Name FROM Account LIMIT 5
```

##  Skills Demonstrated

- Salesforce API Integration (SOAP)
- WSDL usage and structure understanding
- Session management and API calls
- Working with XML in SOAP UI

##  Author

**Jasvinder Singh**  
Salesforce Certified Admin & Developer  
sunni56singh@gmail.com  
LinkedIn Profile - linkedin.com/in/jasvinder-singh-kashmiri

---
