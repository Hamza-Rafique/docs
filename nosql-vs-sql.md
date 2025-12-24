# NoSQL Databases Guide

## 1️⃣ What is NoSQL?

**NoSQL = Not Only SQL**

It means:
- Not fixed schema
- Scales easily
- Designed for speed, large data, distributed systems

👉 **Used in modern apps** (Netflix, Uber, Amazon, Twitter)

---

## 2️⃣ Types of NoSQL (VERY IMPORTANT)

### 1. Document DB (MongoDB)
- Stores JSON-like documents
- Flexible structure

**Example:**
```json
{
  "name": "Hamza",
  "skills": ["React", "Node"],
  "experience": 6
}

### Used for:

-  User profiles
-  Blogs
-  Products
- Dashboards

2. Key-Value DB (Redis)
Data stored as key → value

Extremely fast (in-memory)

Example:

text
"user:123" → "{ name: Hamza }"
Used for:

Caching

Sessions

Rate limiting

3. Columnar DB (Cassandra)
Stores data by columns

Great for big data & analytics

Used for:

Time-series data

Logs

Metrics

4. Graph DB (Neo4j)
Nodes + relationships

Used for:

Social networks

Recommendation engines

3️⃣ SQL vs NoSQL (REAL APP COMPARISON)
Feature	SQL (MySQL)	NoSQL (MongoDB)
Schema	Fixed	Flexible
Scaling	Vertical	Horizontal
Joins	Yes	Limited
Speed	Medium	High
Best for	Banking, ERP	Startups, APIs
📌 Real Example: E-commerce App
Users → MongoDB

Orders → MongoDB

Cart cache → Redis

Payments → SQL

👉 Hybrid systems are normal