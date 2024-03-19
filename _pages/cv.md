---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## EDUCATION  
- **Georgia Institute of Technology, Atlanta, GA**  
  Graduation: May 2024  
  *Master of Science in Computer Science*  
  GPA: 3.9 / 4.0  
  Coursework: Advanced Operating Systems, AI, Advanced Software Engineering, Distributed Computing

- **Amrita Vishwa Vidyapeetham**  
  Jul 2016 - Apr 2020  
  *Bachelor of Technology in Computer Science and Engineering*  
  GPA: 9.54 / 10 (Ranked 5/250)

## WORK EXPERIENCE

- **Software Developer, TCS Research & Innovation Labs** (Nov 2020 – Jul 2022)  
  Designed high-performance, cost-efficient, and scalable cloud architectures for inference and training of Machine and Deep Learning (DL) workloads. Published 6 research papers at top-tier conferences and filed 2 patents in the domain of serverless computing. Achieved a significant 30% reduction in execution costs by implementing a scalable FaaS-based architecture for document processing DL workflow, leveraging AWS Lambda, Elastic File System, and DynamoDB. Devised a Service Level Agreement (SLA) aware workload scheduling cloud architecture using AWS Sagemaker and Lambda, reducing the SLA violation to ~10% for Deep Learning inference.

- **Software Engineer, Oracle Cerner Corporation** (Jan 2020 – Nov 2020)  
  Developed a proof-of-concept full-stack web application that streamlined client service onboarding, reducing 25 man hours per week. Automated data-processing pipelines using Hadoop and Elastic Map Reduce (EMR) clusters to reduce 70% of manual execution steps. Engineered and optimized algorithms to efficiently filter millions of health records, boosting data processing efficiency by 1.3 times. Proficient in professional agile development practices and using tools like Jira for issue tracking, Crucible for reviews, and Jenkins for CI/CD (Continuous Integration and Deployment) for production applications.

- **Software Developer, Georgia Tech** (May 2023 - Aug 2023)  
  Spearheaded the implementation of an end-to-end DevOps pipeline and enabled seamless integration, automated testing, and continuous deployment using Azure DevOps Pipelines, Azure Web App for containers, Git, and Docker. Conceptualized, designed, and developed a dynamic full-stack web application, resulting in a 30% reduction in request processing time and an increase in collaboration efficiency between administrative staff and faculty through a comprehensive ticketing system.

## SELECTED PROJECTS  

- **DishCraft** (Aug 2023 - Dec 2023)  
  Developed an AI-driven cooking project utilizing large language models (LLMs) and retrieval augmented generation (RAG) for accurate recipe generation and cooking assistance. Incorporated an extensive collection of over 2 million recipes from the RecipeNLG dataset, and integrated Wikipedia and Ingredient Prices datasets, resulting in improved recipe knowledge and more accurate cost calculations.

- **MapReduce Library** (Aug 2022 - Sep 2022)  
  Implemented a robust MapReduce Library using C++, gRPC, and CMake, enabling parallel and distributed processing of large-scale data. Successfully reduced data processing time by an impressive 30%.

## TECHNICAL SKILLS / CERTIFICATIONS
- Certification: AWS Developer Associate [Link], AWS Cloud Practitioner [Link], CKAD - in progress
- Programming Languages: Python, Java, C++, C, Ruby, Javascript
- Frameworks: React, Springboot, Ruby on Rails, Angular, Node.js
- AWS: EC2, SQS, Cloud Watch, SageMaker, DynamoDB, Lambda, EFS, Beanstalk
- Miscellaneous: Git, Linux/Unix, Bash, Matplotlib, SQL, HTML, CSS, Kubernetes, Jenkins, Crucible, JIRA, Docker

Projects
======
  <ul>{% for post in site.projects reversed %}
    {% include archive-single-cv.html  %}
  {% endfor %}</ul>
  

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
