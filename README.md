# n8n RAG Local 

A production-ready local setup for building RAG (Retrieval-Augmented Generation) pipelines using **n8n** for workflow automation and **Qdrant** as a vector database.


## 📋 Prerequisites
Before you begin, ensure you have the following installed:
* [Docker Desktop](https://www.docker.com/products/docker-desktop/)
* [Git](https://git-scm.com/)

---

## 🛠️ Step-by-Step Setup

### 1. Clone the Repository
```bash
git clone https://github.com/fransco-go/N8N-RAG-LOCAL.git
cd N8N-RAG-LOCAL
```

### 2. Launch the Stack
``` bash
docker compose up -d
```

### 3. Access the services
Once the containers are running, you can access the dashboards via your browser:
1. n8n: http://localhost:5678
2. Qdrant: http://localhost:6333/dashboard

## 🔄 Importing Workflows

### To use the pre-configured RAG pipeline:

1. Open n8n in your browser.
2. Click on Workflows > Import from File.
3. Select the file located in workflows/rag-pipeline-v1.json.
4. Setup your credentials within the n8n UI.