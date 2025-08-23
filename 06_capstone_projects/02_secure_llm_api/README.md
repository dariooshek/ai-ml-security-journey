# Capstone 2 — Secure LLM API

## Goal
Expose a small local text-generation or classification model via FastAPI with authn/z, rate limiting, input validation, and content controls.

## Tasks
- Minimal model (HF transformers or distilled classifier)
- API with FastAPI
- Middleware: auth, rate limit, logging/redaction
- Abuse monitoring & tests