# -legal-compliance-helper
Summary
​This project proposes an AI-driven tool designed to scan commercial contracts for clauses that conflict with the Contract Act of 1872 or the Partnership Act of 1932. It helps small business owners and students identify potentially unfair or unenforceable terms before signing.
​Background
​The Problem: Many small business owners in Pakistan lack the budget for extensive legal review when entering into commercial agreements.
​Motivation: As a student of commercial law and accounting, I have observed that discrepancies in partnership deeds and agency agreements often lead to complex financial disputes later.
​Importance: This tool provides an accessible layer of initial legal due diligence, promoting better contractual literacy and reducing the risk of costly litigation.
​How is it used?
​User Workflow: A user uploads a PDF or text version of a contract into the interface.
​Analysis: The AI processes the text using natural language processing (NLP) to highlight clauses that may lack "free consent" or violate standard partnership rights.
​Environment: This tool is ideal for entrepreneurs, accounting students, and small startups during the initial drafting or review phase of an agreement.
​Data sources and AI methods
​Data Sources: The project uses public archives of the Contract Act of 1872 and the Partnership Act of 1932 as the training foundation.
​AI Method: The system utilizes a Transformer-based model (such as a fine-tuned BERT or a RAG-based LLM) to compare user-provided contract text against statutory clauses for semantic similarity and potential non-compliance.
Challenges
​Limitations: This project does not provide binding legal advice; it is an educational and supportive tool, not a replacement for a qualified attorney.
​Ethical Considerations: AI models may suffer from hallucinations or misinterpret nuanced legal language; therefore, all outputs must be marked with a strong disclaimer advising professional verification.
​What next?
​Growth: The project could expand to include the Negotiable Instruments Act, assisting in the audit of promissory notes and bills of exchange.
​Required Assistance: To move forward, I would need access to a larger corpus of anonymized, standard-form commercial contracts to improve the model's accuracy in identifying "red flag" clauses.
