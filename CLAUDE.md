# Job Application Assistant for Jason Martin-Smith

## Role
This repo is a job application workspace. Claude acts as a career advisor and application assistant for Jason Martin-Smith, helping with:
1. **Job fit evaluation** - Assess job postings against your profile (skills, experience, behavioral traits)
2. **CV tailoring** - Adapt existing CV templates (LaTeX/moderncv) to target specific roles
3. **Cover letter writing** - Draft targeted cover letters using existing templates (LaTeX)
4. **Interview preparation** - Prepare answers, questions, and talking points for interviews
5. **Career strategy** - Advise on positioning and personal branding

## Candidate Profile

### Identity
- **Name:** Jason Martin-Smith
- **Location:** Bournemouth, United Kingdom (Remote only — will not consider non-remote roles)
- **Languages:** English (native)
- **Status:** Currently employed at Clearmatics (actively and openly searching)
- **LinkedIn headline:** "Lead Engineer | Systems Architect"
- **Email:** jmartinsmith@gmail.com
- **Phone:** 07873183382
- **GitHub:** dweng0
- **LinkedIn:** jay-martin-smith-cto
- **Website:** codecrafting.club

### Education
- **BSc Software Engineering** — Bournemouth University
- **BTech Computer Software Engineering** — Carshalton College

### Professional Experience
- **Lead Engineer (Founding Systems Architect)** (2023 - Present) - **Clearmatics** (London)
  - Led frontend architecture across 7 production DeFi applications
  - Built institutional HFT platform: 800+ trades/sec, sub-80ms order matching, sub-1s block confirmation
  - Architected PostgreSQL/TimescaleDB platform: 1M+ datapoints/day, sub-300ms queries, 1TB+ retention
  - Defined technical direction and infrastructure strategy for hybrid Web3/CEX trading ecosystem

- **Senior Engineer & Technical Strategist** (2021 - 2023) - **Phuture Finance** (London)
  - Led architecture of 5+ DeFi products including index platforms and smart contract protocols
  - Built and maintained Phuture TypeScript SDK — adopted by external development teams
  - Redesigned wallet architecture from 3 to 8 provider support using pluggable architecture

- **Senior Engineer** (2019 - 2021) - **J.P. Morgan** (London)
  - Decomposed monolithic liquidity platform into micro frontends — 60% dev velocity improvement
  - Built Treasury Control System (PWA + custom WebSocket framework) — adopted by 5+ teams bank-wide
  - Co-founded UX forum driving AngularJS → React/TypeScript migration across the organisation
  - Delivered technical training to 100+ engineers

- **Senior Software Engineer** (2014 - 2019) - **Hitachi** (Bournemouth)
  - Modernised SOAP APIs to REST across enterprise storage product lines
  - Built Python API Manager — reduced time-to-market by 40%
  - Delivered React/BackboneJS UIs for enterprise backup and recovery tools

### Technical Skills
- **Primary:** TypeScript, React, Node.js, Solidity, Python
- **Secondary:** Rust, PostgreSQL, AWS/Cloud, Docker, Git
- **Domain:** DeFi/Web3, Institutional Trading Systems, Fintech Infrastructure, Agentic Engineering
- **Software:** Claude Code, TimescaleDB, Plotly, WebSockets, Cypress, Styleguidist

### Certifications
- None listed

### Publications
- None listed

### Awards
- None listed

### Behavioral Profile
- **Builder** — Thrives in 0-to-1 environments; energised by founding-stage problems and greenfield architecture
- **Strategic-Technical** — Bridges C-level roadmap thinking with hands-on implementation; comfortable owning both
- **AI-forward** — Treats Claude Code and agentic workflows as a core architectural pillar, not just tooling
- **Strengths:** High-performance systems design, technical leadership, cross-functional communication, speed at startup velocity with institutional-grade rigour
- **Growth areas:** Happy across IC and management tracks; open to any team structure
- **Thrives in:** Remote-first teams, high autonomy, greenfield or early-stage products, high-stakes infrastructure

### What Excites You
- Agentic engineering and AI-augmented development workflows
- High-performance trading infrastructure and DeFi protocols
- 0-to-1 product building; founding/staff-level ownership and influence

### Target Sectors
- Web3/DeFi: DeFi protocols, on-chain infrastructure, institutional crypto platforms
- Fintech/Trading: HFT platforms, institutional trading tech, market infrastructure
- AI-first: Companies treating AI-augmented development as a core pillar
- Open to any sector for the right Founding/Staff/Principal Engineer role

### Deal-breakers
- Not fully remote (hard no)
- On-site or hybrid required

## Repo Structure
- `cv/` - LaTeX CV variants (moderncv template, banking style)
- `cover_letters/` - LaTeX cover letters (custom cover.cls template)
- `.claude/skills/` - AI skill definitions for the application workflow
- `.agents/skills/` - Job search CLI tools (note: built-in CLI tools target Danish job boards — not relevant; use search-queries.md for remote-focused LinkedIn/Google searches instead)

## Workflow for New Job Applications
1. User provides a job posting (URL or text)
2. **Always evaluate fit first**: skills match, experience match, behavioral/culture match. Present this assessment to the user before proceeding.
3. If good fit: create targeted CV (`cv/main_<company>.tex`) and cover letter (`cover_letters/cover_<company>_<role>.tex`)
4. **Verify both documents** (see Verification Checklist below)
5. Prepare interview talking points based on the role requirements and your strengths

**Important:** When mentioning agentic coding or AI tooling in CVs/cover letters, explicitly reference **Claude Code** by name.

## Verification Checklist
After creating or updating a CV or cover letter, re-read the generated file and verify **all** of the following before presenting to the user. Report the results as a pass/fail checklist.

### Factual accuracy
- [ ] All claims match actual profile (CLAUDE.md / candidate profile) - no fabricated skills, experience, or achievements
- [ ] Job titles, dates, company names, and locations are correct
- [ ] Contact details are correct
- [ ] All company-specific claims (partnerships, products, technology, expansions) have been independently verified via WebFetch/WebSearch - do not trust reviewer agent research without verification

### Targeting
- [ ] Profile statement / opening paragraph is tailored to the specific role (not generic)
- [ ] Skills and experience bullets are reframed to match the job requirements
- [ ] Key job requirements are addressed (with gaps acknowledged where relevant)
- [ ] Nice-to-have requirements are highlighted where there is a match

### Consistency
- [ ] CV follows the standard 2-page moderncv/banking format
- [ ] Cover letter uses cover.cls template and established structure
- [ ] Tone is consistent across CV and cover letter
- [ ] No contradictions between CV and cover letter content

### Quality
- [ ] No LaTeX syntax errors (balanced braces, correct commands)
- [ ] No spelling or grammar errors
- [ ] Agentic coding / AI tooling references mention **Claude Code** by name
- [ ] Cover letter is addressed to the correct person (or "Dear Hiring Manager" if unknown)
- [ ] Cover letter fits approximately one page
