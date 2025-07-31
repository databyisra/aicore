# HRIS SQL Query Organizer – AWS PartyRock App

## Overview

This app was created by me for HRIS analysts to organize, manage, and maximize the reuse of a large collection of prewritten SQL queries related to HR data analytics. Built with AWS PartyRock, it addresses the challenges of finding, understanding, and maintaining SQL statements that answer HR business questions.

## My Original Prompt

*This app was created based on the following prompt:*

> Develop an application for HRIS analysts that streamlines the organization and management of a large repository of prewritten SQL queries. The app should enable users to upload or input SQL statements, provide plain-language descriptions of each query’s purpose, and categorize them based on the HR topics or questions they address. Users should have the ability to search or enter natural language questions (for example, “How many new hires this year?”), with the app returning the most relevant SQL statements in response. Additionally, the app should identify and assist in correcting SQL issues such as syntax errors, spelling mistakes, incorrect date formats, and inefficient or incompatible code—especially those issues that can arise when transferring queries between different SQL platforms or environments. The overarching aim is to enhance query reuse, minimize errors, and make it easier to locate and understand SQL that is relevant to HR data analytics.

## Key Features

- **SQL Query Collection:** Upload or input SQL statements into the app.
- **Plain Language Descriptions:** Describe the purpose and logic of each query in everyday language so anyone can understand its intent.
- **Categorization:** Categorize queries by the type of HR question they answer (e.g., headcount, new hires, turnover, diversity, etc.).
- **Search & Natural Language Q&A:** Enter a natural language question (e.g., “How many new hires this year?”) and get the most relevant SQL queries returned.
- **Error Detection & Correction:** The app automatically detects and helps fix common SQL issues, such as:
  - Syntax errors
  - Spelling mistakes
  - Incorrect date formats
  - Bad coding practices
  - Problems encountered when moving queries between tools (e.g., TOAD to VS Code)
- **Improved Query Reuse:** Make it easier to find, understand, and reuse existing queries, reducing time spent writing new SQL from scratch.
- **Error Reduction:** Catch and fix issues early, reducing errors in HR data analysis.

## Example Use Cases

- An analyst wants to answer “How many employees left last quarter?” – enter the question, and the app surfaces relevant queries.
- Migrating SQL code from different platforms? The app helps detect and resolve compatibility issues.
- Build a library of trusted, well-documented queries for common HR metrics and reporting needs.

## Benefits

- **Faster Answers:** Quickly find SQL to answer HR questions.
- **Better Understanding:** Descriptions and categories make queries easier to interpret and use.
- **Higher Data Quality:** Automated checks improve SQL accuracy and reduce reporting errors.
- **Collaboration:** Share and improve the query library with teammates.

---

> **Goal:** Improve query reuse, reduce errors, and make it easier to find and understand SQL relevant to HR data questions.

---

## Prompt Engineering

I created this app using prompt engineering techniques to help HRIS analysts organize, search, and validate SQL queries for HR analytics. The prompt focuses on enabling users to upload SQL files, input queries, describe them in plain English, and search for relevant queries using natural language. The app also provides error detection and suggestions to improve SQL quality.

---

## App Interface

### App Landing Page

![QueryHR Hub Landing Page](https://i.postimg.cc/X72Gy0hr/Screenshot-2025-07-31-at-10-22-27-AM.png)

*Users can upload SQL files, input queries, provide descriptions, and search using plain English questions.*

### Query Analysis & Helper Widgets

![QueryHR Hub Analysis and Helper](https://i.postimg.cc/JzDnDHZF/Screenshot-2025-07-31-at-10-22-46-AM.png)

*The app provides SQL analysis, matches queries to natural language questions, and offers a helper chat for further assistance.*

---
