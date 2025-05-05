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
**PhD Candidate in Computer Science**  
INRIA Sophia Antipolis | Dec. 2019 – Dec. 2022  
Thesis : AI-based analysis of abdominal ultrasound images to support medical diagnosis  
Developed advanced object detection, self- and semi-supervised, multi-modal learning, and NLP techniques for abdominal ultrasound imaging using both CNNs and Transformer architectures.  
Developed a large-scale database of ultrasound images with matching medical reports in collaboration with medical experts, the Health Data Hub and Paris Hospitals.

**Master’s in Machine Learning - MVA**  
ENS Paris Saclay | 2018 – Sept. 2019  
France’s top AI master’s program, globally recognized for excellence in mathematics and machine learning.  
Advanced theoretical and practical training in modern ML research, with hands-on projects on state-of-the-art methods.

**Undergraduate in Applied Mathematics**  
Paris Dauphine PSL | 2014 – 2018  
Courses: Advanced Mathematical & Computational Analysis.

Work experience
======
**EchOpen**  
*Head of AI | Oct. 2024 – Feb. 2025*  
Led development of a production-ready bladder volume estimation ML library, implemented in C++ and optimized for mobile deployment.  
Collaborated with cross-functional teams to manage the design, development, implementation, and regulatory compliance of the AI solution.  

*AI Scientist | Jan. 2023 – Sep. 2024*  
Trained, validated, optimized, fine-tuned & deployed on mobile state of the art AI models for bladder volume and ejection fraction estimation, effectively contributing to each major stage of model development.  
Managed data ingestion, dataset creation & curation, for example, designing and deploying a secure data ingestion pipeline for medical data, including interface design, GDPR compliance, and cloud transfer using Kafka and broadly implementing data backups, versions, alerts & monitoring.  
Hosted and maintained open-source tools (Label Studio, Metabase, FiftyOne) on-premise to support data acquisition, labeling workflows, and monitoring pipelines critical to AI development.

**GE Healthcare**  
*Research Intern | Apr. 2019 – Sep. 2019*  
Explored deep generative models to interpolate missing Digital Breast Tomosynthesis projections and reduce replication artifacts, achieving higher-quality reconstructions than standard interpolation methods.

Skills
======
**Machine Learning/AI**: Computer Vision, Self/Semi-Supervised Learning, Multi-modal Learning, NLP (including LLMs – strong knowledge of fundamental theory & state of the art techniques).  
**Frameworks/Libraries**: PyTorch, Hugging Face, ONNX, OpenCV  
**Programming**: Python (Advanced), Bash (Intermediate), C/C++ (Beginner), Java (Beginner)  
**Cloud & DevOps**: AWS, Docker, CI/CD, Terraform, Kafka  
**Databases**: PostgreSQL  
**Languages**: Native Arabic & French speaker, Fluent English speaker

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
