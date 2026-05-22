# Conner Defeo
**Software Engineer | Full-Stack | Cloud & DevOps | AI Systems**

BS Software Engineering @ RIT (GPA 3.83)  

---

## Experience 🐳

### Computer Systems Intern
**Linde** · May 2026 – Present

### Software Engineer Team Lead  
**Accessible Learning Labs** · Jan 2026 – May 2026
- Lead a team of 3 software engineers using Agile methodologies to design and implement educational labs on AI bias and hallucinations
- Architected and developed full-stack features using React, Node.js, and PostgreSQL for deployment across 9 academic institutions
- Coordinated sprint planning, task breakdown, and code reviews to ensure work was done fast while maintaining high quality

### Software Engineer Co-op  
**Rochester Regional Health** · Aug 2025 – Jan 2026  
- Implemented CI/CD automation (**GitHub Actions, RenovateBot, NUnit**), cutting maintenance effort by **15–20%**  
- Refactored and optimized **30+ .NET services**, reducing backend execution time by **60%+** on critical paths  
- Consistently delivered sprint work **20–40% ahead of estimates**

### Software Engineer  
**Accessible Learning Labs** · Jan 2025 – May 2025  
- Built a research web platform (**React, Node.js, PostgreSQL**) used by **600+ participants** and adopted for recurring studies  
- Presented at **CCNSE** on the impact of accessible software in education and research  

---

## Projects 🐟

### **PeakFlow** — [peakflowaiautomations.com](https://peakflowaiautomations.com)  
**React (TS) · FastAPI · AWS · Terraform · DynamoDB · SES · EC2 · xAI Grok · Twilio**
Built a document-aware AI pipeline that **systematically parses, chunks, and indexes SEC 10-Ks** to prevent LLM context loss.  
- Streaming conversational model handles natural speech in real time while a parallel background model extracts structured appointment data (name, address, job type, date) to DynamoDB
- Per-turn DynamoDB writes + xAI store_messages + previous_response_id allow conversations to resume seamlessly after dropped WebSockets
- All client-specific behavior (prompts, voices, calendar IDs, greetings) lives in configuration — the core WebSocket handler stays static across clients
- Deployed on EC2 behind nginx (SSL via Certbot) with systemd for persistence and Terraform + S3-backed remote state for IaC

### **FinDiff** — [findiff.com](https://findiff.com)  
**React (TS) · Python · AWS · Terraform · DynamoDB · S3**  
Built a document-aware AI pipeline that **systematically parses, chunks, and indexes SEC 10-Ks** to prevent LLM context loss.  
- AI-generated summaries are created **per section** and cached in **S3** for reuse  
- Subsequent queries refetch pre-processed data instead of re-parsing raw filings  
- Improves accuracy, latency, and cost vs naïve “upload PDF to LLM” approaches  

### **TrackMe** - Mobile Application
**React Native · Expo · Python · AWS · Terraform · PostgreSQL · Docker**  
Mobile app built for a track coach to collect **previously unrecorded athlete workout data**.  
- Replaced email and paper logs with structured in-app submissions  
- Centralized athlete times and metadata into a single coach dashboard  
- Increased recorded practice data by **~600%**. Grew to **20 DAUs**

### **Kaizen Habits**
**React (TS) · C# ASP.NET · AWS EC2 · Docker**  
End-to-end habit tracking web app focused on consistency and long-term progress.  
- Users can create, edit, and delete habits with **streak and historical progress tracking**  
- Social features for adding friends and comparing accountability  
- AI-generated habit recommendations based on user behavior  
- Containerized and deployed on **EC2**, owning backend, frontend, and infrastructure

---

## Skills 🦈

**Languages**  
Python, C#, JavaScript, TypeScript, HTML, CSS  

**Frameworks**  
React, React Native, Expo, Flask, ASP.NET  

**Cloud / Infra / Data**  
AWS, Docker, Terraform, PostgreSQL, DynamoDB, MongoDB, Node.js  

---

## Connect
- LinkedIn: [linkedin.com/in/conner-jack-defeo](https://linkedin.com/in/conner-jack-defeo)
- Portfolio: [connerdefeo.com](https://connerdefeo.com) 
