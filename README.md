**KB Analyzer Agent**

**Overview**

KB Analyzer Agent is a beginner-friendly AI-powered project designed to improve the quality and consistency of knowledge base articles. The system scans a limited set of KB articles and identifies issues such as broken links, outdated product names, and non-inclusive language. It then generates a structured report with suggested fixes for human review and approval.

**Target Audience**
It is designed for customers and internal stakeholders—including support engineers, product managers, technical account managers, and other teams who create, maintain, and rely on knowledge content.

**Features**
Detect broken links in KB articles
Identify outdated product names
Flag non-inclusive language
Generate structured CSV/Excel reports
Human-in-the-loop review workflow
Simple frontend dashboard prototype

**Tech Stack**
*Frontend*
* HTML
* Tailwind CSS

*Backend*
* Python
* APIs
* OpenAI API
* Public API integrations for learning/testing

**Project Structure**

kb-analyzer-agent/

├── frontend/

├── backend/

├── data/

├── reports/

├── prompts/

├── main.py

├── requirements.txt

└── README.md

**Simple Swimlane Architecture Diagram**

![High level architecture diagram] (./image/KB-Analyzer-Swimlane-Diagram.png)
**Setup Instructions**

1. Clone the Repository
_____
git clone <repository-url>
cd kb-analyzer-agent
____

2. Create Virtual Environment
____
python3 -m venv venv
source venv/bin/activate
____

3. Install Dependencies
----
pip install -r requirements.txt
----

4. Run the Project
____
python main.py
____

**Current MVP Scope**

The current MVP:

* Works on a small set of KB articles
* Uses local file storage
* Generates reports manually
* Requires human approval before update

**Future Enhancements**

* Automated scheduled scans
* Enterprise KB API integration
* Interactive React dashboard
* Confidence scoring
* Audit logging
* Auto-fix recommendations

