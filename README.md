# Mehdi Akbari
**Full Stack Developer**

[Email](mailto:mehdi.ak76@hotmail.com) · [LinkedIn](https://www.linkedin.com/in/mehdi-akbari-3697a3241/) · [GitHub](https://github.com/mehdi76sy)

---

## Summary

Full Stack Developer with 3+ years building production SaaS platforms, AI-integrated systems, and cloud infrastructure. Experienced across the entire stack — from architecting AWS VPC and EC2 infrastructure to building complex React frontends with real-time features. Currently leading architecture and development of an AI-powered call screening system and serving as the sole frontend engineer on a multi-tenant recruitment SaaS platform used by government clients.

---

## Work Experience

### Full Stack Developer — XFAANG *(Remote / Hybrid | Jan 2023 – Present)*

Software house delivering production platforms and APIs for startups and private clients.

---

#### Call Screening AI System *(2025 – Present)*

End-to-end AI telephony platform with live call transcription, spam detection, and intelligent routing. Architected and built the full system solo (frontend, backend, infrastructure), leading a mobile developer and collaborating with product and design.

**Architecture & Infrastructure**
- Designed and deployed the full AWS infrastructure: VPC with custom subnets, NAT gateway, route tables, EC2 instances (managed with PM2), Lambda functions (Python, triggered via API Gateway), DynamoDB, CloudWatch logging, and IAM roles
- Built a centralized API layer on EC2, shared across the web dashboard and mobile app, enabling consistent data access and feature parity

**Call Pipeline**
- Incoming call → Twilio Voice → webhook → EC2 API layer → ElevenLabs Scribe v2 for real-time transcription → Gemini LLM for live spam detection → Twilio Studio for routing logic → Lambda for processing → live dashboard update via WebSockets
- Integrated Twilio (Voice API, Studio, SMS, Conference, functions and webhooks), ElevenLabs (AI agent for out-of-reach scenarios, Scribe v2 transcription), and SerwSMS / Zimbra SMTP for fallback communication

**Automation & AI**
- Built an n8n automation pipeline triggered at the end of each call: generates AI-powered call summaries, sends email reports, logs structured data, and runs post-call analytics
- Integrated Gemini for LLM-based live spam detection, with a roadmap to replace with a custom-trained model
- Wrote system-level prompts for the ElevenLabs AI agent (personal assistant per user) and for n8n LLM nodes

**Dashboard**
- Built the full web dashboard in React + TypeScript: live call transcripts via WebSockets, phone number lookup results, spam detection indicators, call routing controls, and post-call report views

**Stack:** React, TypeScript, Python (Lambdas), AWS (EC2, Lambda, DynamoDB, API Gateway, CloudWatch, VPC, IAM), Twilio, ElevenLabs, n8n, Gemini, Node.js

---

#### AI-Powered Clothing Platform *(2025)*

Platform where users photograph clothing items and receive AI-generated descriptions, condition assessments, price estimates, and photorealistic model images (adult/child, appropriate gender) for cross-platform listing.

- Continued development of an existing Next.js frontend, adding Firebase authentication and improving overall architecture
- Integrated Nano Banana (Gemini-based generative image model) for model image generation
- Engineered dynamic prompting strategies for both Gemini (descriptions) and Nano Banana (image generation) to significantly improve output accuracy and consistency
- Implemented gender detection logic to select the appropriate model type automatically

**Stack:** TypeScript, React, Next.js, Firebase, Gemini, Nano Banana

---

#### Wedding Marketplace Platform *(2024 – 2025)*

Frontend team member (team of 3) on a production marketplace connecting wedding service vendors (venues, catering, music, transport, etc.) with couples to build complete wedding packages.

- Diagnosed and replaced a broken global Redux state architecture with SWR, eliminating cascading bugs and improving data consistency
- Implemented frontend UI from Figma designs across vendor listings, booking flows, package builder, availability calendars, and Stripe payment integration
- Collaborated in a structured PR/code review workflow on a shared codebase

**Stack:** TypeScript, React, Next.js, Material UI, SWR, Stripe

---

#### Equity Crowdfunding Platform *(2023 – 2024)*

Production platform for a private client connecting investors and startups.

- Built multi-step authentication flows (registration and login) with full form validation
- Developed reusable React component library and integrated REST APIs across dashboard features
- Wrote unit tests using Jest

**Stack:** TypeScript, React, Next.js, Tailwind CSS, Jest

---


#### ↳ Embedded at Recrout — Frontend Developer *(Nov 2023 – Present)*

*Placed by XFAANG as sole frontend developer on a multi-tenant Applicant Tracking System (ATS) serving government clients and private companies, built on a microservices Python backend. Owning all frontend decisions.*

**Products:**
- Main platform (internal technology demonstrator)
- API-versioned platform (deployed per client, including government clients)
- New client platform (current focus — production-ready)

**Key contributions:**
- Own the entire frontend across three platform variants: dashboards, candidate pipelines, search/filter systems, messaging, analytics, assessments, and team management tooling
- **Messaging system:** Built a full recruiter ↔ candidate messaging system (REST with polling), supporting rich text, file attachments, in-app notifications, and email fallback
- **Team Builder:** Designed and built a feature allowing recruiters to group candidates, compare skill profiles side-by-side with visual graphs and weighted scoring, enabling data-driven hiring decisions
- Revived and productionised a third platform variant that was ~40% hardcoded by a previous team — rewrote it to be fully dynamic and release-ready
- Led a Vite migration initiative to reduce a 12.1 MB bundle (630s build time) caused by accumulated dependencies — improving developer experience and deployment speed
- Integrated OpenAI (via backend endpoint) for automated job description parsing and generation

**Stack:** TypeScript, React, Redux, REST APIs, OpenAI, Python (backend integration)

---

#### Urban Parking Platform *(2023)*

- Built a responsive marketing web dashboard for a European parking booking service
- Delivered mobile app UI designs

**Stack:** TypeScript, React, Tailwind CSS

---

### Frontend Developer — WarsawJS / ConfrontJS *(Feb 2022 – Present)*

Contributor to open-source community platforms for Warsaw's JavaScript developer community (70–100+ monthly attendees, 100+ yearly conference).

- Maintained and improved the WarsawJS website: bug fixes, new sections, and monthly meetup content updates with on-call support
- Rewrote the ConfrontJS conference website from scratch for the yearly Warsaw JS conference
- Supported conference organization for both monthly meetups and the annual event

**Stack:** JavaScript, React (public repositories)

---

### UI/UX Designer — Loogol *(2022 – May 2023)*

- Designed and delivered high-fidelity user interfaces in Figma and Adobe XD

---

## Skills

### Frontend
JavaScript (ES6+), TypeScript, React, Next.js, Redux, SWR, HTML5, CSS3, Tailwind CSS, Material UI, SASS, Responsive Design

### Backend & Infrastructure
Python, Node.js, AWS (EC2, Lambda, DynamoDB, API Gateway, CloudWatch, VPC, IAM, Amplify, S3), REST APIs, PM2, WebSockets

### Integrations & Services
Twilio (Voice, Studio, SMS, Conference), ElevenLabs (Agent, Scribe v2), Firebase / Firestore, OpenAI, Gemini, n8n, Airtable, Stripe, SerwSMS, Zimbra SMTP

### AI & Automation
Prompt engineering (system prompts, LLM nodes), n8n automation pipelines, AI agent integration (ElevenLabs), LLM-based live classification (Gemini), Cursor AI, Gemini CLI

### Tooling & Workflow
Git, GitHub, Bitbucket, PR reviews, CI/CD (AWS auto-deploy on push), Jest, Postman, Figma, Adobe XD

---

## Education

**Karazin University, Ukraine** — Medical Faculty *(2018 – 2022)*
Studies discontinued due to the war in Ukraine after 4 years of coursework.

**Self-taught Software Development** — Poland *(2022 – Present)*
Community-driven and independent learning, applied in production environments.

---

## Languages

- **English** — Fluent
- **Persian** — Native
- **Russian** — Intermediate
- **Polish** — Basic
