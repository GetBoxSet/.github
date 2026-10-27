# 📚 BoxSet

> **Letterboxd for Books.** Track, rate, review, and discover your next read.

---

## 🚀 About this Project

**BoxSet* is a cross-platform book tracking and discovery application designed for book lovers. Inspired by platforms like Letterbox, it focuses on a clean aesthetic, seamless barcode scanning, community-driven reviews, and localized book discovery in the DACH region.

This project is built as a modern, enterprise-grade software architecture piece, lveraging state-of-the-art technologies and secure identity management from day one.

---

## 🏗️ Tech Stack

* **Identity Management:** Keycloak (OAuth2 / OIDC)
* **Backend:** ASP.NET Core (C#)
* **Database:** PostgreSQL
* **Web Frontend:** Angular
* **Mobile App:** Android (Native/Cross-Platform)
* **External APIs:** Google Books API / Open Library API

---

## 📂 Repository Structure

This organization hosts the decoupled microservices and client applications of the BoxSet ecosystem:

* [`getboxset/backend`](https://github.com/getboxset) - **Core API & Business Logic** (ASP.NET Core, EF Core, PostgreSQL integration)
* [`getboxset/web`](https://github.com/getboxset) - **Web Client** (Angular SPA)
* [`getboxset/android`](https://github.com/getboxset) - **Mobile Client** (Android application)

---

## 🗺️ Roadmap & Milestones

- [ ] **Phase 1:** Core Infrastructure (PostgreSQL, Keycloak Setup, ASP.NET Core Auth Setup)
- [ ] **Phase 2:** External Data Integration (Google Books API connection & barcode lookup)
- [ ] **Phase 3:** Core Features (User libraries, star ratings, and reviews)
- [ ] **Phase 4:** Frontend Development (Angular Web App)
- [ ] **Phase 5:** Mobile App Development (Android scanner & tracker)

---

## 🛠️ Project Management

We track our tasks, bugs, and feature requests directly via [Github Projects Kanban Board](https://github.com/orgs/getboxset/projects).