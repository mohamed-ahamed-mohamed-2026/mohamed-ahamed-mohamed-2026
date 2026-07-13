# Hi there, I'm Mohamed Ahmed 👋

I am a Backend Software Engineer and Computer Science graduate from Cairo University. I specialize in engineering concurrent, non-blocking asynchronous architectures, designing highly normalized relational database schemas, and orchestrating containerized multi-service micro-ecosystems.

### 🛠️ Core Technical Stack & Ecosystem

* **Languages & Frameworks:** Python (Django), PHP (Laravel 11), C++, C, SQL, JavaScript
* **Asynchronous & Real-time Systems:** Celery, Redis, Django Channels (WebSockets)
* **Databases & Data Modeling:** PostgreSQL, MySQL, Relational Schema Optimization, Django ORM, Eloquent
* **DevOps & Infrastructure:** Docker, Docker Compose, Linux CLI, Git/GitHub, Postman

---

### 🚀 Technical Project Architecture & Deep Dives

#### 🔹 WebSploit: Bug Bounty Automation Framework (Graduation Project)
*A distributed security reconnaissance platform architected to automate complex vulnerability discovery workflows.*
* **Infrastructure Stack:** Python, Django, Celery, Redis, Django Channels, PostgreSQL, Docker
* **Backend Architecture & Engineering Focus:**
  * **Distributed Task Execution:** Engineered an asynchronous, distributed execution pipeline utilizing Celery workers and Redis as an in-memory message broker to decouple and run resource-heavy, blocking security CLI tools (`ffuf`, `httpx`, `jsluice`) in parallel.
  * **Real-time Event Streaming:** Designed a bidirectional, low-latency communication layer using Django Channels (WebSockets) to capture subprocess terminal outputs and stream real-time task progress logs back to the client interface.
  * **Relational Schema Optimization:** Architected and normalized a 6-table PostgreSQL relational schema, leveraging explicit foreign key constraints, one-to-many, and many-to-many mapping tables to systematically structure target parameters and subdomains.
  * **Service Isolation:** Containerized the monolithic application components and background workers using Docker Compose to ensure local multi-service environment consistency and repeatable deployments.
  * *System Note: Architected locally in a distributed, multi-machine team paradigm; source code consolidated via team lead version control repository.*

#### 🔹 Doctor Reservation System (Vezeeta Clone)
*A secure, multi-role healthcare scheduling engine engineered to manage concurrent patient appointments.*
* **Infrastructure Stack:** PHP (Laravel 11), MySQL, Eloquent ORM, Carbon API
* **Backend Architecture & Engineering Focus:**
  * **Role-Based Access Control (RBAC):** Built robust security boundaries by writing custom Laravel middleware to tightly intercept and validate multi-role token routes (Admin, Doctor, Patient) prior to controller execution.
  * **Schedule Generation Algorithm:** Developed high-accuracy time-slot generation logic using the Carbon library, processing temporal constraints to eliminate appointment overlapping and double-booking race conditions across active Eloquent storage rows.
  * **Dynamic Query Scoping:** Programmed modular, chainable multi-parameter filtering scopes within the persistence layer, enabling sub-millisecond querying of doctor entities by specialty, geographical clinic location, and name variations.

---

### 📈 Let's Build Something Impactful

* **LinkedIn:** [linkedin.com/in/mohamedahmed2026](https://linkedin.com/in/mohamedahmed2026)
* **Email:** [mohamedahamed912@gmail.com](mailto:mohamedahamed912@gmail.com)
