# Sathish G

**Full-Stack & Mobile Systems Engineer**  
Specializing in production mobile architectures, real-time backend infrastructure, and offline-first distributed platforms.

[Portfolio](https://www.sathishdev.in) � [GitHub](https://github.com/Sathish4439) � [LinkedIn](https://www.linkedin.com/in/sathishgobi/) � [Google Play](https://play.google.com/store/apps/dev?id=6517030172709793171) � [Email](mailto:sathishg.dev@gmail.com)

---

## ? Core Engineering Capabilities

| Engineering Domain | Primary Technologies & Tooling |
| :--- | :--- |
| **Mobile Systems** | Flutter, Dart, Kotlin Android Native, Provider/MVVM, Offline-First Sync |
| **Frontend Platforms** | React 19, Next.js 14, TypeScript, Tailwind CSS 4, Vite |
| **Backend & APIs** | Node.js 22, Express 5, TypeScript, RESTful Services, Webhooks, SSE |
| **Databases & ORMs** | PostgreSQL, Prisma ORM 6, Drift (SQLite with WAL), MongoDB |
| **Real-time & Queues** | BullMQ, Redis, Persistent WebSockets (`ws`), Socket.io |
| **Cloud & Hosting** | AWS (EC2, S3), Docker Containerization, Nginx Reverse Proxy, PM2 |
| **Security & Protocols** | AES-256-GCM Payload Encryption, HMAC-SHA256 Webhook Signing, JWT, Zod |
| **DevOps & Testing** | Git, GitHub Actions, Playwright Automation, Micro-benchmarks |

---

## ?? Flagship Engineering Projects

### 1. FlatSMS � Distributed Android SMS Gateway & Control Plane

> High-throughput cloud control plane and real-time WebSocket bridge turning commodity Android devices into an API-driven, 2-way telecommunications gateway.

* **Problem Solved**: Traditional CPaaS providers (Twilio/MessageBird) impose heavy per-segment fees, compliance surcharges, and Carrier A2P 10DLC restrictions that burden early-stage apps and transactional OTP dispatchers.
* **Architecture & Engineering**:
  * Built an event-driven control plane using **Node.js 22**, **Express 5**, and **TypeScript** communicating over persistent full-duplex **WebSockets** to native Android background daemons.
  * Integrated **Redis-backed BullMQ** to guarantee zero-loss message queues with exponential backoff retries and priority dispatching.
  * Enforced end-to-end payload security via **AES-256-GCM** encryption and outbound **HMAC-SHA256** signed webhooks for third-party verification.
  * Designed a high-density, real-time telemetry console in **React 19**, **Vite**, and **Tailwind CSS 4**.
* **Stack**: `Node.js 22` � `TypeScript` � `Express 5` � `BullMQ` � `Redis` � `Prisma ORM` � `PostgreSQL` � `Kotlin Android` � `React 19`
* **Proof**: [Interactive Portfolio Case Study](https://www.sathishdev.in/work/flatsms-sms-gateway) � [System Implementation](https://github.com/Sathish4439)

---

### 2. MyShop � Offline-First Retail POS & Grocery ERP

> Ultra-reliable, 100% offline-resilient Point of Sale (POS) and inventory ledger designed for retail grocery checkout speeds.

* **Problem Solved**: Cloud-only POS systems crash or freeze during unstable network connectivity and rush hours, halting cash registers, delaying billing queues, and creating stock discrepancies.
* **Architecture & Engineering**:
  * Engineered a completely offline-first checkout engine in **Flutter** backed by **Drift (SQLite)** utilizing **Write-Ahead Logging (WAL)** for sub-millisecond local reads and ACID writes.
  * Implemented low-level ESC/POS byte-stream printing over Bluetooth for sub-300ms thermal receipt production without raster lag.
  * Integrated sub-second camera-based barcode parsing and atomic double-entry debit/credit ledger tracking for customer credit lines.
  * Synchronized offline transactions with a central **Node.js/Prisma** backend and **Next.js 14** Multi-Tenant Super Admin dashboard.
* **Stack**: `Flutter` � `Dart` � `Drift (SQLite WAL)` � `Node.js` � `TypeScript` � `Prisma` � `PostgreSQL` � `Next.js 14` � \ESC/POS Bluetooth\
* **Proof**: [Interactive Portfolio Case Study](https://www.sathishdev.in/work/myshop-pos)

---

### 3. Mayiliragu Academy LMS

> Scalable digital learning ecosystem serving government exam aspirants with secure video streaming and responsive assessment engines.

* **Problem Solved**: High-concurrency educational platforms often face massive video hosting overheads, unauthorized media scraping, and poor performance on low-end mobile networks.
* **Architecture & Engineering**:
  * Delivered a cross-platform **Flutter** student application coupled with a **React** administrator curriculum dashboard.
  * Structured a modular **Node.js/Prisma** backend on **AWS EC2**, deploying secure proxy pipelines with **Google Drive API** for tamper-resistant study content.
  * Configured **Firebase Authentication** with automated device binding and session management to prevent credential sharing.
* **Stack**: `Flutter` � `React` � `TypeScript` � `Node.js` � `Express` � `Prisma ORM` � `PostgreSQL` � `AWS EC2` � `Firebase`
* **Proof**: [Google Play App Store](https://play.google.com/store/apps/details?id=com.learning.mayiliragu.mayiliragu)

---

### 4. Judah Food Delivery Suite

> Unified 3-app on-demand logistics ecosystem managing real-time consumer orders, restaurant merchant preparation, and rider dispatch.

* **Problem Solved**: Fragmented order handoffs between restaurants and delivery partners cause extended kitchen wait times, customer blindspots, and route miscalculations.
* **Architecture & Engineering**:
  * Architected three connected Flutter applications (Consumer, Merchant Partner, Delivery Agent) linked via **Socket.io** bidirectional channels.
  * Integrated **Google Maps Directions API** and GPS polyline tracking for real-time driver telemetry and automated ETA calculations.
  * Incorporated transactional **Razorpay** payment gateway processing with strict webhooks verification and order state idempotency.
* **Stack**: `Flutter` � `Dart` � `Socket.io` � `Node.js` � `Express` � `Prisma` � `PostgreSQL` � `Google Maps API` � `Razorpay`
* **Proof**: [Google Play Store Release](https://play.google.com/store/apps/details?id=com.judah.fooddelivery)

---

## ?? Verified Production Experience

| Application | Core Role | Technology Stack | Target Platforms | Current Status |
| :--- | :--- | :--- | :--- | :--- |
| **FlatSMS Gateway** | Principal Architect | Node.js 22, Kotlin, BullMQ, Redis, React 19 | Web + Android Service | Production / Active |
| **MyShop POS ERP** | Principal Architect | Flutter, Drift SQLite, Node.js, Next.js 14 | Android + Web Admin | Production / Active |
| **Mayiliragu LMS** | Lead Full-Stack Engineer | Flutter, React, Node.js, Prisma, AWS EC2 | Android + Web | Live on Google Play |
| **Judah Logistics** | Lead Software Engineer | Flutter, Socket.io, Node.js, Google Maps | Android (3 Apps) | Live on Google Play |
| **Nest Pilot Hostel** | Full-Stack Engineer | Flutter, React, Node.js, PostgreSQL, AWS | Android + Web | Production Deployment |
| **Premium Parts ERP** | Full-Stack Developer | Flutter, Node.js, Prisma, PostgreSQL, QR | Android + Web Admin | Enterprise Deployed |
| **akirva Ride Network** | Mobile UI Architect | Flutter, Firebase Firestore, Google Maps | Android (2 Apps) + Web | Enterprise Deployed |

---

## ?? Core Engineering Principles

* **Offline-First Resilience**: When network availability is intermittent, critical operations must never freeze. Local storage with write-ahead logging (WAL) guarantees instantaneous UI responses and atomic reconciliation.
* **Queue-Driven Asynchrony**: High-throughput telemetry and messaging must decouple ingress from processing. Redis-backed queues provide durability, concurrency control, and deterministic error handling.
* **Strict Boundary Validation**: Never trust external clients or webhooks. Enforce typed schemas (Zod/Prisma) on the server, paired with HMAC signature verification and payload encryption.
* **Single Source of Truth**: Financial calculations, order states, and stock levels adhere to strict transactional consistency (ACID) and double-entry bookkeeping ledgers.
* **Predictable State Architecture**: Modular MVVM and clean domain boundaries separate data providers from presentation logic, maximizing testability and long-term maintainability.

---

## ?? What I Build (Freelance & Product Engineering)

* **Mission-Critical Business Systems**: Offline-first Point of Sale (POS), inventory ledgers, and operations ERPs engineered for zero downtime.
* **Cross-Platform Mobile Products**: High-performance Flutter applications for iOS, Android, and Web with native hardware integration (Bluetooth ESC/POS, GPS, Background Services).
* **High-Throughput Backend Infrastructure**: Node.js/TypeScript REST APIs, WebSocket gateways, background queue processors, and PostgreSQL architectures.
* **Legacy & MVP Modernization**: Upgrading early-stage prototypes into scalable, maintainable, production-ready cloud architectures on AWS.

---

## ?? Professional Experience

#### Full-Stack Software Engineer � **Dhigrowth**
*Coimbatore, TN (Hybrid) � September 2025 � Present*
* Architected the **FlatSMS** distributed cellular SMS gateway (Node.js 22, BullMQ, WebSocket daemon, React 19).
* Engineered the **MyShop** offline-first retail grocery POS with ESC/POS Bluetooth thermal printing and Drift WAL SQLite.
* Built the **Judah** 3-app food delivery dispatch ecosystem with real-time Socket.io driver tracking and Razorpay webhooks.
* Developed the **Nest Pilot** hostel management SaaS and the **akirva** auto-rickshaw ride-hailing applications.

#### Flutter Mobile Developer � **Elanoxtech**
*Chennai, TN (On-site) � July 2024 � September 2025*
* Delivered consumer-facing mobile applications including **Virtual to Live** (360� virtual tour marketplace) and **Ovantica** (gadget re-commerce platform).
* Integrated interactive Google Maps location pipelines, real-time Firestore listeners, and payment workflows.
* Streamlined mobile rendering pipelines and memory consumption across diverse Android device tiers.

#### Independent Software Engineer � **Client Engagements**
*Coimbatore & Karur, TN � June 2023 � June 2024*
* Designed and deployed the **Mayiliragu Academy LMS** (Flutter mobile client, React admin, Node.js/Prisma backend on AWS EC2).
* Built the **WhatsApp Sender Automation** SaaS platform leveraging official Meta Cloud APIs and webhook queues.
* Implemented the **Premium Parts ERP** system featuring QR code asset tracking and automated PDF invoicing.

---

## ?? Recommended GitHub Pinned Repositories

| Repository | Current Focus | Recommended Description |
| :--- | :--- | :--- |
| **1. FlatSMS** | Full-Stack Gateway | *High-throughput distributed Android SMS gateway & control plane built with Node.js 22, BullMQ, WebSockets, and React 19.* |
| **2. MyShop** | Retail POS & ERP | *Offline-first Flutter grocery POS with Drift SQLite WAL, ESC/POS Bluetooth thermal printing, and Next.js 14 admin.* |
| **3. Mayiliragu-Academy** | Educational LMS | *Production LMS suite with Flutter student app, React admin portal, and Node.js/Prisma backend on AWS EC2.* |
| **4. Judah-Food-Delivery** | Multi-App Logistics | *Real-time 3-app on-demand food delivery & dispatch ecosystem with Flutter, Socket.io, and Google Maps.* |
| **5. whatsapp-sender-api** | Automation SaaS | *Meta Business Cloud API automation engine with asynchronous webhook listeners and MongoDB queue tracking.* |
| **6. rag-chatbot-engine** | AI/RAG Search | *Full-stack RAG pipeline with Playwright scraping, Qdrant vector indexing, and real-time SSE streaming via Groq LLaMA 3.1.* |

---

## ?? Engineering Inquiries & Collaboration

* **Recruiters & Engineering Teams**: Open to full-time engineering positions (On-site, Hybrid, or Remote) in Coimbatore, Bangalore, Chennai, or globally.
* **Founders & Enterprise Clients**: Available for select freelance contracts, MVP engineering, and production architecture consultations.

?? **Website**: [www.sathishdev.in](https://www.sathishdev.in)  
?? **LinkedIn**: [linkedin.com/in/sathishgobi](https://www.linkedin.com/in/sathishgobi/)  
?? **GitHub**: [github.com/Sathish4439](https://github.com/Sathish4439)  
?? **Email**: [sathishg.dev@gmail.com](mailto:sathishg.dev@gmail.com)  
?? **Location**: Coimbatore, Tamil Nadu, India
