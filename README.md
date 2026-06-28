# AI-Based Lawyer Hub

![AI Lawyer Hub](<img width="1536" height="1024" alt="ChatGPT Image Jun 28, 2026, 11_19_50 PM" src="https://github.com/user-attachments/assets/07e99b2a-1832-40c2-a5a9-7fba5a92abc3" />
)

AI-Based Lawyer Hub is a full‑stack legal technology platform that combines Artificial Intelligence, Retrieval‑Augmented Generation (RAG), and modern web & mobile development to deliver an intelligent legal assistant, lawyer discovery, appointment management, and a digital legal library.

This repository serves as the central hub for the project: it contains the project overview, system architecture diagrams, documentation, setup notes, and links to each component repository.

---

## Table of Contents

- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Architecture](#architecture)
- [Project Components](#project-components)
- [Quickstart](#quickstart)
- [Contributing](#contributing)
- [Screenshots](#screenshots)
- [License](#license)

---

## Key Features

- Authentication & User Management
  - Secure email registration and verification
  - Login, logout, session management, password reset
  - Role-based profiles for clients and lawyers
- AI-Powered Legal Assistant
  - Conversational question answering using LLMs
  - Retrieval‑Augmented Generation (RAG) for context-aware answers
  - Citation support on request and conversation history
  - AI-assisted guided form/document filling
- Lawyer Discovery & Consultation
  - Search and filter lawyers by specialization, rating, and verification
  - Detailed lawyer profiles and verified (KYC) badges
- Appointment Management
  - Real-time booking, scheduling, confirmation, rescheduling, and cancellation
  - Lawyer availability management and history tracking
- Real-Time Communication
  - Secure client–lawyer messaging with file & image sharing
  - Chat history and media attachments
- Reviews & Ratings
  - Client ratings, reviews and lawyer responses
  - Automatic aggregation of ratings
- Digital Legal Library
  - Browse, search, and download legal resources
  - Category-based filtering
- Admin & KYC Workflows
  - Admin dashboard for user and content management
  - Lawyer identity and license verification workflow
- Legal RAG Pipeline
  - OCR and PDF extraction (pdfPlumber), intelligent chunking
  - Embedding generation and FAISS vector indexing
  - Semantic retrieval and LLM-driven response generation

---

## Technology Stack

- Mobile: React Native, Expo
- Backend: Node.js, Express.js, MongoDB
- AI / RAG: Python, FAISS vector DB, OCR, pdfPlumber, Hugging Face sentence transformers
- Admin: React.js, Node.js

---

## Architecture

![Architecture](https://github.com/user-attachments/assets/d9c9b611-7201-477c-97ba-17278f587d10)

The platform is composed of mobile clients (for users and lawyers), core and admin backends, and a dedicated Legal RAG AI service for document processing and semantic retrieval.

---

## Project Components

- User Mobile App (Client): https://github.com/Danyal-Naqvi/Mobile-LawyerHub-Client
- Lawyer Mobile App: https://github.com/Danyal-Naqvi/Mobile-LawyerHub-Lawyer
- Mobile Backend: https://github.com/Danyal-Naqvi/lawyerhub-nodejs-backend
- Admin Panel: https://github.com/Danyal-Naqvi/Admin-Frontend-Lawyerhub
- Admin Backend: https://github.com/Danyal-Naqvi/Admin-Backend-Lawyerhub-
- Legal RAG Service: https://github.com/Danyal-Naqvi/Pakistan-Legal-RAG

> Note: Each component has its own README with setup and run instructions. Follow those links for per-service details.

---

## Quickstart (developer)

1. Clone the component you want to work on (for example the mobile backend):

   git clone https://github.com/Danyal-Naqvi/lawyerhub-nodejs-backend.git

2. Follow the README in that repository for environment variables, database setup (MongoDB), and any API keys required for AI services.

3. For the Legal RAG service: ensure Python, virtualenv, and required packages are installed, and configure the FAISS vector store and embedding model (Hugging Face).

---

## Contributing

Contributions, bug reports, and feature requests are welcome. To contribute:

1. Fork the target component repository.
2. Create a feature branch: git checkout -b feat/your-feature
3. Commit your changes and open a PR with a clear description and screenshots if applicable.

Please follow the code style and testing guidelines in each component repository.

---

## Screenshots

![Screenshot 1](https://github.com/user-attachments/assets/dd18f80f-74ce-440f-835c-f34f5983aab3)

![Screenshot 2](https://github.com/user-attachments/assets/63447189-40b1-412a-bbe1-54d079c0a9cc)

![Screenshot 3](https://github.com/user-attachments/assets/0c88b91a-6aa0-44e2-b275-1df42a829323)

![Screenshot 4](https://github.com/user-attachments/assets/bbbea1f7-490f-44b9-9f57-51d134b545c8)

![Screenshot 5](https://github.com/user-attachments/assets/11b2a9ab-3758-4fe5-9a04-9fbd359e4aec)

![Screenshot 6](https://github.com/user-attachments/assets/082ed0b7-43f3-47e4-9b27-bdb34340f608)

![Screenshot 7](https://github.com/user-attachments/assets/ae48e0bc-c2d9-40b9-965e-088649b95191)

![Screenshot 8](https://github.com/user-attachments/assets/361f9612-11f7-40e9-987f-4324a2ddacce)

---

## License

This project was developed as a Final Year Project (FYP) for educational purposes.


