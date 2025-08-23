# AI/ML Security Journey

A practical, security-first learning path from foundational math and ML to hands-on AI security, governance, and secure deployment.

## Structure
```
ai-ml-security-journey/
├── 01_math_basics/          # Practical math notebooks + exercises
├── 02_python_basics/        # Python + DS toolbelt
├── 03_ml_models/            # Classic ML models & evaluation
├── 04_dl_projects/          # Deep learning & transformers
├── 05_ai_security/          # Attacks, defenses, privacy, supply chain
├── 06_capstone_projects/    # End-to-end secure AI builds
├── templates/               # Notebook & report templates
└── assets/                  # Diagrams, figures
```

## How to Use
1. Create a virtual env and install deps:
   ```bash
   python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```
2. Start with `/ROADMAP.md` and follow week-by-week tasks.
3. Track progress in Notion (import the provided CSV) or update `/PROGRESS.md`.

## Deliverables to Showcase
- Reproducible notebooks and secure ML demos.
- Security assessments (attack → defense) with writeups in each project folder.
- Architecture diagrams and SBOM/security pipeline artifacts.