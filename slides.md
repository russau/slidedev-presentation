---
theme: dracula
title: Presentation
info: |
  Russell Sayers
transition: slide-left
mdc: true
---

# Publishing, Releasing, Cataloging Content

Let's Automate

---

# Russ Sayers

 - Software engineer 15+ years
 - Technical trainer @ AWS, Confluent 4+ years
 - Curriculum engineering @ AWS, Confluent 4+ years
 - Cloud Technologist @ AWS 5 years

---

# Certifications

 - AWS Certified Solutions Architect - Professional
 - AWS Certified DevOps Engineer - Professional
 - AWS Certified Machine Learning Engineer - Associate
 - AWS Certified Solutions Architect - Associate
 - AWS Certified SysOps Administrator - Associate
 - AWS Certified Developer - Associate
 - AWS Certified Security - Specialty
 - AWS Certified AI Practitioner
 - CKAD: Certified Kubernetes Application Developer
 - CKA: Certified Kubernetes Administrator

---
layout: center
---

# Publishing Content to an LMS

Proposed Architecture

![](/arch_vector.svg)

---

# Continuous Integration

 - 💾 Source control (Github)
   - Stores manifest / labs code
   - Changes automatically trigger a build
 - ⚙️ Automated Build (Github actions)
   - Automation runs here
   - Automated sanity checks
   - Communication to LMS APIs

---

# Manifest

```yaml
course_code: COURSE01
languages:
  - code: ko-KR
    version: 3.1.1
    name: 기본 사항 소개
  - code: en-US
    version: 4.0.0
    name: Introduction to the Basics
```

---

# Catalog - Who / Roles?

 - 🧑 Instructors
   - What version am I teaching / ramping?
 - 👩 Curriculum Developers
   - Search index to find content
 - 🧑 Localization
   - Finding updates to English courses
 - 👩 Training Operations
   - What versions are active?
   - Deprecating versions
 - 👩 Business Development
   - What versions are upcoming?

---

# Demo

https://catalog.beta-seattle.net 

![](/catalog.png)

---
