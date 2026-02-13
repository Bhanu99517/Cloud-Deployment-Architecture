# Full-Cloud-Deployment-Architecture
Edge Device (MaixCAM)         ↓ HTTPS (TLS)         ↓ API Gateway (NGINX)         ↓ JWT Auth Service         ↓ Microservices:    - Attendance Service    - Embedding Service    - Dashboard Service         ↓ Vector DB (FAISS / Pinecone) PostgreSQL (Users + Logs) Redis (Cache)         ↓ Kubernetes Cluster         ↓ Monitoring (Prometheus + Grafana)
