# Matthew McCrory's Project Portfolio

Computer Science @ Georgia Tech | Software Engineering · Full-Stack · Applied AI · Automation

A collection of selected software engineering projects demonstrating experience building full-stack applications, AI-powered systems, automation tools, and data-driven software.

---

## Commercial Real Estate Site Feasibility Platform

**Tech:** React, TypeScript, Python, FastAPI, Leaflet, REST APIs, GIS, AI

Built and deployed an end-to-end site feasibility platform during my AI internship at Macallan Real Estate to streamline how commercial real estate brokers evaluate potential sites.

- Designed a React + TypeScript frontend with an interactive Leaflet map and configurable 1-, 3-, and 5-mile analysis radii.
- Built a FastAPI backend integrating property, demographic, traffic, business, and geospatial data from multiple external services.
- Integrated Google Geocoding and Places, Realie property data, FEMA flood data, GDOT traffic data, and Esri Business Analyst.
- Added AI-generated analysis to transform raw property and market data into concise site summaries.
- Built the application around real brokerage workflows and deployed it for internal company use.
- Designed failure handling around third-party APIs and inconsistent external data sources.

> Source code is private because this project was developed for an employer.

---

## [LLM Gateway — Cost-Aware Multi-Provider Router](https://github.com/mmccrory21/llm-gateway)

**Tech:** Next.js, TypeScript, LLM Routing, Cost Optimization, Analytics

Built an LLM gateway that analyzes incoming prompts and routes requests to different model tiers based on task type and complexity rather than sending every request to the most expensive model.

- Classifies prompts across categories including Q&A, summarization, code generation, creative writing, and complex reasoning.
- Generates a complexity score and maps requests to economy, standard, or frontier model tiers.
- Routes requests across simulated OpenAI, Anthropic, and Gemini provider/model combinations.
- Estimates token usage, request cost, latency, and savings relative to an always-frontier baseline.
- Tracks routing history and aggregate metrics including total spend, savings percentage, latency, and model distribution.
- Built a Next.js dashboard for visualizing routing decisions and cumulative savings.

The current version simulates provider calls so the routing and accounting pipeline can run without external API keys while keeping the architecture ready for real provider SDK integration.

---

## GSCCCA Deed Transfer Lookup Automation

**Tech:** Python, Playwright, Browser Automation, Data Extraction

Developed an automated property-record research workflow during my commercial real estate internship to reduce repetitive deed-transfer research.

- Automated property-record searches using Python and Playwright.
- Extracted grantor, grantee, deed, and transfer information from search results.
- Designed batch-processing workflows to handle searches across multiple date ranges.
- Reduced repetitive browser navigation required for property research.
- Built the tool as a command-line workflow that could fit into existing brokerage research processes.

> Source code is private because this project was developed for an employer.

---

## [Movie Store Web Application](https://github.com/mmccrory21/moviesstore)

**Tech:** Python, Django, HTML/CSS

Built a Django-based web application for browsing and purchasing movies.

- Structured the backend using separate Django modules for movies, accounts, shopping-cart functionality, and core application pages.
- Implemented user-facing movie browsing and e-commerce workflows.
- Worked with Django's server-side architecture and modular application design.
- Developed experience connecting application logic, templates, routing, and persistent data in a full-stack web application.

---

## Technical Skills

**Languages:** Python, Java, C, JavaScript, TypeScript, SQL

**Frontend:** React, Next.js, HTML/CSS, Leaflet

**Backend:** FastAPI, Django, REST APIs

**AI & Data:** LLM Applications, Prompt Routing, AI API Integration, Data Processing

**Tools:** Git, GitHub, Linux, Render, Playwright, Selenium, MySQL

**Concepts:** Full-Stack Development, API Integration, Web Automation, Geospatial Applications, Data Structures & Algorithms

---

## About Me

I'm a Computer Science student at the Georgia Institute of Technology pursuing the **Intelligence and Internetworks** threads.

I enjoy building software that solves real problems for real users. My experience spans full-stack engineering, applied AI, automation, data analysis, and integrating complex third-party systems into usable products.

I'm particularly interested in software engineering opportunities involving **backend systems, full-stack products, infrastructure, and applied AI**.

---

## Currently Exploring

I'm continuing to build projects around production-oriented AI systems, particularly problems involving **model routing, cost optimization, latency, reliability, and observability**, while strengthening my foundations in algorithms and computer systems.

---

## Connect

**GitHub:** [mmccrory21](https://github.com/mmccrory21)

**School:** Georgia Institute of Technology

**Focus:** Software Engineering · Full-Stack Development · Applied AI · Automation
