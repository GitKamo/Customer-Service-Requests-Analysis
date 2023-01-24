# Analysis of Requests for Customer Service

I was tasked with performing a service request data analysis of New York City 311 calls. The NYC 311 service had a mission to provide the public with quick and easy access to all New York City government services and information while offering the best customer service. Each day, NYC311 received thousands of requests related to several hundred types of non-emergency services, including noise complaints, plumbing issues, and illegally parked cars. These requests were received by NYC311 and forwarded to the relevant agencies such as the police, buildings, or transportation. The agency responded to the request, addressed it, and then closed it.

My objective was to understand the patterns in the data and also visualize the major complaint types by focusing on the data wrangling techniques.

To accomplish this, I first imported a 311 NYC service request. Then, I converted the columns ‘Created Date’ and Closed Date’ to datetime datatype and created a new column ‘Request_Closing_Time’ as the time elapsed between request creation and request closing. I used the package/module datetime to do this.

Next, I provided major insights/patterns that I could offer in a visual format (graphs or tables); at least 4 major conclusions that I could come up with after generic data mining. I also ordered the complaint types based on the average ‘Request_Closing_Time’, grouping them for different locations.

Lastly, I performed a statistical test for the following:

I determined whether the average response time across complaint types was similar or not (overall)
I checked if the type of complaint or service requested and location were related.
The dataset I used for my analysis included fields such as 'Unique Key', 'Created Date', 'Closed Date', 'Agency', 'Complaint Type', 'Location Type', and 'Borough'.




