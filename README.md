# Architecture

## General
- Microservices
- Monorepo
    - Dev Tools (linting, formatting, prettier)
    - Build Tools 
    - Containerization (Docker, Podman)
    - CI/CD
- Infra as Code (IaC)
    - VPC
    - Firewall
    - Static Site
    - Routing
    - Load Balancer
    - Pulumi
- Web App
    - Deployment
    - CDN
    - Domain
    - Cloudflare
- Security
    - Authentication
    - Authorization/RBAC
    - CSRF
    - DDOS
- Logging and Observability
    - Opentelemetry
- User Management and Data Privacy
    - KYC
    - GDPR
        - Data portability
        - Right to be forgotten
    - User Onboarding and Offboarding
    - Credential Recovery
 
## Specific
- SaaS
    - Segregation
    - Metering
    - Tiering
- Secure and Private AI (Chat, QnA, Summarization, Assistants, RAG, Workflows, Agents)
      - Server Sent Events (SSE)
      - Streaming
- Dating App (social network/graphs)
- Chatting App (websockets)
- Marketplace App
    - Billing (integrate a bank account) (plaid)
    - Payment Processing (get paid) (stripe)
    - Tax and Accounting
- Auth System
    - Sign-up (JWT issuances)
    - Sign-in (JWT verification/Authentication)
    - Hasing and Salting of Password
    - Password Recovery
- Notification System
  
      - Push Api
      - Service Workers
      - Server Sent Events (SSE)
      - Push Services (https://github.com/pushpad/known-push-services/blob/master/whitelist)
- Event Driven Architecture
  
    - Microservice + Pub/Sub IPC System
    - Orchestrator
    - Saga Pattern
        - Roll-back vs Roll-forward (corrective transactions)
    - Event Sourcing
    - CQRS
