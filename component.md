## Metric Collection Component

The Metric Collection Component is responsible for continuously gathering system performance data to enable real-time monitoring.

### Responsibilities:
- Collecting system metrics such as CPU usage, memory usage, disk usage, and other performance indicators  
- Recording timestamped metric values  
- Storing collected metrics in the database  
- Ensuring continuous and reliable monitoring  

This component forms the foundation of the monitoring system by supplying accurate and timely system data for analysis.

---

## Threshold Management Component

The Threshold Management Component defines acceptable operational limits for system metrics and identifies abnormal behavior.

### Responsibilities:
- Defining upper and lower threshold limits for metrics  
- Comparing collected metric values against predefined thresholds  
- Detecting threshold violations  
- Triggering alert events when limits are exceeded  

This component acts as the decision-making unit of the system, determining whether system performance is within acceptable bounds or requires attention.
