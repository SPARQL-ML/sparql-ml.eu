---
icon: "material/account-group"
title: "Work Plan"
---
# Work Plan

## Work Package 1

This work package, led by OpenLink and involving all partners, aims to define the functional requirements for system components based on specific use cases and align these with the latest research developments. The process begins with a thorough analysis of current and envisioned states, forming the basis for a detailed requirements specification. In the subsequent phase, the consortium will design a technical architecture tailored to these requirements, which will guide the execution of other work packages.

## Work Package 2

This work package centers on integrating the Triple Store Tentris with the eccenca Corporate Memory data management platform to enhance its functionality and efficiency. The key objectives include utilizing Tentris as the backend for storing, managing, and querying Knowledge Graphs within Corporate Memory, and ensuring seamless integration and information retrieval. Additionally, the package focuses on enabling effective Knowledge Graph exploration and incorporating the Content Annotation Manager (CAM) tool into the workflow, thereby improving content annotation and management capabilities within the system.

## Work Package 3

This work package, led by the University of Paderborn, aims to develop a machine learning-based solution for optimizing SPARQL query processing in triplestores by applying Deep Reinforcement Learning (DRL) techniques. The primary goal is to improve query execution time by selecting the optimal join-order in query plans. The DRL framework will involve generating vector embeddings for input SPARQL queries, incorporating additional information as observations, and using a reward-based feedback system to refine the DRL agent's decision-making process. The developed optimization methods will be implemented in the Tentris triplestore and adopted by OpenLink's Virtuoso RDF Quad Store, with performance evaluations conducted using both real-world and synthetic SPARQL benchmarks. The outcome will include a Dockerized DRL-based SPARQL query optimizer, which will also support federated SPARQL queries in subsequent work packages.


## Work Package 4

This work package, led by UPB, focuses on developing an efficient DRL-based federated SPARQL query processing engine for executing queries across multiple public RDF data storage solutions. The primary goal is to enable seamless federation of SPARQL queries, optimizing the query execution plan by selecting the optimal join-order and identifying relevant endpoints for source selection. The finalized execution plan will be tested with different parallelism techniques to improve performance. The proposed methods will be implemented in the 3DFed engine and benchmarked against state-of-the-art federation engines like FedX and SemaGrow, with performance metrics including query execution time, source selection efficiency, and the number of intermediate results generated.

## Work Package 5

This work package, led by OpenLink, focuses on evaluating SPARQL-ML solutions through real-world and industry use cases. The Eccenca use case aims to enhance enterprise knowledge graph query runtime by leveraging Tentris and federated query optimization to address data access bottlenecks in large-scale environments. Eccenca will implement and benchmark these solutions with client query logs to improve services and maintain competitive positioning. The Paderborn use case will apply the developed methods to Linked TCGA, a vast RDF dataset of cancer patient data, to demonstrate scalability and practical benefits. Additionally, OpenLink will use LinkedGeoData and DBpedia, massive RDF datasets from OpenStreetMap and Wikipedia, to showcase the performance improvements achieved by the DRL agent developed in WP3, particularly in handling large-scale SPARQL queries.

## Work Package 6

The Innovation Management and Communication Strategy Work Package (WP6) is crucial to the project's success, focusing on maintaining progress, meeting milestones, and ensuring high-quality outcomes. It emphasizes internal coordination through iterative, agile methodologies, including Scrum, and supports this with tools for code management, continuous integration, and work tracking. WP6 also oversees innovation management, addressing quality control, risk, intellectual property, and exploitation management to ensure the project's financial and technical viability. Additionally, it manages communication, dissemination, and alignment among internal stakeholders, continuously monitoring and guiding project activities and deliverables.