# Priyanshu Kumar

Final-year Computer Science undergraduate at IIITDM Kurnool (B.Tech, 2027). I research open-vocabulary semantic segmentation for remote sensing imagery and build backend and AI/ML systems. Currently looking for backend or AI/ML engineering roles.

[LinkedIn](https://www.linkedin.com/in/priyanshu-kumar-982b5a354/) · [priyanshu.kr.cs@gmail.com](mailto:priyanshu.kr.cs@gmail.com)

## Experience

**AI & DS Engineer Intern** · Rusborn Private Limited · Remote · May–Aug 2026

- Built an end-to-end AI lead-generation agent in Python that automates prospect discovery, web data extraction, enrichment and qualification.
- Implemented the qualification layer on LLM APIs, parsing unstructured company data into structured fields and scoring leads.
- Deployed the MVP as a REST API with OpenAPI docs on Render and a React frontend on Vercel: [Frontend](https://ai-lead-generation-mvp.vercel.app/) · [API docs](https://ai-lead-generation-mvp.onrender.com/docs)
- Developed and evaluated ML models for industrial-training use cases.

## Research

**FreeTraining-OVSS** · Undergraduate research, IIITDM Kurnool · Ongoing · [GitHub](https://github.com/FasterThanAi/FreeTraining-OVSS)

Training-free open-vocabulary semantic segmentation of remote sensing imagery, using PyTorch, SAM 3, DINOv3 and mmsegmentation.

- Reproduced the SegEarth-OV3 baseline on the LoveDA validation set (1,669 images), matching the published 47.38 mIoU.
- Diagnosed its dominant failure mode: at the paper's operating threshold, 29.68% of real land-cover pixels are discarded as background. Relaxing the threshold recovers two-thirds of them at a cost of 5.54 mIoU.
- Now validating a semantic co-occurrence prior over SAM 3 region proposals to recover those pixels, formulated as energy minimisation with DINOv3 feature-similarity and PMI-based semantic terms. Measured 1.3–1.7 bits of class-pair signal against a 0.004-bit noise floor.

## Projects

| Project | Description | Stack |
| --- | --- | --- |
| **AI-Powered Blogging Platform**<br>[Live demo](https://my-blog-page-omega.vercel.app/) · [Code](https://github.com/FasterThanAi/My-Blog-Page) | AI-assisted editor on the Gemini API with streaming generation, summarisation, auto-tagging and ghost-text autocompletion over Server-Sent Events. Multi-tenant Supabase backend with role-based access control and Row-Level Security. | Next.js, TypeScript, Supabase, Gemini API, TipTap |
| **AI Screener**<br>[Code](https://github.com/FasterThanAi/AI-Screener-Project-Backend-) | Recruitment backend that matches resumes to roles using Sentence-Transformers embeddings and cosine similarity, runs a Gemini-powered AI interview with an auto-generated assessment report, and sends magic-link notifications to top candidates. | Node.js, Express, FastAPI, Sentence-Transformers, Gemini |
| **Hostel Management System**<br>[Live demo](https://hostelmanagementsystem-rho.vercel.app/) · [Code](https://github.com/Vermadeepakd1/hostel-management-frontend) | Replaces manual hostel paperwork with a central dashboard for room allocation and student records, backed by REST APIs. | React, Tailwind CSS, Node.js, MySQL |

## Skills

- **Languages:** Python, C++, C, JavaScript, TypeScript, SQL
- **AI/ML:** PyTorch, scikit-learn, NumPy, pandas, OpenCV, mmsegmentation, SAM 3, CLIP, DINOv3, Gemini API, RAG
- **Backend:** FastAPI, Node.js, Express.js, REST APIs, Server-Sent Events, authentication and RBAC
- **Frontend:** React, Next.js, Tailwind CSS
- **Databases:** PostgreSQL, MySQL, MongoDB, Supabase
- **Tools:** Git, Docker, Linux, Postman, Vercel, Render

## Achievements

- 4th place out of 50+ teams, GDG Solasta Hackathon 2025
- 4th place in two BitSquad competitive programming contests, IIITDM Kurnool
- LeetCode rating 1663 · CodeChef 2★ (1450)
- Qualified GATE 2026 (CS) as a third-year student: AIR 13,875 of 211,020 candidates ([scorecard](https://drive.google.com/file/d/1yZuSO0jcR5st0aRNS1TGybNOXKUmRGL0/view?usp=share_link))
