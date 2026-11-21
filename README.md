# Cold Mail Generator

## Overview

An AI-powered cold email generation tool built using **Python, Groq, LangChain, and Streamlit**. It automates personalized business outreach by extracting job listings from a company's careers page and generating relevant cold emails.

The application analyzes job descriptions and retrieves matching portfolio links from a vector database to create targeted emails showcasing relevant services and expertise.

## Use Case

Suppose Nike is hiring a Principal Software Engineer. Instead of going through the complete recruitment process, Nike could partner with Atliq, a software development company, to get a dedicated engineer.

Mohan, a Business Development Executive at Atliq, can use this application to identify the opportunity and generate a personalized email highlighting Atliq's relevant services and portfolio.

## Key Features

- Extracts job listings from company career pages using their URLs.
- Analyzes job descriptions to identify required skills and technologies.
- Generates personalized cold emails using Groq and LangChain.
- Retrieves relevant portfolio links from a vector database.
- Creates targeted business outreach emails automatically.

## Tech Stack

- Python
- Streamlit
- LangChain
- Groq API
- Vector Database
- Web Scraping

## Setup and Installation

**1. Clone the repository**

```bash
git clone <repository-url>
cd <project-folder>
```

**2. Configure the API key**

Generate an API key from the [Groq Console](https://console.groq.com/keys) and add it to `app/.env`:

```env
GROQ_API_KEY=your_api_key_here
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the application**

```bash
streamlit run app/main.py
```

## License

Copyright (C) Codebasics Inc. All rights reserved.

Licensed under the MIT License. Commercial use requires prior written permission from the author. Attribution is required in all copies or substantial portions of the software.
