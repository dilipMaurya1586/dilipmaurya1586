<div align="center">

# 👋 Hi, I'm Dilip Maurya

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1200&color=00D9FF&center=true&vCenter=true&width=750&lines=Java+Full+Stack+Developer;Spring+Boot+%7C+Microservices;Kafka+%7C+Docker+%7C+Kubernetes;AI+Integration+%7C+Cloud+Native" alt="Typing SVG" />

<br/>

**Java Full Stack Developer | Backend & Microservices | Cloud-Native Development**

<br/>

<a href="https://dilipmauryaportfolio.vercel.app/">
<img src="https://img.shields.io/badge/🌐_Portfolio-Visit-00D9FF?style=for-the-badge&labelColor=0D1117" />
</a>

<a href="https://www.linkedin.com/in/dilip-maurya-9061a0306">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
</a>

<a href="mailto:mauryadilip.work@gmail.com">
<img src="https://img.shields.io/badge/Gmail-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
</a>

<a href="https://leetcode.com/u/dilip_143/">
<img src="https://img.shields.io/badge/LeetCode-150%2B_Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=dilipmaurya1586&style=for-the-badge&color=00D9FF&label=PROFILE+VIEWS" />

</div>

---

## 👨‍💻 About Me

I'm a **Java Full Stack Developer** focused on building scalable backend systems and modern full-stack applications.

My primary focus is **Spring Boot, Microservices, REST APIs, Kafka, Docker, Kubernetes and AI integration**, with strong experience in React.js and JavaScript-based full-stack development.

```yaml
Name: Dilip Maurya
Role: Java Full Stack Developer
Location: Pune, Maharashtra 🇮🇳
Education: B.E. Computer Engineering — 2026
Experience: Web Development Intern — Elite Softwares
DSA: 150+ LeetCode Problems

Currently Exploring:
  - Spring Boot & Microservices
  - Apache Kafka & Event-Driven Architecture
  - Docker & Kubernetes
  - CI/CD & Cloud-Native Systems
  - Spring AI & LLM Integration

Open To:
  - Java Full Stack Developer
  - Backend Developer
  - Spring Boot Developer
```

---

# 🚀 Featured Project

<div align="center">

## 💰 SplitSettle

### AI-Powered Group Expense Sharing & Settlement Platform

**A production-oriented microservices application designed to simplify group expenses, debt calculation and settlements.**

<br/>

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white&labelColor=0D1117" />

<br/>

<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=0D1117" />

<br/><br/>

<a href="YOUR_SPLITSETTLE_GITHUB_LINK">
<img src="https://img.shields.io/badge/📂_Source_Code-View_on_GitHub-00D9FF?style=for-the-badge&labelColor=0D1117" />
</a>

<a href="YOUR_SPLITSETTLE_LIVE_LINK">
<img src="https://img.shields.io/badge/🚀_Live_Demo-Open_App-00D9FF?style=for-the-badge&labelColor=0D1117" />
</a>

</div>

### 🏗️ What Makes SplitSettle Special

- **8 independent microservices** built around clear business responsibilities.
- **Eureka Service Discovery** for dynamic service registration and discovery.
- **Spring Cloud Gateway** as the centralized API entry point.
- **Apache Kafka** for asynchronous event-driven communication.
- **Spring AI + Groq** for converting natural-language expenses into structured data.
- **Debt simplification algorithm** to minimize the number of settlement transactions.
- **JWT-based authentication** securing the application.
- **PostgreSQL on Neon** for persistent relational data.
- **Docker + Kubernetes** for containerization and orchestration.
- **GitHub Actions** for automated CI/CD.
- **UptimeRobot** for application monitoring.

### 🔄 System Flow

```text
                    ┌─────────────────────┐
                    │      React 19       │
                    │      Frontend       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   API Gateway       │
                    │ Spring Cloud        │
                    │    Gateway           │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
        ┌──────────┐     ┌──────────┐     ┌──────────┐
        │  User    │     │  Group   │     │ Expense  │
        │ Service  │     │ Service  │     │ Service  │
        └────┬─────┘     └────┬─────┘     └────┬─────┘
             │                │                │
             └────────────────┼────────────────┘
                              │
                              ▼
                    ┌─────────────────────┐
                    │       Kafka         │
                    │ Async Communication │
                    └──────────┬──────────┘
                               │
                ┌──────────────┼──────────────┐
                ▼              ▼              ▼
         ┌────────────┐ ┌────────────┐ ┌────────────┐
         │ Settlement │ │Notification│ │ AI Service │
         │  Service   │ │  Service   │ │ Spring AI  │
         └────────────┘ └────────────┘ └──────┬─────┘
                                              │
                                              ▼
                                         ┌─────────┐
                                         │ Groq LLM│
                                         └─────────┘

              Eureka → Service Discovery
              PostgreSQL → Data Persistence
              Docker → Containerization
              Kubernetes → Orchestration
```

---

# 🧠 Technical Skills

## ☕ Java & Backend

<p>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
</p>

<p>
<img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/REST_APIs-007ACC?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white&labelColor=0D1117" />
</p>

---

## 🧩 Microservices & Distributed Systems

<p>
<img src="https://img.shields.io/badge/Microservices-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Eureka_Service_Discovery-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white&labelColor=0D1117" />
</p>

<p>
<img src="https://img.shields.io/badge/Event--Driven_Architecture-00D9FF?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Async_Communication-00D9FF?style=for-the-badge&labelColor=0D1117" />
</p>

---

## 🤖 AI & LLM Integration

<p>
<img src="https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/LLM_Integration-8A2BE2?style=for-the-badge&labelColor=0D1117" />
</p>

<p>

<code>Natural Language Processing</code>
&nbsp;
<code>Prompt Engineering</code>
&nbsp;
<code>Structured Output</code>

</p>

---

## ☁️ DevOps & Cloud Native

<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/CI%2FCD-F05032?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=0D1117" />
</p>

<p>
<img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Cloud--Native-00D9FF?style=for-the-badge&labelColor=0D1117" />
</p>

---

## 🎨 Frontend

<p>
<img src="https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white&labelColor=0D1117" />
</p>

---

## 🌐 JavaScript & MERN

<p>
<img src="https://img.shields.io/badge/JavaScript_ES6%2B-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white&labelColor=0D1117" />
</p>

---

## 🗄️ Databases

<p>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white&labelColor=0D1117" />
</p>

---
<!-- <p>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=0D1117" />
</p> -->
## 🛠️ Tools & Development Environment

<div align="center">

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=0D1117" />

<br/>

<img src="https://img.shields.io/badge/DBeaver-382923?style=for-the-badge&logo=dbeaver&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black&labelColor=0D1117" />

</div>

---
<!-- <div align="center">

<img src="https://img.shields.io/badge/150%2B-LeetCode_Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117" />

<br/><br/>

`Arrays` · `Hashing` · `Linked Lists` · `Stacks` · `Queues`

`Binary Search` · `Trees` · `Recursion` · `Dynamic Programming`

<br/><br/>

<a href="https://leetcode.com/u/dilip_143/">
<img src="https://img.shields.io/badge/View_LeetCode_Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117" />
</a>

</div> -->
# 🧠 Data Structures & Algorithms

<div align="center">

<a href="https://leetcode.com/u/dilip_143/">
<img src="https://img.shields.io/badge/LeetCode-150%2B_Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117" />
</a>

<br/><br/>

### 📚 Core Data Structures

<img src="https://img.shields.io/badge/Arrays-00D9FF?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Strings-00D9FF?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Linked_Lists-00D9FF?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Stacks_&_Queues-00D9FF?style=for-the-badge&labelColor=0D1117" />

<br/>

<img src="https://img.shields.io/badge/HashMap_&_HashSet-00D9FF?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Trees-00D9FF?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Binary_Trees-00D9FF?style=for-the-badge&labelColor=0D1117" />

<br/><br/>

### ⚡ Algorithms & Problem Solving

<img src="https://img.shields.io/badge/Binary_Search-6DB33F?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Sliding_Window-6DB33F?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Two_Pointers-6DB33F?style=for-the-badge&labelColor=0D1117" />

<br/>

<img src="https://img.shields.io/badge/Recursion-6DB33F?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Backtracking-6DB33F?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Tree_Traversal-6DB33F?style=for-the-badge&labelColor=0D1117" />

<br/>

<img src="https://img.shields.io/badge/Greedy-6DB33F?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Dynamic_Programming-6DB33F?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Sorting_&_Searching-6DB33F?style=for-the-badge&labelColor=0D1117" />

<br/><br/>

### 🎯 Problem Solving Focus

`Time & Space Complexity` · `Optimization` · `Pattern Recognition`

<br/>

<a href="https://leetcode.com/u/dilip_143/">
<img src="https://img.shields.io/badge/→_Explore_My_LeetCode_Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117" />
</a>

</div>

---

# 🎓 Education

**Bachelor of Engineering — Computer Engineering**

Alard College of Engineering & Management, Pune  
Savitribai Phule Pune University

`Graduated: June 2026` · `CGPA: 6.98 / 10`

<br/>

**Higher Secondary Certificate — Science**

Maharashtra State Board · `2021` · `76.17%`

---

# 🏅 Certifications & Learning

<div align="center">

### 🥇 Spring Boot • Microservices • DevOps • AI

<img src="https://img.shields.io/badge/Coding_Shuttle-Spring_Boot_0_to_100-6DB33F?style=for-the-badge&logo=springboot&logoColor=white&labelColor=0D1117" />

<br/><br/>

**Spring Boot Microservices, Apache Kafka, Docker, Kubernetes, CI/CD & Spring AI**

<br/>

`Coding Shuttle` · `March 2026`

<br/><br/>

<img src="https://img.shields.io/badge/✓_Spring_Boot-✓_Microservices-00D9FF?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/✓_Kafka-✓_Docker-00D9FF?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/✓_Kubernetes-✓_Spring_AI-00D9FF?style=for-the-badge&labelColor=0D1117" />

<br/><br/><br/>

### 🥈 Java DSA • MERN Stack Development

<img src="https://img.shields.io/badge/Apna_College-Java_DSA_%26_MERN-F7DF1E?style=for-the-badge&logo=java&logoColor=black&labelColor=0D1117" />

<br/><br/>

**Java Data Structures & Algorithms + MERN Stack Web Development**

<br/>

`Apna College` · `2024 – 2025`

<br/><br/>

<img src="https://img.shields.io/badge/✓_Java_DSA-✓_Problem_Solving-FFA116?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/✓_React.js-✓_Node.js-FFA116?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/✓_MongoDB-✓_Express.js-FFA116?style=for-the-badge&labelColor=0D1117" />

</div>

---

# 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=dilipmaurya1586&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=C9D1D9" width="48%" />

<img src="https://nirzak-streak-stats.vercel.app/?user=dilipmaurya1586&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=FF6B35&currStreakLabel=00D9FF" width="48%" />

</div>

<br/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dilipmaurya1586&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9&langs_count=8" width="40%" />

</div>

---

# 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=dilipmaurya1586&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=6" />

</div>

---

# 📈 Contribution Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dilipmaurya1586&bg_color=0D1117&color=00D9FF&line=00D9FF&point=FFFFFF&area=true&hide_border=true" width="95%" />

</div>

---

# 🐍 Contribution Snake

<div align="center">

<img src="https://profile-readme-generator.com/assets/snake.svg" alt="Contribution Snake Animation" />

</div>

---

# 📫 Connect With Me

<div align="center">

<a href="mailto:mauryadilip.work@gmail.com">
<img src="https://img.shields.io/badge/Email-mauryadilip.work%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
</a>

<a href="https://www.linkedin.com/in/dilip-maurya-9061a0306">
<img src="https://img.shields.io/badge/LinkedIn-Dilip_Maurya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
</a>

<a href="https://dilipmauryaportfolio.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-Visit-00D9FF?style=for-the-badge&logo=vercel&logoColor=black&labelColor=0D1117" />
</a>

<br/><br/>

<i>Building scalable systems • Solving problems • Learning continuously 🚀</i>

</div>





















<!-- <div align="center">

<h1>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=30&pause=1200&color=00D9FF&center=true&vCenter=true&width=750&lines=Hi+there%2C+I'm+Dilip+Maurya+%F0%9F%91%8B;Java+Full+Stack+Developer;Spring+Boot+%7C+Microservices+%7C+Kafka;Cloud+Native+%7C+DevOps+%7C+AI+Integration" alt="Typing SVG" />
</h1>

<p>
  <strong>Java Full Stack Developer focused on Spring Boot, Microservices, Cloud-Native Systems & AI Integration</strong>
</p>

<br/>

<p>
  <a href="https://dilipmauryaportfolio.vercel.app/">
    <img src="https://img.shields.io/badge/🌐_Portfolio-Visit_Now-00D9FF?style=for-the-badge&labelColor=0D1117" />
  </a>
  <a href="https://www.linkedin.com/in/dilip-maurya-9061a0306">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
  </a>
  <a href="mailto:mauryadilip.work@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
  </a>
  <a href="https://leetcode.com/u/dilip_143/">
    <img src="https://img.shields.io/badge/LeetCode-150%2B_Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117" />
  </a>
</p>

<br/>

<img src="https://komarev.com/ghpvc/?username=dilipmaurya1586&style=for-the-badge&color=00D9FF&label=PROFILE+VIEWS" />

</div>

---

## 👨‍💻 About Me

I'm a **Java Full Stack Developer** with hands-on experience building backend systems and full-stack applications using **Spring Boot, Microservices, REST APIs, React.js, Kafka, Docker, and Kubernetes**.

My primary focus is backend and distributed-system development, with a strong interest in **cloud-native architecture, asynchronous communication, and AI-powered applications**.

### 🚀 Currently Focused On

- 🔭 Building and improving **production-style Java Microservices applications**
- 🌱 Deepening expertise in **Spring Boot, Spring Cloud, Kafka, Docker & Kubernetes**
- 🤖 Exploring **Spring AI and LLM integrations**
- 🧩 Strengthening **DSA & problem-solving skills — 150+ LeetCode problems**
- ☁️ Learning more about **Cloud-Native Architecture & CI/CD**

### 🎯 Career Focus

**Java Full Stack Developer · Backend Developer · Spring Boot Developer**

---

# ⭐ Featured Project

<div align="center">

## 💰 SplitSettle

### Group Expense Sharing & Settlement Platform

**A microservices-based application for managing group expenses, splitting bills, simplifying debts, and automating settlements.**

<br/>

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=0D1117" />

<br/><br/>

<a href="YOUR_SPLITSETTLE_GITHUB_LINK">
  <img src="https://img.shields.io/badge/📂_GitHub-View_Project-00D9FF?style=for-the-badge&labelColor=0D1117" />
</a>

<a href="YOUR_SPLITSETTLE_LIVE_LINK">
  <img src="https://img.shields.io/badge/🚀_Live_Demo-Open_App-00D9FF?style=for-the-badge&labelColor=0D1117" />
</a>

</div>

### 🏗️ Architecture

```text
                         ┌──────────────────────┐
                         │      React 19        │
                         │   Frontend Client    │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │   API Gateway        │
                         │ Spring Cloud Gateway │
                         └──────────┬───────────┘
                                    │
              ┌─────────────────────┼─────────────────────┐
              │                     │                     │
              ▼                     ▼                     ▼
       ┌────────────┐        ┌────────────┐        ┌────────────┐
       │   User     │        │   Group    │        │  Expense   │
       │  Service   │        │  Service   │        │  Service   │
       └────────────┘        └────────────┘        └────────────┘
              │                     │                     │
              └─────────────────────┼─────────────────────┘
                                    │
                                    ▼
                           ┌────────────────┐
                           │     Kafka      │
                           │ Async Messaging│
                           └───────┬────────┘
                                   │
                    ┌──────────────┼──────────────┐
                    ▼              ▼              ▼
             ┌────────────┐ ┌────────────┐ ┌────────────┐
             │ Settlement │ │Notification│ │ AI Service │
             │  Service   │ │  Service   │ │Spring AI   │
             └────────────┘ └────────────┘ └─────┬──────┘
                                                 │
                                                 ▼
                                           ┌───────────┐
                                           │ Groq LLM  │
                                           └───────────┘

                    Eureka → Service Discovery
                    PostgreSQL → Persistent Storage
                    Docker → Containerization
                    Kubernetes → Orchestration
```

### 🔥 Key Features

- **8 independent services** — User, Group, Expense, Settlement, Notification, AI, Eureka Server & API Gateway
- **Service Discovery** using Eureka
- **API Routing** through Spring Cloud Gateway
- **Asynchronous communication** using Apache Kafka hosted on Aiven
- **AI-powered expense parsing** using Spring AI + Groq LLM
- Converts natural-language expenses into structured transaction data
- **Debt simplification algorithm** to minimize settlement transactions
- **JWT-based authentication** across services
- PostgreSQL database hosted on **Neon**
- Containerized using **Docker**
- Orchestrated using **Kubernetes**
- **GitHub Actions CI/CD** pipeline
- Application monitoring with **UptimeRobot**

---

# 💻 Other Projects

## 🏨 Hotel Booking Platform — Airbnb Clone

**Java · Spring Boot · Spring Security · PostgreSQL · JWT · React.js · Maven**

- Built a full-stack hotel booking platform with separate **Admin and User roles**.
- Implemented property, room, amenity and policy management for administrators.
- Added search by **city, date range, star rating and price**.
- Implemented **Spring Security + JWT authentication** with role-based authorization.
- Added server-side **date-overlap validation** to prevent conflicting room bookings.
- Built frontend features including search filters, price sorting, image carousel, profile and booking history.
- Deployed frontend using **Vercel**.

<br/>

<div align="center">
  <a href="YOUR_HOTEL_BOOKING_GITHUB_LINK">
    <img src="https://img.shields.io/badge/📂_GitHub-View_Project-00D9FF?style=for-the-badge&labelColor=0D1117" />
  </a>
  <a href="YOUR_HOTEL_BOOKING_LIVE_LINK">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Open_App-00D9FF?style=for-the-badge&labelColor=0D1117" />
  </a>
</div>

---

## 🗳️ Voting Management System

**MongoDB · Express.js · React.js · Node.js · JWT · Tailwind CSS · SendGrid · Multer**

- Built a full-stack voting platform with **Admin and Voter roles**.
- Implemented JWT authentication and **bcrypt password hashing**.
- Added **email OTP verification** using SendGrid.
- Implemented Aadhaar document upload using Multer with **18+ age validation**.
- Developed an admin dashboard for election creation and candidate management.
- Added vote tracking and automated result declaration.
- Secured routes with JWT middleware and implemented protection against duplicate voting.

<br/>

<div align="center">
  <a href="YOUR_VOTING_GITHUB_LINK">
    <img src="https://img.shields.io/badge/📂_GitHub-View_Project-00D9FF?style=for-the-badge&labelColor=0D1117" />
  </a>
  <a href="YOUR_VOTING_LIVE_LINK">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Open_App-00D9FF?style=for-the-badge&labelColor=0D1117" />
  </a>
</div>

---

# 🧑‍💼 Internship Experience

### Web Development Intern — Elite Softwares, Pune
**Dec 2024 – Mar 2025**

- Built **10+ REST APIs using Python and Django** for a real-world Hotel Booking Application, covering room search, booking management, cancellation and user authentication.
- Designed **PostgreSQL database schemas** with input validation and error handling.
- Deployed the application to production by configuring environment variables and domain setup.
- Resolved post-deployment server issues and tested APIs using **Postman**.

---

# 🛠️ Technical Skills

### ☕ Java & Backend

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/REST_APIs-007ACC?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white&labelColor=0D1117" />
</p>

### 🧩 Microservices & Messaging

<p>
  <img src="https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Eureka_Service_Discovery-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white&labelColor=0D1117" />
</p>

### 🤖 AI & LLM Integration

<p>
  <img src="https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/LLM_Integration-412991?style=for-the-badge&labelColor=0D1117" />
</p>

### ☁️ DevOps & Cloud Native

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0D1117" />
</p>

### 🎨 Frontend

<p>
  <img src="https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white&labelColor=0D1117" />
</p>

### 🌐 MERN & Additional Backend

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white&labelColor=0D1117" />
</p>

### 🗄️ Databases

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white&labelColor=0D1117" />
</p>

### 🔧 Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=0D1117" />
</p>

---

# 🧠 DSA & Problem Solving

<div align="center">

### 150+ LeetCode Problems Solved

<br/>

<img src="https://img.shields.io/badge/Arrays-4CAF50?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Hashing-673AB7?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Linked_Lists-9C27B0?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Stacks_%26_Queues-FF5722?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Trees-8BC34A?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Binary_Search-2196F3?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Dynamic_Programming-00BCD4?style=for-the-badge&labelColor=0D1117" />

<br/><br/>

<a href="https://leetcode.com/u/dilip_143/">
  <img src="https://img.shields.io/badge/🧩_View_LeetCode_Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117" />
</a>

</div>

---

# 🎓 Education

### Bachelor of Engineering — Computer Engineering
**Alard College of Engineering & Management, Pune**  
Savitribai Phule Pune University  
**Graduated: June 2026 · CGPA: 6.98/10**

### Higher Secondary Certificate — Science
**Maharashtra State Board · 2021 · 76.17%**

---

# 🏆 Certifications

<div align="center">

| Certification | Platform | Date |
|---|---|---|
| 🎖️ Spring Boot Microservices, Apache Kafka, Docker, Kubernetes, CI/CD & Spring AI | Coding Shuttle | March 2026 |
| 🎖️ Java DSA & MERN Stack Web Development | Apna College | 2024–2025 |

</div>

---

# 📊 GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=dilipmaurya1586&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=C9D1D9" width="49%" />

<img src="https://nirzak-streak-stats.vercel.app/?user=dilipmaurya1586&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=FF6B35&currStreakLabel=00D9FF" width="49%" />

</div>

<br/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dilipmaurya1586&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9&langs_count=8" width="42%" />

</div>

---

# 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=dilipmaurya1586&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=6" />

</div>

---

# 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dilipmaurya1586&bg_color=0D1117&color=00D9FF&line=00D9FF&point=FFFFFF&area=true&hide_border=true" width="95%" />

</div>

---

# 🐍 Contribution Snake

<div align="center">

<img src="https://profile-readme-generator.com/assets/snake.svg" alt="Contribution Snake Animation" />

</div>

---

# 💬 Let's Connect

<div align="center">

**Interested in Java, Spring Boot, Microservices, DSA or Backend Development?**

<br/>

<a href="mailto:mauryadilip.work@gmail.com">
  <img src="https://img.shields.io/badge/Email-mauryadilip.work%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
</a>

<a href="https://www.linkedin.com/in/dilip-maurya-9061a0306">
  <img src="https://img.shields.io/badge/LinkedIn-Dilip_Maurya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
</a>

<a href="https://dilipmauryaportfolio.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-Visit-00D9FF?style=for-the-badge&logo=vercel&logoColor=black&labelColor=0D1117" />
</a>

<a href="https://github.com/dilipMaurya1586">
  <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=dilipmaurya1586&style=flat-square&color=00D9FF&label=Profile+Views" />

<br/><br/>

<i>— Building scalable systems, solving problems, and learning every day. 🚀</i>

</div> -->





<!-- <div align="center">

```
██████╗ ██╗██╗     ██╗██████╗     ███╗   ███╗ █████╗ ██╗   ██╗██████╗ ██╗   ██╗ █████╗
██╔══██╗██║██║     ██║██╔══██╗    ████╗ ████║██╔══██╗██║   ██║██╔══██╗╚██╗ ██╔╝██╔══██╗
██║  ██║██║██║     ██║██████╔╝    ██╔████╔██║███████║██║   ██║██████╔╝ ╚████╔╝ ███████║
██║  ██║██║██║     ██║██╔═══╝     ██║╚██╔╝██║██╔══██║██║   ██║██╔══██╗  ╚██╔╝  ██╔══██║
██████╔╝██║███████╗██║██║         ██║ ╚═╝ ██║██║  ██║╚██████╔╝██║  ██║   ██║   ██║  ██║
╚═════╝ ╚═╝╚══════╝╚═╝╚═╝         ╚═╝     ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝
```

<h1>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+Dilip+Maurya+%F0%9F%91%8B;Java+Full+Stack+Developer;Spring+Boot+%7C+Microservices;Cloud+Native+%7C+DevOps+%7C+AI+Ready" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://dilip-maurya-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/🌐_Portfolio-Visit_Now-00D9FF?style=for-the-badge&labelColor=0D1117" />
  </a>
  <a href="https://www.linkedin.com/in/dilip-maurya-9061a0306">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
  </a>
  <a href="mailto:mauryadilip.work@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Hire_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
  </a>
  <a href="https://leetcode.com/u/dilip_143/">
    <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117" />
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=dilipmaurya1586&style=for-the-badge&color=00D9FF&label=PROFILE+VIEWS" />

</div>

---

## 🧑‍💻 About Me

```yaml
name: Dilip Maurya
role: Java Full Stack Developer
education: B.E. Computer Engineering, Pune (2026)
experience: Ex-Intern @ Elite Softwares
location: Pune, Maharashtra 🇮🇳
status: 🟢 Open to Work

current_focus:
  - 🔭 Building: Secure Online Banking Application (Java Full Stack)
  - 🌱 Mastering: Spring Boot · Docker · Kubernetes · Kafka · CI/CD
  - ☁️  Exploring: Cloud-Native Architecture & AI Integration

strengths:
  - Java Backend: Spring Boot · Microservices · Spring Security · Hibernate ·
  - MERN Stack Backend: Node.js · Express.js · REST API Development · JWT Authentication · MVC Architecture
  - DevOps: Docker · Kubernetes · Kafka · CI/CD Pipelines
  - Frontend: React.js · TailwindCSS · REST APIs
  - Databases: PostgreSQL · MongoDB · MySQL
  - DSA: Competitive Programmer on LeetCode
  - Tools: Git · GitHub · Postman · Vercel ·Render · VS Code · Chrome DevTools · NPM

certifications:
  - "✅ Spring Boot 0 to 100 Cohort 4.0 [AI + DevOps] — Coding Shuttle (March 2026)"
  - "✅ Data Structures and Algorithms with Java & MERN Stack  Developer – Apna College (Dec 2024) & (May 2025)"
```

---

## 🏆 Certifications

<div align="center">

| Certificate | Platform | Date |
|---|---|---|
| 🎖️ **Spring Boot 0 to 100 Cohort 4.0 [AI + DevOps]** | Coding Shuttle | March 16, 2026 |
| 🎖️ **Data Structures and Algorithms with Java & MERN Stack  Developer** | Apna College | (Dec 2024) & (May 2025) |

> Issued by **Anuj Kumar Sharma**, Founder — Coding Shuttle &nbsp;•&nbsp; ID: `QFNRFPGD`

</div>

---

## 💻 Tech Stack

### 🚀 Core Languages
<p>
  <img src="https://img.shields.io/badge/Java-Expert-%23ED8B00?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-%23F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=0D1117" />
</p>

### 🌿 Backend & Java Ecosystem
<p>
  <img src="https://img.shields.io/badge/Spring_Boot-%236DB33F?style=for-the-badge&logo=springboot&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Microservices-%236DB33F?style=for-the-badge&logo=spring&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Spring_Security-%236DB33F?style=for-the-badge&logo=springsecurity&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Hibernate-%2359666C?style=for-the-badge&logo=hibernate&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/REST_APIs-%23007ACC?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/JWT-%23000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white&labelColor=0D1117" />
</p>

### ☁️ DevOps & Cloud Native
<p>
  <img src="https://img.shields.io/badge/Docker-%232496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Kubernetes-%23326CE5?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Apache_Kafka-%23231F20?style=for-the-badge&logo=apachekafka&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/CI%2FCD_Pipelines-%23F05032?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=0D1117" />
</p>

### 🎨 Frontend Development
<p>
  <img src="https://img.shields.io/badge/React.js-%2320232A?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/TailwindCSS-%2338B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/HTML5-%23E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/CSS3-%231572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Bootstrap-%23563D7C?style=for-the-badge&logo=bootstrap&logoColor=white&labelColor=0D1117" />
</p>

### 🗄️ Databases
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-%23316192?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/MySQL-%2300758F?style=for-the-badge&logo=mysql&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/MongoDB-%2347A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=0D1117" />
</p>

### 🛠️ MERN Stack (Also Worked With)
<p>
  <img src="https://img.shields.io/badge/Node.js-%23339933?style=for-the-badge&logo=node.js&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Express.js-%23000000?style=for-the-badge&logo=express&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/MongoDB-%2347A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=0D1117" />
</p>

### 📊 Data Structures & Algorithms
<p>
  <img src="https://img.shields.io/badge/Arrays-%234CAF50?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Linked_Lists-%239C27B0?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Trees-%238BC34A?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Stacks_&_Queues-%23FF5722?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Hashing-%23673AB7?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Dynamic_Programming-%2300BCD4?style=for-the-badge&labelColor=0D1117" />
</p>

### ⚙️ Tools & Workflow
<p>
  <img src="https://img.shields.io/badge/Git-%23F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/GitHub-%23181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Postman-%23FF6C37?style=for-the-badge&logo=postman&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-%23000000?style=for-the-badge&logo=intellijidea&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/VS_Code-%23007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Figma-%23F24E1E?style=for-the-badge&logo=figma&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Maven-%23C71A36?style=for-the-badge&logo=apachemaven&logoColor=white&labelColor=0D1117" />
</p>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dilipmaurya1586&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=c9d1d9" width="49%" />
  <img src="https://nirzak-streak-stats.vercel.app/?user=dilipmaurya1586&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=FF6B35&currStreakLabel=00D9FF" width="49%" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dilipmaurya1586&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=c9d1d9&layout=compact&langs_count=8" width="45%" />
</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=dilipmaurya1586&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=6" />
</div>

---

## 🐍 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=dilipmaurya1586&bg_color=0D1117&color=00D9FF&line=00D9FF&point=FFFFFF&area=true&hide_border=true" />
</div>

<div align="center">
  <img src="https://profile-readme-generator.com/assets/snake.svg" alt="Snake animation" />
</div>

---

### ✍️ Dev Quote of the Day
<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
</div>

---

### 🔝 Top Contributed Repositories
<div align="center">
  <img src="https://github-contributor-stats.vercel.app/api?username=dilipmaurya1586&limit=5&theme=tokyonight&combine_all_yearly_contributions=true&hide_border=true" />
</div>

---

<div align="center">

**💬 Ask me about:** `Java` · `Spring Boot` · `Microservices` · `DSA` · `System Design`

**📫 Reach me:** [mauryadilip.work@gmail.com](mailto:mauryadilip.work@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://linkedin.com/in/dilip-maurya-9061a0306)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:mauryadilip.work@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-00D9FF?style=for-the-badge&logo=vercel&logoColor=black&labelColor=0D1117)](https://dilip-maurya-portfolio.vercel.app/)

<br/>

[![](https://visitcount.itsvg.in/api?id=dilipmaurya1586&icon=6&color=9)](https://visitcount.itsvg.in)

*— Proudly crafted with ❤️ by Dilip Maurya —*

</div> -->
