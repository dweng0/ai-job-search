# Interview Preparation Guide

<!-- SETUP: STAR examples are personalized by running /setup based on your actual experience -->

## STAR Format

Structure answers as: **Situation** (context), **Task** (your responsibility), **Action** (what you did), **Result** (outcome).

Keep answers to 1-2 minutes. Be specific. End with what you learned or would do differently.

## Ready-Made STAR Examples

### 1. Clearmatics HFT Trading Platform (Systems Architecture / 0-to-1 Build)
**S:** Clearmatics needed to build a high-frequency institutional trading platform from scratch to power their hybrid Web3/CEX ecosystem. No existing infrastructure, tight performance requirements.
**T:** As Founding Systems Architect, I owned the full technical architecture and delivery of the core trading platform.
**A:** Designed the system from the ground up — order book engine, WebSocket streaming layer, charting infrastructure, and time-series data platform (PostgreSQL/TimescaleDB). Made key architectural decisions around latency targets, block confirmation windows, and data retention.
**R:** Platform handles 800+ trades/second with sub-80ms order matching latency and sub-1s block confirmation. TimescaleDB platform ingests 1M+ datapoints/day with sub-300ms analytics queries and 1TB+ retention.
**Use for:** "Tell me about a complex system you designed", "Describe a time you built something from scratch", "What's your most challenging technical achievement?"

### 2. Phuture TypeScript SDK (Technical Ownership / Developer Experience)
**S:** Phuture Finance needed external developers to be able to interact with their DeFi smart contracts reliably. There was no SDK — developers were integrating directly with contracts, leading to fragile integrations.
**T:** Design and build a TypeScript SDK that abstracts smart contract interactions and becomes the standard integration layer for the Phuture protocol.
**A:** Architected the SDK with clean abstractions over contract ABIs, typed interfaces, and clear developer ergonomics. Maintained it alongside evolving protocol changes and documented it for external consumption.
**R:** SDK is now adopted by external development teams as the primary way to interact with Phuture's contracts. Became a key piece of the protocol's ecosystem.
**Use for:** "Tell me about a time you thought about developer experience", "Describe owning a product end-to-end", "Tell me about technical leadership"

### 3. J.P. Morgan Treasury Control System (Delivery Under Constraints / Adoption)
**S:** J.P. Morgan's internal treasury operations had no centralised funding control tooling — teams were working across fragmented systems with no unified PWA-capable tool.
**T:** Design and deliver a greenfield treasury control system for internal operations, with real-time capabilities and enterprise adoption targets.
**A:** Built the tool from scratch with PWA capabilities and a custom WebSocket framework for real-time updates. Worked closely with stakeholders to ensure the tool matched operational workflows.
**R:** Tool was adopted by 5+ teams bank-wide — a strong result in a large organisation where internal tooling often fails to achieve cross-team adoption.
**Use for:** "Tell me about a time your work had broad organisational impact", "Describe delivering under enterprise constraints", "Tell me about a project you're proud of"

### 4. J.P. Morgan AngularJS → React Migration (Technical Leadership / Change Management)
**S:** J.P. Morgan's investment technology division was running a large AngularJS codebase with growing maintenance burden and difficulty attracting engineers comfortable with modern tooling.
**T:** Lead the organisation-wide migration to React with TypeScript, including establishing new engineering standards and gaining buy-in across teams.
**A:** Co-founded a UX forum that drove consensus and coordination across the division. Established engineering standards for linting, component reuse, and development workflows. Delivered technical presentations on component-driven development and testing to 100+ engineers.
**R:** Organisation-wide adoption of React/TypeScript. Knowledge transfer to 100+ engineers. Established long-lasting engineering standards across the division.
**Use for:** "Tell me about leading change in a large organisation", "Describe a time you influenced without authority", "Tell me about mentoring or knowledge transfer"

## Common Tough Questions

### "Why did you leave [previous company]?"
> [PREPARE YOUR ANSWER - be honest, forward-looking, no negativity about former employer]

### "You don't have [specific skill/experience]."
> [PREPARE YOUR ANSWER - acknowledge the gap, bridge to adjacent experience, show willingness to learn]

### "Where do you see yourself in 5 years?"
> [PREPARE YOUR ANSWER - show ambition aligned with the role's growth path]

### "What's your biggest weakness?"
> [PREPARE YOUR ANSWER - genuine weakness with concrete mitigation strategy]

### "Why this company specifically?"
> Customize per company. Must reference: specific projects, company values, market position, or team structure. Never give a generic answer.

## Questions You Should Ask Interviewers

### About the Role
- "What does a typical week look like in this role?"
- "What would success look like in the first 6 months?"
- "What's the biggest challenge the team is facing right now?"

### About the Team
- "How big is the team, and how do you divide work?"
- "What does the development/project lifecycle look like, from idea to production?"
- "How do you onboard new team members?"

### About Tech & Growth
- "What's your current tech stack for [relevant area]?"
- "Is there room to grow into more architectural or strategic decisions?"
- "How does the team stay current with new tools and methods?"

### About Culture (use these to prevent disappointment)
- "How would you describe the team culture?"
- "What does professional development look like here?"
- "Is there flexibility for remote/hybrid work?"
- "What's the balance between development/new projects and maintenance work?"
- "How would you describe the leadership style in this team?"
- "What do people who thrive here have in common?"

## Phone/Video Interview Tips
- Have STAR examples written out (use this file)
- Keep a glass of water nearby
- Smile when speaking (it changes your tone)
- Ask for clarification if a question is vague
- It's OK to take 5 seconds to think before answering
- End with: "Is there anything else you'd like to know about my background?"

## After the Application (Best Practice)

### Follow-Up Etiquette
- **Don't call to "stand out"** or to learn more about the role post-submission - this risks a negative impression
- If the employer specified a timeline, respect it and wait
- If no timeline was given and significant time has passed (2+ weeks), a brief call to ask about status is acceptable
- If you have genuinely new, relevant information to share, a short follow-up is fine

### Thank-You Notes
- When you receive any update (interview invitation, rejection, or status update), send a brief thank-you message
- Express appreciation for their time and the process
- Keep it short (2-3 sentences)

## Roleplay Guidelines
When the user asks for interview practice:
1. Ask which role/company to simulate
2. Start with easy warm-up questions ("Tell me about yourself")
3. Progress to role-specific technical questions
4. Include 1-2 behavioral questions using the competencies from the job posting
5. End with a tough question or curveball
6. After each answer, give brief feedback: what worked, what to sharpen
7. Suggest which STAR example would work best for each question
