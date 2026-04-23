# Search Queries for Job Scraper

<!-- Configured for Jason Martin-Smith — fully remote, UK-based, actively searching -->
<!-- Note: The built-in CLI tools (.agents/skills/) target Danish job boards and are not relevant. -->
<!-- Use the queries below directly in a browser or via the web search tool. -->

## Search Sites

Primary (remote-first job boards):
- **linkedin.com/jobs** — filter: Remote, United Kingdom or Worldwide
- **wellfound.com** (formerly AngelList) — best for founding/staff engineer roles at startups
- **remotive.com** — curated remote-only tech roles
- **remote.co/jobs** — remote engineering roles
- **weworkremotely.com** — remote engineering roles
- **otta.com** — London/UK tech roles, supports remote filter

Secondary (company career pages):
- Direct Google searches: `site:jobs.lever.co "staff engineer" "remote" typescript`
- Direct Google searches: `site:greenhouse.io "founding engineer" "remote" solidity`
- Direct Google searches: `site:boards.greenhouse.io "principal engineer" "remote" typescript`

## Query Categories

### Priority 1: Founding Engineer / Staff Engineer (strongest fit)

These match Jason's experience level and the 0-to-1 ownership he thrives in.

```
site:linkedin.com/jobs "founding engineer" remote typescript
site:linkedin.com/jobs "staff engineer" remote typescript
site:linkedin.com/jobs "founding engineer" remote solidity
site:wellfound.com "founding engineer" typescript remote
site:wellfound.com "staff engineer" typescript remote
"founding engineer" typescript remote -site:indeed.com
"staff engineer" typescript solidity remote
```

### Priority 2: DeFi / Web3 Engineering (domain expertise)

These match Jason's deep DeFi and smart contract background.

```
site:linkedin.com/jobs "lead engineer" DeFi remote
site:linkedin.com/jobs "senior engineer" solidity typescript remote
site:linkedin.com/jobs "staff engineer" web3 remote
site:wellfound.com solidity typescript "lead engineer" remote
"DeFi" "lead engineer" typescript remote
"smart contract" "principal engineer" typescript remote
"blockchain" "staff engineer" remote typescript
```

### Priority 3: Principal Engineer / Technical Lead (adjacent titles)

Broader senior individual contributor titles.

```
site:linkedin.com/jobs "principal engineer" typescript remote
site:linkedin.com/jobs "principal engineer" "trading" remote
site:linkedin.com/jobs "technical lead" typescript remote "fintech"
site:linkedin.com/jobs "lead engineer" "trading systems" remote
"principal engineer" typescript remote fintech
"technical lead" solidity typescript remote
```

### Priority 4: High-Performance Systems / Trading Infrastructure (domain pivot)

For companies building trading tech outside of Web3 specifically.

```
site:linkedin.com/jobs "lead engineer" "trading platform" remote typescript
site:linkedin.com/jobs "staff engineer" "low latency" remote
site:linkedin.com/jobs "principal engineer" "real-time systems" remote
"trading" "staff engineer" typescript remote
"high frequency" "lead engineer" remote
"websocket" "lead engineer" typescript remote fintech
```

### Priority 5: Agentic Engineering / AI-augmented tooling (emerging niche)

For companies building developer tooling with AI at the core.

```
site:linkedin.com/jobs "staff engineer" "agentic" remote
site:linkedin.com/jobs "founding engineer" "AI" "developer tools" remote
site:wellfound.com "founding engineer" "AI tooling" remote
"agentic" "staff engineer" typescript remote
"developer tools" "founding engineer" typescript remote
```

## Location Filter

Jason is **remote-only**. All results must be:
- Fully remote (PASS)
- Remote-first with optional in-person (FLAG — confirm with user)
- Hybrid or on-site (FAIL — discard immediately, do not present)

No location preference otherwise — open globally as long as the role is remote.

## Date Filter

Only include jobs posted within the last 14 days, or with an application deadline that has not yet passed. If a posting date cannot be determined, include it but flag as "date unknown".

## Adapting Queries

If the user specifies a focus area:
- `/scrape defi` → Priority 2 queries + custom DeFi-specific searches
- `/scrape founding` → Priority 1 queries
- `/scrape trading` → Priority 4 queries
- `/scrape ai` → Priority 5 queries
- `/scrape [company name]` → `site:[company-careers-url] engineer remote`
