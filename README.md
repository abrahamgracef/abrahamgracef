# Abraham Grace F

**Software Engineering Student | Java Backend Developer | AI Systems**

Software Engineering student at **Vellore Institute of Technology**, focused on backend development and AI-powered software systems.

My primary stack is **Java, Spring Boot, PostgreSQL, REST APIs, and AI integrations**. I enjoy designing backend systems, experimenting with LLM applications, and turning ideas into working software.

[Email](mailto:abrahamgracef@gmail.com) · [GitHub](https://github.com/abrahamgracef)

---

## About

- Currently pursuing **M.Tech Integrated Software Engineering** at VIT Vellore
- Focused on **Java backend development and Spring Boot**
- Building applications that integrate **LLMs with traditional backend systems**
- Interested in **software architecture, distributed systems, cloud computing, and open source**
- Currently developing **OmniAssist**, an AI-powered assistant

---

## Technical Skills

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### Backend & Frameworks

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![REST](https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square)

### AI

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

### Database & Tools

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

---

## Featured Projects

### WhatsApp AI Notification Router

**Java 21 · Google Gemini · Multimodal AI**

An AI-powered notification routing system that determines whether incoming WhatsApp messages should **notify the user immediately, be included in a digest, or be muted**.

The system combines multimodal AI reasoning with personalized contextual information rather than evaluating messages in isolation.

**Key engineering areas:**

- Multimodal processing of text, images, and voice notes
- Personalized user and conversation context
- Historical message and interaction retrieval
- Group, business, and sender relationship metadata
- Notification history and notification-fatigue awareness
- Structured confidence scores and explanations
- Evidence-based routing decisions
- Rate-limit retry handling
- Automated CSV prediction generation

**Architecture**

```text
Incoming Message
       |
       v
Dataset Loader
       |
       v
Context Builder
       |
       +---- User Behaviour
       +---- Group Metadata
       +---- Message History
       +---- Notification History
       +---- Interaction Evidence
       |
       v
Prompt Builder
       |
       v
Gemini Multimodal Model
       |
       v
Routing Decision
   /       |       \
Notify   Digest    Mute
