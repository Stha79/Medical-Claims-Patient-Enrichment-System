Medical Claims & Patient Enrichment System
📌 Overview

The Medical Claims & Patient Enrichment System is an enterprise integration solution designed to automate and streamline the processing of medical insurance claims while improving the quality of patient data through enrichment processes.

The system is built using IBM App Connect Enterprise (ACE) for integration flows, IBM MQ for reliable messaging, and PostgreSQL as the primary database for persistent storage.

⚙️ Architecture

The system follows a message-driven architecture:

IBM MQ handles asynchronous message communication between services
IBM ACE processes, transforms, and routes incoming claim data
External/Reference Data Sources are used for patient data enrichment
PostgreSQL Database stores patient records, claims, and enriched data

🚀 Key Features
Automated medical claims processing
Message-driven integration using IBM MQ
Data transformation and routing with IBM ACE
Patient data enrichment for improved accuracy
Persistent storage using PostgreSQL
Scalable and loosely coupled architecture

🔄 Workflow
Medical claim is submitted into the system
Message is published to IBM MQ
IBM ACE consumes and processes the message
Patient data is validated and enriched
Processed data is stored in PostgreSQL
Final enriched claim is made available for reporting or downstream systems

🛠️ Technologies Used
IBM App Connect Enterprise (ACE)
IBM MQ
PostgreSQL
SQL
Message-driven architecture

📂 Project Structure
/flows
   - ACE integration flows
/mq
   - MQ configuration and message formats
/database
   - PostgreSQL scripts and schema
/docs
   - Architecture diagrams and documentation

   📈 Benefits
Reduces manual claim processing
Improves data accuracy through enrichment
Ensures reliable message delivery
Enhances scalability and system decoupling

👨‍💻 Author

Developed by STHABISO SIBISI
