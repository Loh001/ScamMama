# ScamMama - SimplifyNext AgenticAI Submission
An agentic AI assistant that investigates, analyzes, and reports potential scams targeting Singaporeans.

Problem Statement
Online scams in Singapore are on the rise. Hotlines are overwhelmed, and we lack sufficient manpower to handle the growing number of scam alert calls. ScamMama is designed to support hotline staff and end-users by automatically investigating, analyzing, and reporting potential scams.

Key Features
1. Active Investigation Tools
- Real-time website crawling & extraction (tavily_crawl, tavily_extract)
- Web search with exa_search to gather up-to-date scam information
- HTTP requests to verify suspicious sites and services

2. Documentation & Reporting
- Generates structured reports that can be saved and retrieved
- Logs all findings with timestamps and evidence using file_write / file_read

3. Multi-Modal Analysis
- Analyzes websites, text messages, phone numbers, and emails
- Assigns numerical risk ratings (0–10) with clear explanations
- Breaks down why content or behavior may be suspicious

4. Transparency
- Explains reasoning instead of simple yes/no answers
- Acknowledges limitations and uncertainties
- Cites specific evidence behind every conclusion

Usage Philosophy:
By using ScamMama, we aim to:
1. Encourages the use of multiple tools and services for better protection
2. Help users stay updated on emerging scam tactics
3. Promotes cautious decision-making when handling suspicious communications
