<!-- ═══════════════ HEADER ═══════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:FF6B5B,50:00A8E8,100:00D9FF&text=Hiruna%20Daksitha%20Serasinha&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=Automation%20Specialist%20%C2%B7%20Full-Stack%20Developer%20%C2%B7%20System%20Architect&descSize=18&descAlignY=58&animation=fadeIn" alt="Hiruna Daksitha Serasinha banner" width="100%" />

<a href="https://github.com/HD-dev">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=00A8E8&center=true&vCenter=true&width=760&lines=Building+scalable+full-stack+systems;Web+%26+mobile%3A+Next.js+%C2%B7+Vue+%C2%B7+React+Native;Backends+in+C%23+%2F+.NET+%C2%B7+Spring+Boot+%C2%B7+Node.js;Automating+the+boring+parts%2C+architecting+for+change" alt="Typing animation" />
</a>

<br/>

📍 Colombo, Sri Lanka &nbsp;|&nbsp; 💼 3+ Years Experience &nbsp;|&nbsp; 🟢 Open to Remote · On-site · Contract · Full-time

<br/>

[![Visitors](https://komarev.com/ghpvc/?username=HD-dev&color=FF6B5B&style=flat-square&label=Profile+Views)](https://github.com/HD-dev)
[![Followers](https://img.shields.io/github/followers/HD-dev?color=00A8E8&style=flat-square&label=Followers)](https://github.com/HD-dev?tab=followers)
[![Stars](https://img.shields.io/github/stars/HD-dev?color=00D9FF&style=flat-square&label=Total%20Stars)](https://github.com/HD-dev?tab=stars)

</div>

---

## 👋 About Me

I build production-grade **web and mobile applications** and automation workflows that cut manual effort and lift team productivity. I work across **Next.js / Vue / React Native** on the front, **Node.js, C# / .NET and Java Spring Boot** on the back, and I design the systems around them: service boundaries, APIs, data models, and CI/CD.

```ts
const hiruna = {
  role:        ["Full-Stack Developer", "Automation Specialist", "System Architect"],
  location:    "Colombo, Sri Lanka 🇱🇰",
  experience:  "3+ years",
  recognition: "Best Employee 2025 @ ProAccount Lanka",
  languages:   ["TypeScript", "JavaScript", "C#", "Java"],
  web:         ["Next.js", "React", "Vue", "Angular"],
  mobile:      ["React Native"],
  backend:     ["Node/Express", ".NET", "Spring Boot"],
  strengths:   ["System architecture", "API design", "CI/CD & automation", "Containerization"],
  currentlyLearning: ["PHP", "Distributed systems", "Cloud architecture"],
  openTo:      ["Remote", "On-site", "Contract", "Full-time"],
  philosophy:  "Automate the boring parts. Architect for change.",
};
```

---

## 🛠️ Tech Stack

<div align="center">

| | |
|:---|:---|
| **Languages** | <img src="https://skillicons.dev/icons?i=ts,js,cs,java,html,css&theme=dark" alt="Languages" /> |
| **Web Frontend** | <img src="https://skillicons.dev/icons?i=nextjs,react,vue,angular&theme=dark" alt="Web frontend" /> |
| **Mobile** | <img src="https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,express,dotnet,spring&theme=dark" alt="Backend" /> |
| **Databases** | <img src="https://skillicons.dev/icons?i=mongodb,postgres&theme=dark" alt="Databases" /> |
| **DevOps** | <img src="https://skillicons.dev/icons?i=docker,githubactions,git,github&theme=dark" alt="DevOps" /> |
| **Design & Tools** | <img src="https://skillicons.dev/icons?i=figma,vscode&theme=dark" alt="Tools" /> |

</div>

---

## 🏗️ How I Think About Architecture

A reference layout I design around: clean separation between clients, an API layer, independently deployable services, and automated delivery.

```mermaid
flowchart LR
    subgraph Clients
        W[Web<br/>Next.js · Vue · React · Angular]
        M[Mobile<br/>React Native]
    end

    subgraph Edge
        G[API Gateway<br/>Auth · Rate limiting · Routing]
    end

    subgraph Services
        N[Node.js / Express<br/>Automation & Integrations]
        D[C# / .NET<br/>Business Services]
        S[Spring Boot<br/>Core Domain APIs]
    end

    subgraph Data
        MDB[(MongoDB)]
        PG[(PostgreSQL)]
    end

    subgraph Delivery
        GH[GitHub Actions<br/>CI/CD] --> DK[Docker<br/>Containers]
    end

    W --> G
    M --> G
    G --> N
    G --> D
    G --> S
    N --> MDB
    D --> PG
    S --> PG
    DK -. deploys .-> Services
```

<details>
<summary><b>⚙️ Delivery pipeline: from commit to production</b></summary>

<br/>

```mermaid
flowchart LR
    A[Commit / PR] --> B[Lint & Type-check]
    B --> C[Unit & Integration Tests]
    C --> D[Build Docker Image]
    D --> E[Push to Registry]
    E --> F{Branch?}
    F -- feature --> G[Preview Environment]
    F -- main --> H[Staging]
    H --> I[Smoke Tests]
    I --> J[Production]
```

</details>

<details>
<summary><b>📐 Principles I work by</b></summary>

<br/>

- **Separate concerns:** thin controllers, clear domain layers, replaceable infrastructure
- **Design APIs first:** consistent REST contracts, versioning, and validation at the edge
- **One backend, many clients:** a single API contract serves Next.js, Vue, and React Native alike
- **Automate delivery:** every merge builds, tests, and ships through a pipeline
- **Plan for failure:** observability, retries, and graceful degradation over heroics

</details>

---

## 💼 Experience

### Automation Specialist · ProAccount Lanka (Pvt) Ltd
*2022 – Present · 3+ years*

| Impact | |
|:---|:---|
| 🏆 **Recognition** | Best Employee 2025 for outstanding contributions |
| ⚙️ **Automation** | Designed workflows that reduced manual tasks by **40%+** |
| 🚀 **Full-stack delivery** | Built tools connecting automation backends with responsive frontends |
| 🏗️ **Architecture** | Designed scalable backend services across Node.js, C#/.NET, and Spring Boot |
| 📊 **Productivity** | Custom CI/CD pipelines and automation tooling for the team |

`JavaScript` `TypeScript` `Vue.js` `Next.js` `React Native` `Node.js` `C#` `.NET` `Java` `Spring Boot` `Docker` `GitHub Actions` `MongoDB` `Express.js`

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📱 [Easy Invoice.lk](https://github.com/HD-dev/easy-invoice)
Smart invoicing platform for small businesses (web + mobile).

- Invoicing, client management, payment tracking
- Real-time sync between web and mobile
- Responsive UI and secure backend APIs

`Vue.js` `TypeScript` `Node.js` `Express.js` `MongoDB`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/HD-dev/easy-invoice)

</td>
<td width="50%" valign="top">

### 📝 [Vue Blog Project](https://github.com/HD-dev/vue-blog)
Production-ready blog platform built with Vue 3.

- Auth, comments, categories, and role-based access
- REST API integration and scalable structure
- Typed end to end with TypeScript

`Vue.js` `TypeScript` `Node.js` `Express.js`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/HD-dev/vue-blog)

</td>
</tr>
</table>

---

## 🎯 Expertise

| Domain | Proficiency | Highlights |
|:---|:---|:---|
| Full-Stack Web Development | `█████████░` 90% | Next.js, Vue, React, Angular · Node.js, Express |
| API Development & Integration | `█████████░` 90% | REST design, Axios, microservice patterns |
| TypeScript & Modern JavaScript | `█████████░` 90% | Type-safe development, ES6+, async/await |
| Automation & CI/CD | `█████████░` 90% | GitHub Actions, Docker, workflow automation |
| Mobile Development | `████████░░` 80% | React Native, shared API contracts with web |
| System Architecture & Design | `████████░░` 80% | Scalable design, microservices, design patterns |
| Backend: C# / .NET | `████████░░` 80% | .NET APIs, enterprise-style backend services |
| Backend: Java / Spring Boot | `████████░░` 80% | Spring Boot, REST services, layered architecture |
| DevOps & Containerization | `████████░░` 80% | Docker, deployment automation |
| Database Design | `████████░░` 80% | MongoDB, PostgreSQL, data modeling |

<details>
<summary><b>🧭 Tech radar</b></summary>

<br/>

| Ring | Technologies |
|:---|:---|
| 🟢 **Core** (daily drivers) | TypeScript · JavaScript · Vue · Next.js · React · Node.js · Express · Docker · GitHub Actions |
| 🔵 **Proficient** | C# / .NET · Java / Spring Boot · React Native · Angular · MongoDB · PostgreSQL |
| 🟡 **Learning** | PHP · Distributed systems · Cloud architecture |
| 🟣 **Exploring** | Microservices at scale · Cloud-native development |

</details>

---

## 🎓 Education

**Software Engineering Degree** · A.T.A.R.I · 2019

---

## 🧭 Now

<table>
<tr>
<td valign="top" width="33%">

**📚 Learning**
- PHP backend development
- Distributed systems
- Cloud architecture

</td>
<td valign="top" width="33%">

**🔨 Building**
- Easy Invoice.lk v2
- Automation workflow optimization tools
- Full-stack SaaS solutions

</td>
<td valign="top" width="33%">

**🔭 Exploring**
- Microservices at scale
- Cloud-native development

</td>
</tr>
</table>

---

## 🤝 Let's Work Together

I'm open to **remote, on-site, contract, and full-time** roles in full-stack development, mobile, backend engineering, automation, and system architecture.

<div align="center">

<a href="#"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-FF6B5B?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
<a href="#"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-00A8E8?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="#"><img alt="Email" src="https://img.shields.io/badge/Email-FFB563?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/HD-dev"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

<sub>*"Building elegant solutions to complex automation challenges, one commit at a time."*</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:FF6B5B,50:00A8E8,100:00D9FF&section=footer" alt="footer" width="100%" />

</div>
