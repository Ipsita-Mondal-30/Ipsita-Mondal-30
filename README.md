# Hi, I'm Ipsita Mondal

**Full Stack AI Engineer building LLM-powered products.** I like taking a messy real-world workflow (student management, hiring, brand visibility, marketplaces) and turning it into something people actually use, from the database to the UI to the AI layer.

CS student at Bennett University · Worked with 7+ international clients · Winner, Project Showcase 2024 · Winner, Bot Bonanza Ideathon

[LinkedIn](https://www.linkedin.com/in/ipsita-mondal-865912313/) · [Portfolio](https://tech-ips-portfolio.vercel.app/) · [Email](mailto:ipsitaamondal@gmail.com)

---

## Featured projects

### Workpunkt: student management platform (Germany)
Workpunkt is an education and student-management platform based in Germany. I worked on it as a **Full Stack AI Engineer**.

**The problem:** much of the student-management workflow was running through Excel sheets and fragmented processes: applications, documents, counsellor and agent workflows, and student information. The goal was to bring all of it into one centralized platform.

#### Klara: AI consultancy assistant
Klara is an AI consultancy assistant inside Workpunkt that gives students personalised guidance. The interesting part was not connecting an LLM to a chatbot. It was making the AI useful for a student's actual situation by giving it controlled, structured context from the platform.

Instead of treating the LLM as the source of truth, we used it as a **reasoning and communication layer over trusted student and business data**.

**What I built:**
- Full-stack integration of the assistant into the platform
- Structured system prompts and context design
- Controlled context, so the model reasons over the relevant student and business information rather than behaving like a generic chatbot
- Mechanisms to keep responses relevant and reduce hallucinations

---

### Cyted (live as "Strand"): AI visibility platform
**[Live demo](https://cyted-neon.vercel.app/)**

Tells a brand how AI assistants talk about it. Customers now ask ChatGPT or Gemini what to buy, and traditional SEO tools can't show what those models actually recommend. Cyted measures that.

**How it works**

1. **Start an analysis:** enter a company name, website, description, and optionally a list of competitors.
2. **Clean the input:** brand and competitor names are typo-corrected automatically, and five extra competitors are discovered and de-duplicated against what you entered.
3. **Query multiple models:** the same prompts and topics are sent to ChatGPT, Gemini, Claude and Groq, with live web search turned on so answers reflect the current web.
4. **Score visibility:** responses are analysed for how often the brand is mentioned and how often it is recommended, compared with its competitors.
5. **Track and act:** choose the prompts and topics that matter, watch mentions over time, and use the results to decide what to improve.

**What I built:** the multi-model LLM query pipeline, competitor discovery and de-duplication, brand mention and recommendation scoring, the asynchronous analysis workflow (BullMQ and Redis workers), backend APIs, database integration, and the analysis dashboard.

---

### Pensyl: AI writing and orchestration workspace
**[Repository](https://github.com/Ipsita-Mondal-30/pensyl-workspace)**

Modern writing workflows are scattered across Google Docs, Notion and other productivity tools. Pensyl explores something conceptually similar to Cursor, but for writing: the AI isn't just generating text, it orchestrates different tools and actions as part of the workflow.

**What I worked on:** structuring the orchestration layer with LangChain, connecting the LLM to tools, and managing the flow between the model, tool execution and the final output.

---

### Talora: AI-powered HR platform
An HR platform connecting candidates, recruiters and employees, with AI doing the repetitive evaluation work.

- **AI features:** resume parsing, candidate evaluation using Gemini, Cohere and Groq, and AI interview assistance
- **Product features:** role-based authentication, employee management
- **Stack:** Next.js, React, Node.js, Express, MongoDB, PostgreSQL
- **What I built:** the entire project, end to end: role-based authentication and workflows, backend APIs, database models, AI-powered resume and candidate evaluation flows, and the integration of Gemini, Cohere and Groq for different AI tasks.
- **Links:** [Live demo](http://hr-frontend-54b2.vercel.app/)

### Influmojo: influencer marketplace
A marketplace connecting brands and influencers, with payments, messaging and a mobile app.

- **Features:** brand and influencer flows, Razorpay payments, messaging and notifications, AWS S3 storage, mobile app
- **Stack:** React, Node.js, Express, PostgreSQL, Prisma
- **Links:** [Live site](http://influmojo.com/)

---

## Also built

- **Orchestration workflows:** connecting LLMs with different tools and services, exploring how an agent decides what action to take, invokes the right tool, and uses the result to continue the workflow
- **NexaGrow:** SEO-optimised e-commerce site for organic wellness products (Next.js, Tailwind CSS)
- Smaller projects and experiments are in my repositories.

---

## Tech stack

| Area | Tools |
|---|---|
| Languages | TypeScript, JavaScript, Java, C++, SQL |
| Frontend | React, Next.js, React Native, Tailwind CSS |
| Backend | Node.js, Express, Spring Boot |
| Data | PostgreSQL, MongoDB, Prisma, Redis |
| AI / LLMs | OpenAI, Gemini, Claude, Cohere, Groq, LangChain (multi-model API integration, prompt design, live web search) |
| DevOps | Docker, GitHub Actions, AWS, Linux |

---

## Currently

- **Going deeper into LLM application development:** agents, RAG, retrieval, structured outputs, tool/function calling, context engineering, prompt design, and validating model responses
- **Production AI architecture:** queues, Redis, rate limiting, API gateways, caching, retries, observability, worker-based processing, and scalable LLM pipelines
- **Making LLM apps more reliable:** controlled context, retrieval, deterministic business rules, structured validation, fallback strategies, and human-in-the-loop workflows
- **Building Lezi,** a women-focused dating platform. I'm working on the backend architecture with Node.js, Supabase Auth and PostgreSQL, covering authentication, onboarding, profiles, preferences, discovery, likes and matching

---

## Client work

I have worked with **7+ international clients** across **Australia, Germany, Los Angeles (USA), Slovenia and the Philippines**, taking requirements from people in different time zones and turning them into shipped products.

---

## Recognition

- Winner, Project Showcase 2024, Bennett University
- Winner, Bot Bonanza Ideathon
- 190+ DSA problems solved ([Codolio profile](https://codolio.com/profile/ipsitaa_30))

---

## Contact

I'm happy to talk about product, AI and logistics-style workflow problems. Reach me on [LinkedIn](https://www.linkedin.com/in/ipsita-mondal-865912313/) or at ipsitaamondal@gmail.com.
