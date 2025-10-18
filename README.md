# Website-Metadata-IP-Collector
A Python tool that collects IP addresses, response times, and web metadata (title, meta description, server type, etc.) from the top 1000 websites.
It uses socket, requests, BeautifulSoup, and pandas to gather and export the data into an Excel file.

🔹 Features

Fetches website IP and response time

Extracts title, meta description, server, and content type

Handles errors gracefully for unreachable sites

Saves results to website_metadata.xlsx

🛠 Tech Stack

Python · requests · socket · BeautifulSoup · pandas

📊 Output Columns

Website | IP Address | Response Time | Content Type | Server | Title | Meta Description | Error
