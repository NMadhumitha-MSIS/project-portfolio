# Project Portfolio - Madhumitha Nandhikatti

Master of Science in Information Systems (MSIS) graduate student at Northeastern University with experience across data analytics, backend systems, cloud technologies, and fullstack development.

This repository serves as a central hub for my academic, professional, and personal projects across data science, software engineering, cloud, and systems design.

## Featured Projects
### MarketFlow - Real-Time Market Data Stream Processor (C++)
**Tech:** C++, STL, Statistical Analysis, Data Pipelines

- Engineered a C++ stream processing engine that generates and ingests 10,000+ simulated market price points, modeling real-world volatility with configurable random walk and 1% probability spike injection events
- Implemented a 20-period rolling moving average algorithm from scratch using STL vectors, computing buy/sell signals by comparing live price against the smoothed baseline at each time step
- Designed a statistical anomaly detection system using a 2-standard-deviation threshold, flagging 775 anomalies (7.7% rate) across 10,000 data points including engineered extreme spike events of ±$15–$30
- Exported structured anomaly reports to CSV with timestamp, price, moving average, standard deviation, and deviation columns, enabling downstream analysis and visualization pipelines

Repository: https://github.com/NMadhumitha-MSIS/MarketFlow

### Drug Interaction Checker
**Tech:** Python, LangChain, FAISS, LLaMA 3.1 8B (Groq), NIH RxNorm API, FDA OpenFDA API, RAG

- Built an AI-powered drug interaction checker for non-expert caregivers, grounded in official FDA label data using Retrieval-Augmented Generation (RAG)
- Normalizes brand names to generic via NIH RxNorm API, then retrieves live FDA drug labels for each drug
- Uses FAISS vector store + LangChain with LLaMA 3.1 8B (via Groq) to generate plain-English interaction summaries with citations
- Includes a completeness check that blocks output and warns users if any drug label fails to retrieve
- Evaluated across 50 drug pairs (high severity, moderate, and control cases) with a target silent failure rate of 0%

Repository: https://github.com/Gagana2572/Drug-Interaction-Checker

### Madison RL Intelligence Agent
**Tech:** Python, Reinforcement Learning, Contextual Bandits, REINFORCE, Groq LLaMA, Wikipedia, arXiv, Reddit, DuckDuckGo

- Reinforcement learning system integrated into the Humanitarians.AI Madison agent framework for autonomous research and analysis
- Implements two RL approaches: Contextual Bandits with UCB1 for per-step source selection, and REINFORCE with baseline for episode-level policy learning
- Queries five free data sources (Wikipedia, arXiv, Reddit, DuckDuckGo) with Groq LLaMA synthesizing final intelligence reports
- Built a custom RewardSignalEngine scoring fetched content on success, length, and keyword relevance, clipped to [-1.0, 2.0]
- UCB Bandit improved average reward from 0.590 to 0.873 over training; REINFORCE improved from 0.465 to 0.553
- Fully CPU-compatible; runs in ~5–8 minutes on Google Colab with no GPU required

Repository: https://github.com/NMadhumitha-MSIS/Madison-RL-Agent

### Instacart Customer Behavior & Product Popularity Analysis
**Tech:** Python, Pandas, Scikit-learn, EDA, K-Means, Random Forest  
- Analyzed 3M+ grocery orders to uncover customer behavior and reorder patterns  
- Segmented customers using RFM metrics and K-Means clustering  
- Predicted product popularity using ML models, with Random Forest performing best  
- Delivered actionable insights for inventory planning and personalized marketing 

Repository: https://github.com/NMadhumitha-MSIS/instacart-customer-behavior-ml

### NetGuard – Cyberattack Detection Simulation (Java)
- Simulated real-time cyberattack propagation across a network graph
- Implemented Dijkstra’s algorithm using a custom MinHeap for packet routing
- Built a recursive DefenseAI to isolate infected nodes and contain threats
- Visualized infection spread and containment using a Java Swing GUI  

Repository: https://github.com/NMadhumitha-MSIS/netguard-cyberattack-simulation

### E-Commerce Retail Platform - Database Management & Analytics
- Designed a CRUD-based retail system using MySQL with stored procedures and triggers
- Handled 30+ transactional workflows reliably with strong data integrity
- Built ETL pipelines and KPI dashboards in Power BI for customer and inventory insights
- Explored Apache Spark for scalable transaction analytics  

Repository: https://github.com/NMadhumitha-MSIS/ecommerce-retail-dbms-analytics

### Cloud-Native Web Application (AWS + Terraform + DevOps)
- Deployed a production-grade Node.js application on AWS using Infrastructure as Code (Terraform)
- Implemented CI/CD pipelines with GitHub Actions and built custom AMIs using Packer
- Designed a highly available and secure architecture with ALB, Auto Scaling, RDS, and CloudWatch
- Simulated real-world collaboration between Application and Platform teams  

Repository: https://github.com/NMadhumitha-MSIS/cloud-native-aws-terraform-devops

### YouthWise - Java Application Dashboard
- Built a Java Swing dashboard to track academic, health, and sports data for 50+ users
- Integrated interactive visualizations using Chart.js
- Improved usability and data accessibility through role-based UI components  

Repository: https://github.com/NMadhumitha-MSIS/youthwise-java-dashboard

### Ampan (AA) & Co - Fullstack E-Commerce Website
- Developed a multi-role e-commerce platform with admin and user dashboards
- Built product catalogs, cart modules, and responsive UI across 15+ pages
- Integrated PayPal sandbox payments and optimized UI/UX performance  

Repository: https://github.com/NMadhumitha-MSIS/ampan-aa-co-ecommerce

### TRUNK: E-Vault - Blockchain-Based Document Storage
- Designed a decentralized document storage system using Solidity and IPFS
- Enabled secure, tamper-proof file management on Ethereum
- Processed blockchain transaction logs using Pandas and NumPy for transparency  

Repository: Coming soon

### Missing Person Finder - Android Mobile Application
- Co-developed a community-driven Android app for locating missing persons
- Implemented authentication, profile management, and community posting features
- Designed XML-based screens and Java backend logic for smooth user flows  

Repository: Coming soon

### PBL Hub - MERN Stack Learning Platform
- Built a collaborative learning and grading platform using MERN stack
- Supported 25+ students and reduced grading time by 25%
- Created Tableau dashboards for fast student performance insights  

Repository: Coming soon

## Skills & Tools
### Programming Languages
- Python, Java, SQL, JavaScript

### Data Science & Analytics
- Exploratory Data Analysis (EDA)
- Machine Learning (Logistic Regression, Decision Trees, Random Forest, K-Means)
- Feature Engineering & Model Evaluation
- Pandas, NumPy, Scikit-learn
- Power BI, Tableau

### Databases & Data Engineering
- MySQL, PostgreSQL, MongoDB
- Stored Procedures, Triggers, ER Modeling
- ETL Pipelines
- Apache Spark (introductory / academic)

### Backend & Systems
- Node.js, Express.js
- REST APIs, Postman
- Java Swing (desktop applications)
- Data Structures & Algorithms (Graphs, Queues, Heaps, Recursion)

### Cloud & DevOps
- AWS (EC2, RDS, S3, ALB, Route 53, CloudWatch, KMS, Secrets Manager)
- Infrastructure as Code (Terraform)
- CI/CD (GitHub Actions)
- Packer, Linux, Bash

### Frontend & Mobile
- React.js, HTML, CSS, Bootstrap
- Chart.js
- Android Development (Java, XML)

### Blockchain & Web3
- Solidity
- Ethereum, MetaMask
- IPFS
- Web3.js
- Cryptographic Hashing (SHA-256)

### Tools & Platforms
- Git, GitHub
- NetBeans, Android Studio
- Jupyter Notebook
- Figma

## Links
- [Resume](https://docs.google.com/document/d/18yOjV_jlpMswW078qHHbbtyZsct-ky6p5ZISJQZnGsU/edit?usp=sharing)
- [LinkedIn](https://www.linkedin.com/in/n-madhumitha/)
