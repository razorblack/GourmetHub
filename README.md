# GourmetHub 🍲

**GourmetHub** is a modern, AI-enhanced recipe publishing and discovery platform.  
It combines traditional recipe sharing with intelligent features powered by a locally hosted LLM, offering chefs and food lovers a secure and seamless experience.

---

## 🚀 Features

- **Public Recipes**
  - Browse and filter recipes with keyword search, labels, chef handles, and publish dates.
  - Paginated results with metadata for easy navigation.

- **Auth & Chef Onboarding**
  - Secure sign-up and login with JWT-based authentication.
  - Roles: `user`, `chef`, `admin`.
  - Chef accounts can publish and manage recipes.

- **Recipe Authoring**
  - Create, update, and delete recipes (draft or published).
  - Upload multiple images per recipe with automatic resizing and optimization.
  - Admins can moderate recipes.

- **AI-Powered Features (Local LLM)**
  - Smart tagging and label suggestions for recipes.
  - Content moderation (text and images).
  - Semantic search powered by embeddings.
  - Natural-language query assistance.

- **Worker Service**
  - Runs as a separate Spring Boot app.
  - Handles background tasks like image processing, ingestion, and LLM requests.

---

## 🛠️ Tech Stack

- **Backend (API):** Spring Boot (Java)  
- **Frontend (UI):** React / Next.js (planned)  
- **Database:** PostgreSQL + pgvector  
- **Object Storage:** MinIO (or local filesystem)  
- **Message Broker:** RabbitMQ  
- **Worker:** Spring Boot (background tasks)  
- **AI Service:** Locally hosted LLM in Docker  

---

## ⚙️ Getting Started (Development)

### Prerequisites
- [Docker & Docker Compose](https://docs.docker.com/get-docker/)  
- [Java 17+](https://adoptium.net/)  
- [Node.js 18+](https://nodejs.org/) (for UI)  

### Clone this repo
```bash
git clone https://github.com/your-org/gourmethub.git

```

