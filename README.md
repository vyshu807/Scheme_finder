# Scheme Finder

Helps people find the government schemes they are eligible for, in simple language (English, Telugu, Hindi).

## The problem

Many students and families miss government schemes, scholarships and subsidies because:

- They don't know the schemes exist
- They can't tell if they qualify
- Information is scattered across many websites and mostly in English

## What this project does

1. The user answers a few simple questions (age, state, income, occupation, education).
2. The app checks the answers against each scheme's eligibility rules.
3. The user sees three groups:
   - **Eligible**: with the reason, documents needed and how to apply
   - **Almost eligible**: with exactly what is missing
   - **Not eligible**: with the reason

Eligibility is decided by rules stored as data, not by AI. AI is only used to explain schemes in simple language and translate them.

## Current scope

- State: Andhra Pradesh (plus central schemes)
- Category: education and scholarships first

## Tech stack (planned)

- Backend: FastAPI
- Database: PostgreSQL
- Frontend: mobile-friendly web app
- Languages: English, Telugu, Hindi

## Roadmap

- [ ] Week 1: collect 15-20 verified schemes and talk to 5 real users
- [ ] Week 2: database design and rules engine
- [ ] Week 3-4: backend API and tests
- [ ] Week 5-6: frontend
- [ ] Week 7-8: multilingual support and AI explanations
- [ ] Week 9+: real user testing and feedback

## User research

_To be filled after talking to 5 people: what they know, what they missed, what was hard._

## Data and limitations

- Scheme data comes from official government sources only.
- Rules can change. Every result should be confirmed on the official website.
- No personal user data is stored without consent.
