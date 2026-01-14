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
Setting up the deployment workflow was the most interesting part. I had to configure `pages-deploy.yml` to handle the theme compilation and ensure the GitHub Pages environment was set to **GitHub Actions** rather than the default builder.
The setup process was more challenging than I initially expected. I encountered issues related to:

- Understanding Jekyll’s project structure and configuration  
- Correctly setting up and customizing the Chirpy theme  
- Resolving build and dependency errors  
- Configuring GitHub Pages and CI pipelines for successful deployment  
- Debugging failed builds caused by small syntax or configuration mistakes ultimately having to delete and try it again

While these challenges were sometimes frustrating, they were also highly educational. The process strengthened my understanding of how static sites are built and deployed, how CI/CD workflows function, and how to troubleshoot infrastructure-related issues—skills that are directly relevant to a career in data engineering, platform engineering, and DevOps.
This blog will serve as a technical journal throughout the Data Engineering Zoomcamp and beyond. I plan to use it to document hands-on projects, architectural concepts, and lessons learned while working with data pipelines, cloud services, orchestration tools, and analytics systems.
Building the blog itself became my first real-world exercise in infrastructure setup and deployment. It reinforced an important lesson: learning happens most effectively when you step outside of guided tutorials and start building real systems, even when things break along the way.
This is the beginning of my journey, and I look forward to sharing what I learn as I continue to grow in the field of data engineering.

## What's Next?
Next up is **Week 1 of the Zoomcamp**, where I'll be diving into Docker and Terraform to set up my data infrastructure on GCP!
