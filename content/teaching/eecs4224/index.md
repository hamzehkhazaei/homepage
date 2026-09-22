---
title: EECS 4224
summary: Machine Learning Systems

tags:
- undergrad
date: "2026-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Machine Learning Systems
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/HamzehKhazaei
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
This course analyzes the systems engineering principles required to build, deploy, and maintain machine
learning systems at scale. It examines the architecture of data pipelines, distributed training strategies,
and low-latency model serving frameworks. Students evaluate trade-offs between computational efficiency,
scalability, and reliability while gaining hands-on experience with hardware accelerators and cloud-based ML
infrastructure. Prerequisites: LE/EECS 3221 3.00 and (LE/EECS 3404 3.00 or LE/EECS 3405 3.00 or LE/CSSD 3131
3.00).

This course focuses on the design and implementation of machine learning systems in production settings, with
an emphasis on scalability, performance, and reliability. It covers the end-to-end ML lifecycle, including data
ingestion, feature engineering, distributed training, model evaluation, and deployment. Students explore
system-level challenges such as resource management, fault tolerance, and hardware acceleration (e.g., GPUs),
as well as trade-offs between latency, throughput, and cost in cloud environments.

The course adopts a systems-oriented perspective, drawing on concepts from distributed systems and software
engineering. Students engage with modern ML infrastructure and frameworks, and complete programming
assignments and a substantial project that involves building and optimizing components of real-world ML
systems. Case studies from industry and recent research are used to illustrate practical design patterns and
emerging trends in ML systems.

**Tentative topics:**
- Introduction to ML systems: overview of the ML system lifecycle; model-centric vs. system-centric
  perspectives; case studies of production ML systems.
- Data pipelines and feature engineering systems: data ingestion, preprocessing, feature stores, data
  validation, and pipeline orchestration.
- Storage systems for ML: distributed storage, data formats, batch vs. streaming systems, data locality.
- Distributed training: parallelism strategies (data, model, pipeline parallelism), distributed ML frameworks,
  parameter servers, all-reduce, communication efficiency, and fault tolerance.
- Hardware acceleration: GPUs, TPUs and accelerators, memory hierarchies, performance optimization techniques.
- Model serving systems: batch vs. online inference, serving architectures, serverless vs. serverful, latency,
  throughput, and scaling challenges.
- Caching, optimization, and resource management: caching strategies, scheduling, autoscaling, quantization,
  pruning, distillation, and cost-performance trade-offs in cloud environments.
- ML system reliability and monitoring: logging, monitoring, debugging, and system failures.
- Edge computing and mobile ML: edge computing architecture, model compression, on-device inference frameworks,
  federated learning.
- MLOps and continuous deployment: CI/CD for ML, model lifecycle management, governance, and ethical
  considerations.
- Emerging topics: foundation models, distributed inference, serverless ML, and student project presentations.

By the end of this course, students will be able to:
- Design and implement end-to-end machine learning systems architecture.
- Engineer scalable data pipelines for ML workloads.
- Deploy and monitor ML models in production environments.
- Implement testing and quality assurance practices for ML systems.
- Optimize ML systems for performance and cost-effectiveness.
- Apply MLOps practices to ensure reproducibility and maintainability of ML systems.

This new course will be offered starting Fall 2027.
