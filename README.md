# Smart India Hackathon Workshop
# Date:09/03/2025
## Register Number:212224230282
## Name:SUSHMITHA S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

To create a Smart Interview System for DRDO’s RAC, we propose an AI-driven Virtual Boardroom that simulates real-life interviews. The system will have the following key features:

1. Candidate Profiling & Question Matching

Extract candidate’s expertise from their resume/application.

AI generates relevant interview questions dynamically.

Gradual progression from ice-breaking to complex technical/managerial questions.



2. AI-Assisted Interview Process

Panel members can use AI-suggested questions or ask their own.

AI analyzes real-time speech/text responses for relevancy and depth.



3. Real-Time Response Evaluation

NLP-based Semantic Analysis to score responses based on correctness, depth, and relevance.

Checks confidence level using speech tone analysis (optional).



4. Final Scoring & Report Generation

Candidate is scored based on response accuracy, depth, and expertise relevance.

Generates a final scorecard for automated shortlisting.


## Proposed Solution / Architecture Diagram


![webbb](https://github.com/user-attachments/assets/020c9255-dcd0-4b1a-afcf-245ac628eaa7)



## Use Cases

1. Candidate Registration & Profile Setup

Upload resume → AI extracts expertise → Creates interview roadmap.



2. Interview Panel Setup

Experts log in & review AI-generated question set.

Option to modify/add questions.



3. AI-Assisted Interview Execution

Candidate joins via video/audio.

AI suggests questions dynamically.

AI scores responses in real time.



4. Post-Interview Evaluation & Reporting

Final candidate ranking based on AI-generated score.

Generates detailed feedback reports.




## Technology Stack

Frontend (User Interface)

Frameworks: React.js / Angular / Vue.js

Styling: Tailwind CSS / Bootstrap / Material UI

WebRTC API: For live video conferencing


Backend (Server & APIs)

Language: Python

Frameworks: Django / FastAPI / Flask

Authentication: OAuth 2.0 / JWT (JSON Web Tokens)

Speech Processing: Google Speech-to-Text / Whisper AI


AI/NLP Components

AI Model for Question Generation: OpenAI GPT / BERT

AI Model for Answer Evaluation: BERT / RoBERTa / T5

Text Processing: NLTK / SpaCy / Transformers

Sentiment Analysis & Scoring: VADER / SentimentIntensityAnalyzer


Database & Storage

Relational Database: PostgreSQL / MySQL

NoSQL Database (for AI logs & feedback): MongoDB / Firebase Firestore

Cloud Storage: AWS S3 / Google Cloud Storage / Azure Blob


Deployment & Hosting

Cloud Providers: AWS / Azure / Google Cloud

Containerization: Docker + Kubernetes

Serverless Functions: AWS Lambda / Google Cloud Functions


## Dependencies
1. Pre-trained AI models for NLP-based question generation and response evaluation.


2. Secure Video Conferencing API (e.g., WebRTC, Zoom SDK) for remote interviews.


3. Cloud Hosting (or on-prem) for scalable storage & processing.


4. Integration with existing DRDO HR systems for seamless operations.
