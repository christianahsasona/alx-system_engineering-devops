<img src= "https://twitter.com/devopsreact/status/834887829486399488"/>
<h1>Issue Summary:</h1>
<p>On July 23rd, 2023, at 10:00 AM WAT, the Nginx server hosting or company's website experienced an outage that lasted for 2 hours. During this time, users were unable to access the website, resulting in a 100% outage rate.0
</p>
<h1>Root Cause:</h1> 
<p>The root cause of the outage was a configuration issue in the Nginx server that caused it to crash when handling a sudden spike in traffic. This was due to an incorrect setting in the server configuration file that was not caught during the testing phase.
</p>
<h1>Timeline:</h1>
<p>10:00 AM: The issue was first detected by our monitoring system, which alerted our team of the server's unresponsiveness.10:05 AM: An engineer noticed the issue and attempted to restart the Nginx server, but it failed to start. 10:10 AM: The team investigated the server logs and found no indication of any hardware or network failure. 10:20 AM: Assumptions were made that the issue was related to the server configuration and the team began investigating. 11:00 AM: The team discovered the incorrect configuration setting, which was quickly fixed. 11:15 AM: The server was restarted, and the website was once again accessible to users. Misleading Investigation/Debugging Paths: During the investigation, the team initially focused on hardware and network issues, as these were common causes of server outages. This led to some time being wasted on checking hardware logs and network connectivity, which ultimately had no relevance to the root cause of the issue.
</p>
<h1>Escalation:</h1>
<p>The incident was initially escalated to the server team responsible for managing the Nginx server. When the issue was found to be related to the configuration file, it was escalated to the development team responsible for website deployment and configuration management.
</p>
<h1>Resolution:</h1> 
<p>The incorrect configuration setting was found and corrected, allowing the Nginx server to be restarted and the website to become accessible again.
</p>
<h1>Corrective and Preventative Measures:</h1>
<p><b>To prevent similar issues from occurring in the future, the following measures will be taken:
</b>
Implement better testing procedures for server configuration changes to catch issues before they become live. Improve the monitoring system to provide more detailed alerts that can help diagnose issues more quickly. Develop a more robust failover system to ensure that website access can be maintained in the event of a server outage. In conclusion, the Nginx server outage on July 23rd, 2023, was caused by a configuration issue that led to a sudden spike in traffic, resulting in the server crashing. The issue was quickly resolved, but measures will be taken to prevent similar issues from occurring in the future.
</p>
