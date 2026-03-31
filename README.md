<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Syne&weight=700&size=36&pause=99999&color=FFFFFF&center=true&vCenter=true&width=600&height=80&lines=M.V.M+Eswar+Chandra" alt="name" />

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=400&size=15&pause=99999&color=94A3B8&center=true&vCenter=true&width=600&height=30&lines=AI+Engineer+%E2%80%94+RAG+%2F+LLMs+%2F+Vector+Search+%2F+Full-Stack" alt="title" />

<br/>

[![](https://img.shields.io/badge/LinkedIn-0f172a?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/eswar-mamidi)
[![](https://img.shields.io/badge/Email-0f172a?style=flat&logo=gmail&logoColor=white)](mailto:eswarchandra.016@gmail.com)
[![](https://img.shields.io/badge/GitHub-0f172a?style=flat&logo=github&logoColor=white)](https://github.com/mec-256)
![](https://komarev.com/ghpvc/?username=mec-256&style=flat&color=0f172a&label=profile+views)

</div>

<br/>

---

I build things with LLMs that are meant to ship — not just demo. Most of my focus right now is on **retrieval-augmented generation**: getting hybrid search right, tuning chunking strategies, cross-encoder re-ranking, the parts of the pipeline that actually determine whether your RAG system is useful or frustrating.

Currently a CS undergrad at Mahindra University (2027). I got into AI engineering before it was the obvious move, and I've been building production-grade systems since. Outside of AI — I placed **1st at Shellshock CTF out of 200+ teams**, which is a different kind of problem-solving, but the debugging instinct is the same.

---

<br/>

## ` RAG & LLM Stack `

The tools I reach for when building retrieval and generation pipelines:

| Layer | Tools |
|---|---|
| **Orchestration** | LangChain · Prompt Engineering |
| **LLMs** | Llama 3.3 70B · OpenAI API · Groq API |
| **Retrieval** | pgvector · ChromaDB · BM25 · Cross-encoder re-ranking |
| **Embeddings** | Semantic Search · Dense + Sparse hybrid |
| **Backend** | FastAPI · PostgreSQL · Supabase · Docker · JWT/RBAC |
| **Frontend** | React · Next.js · TypeScript · Vercel |

<br/>

---

## ` Work `

<br/>

### InsightLayer &nbsp;—&nbsp; AI Document Q&A &nbsp; [↗ GitHub](https://github.com/mec-256) &nbsp; [↗ Live](https://github.com/mec-256)

Full-stack RAG system for semantic search across uploaded PDFs and text. The interesting engineering was moving beyond naive cosine similarity — I implemented **hybrid search** (vector + BM25) with **cross-encoder re-ranking**, which pushed retrieval accuracy up 35%. The model layer runs Llama 3.3 70B through Groq for low-latency responses with source citations. Multi-tenant, JWT-authenticated, built to be production-ready from the start.

`Python` `FastAPI` `LangChain` `pgvector` `PostgreSQL` `Groq` `Llama 3.3`

<br/>

### RAG Assistant &nbsp; [↗ Live](https://github.com/mec-256)

An earlier, leaner RAG chatbot — this is where I worked out the chunking strategy and embedding pipeline that I later improved in InsightLayer. OpenAI API + ChromaDB. Retrieval precision up 35% after iterations on the ingestion pipeline.

`Python` `OpenAI API` `ChromaDB`

<br/>

### Student Portal &nbsp; [↗ Live](https://github.com/mec-256)

Full-stack management platform. Next.js with SSR, Supabase, optimized PostgreSQL queries (20% response time reduction). I led the 4-person dev team — sprint planning, architecture decisions, code reviews.

`Next.js` `React` `Supabase` `PostgreSQL` `Vercel`

<br/>

---

## ` Highlights `

<br/>

> **🥇 Shellshock CTF — 1st Place** &nbsp;·&nbsp; Nov 2025
> 
> 200+ teams. Won ₹30,000. Applied reverse engineering, binary exploitation, and debugging under pressure. One of those experiences that changes how you think about systems.

> **👥 Engineering Team Lead** &nbsp;·&nbsp; Jul 2025
> 
> Led a team of 4 devs. Owned sprint planning, technical architecture, and code review process.

> **🎓 Mahindra University** &nbsp;·&nbsp; CGPA 8.0 / 10 &nbsp;·&nbsp; Expected 2027

<br/>

---

## ` Stats `

<br/>

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mec-256&show_icons=true&hide_border=true&bg_color=0d1117&title_color=ffffff&icon_color=94a3b8&text_color=94a3b8&hide=stars" />
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mec-256&layout=compact&hide_border=true&bg_color=0d1117&title_color=ffffff&text_color=94a3b8&langs_count=6" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=mec-256&hide_border=true&background=0d1117&ring=ffffff&fire=94a3b8&currStreakLabel=ffffff&sideLabels=94a3b8&dates=64748b&currStreakNum=ffffff&sideNums=ffffff" height="165" />

</div>

<br/>

---

<div align="center">
  <sub>Open to AI/ML internships and interesting collaboration — <a href="mailto:eswarchandra.016@gmail.com">reach out</a>.</sub>
</div>
