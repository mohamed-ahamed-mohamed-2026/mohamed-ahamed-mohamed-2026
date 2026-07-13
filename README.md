# Hi there, I'm Mohamed Ahmed 👋

I am a Backend Software Engineer and Computer Science graduate from Cairo University. I specialize in building reliable backend systems, optimizing relational database schemas, and orchestrating containerized development environments.

### 🛠️ Core Stack & Technologies

* **Languages & Frameworks:** Python (Django), PHP (Laravel 11), C++, C, SQL, JavaScript
* **Asynchronous Processing:** Celery, Redis, Django Channels (WebSockets)
* **Databases & ORMs:** PostgreSQL, MySQL, Django ORM, Eloquent, Relational Schema Design
* **DevOps & Infrastructure:** Docker, Docker Compose, Linux CLI, Git/GitHub

---

### 🚀 Technical Project Architecture

#### WebSploit: Bug Bounty Automation Framework (Graduation Project)
*A distributed security reconnaissance framework built to automate vulnerability discovery workflows.*
* **Tech Stack:** Python, Django, Celery, Redis, Django Channels, PostgreSQL, Docker
* **Core Architecture Contributions:**
  * Co-designed and implemented the asynchronous distributed task execution pipeline using Celery workers to handle heavy, blocking security CLI tools (`ffuf`, `httpx`, `jsluice`).
  * Structured the persistent communication layer using WebSockets (Django Channels) to stream sub-process execution logs to the frontend client in real time.
  * Designed and normalized a 6-table PostgreSQL schema utilizing one-to-many and many-to-many relationships to manage targets, subdomains, and vulnerability vectors.
  * Configured isolated multi-container environments using Docker Compose to orchestrate the application components.
  * *Note: Developed in a local multi-machine team environment; codebase aggregated and deployed via central team workflow.*

#### Doctor Reservation System (Vezeeta Clone)
*A multi-role healthcare appointment booking and scheduling platform.*
* **Tech Stack:** PHP (Laravel 11), MySQL, Eloquent ORM
* **Core Architecture Contributions:**
  * Implemented Role-Based Access Control (RBAC) layers utilizing custom Laravel middleware to separate Admin, Doctor, and Patient routing mechanics.
  * Engineered scheduling algorithms utilizing the Carbon library to parse date-time parameters and validate against active Eloquent entries to block overlapping intervals.
  * Programmed dynamic multi-parameter filtering scopes in the persistence layer to handle multi-criteria practitioner lookups.

---

### 📈 Contact & Links

* **LinkedIn:** [linkedin.com/in/mohamedahmed2026](https://linkedin.com/in/mohamedahmed2026)
* **Email:** [mohamedahamed912@gmail.com](mailto:mohamedahamed912@gmail.com)
