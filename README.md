# XcelerateIT Phase 2 Integration Challenge – Smart Job Board + Resume Matcher

Welcome to Phase 2 of the XcelerateIT Hiring Process.

This challenge evaluates your ability to **collaborate across roles** and build a working, integrated solution that combines a full-stack job platform with an AI-powered resume matcher.

You will work together (one Full Stack Developer + one AI/ML Developer) to deliver a unified application.

---

## Objective

Integrate the previously built Full Stack Job Board and Resume Matcher to create a seamless product where:

- Employers can post jobs (as before)
- Job seekers can upload their resume
- The system returns top 3 matching jobs for the resume
- A clear explanation is shown for why the match was made

---

## Key Features to Implement

### Resume Upload and Matching Integration

- Job seeker can upload a resume from the frontend
- Resume is sent to the AI/ML resume matcher backend
- Matcher returns:
  - Top 3 matched jobs
  - Match score
  - Matched skills/phrases

### UI Integration

- Match results are displayed to the job seeker on the frontend
- Optional: provide button to "Apply" for matched jobs

### System Communication

- Resume file → AI API → Results → UI
- Must be functional end-to-end, not mocked

---

## Tech Stack Guidelines

You must reuse your own tech stack from Phase 1.

### Integration Requirements

- Frontend must connect to AI/ML backend via REST API
- Deployment can be local or cloud (Streamlit/Render/Vercel)
- Code should be modular and properly commented

---

## Collaboration Guidelines

- Use GitHub with a shared repo or two linked repos
- Maintain clear Git history per developer
- Both candidates must:
  - Contribute to integration
  - Be able to explain how the integration works
  - Join the final demo session together

---

## Submission Instructions

1. Create a new repo (or use one candidate's repo) for the integrated project.
2. Push all integrated code with:
   - Clear separation of frontend, backend, and AI logic
   - `README.md` updated with:
     - Setup instructions
     - Integration flow (1–2 paragraph explanation)
     - Sample resume + sample output screenshot
4. Submit your GitHub repo link to the following email ID:  
    **support@xcelerateit.ai**
5. Use the subject line:  
   `[Role] - [Your Full Name] - GitHub Submission`  
   Example: `AI/ML Developer - Anjali Mehta - GitHub Submission`   

---

## Evaluation Criteria

| Area                | What We're Looking For                              |
|---------------------|------------------------------------------------------|
| Collaboration        | Clear handoff, coordination, and Git history        |
| Functional Integration | End-to-end flow from UI → API → AI → results     |
| Code Ownership       | Each member can explain their contribution          |
| UI Experience        | Clean display of results and UX consistency         |
| Bonus                | Deployed version, retry logic, or enhanced filtering|

---

## Time Expectation

- Duration: **1–2 days**
- Final review includes:
  - Live demo
  - Q&A with both candidates

---

## FAQs

**Q. Can we use tools like Postman or Swagger to test APIs?**  
Yes, but final demo must show UI + API + AI integration working end-to-end.

**Q. Can we collaborate on Google Meet or GitHub Projects?**  
Yes. We encourage structured collaboration and clarity.

**Q. Will this project be evaluated independently?**  
No. This is a **joint evaluation**, and both candidates must present the solution.

---

All the best!  
— Team XcelerateIT  
https://xcelerateit.ai/
