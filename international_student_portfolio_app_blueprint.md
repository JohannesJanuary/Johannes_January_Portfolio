# International Student Portfolio Builder Blueprint

## Purpose

Build a guided system that helps international students turn their education, coursework, projects, work experience, and career goals into a polished job-market portfolio, resume package, and LinkedIn-ready professional profile.

The system should feel like a practical career coach plus portfolio designer. It should not only create a website, but help students explain their value clearly to recruiters in the U.S. job market.

## User Problem

International students often have strong academic and work backgrounds, but struggle to translate them into U.S.-style career materials. Common barriers include unclear positioning, weak project descriptions, unfamiliar resume expectations, uncertainty around work authorization wording, limited local networks, and difficulty showing proof of skills.

## Target Users

Primary users:
- International graduate students
- International undergraduate students preparing for internships
- Recent international graduates on OPT or STEM OPT

Secondary users:
- Career services offices
- Faculty mentors
- International student offices
- Graduate program directors

## Core Outcome

Each student should leave with:
- A professional portfolio website
- A downloadable resume
- A recruiter-ready LinkedIn headline and About section
- Project case studies written in strong business language
- A skills map connected to coursework and evidence
- A 30-day job-search action plan

## Portfolio Creation Flow

### 1. Student Profile Intake

Collect:
- Name
- Degree program
- University
- Graduation date
- GPA, if strong
- Target roles
- Target industries
- Work authorization status
- LinkedIn URL
- Email
- Location preferences
- Existing resume

Output:
- Career positioning statement
- Role-fit summary
- Portfolio headline
- Recruiter snapshot

### 2. Experience Translation

The system should help students convert previous experience into U.S. recruiter language.

Examples:
- Retail experience becomes customer behavior, sales operations, inventory, merchandising, and KPI experience.
- Manufacturing experience becomes account management, order fulfillment, revenue operations, supplier coordination, and process improvement.
- Academic projects become applied analytics, stakeholder communication, technical methods, and business recommendations.

Output:
- Improved resume bullets
- LinkedIn About section
- Role-fit cards for the portfolio

### 3. Coursework and Skills Mapping

Students upload syllabi, transcripts, or course lists.

The system extracts:
- Course name
- Tools used
- Methods learned
- Business skills gained
- Technical skills gained
- Evidence that can support portfolio claims

Output:
- Collapsible coursework section
- Skills grouped by business value
- Academic performance proof cards

### 4. Project Case Study Builder

For each project, the system asks:
- What was the problem?
- What data was used?
- What was your role?
- What methods or tools did you use?
- What did you find?
- What was the business or decision value?
- What visual evidence can be shown?

Portfolio project structure:
- Project title
- Short summary
- Tags
- Visual story panel
- Use case
- Metric
- Focus
- Business value callout
- Problem
- My role
- Methods
- Result

This mirrors the structure we used in Johannes's portfolio.

### 5. Visual Story Design

Every project should include a small visual that tells a story, even if the original project artifact is a report or presentation.

Visual types:
- Model comparison chart
- Topic evolution panel
- Data warehouse schema
- Dashboard preview
- KPI card
- Process map
- Before-and-after workflow

Design rule:
The visual should not be decorative. It should communicate the project logic quickly.

### 6. Resume Integration

The website should include:
- Download resume button
- Resume link in footer/contact section
- Stable asset path for updates
- One-page resume recommendation for early-career applicants

Recommended portfolio resume link format:
`assets/Student_Name_Resume.pdf`

### 7. LinkedIn Integration

The system should generate:
- LinkedIn headline
- About section
- Featured section instructions
- Portfolio link text
- Networking message templates

Best LinkedIn placement:
- Contact Info website field
- Featured section
- About section closing line

### 8. Career Action Plan

The system should create a 30-day plan with daily deliverables.

Plan areas:
- Resume tailoring
- Portfolio project evidence
- LinkedIn improvement
- Networking outreach
- Target employer research
- Internship/job applications
- Interview story preparation
- GitHub cleanup

## Recommended Website Structure

Sections:
- Header with student name and portfolio label
- Hero with role positioning
- Proof cards
- Role fit
- Selected projects
- Coursework
- Skills
- Contact
- Footer with last updated year and copyright

Navigation:
- Role Fit
- Projects
- Courses
- Skills
- Contact

## Design Principles

The site should feel:
- Professional
- Recruiter-friendly
- Clean
- Evidence-based
- Premium but not flashy

Avoid:
- Generic AI-sounding language
- Oversized decorative sections
- Weak project summaries
- Empty visual space
- Long blocks of text with no structure
- Claims without evidence

Use:
- Clear role positioning
- Compact cards
- Collapsible detail sections
- Project visuals that explain the work
- Business value callouts
- Strong metrics where available

## App Features

Minimum viable product:
- Intake form
- Resume upload
- Course/project entry forms
- AI-assisted bullet rewriting
- Portfolio preview
- PDF resume upload
- Static portfolio export

Next version:
- Syllabus extraction
- LinkedIn profile generator
- GitHub Pages deployment guide
- Project evidence checklist
- Job-search dashboard
- Networking tracker

Advanced version:
- University admin dashboard
- Program-specific templates
- OPT/STEM OPT wording guidance
- Faculty review workflow
- Portfolio scoring rubric
- Recruiter-readiness score

## Data Model

Student:
- name
- email
- LinkedIn URL
- portfolio URL
- degree
- university
- graduation date
- target roles
- target industries
- work authorization note

Course:
- course name
- grade
- tools
- skills gained
- business applications

Project:
- title
- summary
- tools
- problem
- role
- methods
- result
- business value
- visual type
- evidence files

Resume:
- file name
- upload date
- version
- public download path

## Success Metrics

Student-level metrics:
- Portfolio completed
- Resume updated
- LinkedIn updated
- Number of projects documented
- Number of applications submitted
- Number of networking messages sent
- Interview invitations

Institution-level metrics:
- Student portfolio completion rate
- Internship placement support
- Employer engagement
- Career-services usage

## Product Positioning

Suggested product concept:
An AI-guided career portfolio builder for international students that transforms academic work, prior experience, and project evidence into U.S.-ready career materials.

Suggested tagline:
From international experience to U.S.-ready career evidence.

## Why This Matters

International students often have the skills, discipline, and experience employers need, but they need help translating that value into a format recruiters understand quickly. This system bridges that gap by combining resume strategy, portfolio design, project storytelling, and job-search planning into one guided workflow.
