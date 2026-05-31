# 🏴‍☠️ Dev's First Mate
> WeMakeDevs Hackathon — Pirates of Coral-bean | Track 2: Personal Agent

![Live Demo (https://img.shields.io/badge/%F0%9F%8C%90_Live_Demo-devs--first--mate.onrender.com-blue)](https://devs-first-mate.onrender.com)
![Built with Coral (https://img.shields.io/badge/Powered_by-Coral_SQL-0A7C8A)](https://git.new/coral-wemakedevs-may26)
![Python (https://img.shields.io/badge/Python-3.11-yellow?logo=python)](https://python.org)
![Flask (https://img.shields.io/badge/Flask-Backend-black?logo=flask)](https://flask.palletsprojects.com)
![Deployed on Render (https://img.shields.io/badge/Deployed_on-Render-46E3B7?logo=render)](https://render.com)

> *"What needs my attention today?"* — answered in one shot by joining GitHub and Slack through Coral (https://git.new/coral-wemakedevs-may26)'s unified SQL runtime.

---

## 👥 Crew

| Member | GitHub |
|---|---|
| Sagar Maurya | @mauryasagar (https://github.com/mauryasagar) |
| Disha Sonowal | @ritamonisonowal2 (https://github.com/ritamonisonowal2) |

---

## 🎯 The Problem

Developers context-switch constantly — GitHub for issues and PRs, Slack for team discussions. There's no single place that says *"here's what actually matters right now."* Every tool requires separate logins, separate queries, and mental stitching.

---

## ✨ What Dev's First Mate Does

- 🐛 Triages open GitHub issues — ordered by recency so nothing falls through
- 🔁 Detects duplicate issues — using keyword matching to cut noise
- ✅ Drafts release notes — auto-generated from merged PRs
- 💬 Shows Slack activity — recent channel messages in context
- ⚡️ Cross-source JOIN — GitHub + Slack answered in one Coral SQL query
- 🤖 MCP Integration — AI agents can query your data directly via Coral's MCP server

---

## 📸 Screenshots

!Dev's First Mate Dashboard

---

## 🛠️ Coral Features Used

| Feature | How We Used It |
|---|---|
| SQL Interface | coral sql "SELECT ..." to query GitHub & Slack |
| Cross-source JOIN | FROM github.issues JOIN slack.messages in a single query |
| Schema Learning | SELECT * FROM coral.tables to discover available data |
| MCP Server | coral mcp to expose data to AI agents |
| Caching | Built-in Coral caching on repeated queries for speed |
| Source Discovery | coral source discover to explore bundled sources |

---

## 🚀 Tech Stack

| Layer | Technology |
|---|---|
| Data Runtime | Coral — Cross-source SQL |
| Backend | Flask (Python) |
| Frontend | HTML / CSS |
| Deployment | Render (Free tier) |

---

## ⚡️ Coral SQL Queries

### Open Issues Triage
