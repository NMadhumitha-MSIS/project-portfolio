# Madhumitha Nandhikatti: Project Portfolio

Master of Science in Information Systems (MSIS) graduate student at Northeastern University with experience across data analytics, backend systems, cloud technologies, and fullstack development.

This repository serves as a central hub for my academic, professional, and personal projects across data science, software engineering, cloud, and systems design.

## Links
- [Resume](https://docs.google.com/document/d/18yOjV_jlpMswW078qHHbbtyZsct-ky6p5ZISJQZnGsU/edit?usp=sharing)
- [LinkedIn](https://www.linkedin.com/in/n-madhumitha/)

## Featured Projects

### Access Checker: Small Business Accessibility Scanner (Node.js + Express)

**Tech:** Node.js, Express, Puppeteer, axe accessibility engine, JavaScript, HTML/CSS

- Built a web tool that scans small business websites for accessibility barriers and explains each problem in plain English for owners who are not technical
- Runs real browser audits with Puppeteer and the axe accessibility engine, with an Express API that ranks findings from critical to minor
- Created a plain English rule library covering 26 accessibility rules, expanded whenever real scans surfaced new issues
- Field tested on 9 Boston area small business websites, finding problems on 7 of 8 scannable sites, with low contrast text as the most common issue
- Detects bot protection pages to avoid misleading reports, after screenshot debugging showed a scan had checked a security page instead of the real site

Repository: https://github.com/NMadhumitha-MSIS/access-checker

### Drug Interaction Checker

**Tech:** Python, LangChain, FAISS, LLaMA 3.1 8B (Groq), NIH RxNorm API, FDA OpenFDA API, RAG

- Built an AI drug interaction checker for caregivers without medical training, grounded in official FDA label data using Retrieval Augmented Generation (RAG)
- Converts brand names to generic names with the NIH RxNorm API, then retrieves live FDA labels for each drug
- Uses a FAISS vector store and LangChain with LLaMA 3.1 8B (via Groq) to write plain English interaction summaries with citations
- Blocks the answer and warns the user if any drug label fails to load, so caregivers never get a silently incomplete result
- Evaluated across 50 drug pairs (high severity, moderate, and control cases) with a target silent failure rate of 0%

Repository: https://github.com/Gagana2572/Drug-Interaction-Checker

### GovSpend: Federal Spending Data Pipeline (Python + PostgreSQL)

**Tech:** Python, PostgreSQL, Streamlit, REST API, pandas

- Built a complete data pipeline that fetches real US federal contract data from the USASpending.gov public API, processing over $679.5B in government awards
- Designed a PostgreSQL schema to store, query, and manage award records with automated daily ingestion
- Built a data cleaning layer that normalizes messy government descriptions and sorts contracts into spending tiers (Mega 10B+, Large, Medium, Small)
- Developed an interactive Streamlit dashboard with filtering by agency, charts of top recipients, and a searchable data table

Repository: https://github.com/NMadhumitha-MSIS/govspend

### Instacart Customer Behavior and Product Popularity Analysis

**Tech:** Python, pandas, EDA, KMeans, Random Forest

- Analyzed over 3 million grocery orders to uncover customer behavior and reorder patterns
- Segmented customers using RFM metrics and KMeans clustering, identifying a loyal VIP group
- Predicted product popularity with machine learning, with Random Forest performing best
- Turned findings into practical recommendations for inventory planning and personalized marketing

Repository: https://github.com/NMadhumitha-MSIS/instacart-customer-behavior-ml

## More Projects

### Madison RL Intelligence Agent

**Tech:** Python, Reinforcement Learning, Contextual Bandits, REINFORCE, Groq LLaMA

- Reinforcement learning system for the Humanitarians.AI Madison agent that learns which research sources give the most useful results
- Uses Contextual Bandits with UCB1 for per step source selection and REINFORCE with baseline for episode level policy learning
- Queries free data sources (Wikipedia, arXiv, Reddit, DuckDuckGo), with Groq LLaMA writing the final reports
- UCB Bandit improved average reward from 0.590 to 0.873 over training, and runs fully on CPU in about 5 to 8 minutes

Repository: https://github.com/NMadhumitha-MSIS/Madison-RL-Agent

### MarketFlow: Real Time Market Data Stream Processor (C++)

**Tech:** C++, STL, Statistical Analysis, Data Pipelines

- Built a C++ stream processing engine that generates and ingests 10,000+ simulated market prices with realistic volatility and injected spike events
- Implemented a 20 period rolling moving average from scratch to produce buy and sell signals
- Flagged 770 anomalies (7.7% rate) using a two standard deviation threshold, exported to CSV for further analysis

Repository: https://github.com/NMadhumitha-MSIS/MarketFlow

### NetGuard: Cyberattack Detection Simulation (Java)

- Simulated real time cyberattack spread across a network graph of servers
- Implemented Dijkstra's algorithm with a custom MinHeap for packet routing, and a recursive defense algorithm that isolates infected nodes
- Visualized infection spread and containment in a Java Swing interface

Repository: https://github.com/NMadhumitha-MSIS/netguard-cyberattack-simulation

### Cloud Native Web Application (AWS + Terraform + DevOps)

- Deployed a production grade Node.js application on AWS using Infrastructure as Code (Terraform)
- Built CI/CD pipelines with GitHub Actions and custom AMIs with Packer
- Designed a highly available, secure architecture with ALB, Auto Scaling, RDS, and CloudWatch

Repository: https://github.com/NMadhumitha-MSIS/cloud-native-aws-terraform-devops

### Ecommerce Retail Platform: Database Management and Analytics

- Designed a MySQL retail system with stored procedures and triggers, handling 30+ transactional workflows reliably
- Built ETL pipelines and Power BI dashboards for customer and inventory insights

Repository: https://github.com/NMadhumitha-MSIS/ecommerce-retail-dbms-analytics

### YouthWise: Java Application Dashboard

- Built a Java Swing dashboard with Chart.js visualizations tracking academic, health, and sports data for 50+ users

Repository: https://github.com/NMadhumitha-MSIS/youthwise-java-dashboard

### Ampan (AA) & Co: Full Stack Ecommerce Website

- Developed an ecommerce platform with admin and user dashboards, product catalogs, and cart modules across 15+ pages
- Integrated PayPal sandbox payments

Repository: https://github.com/NMadhumitha-MSIS/ampan-aa-co-ecommerce

### TRUNK: E Vault, Blockchain Document Storage

- Designed a decentralized document storage system using Solidity, Ethereum, and IPFS for tamper resistant file management

Repository: Coming soon

### Missing Person Finder: Android Mobile Application

- Built with a teammate: a community Android app for sharing and finding missing persons information, with login, profiles, and posts

Repository: Coming soon

### PBL Hub: MERN Learning Platform

- Built a learning and grading platform using the MERN stack that supported 25+ students and reduced grading time by 25%

Repository: Coming soon

## Skills and Tools

**AI, ML, and Data Science:** Retrieval Augmented Generation (RAG), LLM integration (LLaMA, Groq), LangChain, FAISS, Reinforcement Learning, Exploratory Data Analysis, Machine Learning (Logistic Regression, Decision Trees, Random Forest, KMeans), pandas, NumPy, Power BI, Tableau

**Databases and Data Engineering:** MySQL, PostgreSQL, MongoDB, Stored Procedures, Triggers, ER Modeling, ETL Pipelines, Apache Spark (introductory)

**Backend and Systems:** Node.js, Express.js, REST APIs, WebSocket, Postman, Java, Data Structures and Algorithms

**Cloud and DevOps:** AWS (EC2, RDS, S3, ALB, Route 53, CloudWatch, KMS, Secrets Manager), Terraform, CI/CD (GitHub Actions), Packer, Linux, Bash

**Frontend and Mobile:** React.js, Next.js, HTML, CSS, Tailwind CSS, Bootstrap, Chart.js, Android (Java, XML)

**Accessibility and Testing:** Puppeteer, axe accessibility engine, WCAG accessibility guidelines

**Blockchain:** Solidity, Ethereum, MetaMask, IPFS, Web3.js

**Tools:** Git, GitHub, VS Code, NetBeans, Android Studio, Jupyter Notebook, Figma
