# SacLab Web Portal – Front-End

This repository contains the **front-end** of a web portal built for the **Space Advanced Concepts Lab (SacLab)** at ISAE-SUPAERO.  
It was developed during my technical internship as a **web developer** in the SacLab team.

🔗 **Live demo:**  
https://aliel03.github.io/saclab.github.io/

---

## 🌍 Project in a Few Words

The goal of this project was to provide SacLab with a modern web interface to:

- present the **chair, missions and partners**,  
- showcase **research themes, tools and student projects**,  
- centralise **internal and external communications**,  
- give access to **teaching and tools** used in the lab. :contentReference[oaicite:0]{index=0}  

This repository focuses on the **front-end implementation**.  
The original back-end (APIs, authentication, internal data) was hosted on internal servers and is **not included here**.

---

## 🎯 What I Worked On During the Internship

**Role:** Technical intern – web development (SacLab Team)  
**Scope:**

- Development and maintenance of **internal web tools** for the lab.
- Implementation of pages and components for the **SacLab web portal** (this repository).
- Collaboration on an **SOA-oriented architecture** (front-end + micro-services / APIs).
- Participation in **test and validation automation** for some internal tools.

**Technologies used during the internship:**

- Front-end: **React**, **Angular**, **TailwindCSS**
- Back-end / APIs: **Express** (Node.js)
- Dev & tooling: **Git**, **Docker**

> ⚠️ In this repository, you will mainly find the React front-end of the SacLab portal.
> The Express back-end and some Angular-based internal tools were also developed during my internship, but they were hosted on the ISAE-SUPAERO GitLab and I no longer have access to them, so they are not included here.

> The Express back-end and some Angular-based internal tools were developed during the internship but could not be published (internal code).

---

## 🧩 Main Features of the Front-End

From the live version, the front-end provides: :contentReference[oaicite:1]{index=1}  

- A **bilingual interface** (English / French) with navigation in both languages.
- A structured **navigation bar** with:
  - *Home* and *Last News*,
  - *ADM* section (Chair, Materials, Internal/External Comms),
  - *Research* (Launcher, Exploration, Orbital Systems / SST / STM),
  - *Education* (FISE, MAE, MASTER, Student Projects),
  - *Tools* (Gigante, Sempy, Ecocel, Nanostar, Nanospace, JSatorb, Luplink, HyCube, Alice, Satnogs Station),
  - *Members Area*.
- Several content sections explaining:
  - **Who we are / missions of the chair**,  
  - **Research topics and tools**,  
  - **Presentation of projects and facilities**. :contentReference[oaicite:2]{index=2}  
- A **responsive layout** that adapts to desktop screens (and can easily be extended to mobile).
- A footer with **contact information, map and links**.

Even without the original back-end, this front-end demonstrates:

- navigation and layout,
- content structure,
- static pages that can be wired to real APIs.

---

## 🛠️ Tech Stack (Front-End)

The project is designed as a **single-page application** with reusable components.

- **React** – main front-end framework.
- **TailwindCSS** – utility-first CSS for layout, spacing and typography.
- **HTML / JSX** – page structure and components.
- **GitHub Pages** – hosting of the static build (`gh-pages`).

> During the internship, I also worked with **Express** for APIs, **Angular** on other internal tools, and **Docker** to containerise some services, but these parts are not included in this public repo.

---

## 🚀 How to Run Locally (Typical React Setup)

If you clone this project and it contains the React source code (e.g. `package.json`, `src/`, etc.), you can run:

```bash
# 1. Clone the repository
git clone https://github.com/aliel03/saclab.github.io.git
cd saclab.github.io

# 2. Install dependencies
npm install

# 3. Start the development server
npm start
