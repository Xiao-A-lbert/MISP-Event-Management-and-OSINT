# MISP Event Management and OSINT

<h2>Description</h2>
In this Threat Intelligence task, I explore MISP, create an event from an DFIR report, and ingest attributes from OSINT. 

<h2>Languages and Utilities Used</h2>

- <b>MISP</b>
- <b>Linux CLI</b>

<h2>Environments Used </h2>

- <b>Ubuntu</b> 

<br />
<br />
Adding an event from a published DFIR Report about OneNote Ransomeware. 

![1) create event](https://github.com/user-attachments/assets/24fb0498-8500-4441-81dc-77e3be8d9aeb)

<br />
<br />
Event Created with link to original report. 

![2) first attribute](https://github.com/user-attachments/assets/5cf70f48-99ba-49aa-a1e4-e111067c5998)

<br />
<br />  
Ingesting IOCs provided from the report. 

![3) importing IOCs from the report into MISP](https://github.com/user-attachments/assets/771c4945-dede-42d8-bac0-dd886ed3a721)

<br />
<br />
Enriching IOCs with dns, reversedns, yara_query, and malwarebazaar. 

![4) enriching events](https://github.com/user-attachments/assets/bbedb6cb-7da6-41dd-85b8-d487ac6f6ab1)

<br />
<br />
Yara rule shown after enrichment. 

![5) yara rule created](https://github.com/user-attachments/assets/807f8c74-bbc1-4a49-8311-10435b8ebe89)

<br />
<br />
Ingesting attributes from OSINT. 

![6) ingesting external feeds into instance](https://github.com/user-attachments/assets/a0a6501d-7417-4a2c-bc73-e1f2e8dd7078)

<br />
<br />  
Searching for botnet POS OSINT. 

![7) examining point of sale brute force](https://github.com/user-attachments/assets/88e71783-1950-4fc1-989b-b5d39b28a449)

<br />
<br />  
Looking at timeline for attributes and attribute list.

![8) timeline and attributes](https://github.com/user-attachments/assets/edc9f286-fa06-4420-a5b8-7100eb20d6e5)

<br />
<br />
