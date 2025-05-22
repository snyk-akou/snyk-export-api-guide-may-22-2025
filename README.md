# Snyk Export API Guide

This repository provides a complete guide and example implementation for using the [Snyk Export API](https://docs.snyk.io/snyk-api-info/export-api), which enables scalable, secure exports of Snyk issue data for analytics, reporting, and compliance.

> ⚠️ The Export API is in **Early Access** and only available for **Enterprise** plans. Contact your Snyk account team to enable this feature.

---

## 📦 Contents

- 📁 `scripts/` — Shell scripts to initiate, track, and retrieve exports
- 📁 `examples/` — Sample API request bodies for group/org exports
- 📁 `docs/` — Detailed documentation of available filters and columns
- `.env.example` — Example env file to securely store your Snyk API token

---

## 🚀 How to Use

### 🔧 Setup

1. Clone this repo
2. Copy `.env.example` to `.env` and add your token:
   ```bash
   cp snyk.env.example .env
