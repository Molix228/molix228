# Hi, I'm Oleksandr Mesliuk 👋

I am a **Middle/Middle+ Software Engineer** focused on building scalable APIs, microservices, and robust cloud infrastructure. I thrive on solving complex architectural challenges, optimizing cloud costs, and integrating modern GenAI solutions.

### 🚀 What I'm Currently Building: **Cariff**
I am currently the Lead Architect and Full-Stack Developer for **[Cariff](https://cariff.com)**, a modern automotive marketplace platform. 

The source code is hosted in a private organization as it is a production MVP, but here is a look under the hood at the infrastructure I built:
- **Architecture:** Distributed microservices backend on NestJS with decoupled domain modules, inter-service messaging via Redis Pub/Sub, and centralized configurations via AWS SSM Parameter Store.
- **Performance & Caching:** Engineered an asynchronous view-counter ingestion pipeline leveraging Redis buffer caching to offload direct write pressure from PostgreSQL (Supabase).
- **Frontend & Security:** Next.js (App Router) implemented with Feature-Sliced Design (FSD). The platform is secured with JWT Refresh Token Rotation, CSRF mitigations, and Cloudflare Turnstile bot protection.
- **DevOps:** Fully automated GitHub Actions CI/CD pipelines deploying to AWS Lightsail VPS, with strict dev/prod environment isolation.

### 💡 Professional Highlights
- ☁️ **Cloud FinOps:** Architected an AWS cost-optimization strategy for microservices, reducing monthly cloud infrastructure costs by >90% (from ~$3,000/mo to minimal storage fees) via automated resource hibernation.
- 🤖 **GenAI Integration:** Developed a production-grade AI Assistant using AWS Bedrock (Claude models), leveraging Tool/Function Calling for backend actions and Server-Sent Events (SSE) for sub-second UI response times.
- 🛠 **Highload & Debugging:** During my time at **Bolt**, I resolved database bottlenecks, optimized PostgreSQL query execution, and fixed inter-service communication issues in asynchronous microservices.
- 👨‍🏫 **Mentorship:** Mentored students in full-stack web fundamentals (React, JavaScript) and designed practical, project-based curricula.

### 🛠 Tech Stack
- **Backend & Architecture:** Node.js, NestJS, Microservices, REST/GraphQL/gRPC, Redis, Kafka, CQRS, Event-Driven Patterns.
- **Frontend:** Next.js (App Router & Pages), React.js, Redux Toolkit, WebSockets / SSE.
- **Databases:** PostgreSQL, MySQL, Redis, TypeORM, Prisma.
- **Cloud & DevOps:** AWS (Bedrock, ECS, EC2, RDS, Lightsail, etc.), Azure AD B2C, Docker, GitHub Actions (CI/CD).

### 📫 Let's Connect
- **Email:** alex.mesanya@gmail.com
- **Education:** Bachelor's Degree in Systems Development (EU Diploma), University of Tartu
