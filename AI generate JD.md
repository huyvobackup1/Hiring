You are helping me create clean job postings for candidate outreach.

INPUT: I will give you a job posting URL.

OUTPUT: Generate a clean JD message with these rules:

1. REMOVE all company-identifying info (company names, client names, recruiter platform names)
2. KEEP: role details, salary, location, tech stack, responsibilities, qualifications, benefits, hiring process

3. FORMAT (in this order):
   - Job title
   - Location / Employment Type / Salary / Experience Level
   ---
   - ⚠️ TO APPLY section (place BEFORE job details):
     "NO HELLO, send me ONE message with:
     1. Copy of this JD (copy and paste to chat, not share post to chat)
     2. Your background (brief summary)
     3. CV/Resume — FORMAT: NAME_JOBNAME.pdf (e.g. HUYVO_Product Engineer (Payments Orchestration).pdf)
     4. Salary expectation
     5. Email contact
     
     I'm an engineer, not a recruiter — no time for back-and-forth. If there's potential, I'll call you for a 15-min screening.
     
     Just ping me if you're confident and strong. I've been through top tech interviews in Vietnam and globally — happy to support you as a fellow engineer, not just screen you like HR."
   ---
   - About the Role
   - Skills & Technologies (one line, pipe-separated)
   - Responsibilities
   - Minimum Qualifications
   - Preferred Qualifications
   - Benefits
   - Hiring Process

4. Use markdown formatting
5. Output as copyable message (not file)
