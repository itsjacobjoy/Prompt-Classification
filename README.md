# Prompt-Classification
**Overview**
This project focuses on developing a prompt classification system by supervised fine-tuning a pre-trained language model, gemini-1.0-pro-002. The tuned model can successfully classify prompts into specific categories to enhance the efficiency and accuracy of natural language processing tasks.

**Classes**
The tuned model can classify the following classes:

- Chatbots and Virtual Assistants
- Conversation
- Mental Health
Image Generation
Video Generation
Music Creation
Speech Generation
Podcast Content Creation
Storytelling
Social Media Posts
Product Descriptions (repeated twice)
SEO Optimization
Educational Content Creation
Presentation Creation (repeated twice)
Email Generation
Legal Document Drafting
Contract Generation
Recipe Generation
Fitness & Health Plans Recommendations
Homework Solutions
AI Content Detection
Branding and Logo Design
Travel Itinerary Creation
Event Planning
Data Analysis
Financial Report Generation
API Integration
Translation
Blog Writing
Market Analysis
Coding and Programming Assistance
Language Learning Assistance
Personalized Recommendations
Resume and Cover Letter Writing
Job Description Creation
Research Paper Data
Summarizations
News Article Generation

**Project Structure**

- Model Training
Utilized the gemini-1.0-pro-002 model.
Fine-tuned the model with supervised learning using a curated dataset.
The dataset contains varied prompts covering all specified categories.

- Model Deployment
The tuned model is deployed and ready to classify prompts in real-time.

- API Integration
Implemented API integration to handle prompt classification requests.
Routed to a general LLM for handling prompts classified as "Others."

- Validation
Validation dataset created to ensure the model's performance.
Continuous testing to maintain classification accuracy.
