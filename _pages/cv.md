---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Master’s Degree in Computer Engineering**, Alma Mater Studiorum --- Università di Bologna, 2025 -- Present
  * Focus on Distributed Systems, Parallel Computing, and Cloud-native architectures.
  * Actual GPA: 29.5/30
* **Bachelor’s Degree in Computer Engineering**, Alma Mater Studiorum --- Università di Bologna, 2022 -- 2025
  * Grade: 107/110
  * **Thesis:** "Performance Analysis and Monitoring in Cloud-Edge Environments for IoT"
  * Developed a cloud-edge distributed system using Kubernetes Operators, Crossplane, and Istio Service Mesh.
* **High School Diploma**, Liceo Scientifico Galileo Galilei, Potenza, 2017 -- 2022
  * Focus on Adobe Creative Cloud, Multimedia Content Production, and Graphic Design.

Work experience
======
* **Junior DevOps Engineer** | HoDiritto (Startup) | Feb 2026 -- Present
  * Led end-to-end system design and infrastructure architecture for an early-stage MVP.
  * Managed service containerization and implemented API security best practices.
  * Provisioned cloud infrastructure using Terraform and automated CI/CD pipelines.
* **Academic Tutor (System Administration)** | Università di Bologna | Feb 2026 -- Present
  * Supported undergraduate course "System Administration and Security".
  * Guidance on Linux system administration, shell scripting, and security practices.
* **Software Engineer** | Project Quality Systems S.R.L. | 2023 -- 2026
  * Developed and maintained a C# desktop application for audit management.
  * Designed and implemented full-stack features using React.js, Node.js, and MySQL.

Projects
======
* **Cloud-Edge IoT Orchestration Platform**
  * Distributed architecture for managing low-power IoT devices across edge and cloud using Istio and Kubernetes.
  * Implemented Kubernetes Custom Resources and controllers.
* **Open-source Contributions (GitHub)**
  * Focus on Kubernetes tooling, automation, and cloud-native workflows.

Skills
======
* **Languages:** Go, C, Java, C#, JavaScript (React.js, Node.js), Python, SQL, NoSQL, CUDA.
* **Cloud & DevOps:** Kubernetes, Docker, Terraform, Ansible, Vagrant, CI/CD, Istio, Crossplane.
* **Observability:** Prometheus, Grafana, OpenTelemetry.
* **Systems & IoT:** Linux system administration, shell scripting, MQTT, Cybersecurity.
* **Tools:** Git, Adobe Creative Suite (Photoshop, Illustrator, Premiere).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
