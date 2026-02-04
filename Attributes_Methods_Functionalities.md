## 1. Login
Attributes
username
password
emailId
contactNum
role

## 2. Alerts
Attributes
alertId
severity (enum)
status (enum)
Methods
generateAlert()
escalate()
closeAlert()

## 3. Notification
Attributes
notificationId
Methods
sendEmail()
sendSMS()

## 4. User (extends Login)
Attributes
userId
username
emailId
contactNum
role
regUser
internalAPI
Methods
manageProfile()
viewAlert()
changeThreshold()
changeNotificationSettings()

## 5. Dashboard
Methods
historicalDataView()
filteringAndSearching()

## 6. Admin
Methods
manageRoles()
monitorSystemMetrics()
Note
Admin extends User
Admin has access to alerts and dashboard

## 7. AI Model
Methods
predictAnomaly()

## 8. Metrics
Attributes
metricType
metricValue
timestamp
Methods
storeMetric()
