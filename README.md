# 💻 System Development Technology (SECP3723)

Welcome to my repository for the System Development Technology course. This space documents my progression from front-end fundamentals and PHP/MySQL practice drills all the way to a full client-commissioned capstone, where my group designed, built, and deployed a real-world web system for an external organisation.

---

## 📖 Course Overview
This course is built around the practical execution of the Software Development Life Cycle (SDLC), taught under the Faculty of Computing by Dr. Haza Nuzly Bin Abdull Hamed. Rather than staying purely theoretical, the course pairs weekly hands-on web development exercises with a **Work-Based Learning (WBL)** project: partnering with a real organisation to digitise an actual operational pain point.

My group worked with **Lembaga Kemajuan Pertanian Kemubu (KADA)**, a Malaysian agricultural cooperative, to replace their fully manual, paper-based membership and loan system with a secure web application we named **SDT Synapse** (the Koperasi KADA Automated System). Key themes include requirements gathering through Joint Application Development (JAD) and industry talks, modular PHP system design, database-driven workflows, role-based access control, automated PDF reporting, and structured Alpha/Beta/UAT testing cycles.

---

## 📂 Repository Structure & Project Breakdown

### 🔹 Foundational Lab Exercises
* **Bootstrap Front-End Drills**: A sequential set of HTML practice files covering Bootstrap grid systems, containers, fixed vs. fluid layouts, padding, borders, typography, colours, and responsive tables — the building blocks reused in every interface built later in the course.
* **Course Registration System Prototype**: An early PHP + MySQL mini-system modelling student, lecturer, and admin course registration, complete with a normalised database schema and role-specific headers — my first real exposure to multi-role access control.

### 🔹 CRS Mini-Project Iteration
* **Course Registration Logic**: Refined iterations of the CRS prototype, adding a full course approval workflow, assigned-course management, and Composer-managed dependencies — practice for the larger application patterns later used in the capstone.
* **Development Progress Gallery**: A timestamped screenshot log documenting iterative UI and feature checkpoints throughout the CRS build.

### 🏆 Capstone Industry Project: SDT Synapse — Koperasi KADA Automated System
The centrepiece of the course: a client-commissioned, full-stack system replacing KADA's manual, paper-based membership and loan operations.
* **Work-Based Learning Report**: Documents the full SDLC executed for the client — client and problem background, proposed solution, JAD-based requirements gathering, the seven-module system architecture, and Alpha/Beta/UAT testing reports.
* **System Requirement Specification**: Formal hardware, software, and communication interface requirements, plus performance (500 concurrent users, sub-2-second response times), safety, and security requirements (multi-factor authentication, role-based access, GDPR-aligned data handling).
* **Source Code**: Over a thousand PHP files powering the system's seven core modules — Membership Application, Terminate Membership, Review, Loan Application, Approve Application, Statement Report Production (via TCPDF/FPDI), and Financial Tracking — backed by a MySQL database and deployed to a live hosting environment.
* **User Manual**: A 60-page guide walking applicants, admins, and the cooperative's board (ALK) through every system workflow.
* **Project Presentation & Declaration**: The final pitch deck and our team's signed declaration of individual module contributions.

---

## 🛠️ Core Themes & Technical Stack
* **Front-End:** HTML5, CSS, Bootstrap, JavaScript
* **Back-End:** PHP, MySQL, phpMyAdmin, XAMPP (Apache/MySQL/PHP)
* **Tools & Libraries:** Draw.io (ERDs and use-case diagrams), Composer, TCPDF/FPDI (automated PDF statement generation), Jimat Hosting (deployment)
* **Process & Methodology:** SDLC (Planning → Analysis → Design → Implementation → Testing), Joint Application Development (JAD), role-based access control, Alpha/Beta/UAT testing cycles

---

## 💡 Course Reflection & Key Takeaways
This course was where I stopped writing isolated PHP exercises and started thinking like a system developer accountable to a real client. Sitting through the KADA industry talk and translating the cooperative's manual, paper-based pain points into a working membership-and-loan platform taught me that requirements gathering is as much about listening as it is about coding. Owning the Terminate Membership and Loan Application modules showed me how a role-based workflow — applicant submission, admin review, and ALK approval — has to be designed around how an organisation actually makes decisions, not just how a database table is structured. Running through Alpha, Beta, and UAT testing with the cooperative's own staff was humbling: feedback from people who would use the system every day exposed gaps that no amount of solo testing could have caught. Ultimately, SDT Synapse taught me that good system development isn't just functional code — it's code that earns the trust of the people whose paper trail you're replacing.
