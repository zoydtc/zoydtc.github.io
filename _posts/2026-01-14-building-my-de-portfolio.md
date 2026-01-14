---
title: Building a Data Engineering Portfolio with Jekyll and Chirpy
date: 2026-01-14 12:00:00 +0000
categories: [General, Portfolio]
tags: [github-pages, jekyll, chirpy, documentation]
---

## Why I'm building this blog
As I begin the **DataTalksClub Data Engineering Zoomcamp**, I wanted a dedicated space to document my technical growth and share the challenges I work through along the way. This blog serves both as a digital portfolio and as a living record of my engineering journey, showcasing hands-on projects, lessons learned, and the evolution of my skills in data and infrastructure engineering.

## The Tech Stack
To build this site, I chose:
* **Jekyll**: A static site generator that plays perfectly with GitHub.
* **Chirpy Theme**: A highly customized, mobile-friendly theme designed for technical writing.
* **GitHub Actions**: To automate the deployment process.

## Key Challenges
Designing and stabilizing the deployment workflow proved to be the most engaging part of the setup. This required configuring pages-deploy.yml to handle theme compilation and explicitly setting the **GitHub Pages** environment to use GitHub Actions rather than the default build engine.

The overall setup was more involved than anticipated, particularly in the following areas:

- Gaining familiarity with Jekyll’s project structure and configuration model
- Installing, configuring, and customizing the Chirpy theme  
- Resolving build-time and dependency-related issues 
- Configuring GitHub Pages and CI/CD pipelines for reliable, repeatable deployments
- Troubleshooting failed builds caused by minor syntax and configuration errors, in some cases requiring a full rebuild of the site to reestablish a clean, working state

While occasionally frustrating, these challenges were ultimately valuable and instructive. The process deepened my understanding of how static sites are built and deployed, how DNS and hosting integrate, and how CI/CD workflows operate in practice.

This blog will serve as a technical journal throughout the Data Engineering Zoomcamp and beyond. I will use it to document hands-on projects, architectural patterns, and lessons learned while designing and operating data pipelines, cloud infrastructure, orchestration platforms, and analytics systems.

This marks the beginning of a focused learning and build journey, and I look forward to sharing practical insights as I continue to develop deeper expertise in data engineering and platform architecture.

## What's Next?
Next up is **Week 1 of the Zoomcamp**, where I'll be diving into Docker and Terraform to set up my data infrastructure on GCP!
