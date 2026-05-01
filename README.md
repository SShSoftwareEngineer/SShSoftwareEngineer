<!--
**SShGitHubUser/SShGitHubUser** is a ✨ _special_ ✨ repository because its `README.md` (this file) 
appears on your GitHub profile.
-->

## Projects

- ### [Book Scraper](https://github.com/SShSoftwareEngineer/Book-Scraper.git)  
  Distributed web scraping system (Playwrite) with async processing and task queues.  
  Multi-stage pipeline: async scrapers collect HTML → task queue (queue.Queue or Celery) distributes to worker threads → parsers extract structured data → separate writer thread stores to PostgreSQL. Implements producer-consumer pattern, error handling, retry logic.   
  Key achievements:
  - Built distributed processing architecture with task queues
  - Implemented async scraping with rate limiting
  - Designed fault-tolerant pipeline with retry mechanisms
  - Optimized performance with multi-threading/multiprocessing
####
- ### [Telegram Saver](https://github.com/SShSoftwareEngineer/Telegram_Saver.git)  
  Data extraction and storage system for Telegram content with flexible retrieval options.  
  Key features:
  - Manual and automated data extraction from Telegram channels using Telethon API
  - SQLAlchemy ORM for database-agnostic storage (SQLite/PostgreSQL ready)
  - Processing of multiple content types: messages, media files, documents, user info, etc.
  - Web-based interface for saved content exploration (Flask + JavaScript)
  - Asynchronous operations with AsyncIO for efficient data handling
  Use case: Personal archive and data analysis tool for selective content preservation  
  Impact: 
  - Archived 2,000+ messages from monitored channels
  - Organized 500+ media files with metadata
  - Database design supports easy migration to PostgreSQL for scaling
####
- ### [Job Posting Parser](https://github.com/SShSoftwareEngineer/Job_Posting_Parser)  
  Multi-source job market intelligence system for automated vacancy data collection and analysis.  
  Key features:
  - Dual-source data extraction: Telegram channels (Telethon) + Email newsletters (IMAPClient)
  - Two-stage parsing: initial posts + full vacancy details from website links (BeautifulSoup, AIOHTTP)
  - Comprehensive data extraction: 18+ parameters per vacancy (position, salary, tech stack, location, experience, company details, etc.)
  - Concurrent scraping with rate limiting (AsyncIO Semaphore) to avoid blocking
  - Structured storage: SQLAlchemy ORM with SQLite (PostgreSQL-ready architecture)
  - Excel reporting with Pandas for stakeholder analysis  
  Use case: Job market trend analysis, salary benchmarking, technology demand tracking, career planning
  Impact:
  - Analyzed 3800+ job postings from multiple sources
  - 18 extracted fields enable multi-dimensional filtering and analysis
  - Identified salary trends, in-demand technologies, and remote work patterns  
####
- ### [Coop Manager](https://github.com/SShSoftwareEngineer/Coop_Manager.git)  
  Database design and Django backend for cooperative organization management system (garage cooperative case study).  
  Architecture & Data Model:
  - Designed normalized database schema with 8 interconnected models: Estate (garages, storage units, annexes), Person (members, family, tenants), Address, Contact, Relation (ownership, family ties, rental agreements)
  - Django ORM implementation with many-to-many and foreign key relationships
  - Flexible data model supports multiple property types and complex member relationships
  - SQLite (development), PostgreSQL-ready architecture  
  Current implementation:
  - Admin interface for member and property management (Django Admin)
  - Basic HTML templates for data viewing
  - CRUD operations via admin panel
  - Property assignment to members and related persons (family, tenants)  
  Use case: Digital transformation for cooperative administration, designed as universal solution applicable to garage, housing, or agricultural cooperatives  
  Project status: MVP/proof-of-concept demonstrating database architecture and Django backend capabilities

## Certificates

- [Python Developer Diploma](https://testprovider.com/ru/search-certificate/TP75891538D)
    - [Python Advanced](https://testprovider.com/ru/search-certificate/TP22720228)
    - [Databases. PostgreSQL](https://testprovider.com/ru/search-certificate/TP96877762)
    - [Git](https://testprovider.com/ru/search-certificate/TP29442845)
    - [Django Starter](https://testprovider.com/ru/search-certificate/TP42857906)
- [Docker](https://testprovider.com/ru/search-certificate/TP91237119)
- [HTML5&CSS3 Starter](https://testprovider.com/ru/search-certificate/TP24404857)
- [JavaScript Starter](https://testprovider.com/ru/search-certificate/TP13025243)
- [C++ Starter](https://testprovider.com/ru/search-certificate/TP07430920)

## Courses

ITVDN & CyberBionic Systematics  
[Python Developer](https://github.com/Studies-in-specialty-Python-Developer)
<details>
  <summary>Python Developer Study Program</summary>

* <b>Python</b>

1. Introduction to Python
2. Primitive data types and variables
3. Conditional constructions
4. Cyclic constructions
5. Sequences
6. Lists
7. Sets and mapping
8. Functions, part 1
9. Functions, part 2
10. PEP8
11. OOP. Classes, attributes, methods, constructor
12. OOP. Inheritance and abstraction
13. OOP. Encapsulation and polymorphism
14. Exceptions and their handling
15. Introspection and reflection
16. Iterators
17. Generators
18. Work with files
19. Modules and packages
20. Regular expressions
21. Elements of functional programming
22. Working with the network
23. Data warehouses
24. SQLite. Syntax and queries
25. Asynchronous programming in Python
26. Multithreaded programming in Python
27. Typed Python. Unit Testing
28. Practical lesson. Scraping
29. Practical lesson. SQLite
30. Virtual environments

* <b>Git</b>

1. Git Basics
2. Repository publication
3. IDE integration

* <b>Databases. PostgreSQL</b>

1. Creating infrastructure
2. Basic PostgreSQL data types and simple queries
3. Joining of tables (JOIN) and subqueries
4. Other objects of databases: views and functions
5. Database design. DDL - managing databases and database objects

* <b>Django Starter</b>

1. Introduction to Django
2. Routing
3. Templates and mappings
4. The models
5. The forms
6. Django ORM and admin panel
7. Django and REST. REST Overview, Django Rest Framework Overview
8. Django application deployment
9. Security in Django
10. Practical lesson. A ToDo list creation

</details>


ITVDN & CyberBionic Systematics  
Docker
<details>
  <summary>Docker Study Program</summary>

1. Introduction to Docker
2. Creation of a Docker image 
3. Running web-application in Docker
4. Orchestration in Docker
5. Docker tools

</details>

[![SShSoftwareEngineer profile views](https://u8views.com/api/v1/github/profiles/126820296/views/day-week-month-total-count.svg)](https://u8views.com/github/SShSoftwareEngineer)