# Gans E-Scooter Data Engineering Project

Summary

This project focuses on building an end-to-end data pipeline for Gans, a German e-scooter rental company, to support data-driven decisions regarding e-scooter demand and distribution. Key tasks included data collection through web scraping and APIs, data storage in MySQL, and deploying an automated ETL pipeline on Google Cloud Platform (GCP). The project aims to optimize Gans' operations by providing insights into city-specific e-scooter usage patterns.

For a more detailed breakdown of the process, you can read my Medium article https://medium.com/@sushma25.gowda/transforming-data-my-adventure-from-local-scripts-to-cloud-automation-%EF%B8%8F-cb2e61594725.

Languages and Libraries Used

Languages: Python
Libraries: BeautifulSoup, Requests, MySQL Connector, Google Cloud SDK
Database: MySQL (Local & Google Cloud MySQL)
Cloud Services: Google Cloud Platform (Cloud Functions, Cloud Scheduler)
Key Learnings

Data Engineering Pipelines: Gained practical experience in creating and automating data pipelines for large datasets and integrating multiple data sources.
Cloud Computing: Learned to use GCP tools like Cloud Functions and Scheduler for seamless cloud automation and scaling.
Technical Communication: Improved skills in documenting complex workflows to facilitate knowledge transfer and understanding among both technical and non-technical stakeholders.
Challenges Overcame

Data Quality Issues: Managed unstructured data from various sources by implementing data cleaning steps to standardize inputs before storing them in databases.
Automation Complexity: Setting up a fully automated pipeline was challenging due to API rate limits and differing data formats, which I resolved by creating custom error handling and scheduling strategies.
Cloud Integration: Overcame initial configuration issues with GCP services by referring to documentation and troubleshooting network and permission settings.
Additional Reflections

Working on this project provided a comprehensive understanding of the end-to-end data engineering workflow, from data acquisition to cloud deployment. It was rewarding to see the automation of the pipeline come to fruition, as it emphasized the power of data engineering in real-time decision-making for scalable operations. This project also highlighted the importance of adaptable skills, as it required a blend of technical and problem-solving capabilities.
