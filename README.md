## Kit à Planter (Internship at Terrasse des Oliviers)

> **⚠️ Note:** This project was developed in a professional context. The source code is proprietary to the company and cannot be shared. This document serves as a technical case study of my contributions.

**Description**
As part of the digital transformation for *Terrasse des Oliviers*, I contributed to the development of "Kit à Planter" (KAP), a web-based configurator allowing users to design their terraces with plant modules. The application is built on a full-stack architecture separating the Front-end (Next.js) from the Back-end (Node.js).

**Tech Stack**
* **Back-end:** Node.js, Express.js
* **Database:** PostgreSQL (via Prisma ORM)
* **Testing & QA:** Jest, Supertest (**100% test coverage**)
* **Tools:** JWT (Auth), Multer/Sharp (File management), jsPDF (PDF Generation), GitHub Actions (CI/CD)

**Key Contributions & Features**
My role focused on the architecture and development of the REST API:
* **Authentication & Security:** Implementation of secure routes with role-based access control using JWT.
* **Modular Architecture:** Organized code into controllers, services, and middlewares to ensure maintainability.
* **Complex CRUD:** Full management of entities (Plants, Pots, Collections) and user configuration saves.
* **Document Generation:** Automated creation of quotes and invoices in PDF format using `jsPDF`.
* **Legacy Integration:** Connecting and synchronizing the new API with the company's existing PHP Back-office.

---

### Technical Feedback & Learnings

**Challenges Faced**
* **Code Reliability:** A major requirement was API stability before production deployment. I met the challenge of writing comprehensive unit and integration tests with Jest and Supertest, achieving 100% code coverage.
* **Interoperability:** Ensuring communication between the new Node.js stack and the legacy PHP system required rigorous data exchange design.

**Key Takeaways**
* Mastery of a professional production architecture.
* Collaboration within an Agile team alongside Front-end developers.
* The critical importance of automated testing in large-scale projects.
