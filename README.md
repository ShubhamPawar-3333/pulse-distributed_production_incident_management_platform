# Pulse — Distributed Production Incident Management Platform

AI-powered incident management platform that ingests operational telemetry,
correlates events into incidents, and performs evidence-backed root-cause analysis.

## Quick Start

```bash
docker-compose up -d
cd backend && pip install -e ".[dev]"
uvicorn app.main:app --reload
```