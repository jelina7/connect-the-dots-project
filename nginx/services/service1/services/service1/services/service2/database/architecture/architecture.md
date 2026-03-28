# Architecture Design

This project uses:

- Nginx reverse proxy
- Two backend services
- PostgreSQL database
- Docker Compose orchestration

Traffic Flow:

User → Nginx → Services → Database

Cost Optimization:

- Single container environment
- Minimal resources
- Lightweight images
