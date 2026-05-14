# Project Repository Database

*Master database of every project worked on. Copy and paste the relevant blocks into the LaTeX files when adapting the CV. Bullets follow the Action → Technical Context → Outcome structure.*

---

## Project Name: PocketQube – Modular COTS Satellite Platform
**Status:** Ongoing (Mar 2026 – Jul 2026)
**Institution / Context:** ISEL – Final-year Engineering Project
**Keywords:** Embedded Systems, FreeRTOS, ESP32-C3, RF Communications (433 MHz), Power Management, Satellite Subsystems, Telemetry, COTS, PCB Integration, Systems Engineering
**Summary (For Cover Letters):** Low-cost, modular Pocket-class satellite platform built around commercial off-the-shelf components, designed to lower the entry barrier for academic space missions.
**CV Bullet Points:**
*   Designed a modular PocketQube satellite platform around COTS components, integrating power management, ESP32-C3 compute, and a 433 MHz RF link.
*   Developed embedded firmware on FreeRTOS for real-time telemetry acquisition, scheduling, and ground transmission.
*   Specified subsystem interfaces and bus protocols to allow independent hardware modules to be swapped without firmware rewrites.

---

## Project Name: Smart Car – Web-Controlled IoT Robot
**Status:** Completed (Jan 2023 – Jul 2023)
**Institution / Context:** Personal / Vocational Project
**Keywords:** Raspberry Pi, WebSockets, OpenCV, Python, REST API, IoT, Real-Time Streaming, Computer Vision, Full-Stack
**Summary (For Cover Letters):** Web-controllable smart car streaming live OpenCV video and accepting remote commands through a custom telemetry API — an end-to-end IoT prototype covering hardware, networking, and frontend.
**CV Bullet Points:**
*   Built a web-controllable smart car on Raspberry Pi using WebSockets, delivering low-latency live video via OpenCV.
*   Designed a custom REST API for real-time telemetry and bidirectional control between browser and vehicle.
*   Integrated hardware, networking, and frontend layers into a single deployable prototype.

---

## Project Name: GSM 900 MHz Macro-Cellular Network Planning – Lisbon
**Status:** Ongoing (Apr 2026 – Jun 2026, report due 6 Jun 2026)
**Institution / Context:** ISEL – Mobile Network Planning & Optimization (PORM)
**Keywords:** GSM, Radio Planning, Link Budget, Cell Dimensioning, Frequency Reuse, Erlang B, Co-Channel Interference, Radio Mobile, Google Earth, RF Propagation, Capacity Planning
**Summary (For Cover Letters):** Full radio-planning project for a 36 km² GSM 900 MHz macro-cellular network in central Lisbon, dimensioned to deliver in-building coverage to 50,000 subscribers with 95% indoor coverage and 2% GoS.
**CV Bullet Points:**
*   Planned a GSM 900 MHz macro-cellular network covering 36 km² of central Lisbon, dimensioned for 50,000 subscribers with 95% indoor coverage and 2% Grade of Service (Erlang B).
*   Executed full link-budget analysis for omni-directional and tri-sectorised sites, evaluating LNA gain, feeder loss (LCF 1/2''–1-5/8''), and maximum path loss to derive minimum site count.
*   Designed frequency reuse pattern and TCH/SDCCH allocation across 36 channels (7.2 + 7.2 MHz), reserving one PDCH per cell for GPRS.
*   Validated coverage and co-channel interference using Radio Mobile RF propagation simulator and Google Earth geo-referencing, producing 10 dB coverage maps and 6 dB interference plots.

---

## Project Name: CN2026Labels – Elastic Cloud Image-Labeling System (GCP)
**Status:** Ongoing (May 2026, delivery 26 May 2026)
**Institution / Context:** ISEL – Cloud Computing (LEIRT/LEIC/LEIM)
**Keywords:** Google Cloud Platform, gRPC, Cloud Storage, Firestore, Pub/Sub, Compute Engine, Cloud Functions, Vision API, Translation API, Protobuf, Work-Queue Pattern, Elastic Scaling, Distributed Systems
**Summary (For Cover Letters):** Elastic, multi-service GCP system that ingests images via gRPC, detects labels with the Vision API, translates them with the Translation API, and exposes management endpoints for scaling worker and server instance groups.
**CV Bullet Points:**
*   Architected an elastic image-labeling system on GCP integrating Cloud Storage, Firestore, Pub/Sub, Compute Engine, and Cloud Functions.
*   Implemented a gRPC service with streaming upload, persistent request IDs, and management endpoints to scale gRPC server and worker instance groups on demand.
*   Decoupled producers from consumers using a Pub/Sub work-queue pattern, enabling horizontal scaling of Vision API + Translation API workers.
*   Built an HTTP Cloud Function for dynamic gRPC server discovery via instance-group IP lookup, enabling client failover without static endpoints.

---

## Project Name: Multi-Vendor Network Automation with CI/CD and Streaming Telemetry
**Status:** Ongoing (Spring 2026)
**Institution / Context:** ISEL – Network Automation and Orchestration (NetOps)
**Keywords:** Ansible, NAPALM, Netmiko, Jinja2, ContainerLab, Docker, Arista cEOS, Nokia SR Linux, Mikrotik RouterOS, RESTCONF, gNMI, gnmic, Prometheus, Grafana, OSPF, OpenConfig YANG, GitHub Actions, CI/CD, Digital Twin, Python
**Summary (For Cover Letters):** End-to-end network-automation project covering a multi-vendor lab (Arista, Nokia, Mikrotik), configuration management with Ansible roles, gNMI streaming telemetry into Grafana, and a CI/CD pipeline that validates every change against a ContainerLab digital twin before touching production.
**CV Bullet Points:**
*   Provisioned a multi-vendor lab (Arista cEOS, Nokia SR Linux, Mikrotik RouterOS) on ContainerLab and configured a multi-area OSPF backbone across four sites.
*   Automated configuration and troubleshooting with Ansible roles, Jinja2 templates, NAPALM, and Netmiko, including a layered diagnostic playbook covering interfaces, IP, OSPF adjacencies, and routing tables.
*   Compared and operated RESTCONF (Arista) and gNMI (Nokia SR Linux) management APIs, including PATCH/PUT semantics and gNMI Subscribe in SAMPLE and ON_CHANGE modes.
*   Built a streaming-telemetry stack with gnmic, Prometheus, and Grafana, exposing per-interface counters and OSPF neighbour state with sub-second detection of link failures.
*   Engineered a GitHub Actions CI/CD pipeline on a self-hosted runner that lints YAML/Ansible/Jinja2, deploys a ContainerLab digital twin, validates the change end-to-end, and only then rolls out to production.

---

## Project Name: Software Developer Internship – YEPKIT
**Status:** Completed (May 2023 – Jul 2023)
**Institution / Context:** YEPKIT (Portugal, Hybrid)
**Keywords:** Node.js, Docker, REST API, Backend, Git, Full-Stack, Modular Design
**Summary (For Cover Letters):** Industry internship contributing backend services and APIs to a hardware-software product, applying engineering best practices in a hybrid team.
**CV Bullet Points:**
*   Developed backend services in Node.js and containerised them with Docker, improving deployment consistency.
*   Contributed to full-stack feature work and API design, increasing system reliability across releases.
*   Applied modular design and Git-based version control to keep changes auditable and reviewable.

---

## Project Name: CubeSat Portugal Bootcamp – Team Lead
**Status:** Completed (April 2025)
**Institution / Context:** ISEL-Space Club, with Portuguese Space Agency mentorship
**Keywords:** CubeSat, Team Leadership, Embedded Systems, Communications, Mission Planning, Hardware-Software Integration
**Summary (For Cover Letters):** Led a 30-member multidisciplinary team to design and integrate a CubeSat prototype during an intensive bootcamp mentored by Portuguese Space Agency experts.
**CV Bullet Points:**
*   Led a 30-member team through CubeSat design, integration, and prototype delivery.
*   Coordinated embedded systems, communications, and mission planning sub-teams under Portuguese Space Agency mentorship.
*   Drove cross-functional collaboration between hardware and software groups, strengthening collective technical output.

---

## Project Name: Robotics Competitions – Team Lead
**Status:** Completed (2022 – 2023)
**Institution / Context:** Escola Secundária Gago Coutinho
**Keywords:** Arduino, Python, OpenCV, Autonomous Robotics, Git, Competition Engineering, Team Leadership
**Summary (For Cover Letters):** Led student teams to compete internationally at the First Global Challenge (Geneva), European RoboCup, the Portuguese National Robotics Festival, and CanSat 2022.
**CV Bullet Points:**
*   Led teams at First Global 2022 (Geneva), European RoboCup 2022, Festival Nacional da Robótica 2023, and CanSat 2022.
*   Designed and programmed autonomous robots using Arduino, Python, and OpenCV.
*   Oversaw documentation, Git-based version control, and cross-functional coordination across software, electronics, and mechanics.
