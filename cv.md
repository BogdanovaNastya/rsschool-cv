# rsschool-cv

## **Bogdanova Anastasiia**


### **Contact information:**

* mail: spbnastyab@gmail.com
* telegram: [@AnastasiiaBogdanova](https://t.me/AnastasiiaBogdanova)
* linkedin: [Anastasia-Bogdanova](https://www.linkedin.com/in/anastasia-bogdanova-b63582119/)

___

### **About me:**

* graduated from Higher School of Economics, have Bachelor in Logistics
* live in Saint-Petersburg
* work as BI-developer, create dashboards using Qlikview and Qlik Sense
* due to politics we have to change foreign BI-platform to Russian, so I need to learn front-end

    ![мем](/rsschool-cv/img/meme.jpg)

___

### **Skills:**

* Excel guru
* Mind reading of business users
* Data visualization and data modeling using Qlik tools
* SQL

___

### **Code examples:**

```
# I guess something is better than nothing
SELECT 
    ma.first_name,
    ma.last_name,
    DATE_FORMAT(SEC_TO_TIME(AVG(ca.duration_sec)),"%H:%i:%s") as avg_duration
FROM calls as ca
JOIN clients as cl ON cl.id = ca.client_id
JOIN managers as ma ON ma.id = ca.manager_id
LEFT JOIN companies as co ON cl.company_id = co.id
WHERE 
    co.name = 'Cloud Computing'
GROUP BY 
    ma.id
ORDER BY 
    avg_duration DESC
```

___

### **Experience:**

* 0.5 year as Data Analyst
* 1.5 years as BI-developer

### **Languages:**

* Russian - Native
* English - Upper-Intermediate