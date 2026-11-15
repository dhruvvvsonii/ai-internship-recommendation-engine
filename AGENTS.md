# Project: AI-Based Internship Recommendation Engine for PM Internship Scheme

## 1. Project Objective

Build a production-quality academic major project that recommends suitable PM Internship Scheme opportunities to students based on:

- Eligibility
- Education
- Skills
- Interests
- Location
- Preferences
- Career goals

The system must provide explainable recommendations and identify skill gaps.

## 2. Technology Stack

### Frontend
- React
- Tailwind CSS
- JavaScript/TypeScript
- Axios
- React Router
- Recharts

### Backend
- Python
- FastAPI
- REST API
- JWT Authentication

### Database
- PostgreSQL

### Machine Learning
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF
- Cosine Similarity
- Sentence Transformers/Embeddings

### Development Tools
- Git
- GitHub
- VS Code
- Postman
- Docker

## 3. Core Features

1. Student registration and authentication
2. Student profile management
3. Education information
4. Skills management
5. Internship database
6. Internship eligibility checking
7. AI-based internship recommendations
8. Match score
9. Explainable recommendations
10. Skill-gap analysis
11. Resume analysis
12. Internship saving
13. Application tracking
14. Admin dashboard

## 4. AI Recommendation Principles

The recommendation engine should:

- First check eligibility.
- Compare student skills with internship requirements.
- Consider education and interests.
- Consider location and preferences.
- Calculate a transparent match score.
- Rank suitable internships.
- Explain why an internship was recommended.
- Identify missing skills.

Do not make an LLM the sole recommendation engine.

The core recommendation logic must be deterministic/ML-based and testable.

## 5. Data Rules

- Do not invent real PM Internship Scheme data.
- Use official/public data where permitted.
- Clearly label synthetic data used for development or testing.
- Validate and clean datasets before using them.
- Keep raw and processed data separate.

## 6. Security Rules

- Never hardcode passwords, API keys, tokens, or secrets.
- Use environment variables.
- Hash passwords securely.
- Validate user input.
- Protect APIs with authentication where required.
- Use proper authorization and role-based access control.
- Validate uploaded files.
- Protect against SQL injection.
- Configure CORS correctly.

Never commit `.env` files or secrets to GitHub.

## 7. Code Quality Rules

- Follow modular architecture.
- Keep frontend, backend, ML, database, and tests separated.
- Avoid unnecessarily large files.
- Use meaningful variable and function names.
- Write reusable components and services.
- Add error handling.
- Add tests for important functionality.
- Do not modify unrelated files.
- Do not remove existing functionality without a reason.

## 8. Development Workflow

Follow this workflow:

PLAN
↓
DESIGN
↓
IMPLEMENT ONE MODULE
↓
TEST
↓
REVIEW
↓
COMMIT
↓
NEXT MODULE

Do not generate the entire application at once.

Before making major architectural changes, explain the change and its reason.

## 9. Git Commit Convention

Use meaningful commit messages such as:

- `feat: add student authentication`
- `feat: add internship database`
- `feat: add eligibility engine`
- `feat: add recommendation engine`
- `fix: resolve recommendation scoring`
- `refactor: improve database service`
- `test: add recommendation tests`
- `docs: update project documentation`

## 10. Academic Project Requirements

The project must be suitable for a BTech CSE major project.

Important areas that should be demonstrable during the project viva:

- System architecture
- Database design
- API design
- Recommendation algorithm
- NLP processing
- Machine learning methodology
- Match-score calculation
- Explainability
- Skill-gap analysis
- Model evaluation
- Testing
- Security
- Deployment

Do not invent experimental results or evaluation metrics.

All ML performance metrics must come from actual experiments.

## 11. AI Coding Assistant Rules

Before writing substantial code:

1. Inspect the existing project structure.
2. Read `AGENTS.md`.
3. Understand the existing implementation.
4. Explain the planned changes.
5. Implement only the requested module.
6. Run relevant tests.
7. Report what was changed.
8. Report any remaining issues.

Do not rewrite the entire project when fixing a small problem.

## 12. Project Principle

The system is not simply another internship listing website.

Its primary purpose is:

> Determine which PM Internship Scheme opportunities are most suitable for a particular student, whether the student is eligible, why the opportunity matches, what skills are missing, and what the student should do next.