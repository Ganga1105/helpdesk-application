# Module 1: Core Infrastructure & Authentication (Ganga / Saravanan)

### Ganga's Presentation Content (Frontend)
In Module 1, I focused on building the foundational user experience, starting with the entry points into our "Neural Archive" ecosystem. I developed the 'Landing' and 'Home' pages, which set the tone for the application's clean, futuristic aesthetic while ensuring intuitive navigation for all user roles. A major part of my work involved creating the 'Login' interface, which is not only visually striking but also features deep integration with our authentication context to provide seamless transitions and real-time validation feedback. I collaborated closely with the backend team to ensure that our 'AuthContext' robustly handles JWT token persistence, multi-role redirect logic, and secure session management. My implementation ensures that from the very first interaction, users experience a smooth, high-fidelity gateway into the system that prioritizes both security and visual excellence.

### Saravanan's Presentation Content (Backend)
For the backend of Module 1, I architected the core security infrastructure that powers the entire Helpdesk application. I developed a comprehensive 'Authentication' module that handles everything from secure registration and password hashing to JWT-based session issuance and verification. I designed a group of multi-layered middleware functions that intercept every request to enforce strict authentication and granular authorization across five distinct user roles. By implementing a centralized token management system, I ensured that we have a scalable and secure way to handle user state across all subsequent modules. My contribution provides the project with its "heart"—a reliable, robust, and highly-performant security layer that protects our data while providing the necessary context for personalized user experiences across our API.

### **Files in this Module**
- [Login.jsx](Login.jsx)
- [Landing.jsx](Landing.jsx)
- [Home.jsx](Home.jsx)
- [auth.js (Routes)](auth.js)
- [auth.js (Middleware)](auth.js)
