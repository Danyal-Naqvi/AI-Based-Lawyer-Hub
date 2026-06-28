AI-Based Lawyer Hub is a full-stack legal technology platform that combines Artificial Intelligence, Retrieval-Augmented Generation (RAG), and modern web/mobile development to provide intelligent legal assistance and digital legal services.

This repository serves as the central hub for the entire project. It contains the project overview, system architecture, documentation, setup instructions, and links to all individual repositories that make up the platform.
Project Components

The AI-Based Lawyer Hub ecosystem consists of the following interconnected applications and services:

Client Mobile Application (React Native):
Provides an AI-powered legal assistant, lawyer directory, appointment scheduling, real-time chat, document sharing, digital law library, AI-assisted legal document filling, and client profile management.

Lawyer Mobile Application (React Native):
Enables lawyers to manage appointments, publish availability, communicate with clients, complete KYC verification, respond to reviews, and maintain professional profiles.

Core Backend (Node.js & Express.js):
Acts as the primary API server, handling authentication, authorization, user management, appointment scheduling, chat services, document management, notifications, reviews, and integration with AI services.

Admin Dashboard (React):
Provides administrators with a centralized interface to manage users, verify lawyers, maintain the digital law library, monitor platform activities, and configure notification templates.

Admin Backend (Node.js & Express.js):
Supports administrative operations by exposing secure APIs for user management, lawyer verification, content management, analytics, and system administration.

Legal RAG Service (Python):
Implements a Retrieval-Augmented Generation (RAG) pipeline that processes legal documents using OCR and PDF extraction, performs intelligent chunking and embedding generation, retrieves relevant legal context from a vector database, and generates context-aware legal responses using Large Language Models (LLMs).

Technology Stack
Mobile:
React Native
Expo
Backend:
Node.js
Express.js
MongoDB
AI /RAG:
Python
FAISS Vector Database
OCR
PDF Processing(pdfPlumber)
Sentence transformer via Huggingface
Admin
React.js
Node.js

Features:

Authentication & User Management

* Secure email-based registration with email verification
* Login, logout, and session management
* Password reset via email
* Profile management for clients and lawyers
* Secure account deletion

AI-Powered Legal Assistant

* Conversational legal question answering using LLMs
* Retrieval-Augmented Generation (RAG) for context-aware responses
* Citation support on request
* AI-assisted legal document filling guidance
* Conversation history management

Lawyer Discovery & Consultation

* Search lawyers by name and specialization
* Filter lawyers by ratings and verification status
* View detailed lawyer profiles
* Verified lawyer badges (KYC)

Appointment Management

* Real-time appointment booking
* Lawyer availability scheduling
* Appointment confirmation and rejection
* Appointment rescheduling and cancellation
* Appointment history and status tracking

Real-Time Communication

* Secure client-lawyer messaging
* Document and image sharing
* Chat history management

Review & Rating System

* Client ratings and reviews
* Lawyer replies to reviews
* Automatic rating aggregation

Digital Legal Library

* Browse and search legal books
* Download legal resources
* Category-based filtering

Lawyer Verification (KYC)

* Identity and license document submission
* Admin review and approval workflow
* Verified lawyer status management

Administrative Dashboard

* User and lawyer management
* Lawyer verification approval
* Book and document catalog management
* Notification template management
* Platform monitoring and administration

 Legal RAG Pipeline

* OCR and PDF text extraction
* Intelligent document preprocessing
* Embedding generation
* Vector database indexing
* Semantic retrieval
* Context-aware response generation using Large Language Models (LLMs)

Backend & Infrastructure

* RESTful API architecture
* JWT-based authentication
* Role-based access control
* Secure file upload and storage
* Modular architecture
* Scalable AI service integration


Component	Repository
User Mobile App(https://github.com/Danyal-Naqvi/Mobile-LawyerHub-Client)
Lawyer Mobile App(https://github.com/Danyal-Naqvi/Mobile-LawyerHub-Lawyer)
Mobile Backend(https://github.com/Danyal-Naqvi/lawyerhub-nodejs-backend)
Admin Panel(https://github.com/Danyal-Naqvi/Admin-Frontend-Lawyerhub)
Admin Backend(https://github.com/Danyal-Naqvi/Admin-Backend-Lawyerhub-)
Legal RAG Service(https://github.com/Danyal-Naqvi/Pakistan-Legal-RAG)

Architecture
<img width="943" height="734" alt="image" src="https://github.com/user-attachments/assets/d9c9b611-7201-477c-97ba-17278f587d10" />

Screenshots:
<img width="301" height="492" alt="image" src="https://github.com/user-attachments/assets/dd18f80f-74ce-440f-835c-f34f5983aab3" />
<img width="298" height="516" alt="image" src="https://github.com/user-attachments/assets/63447189-40b1-412a-bbe1-54d079c0a9cc" />
<img width="264" height="524" alt="image" src="https://github.com/user-attachments/assets/0c88b91a-6aa0-44e2-b275-1df42a829323" />
<img width="246" height="500" alt="image" src="https://github.com/user-attachments/assets/bbbea1f7-490f-44b9-9f57-51d134b545c8" />
<img width="910" height="404" alt="image" src="https://github.com/user-attachments/assets/11b2a9ab-3758-4fe5-9a04-9fbd359e4aec" />
<img width="292" height="611" alt="image" src="https://github.com/user-attachments/assets/082ed0b7-43f3-47e4-9b27-bdb34340f608" />
<img width="241" height="536" alt="image" src="https://github.com/user-attachments/assets/ae48e0bc-c2d9-40b9-965e-088649b95191" />
<img width="234" height="477" alt="image" src="https://github.com/user-attachments/assets/361f9612-11f7-40e9-987f-4324a2ddacce" />






