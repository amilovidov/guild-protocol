# Guild Protocol: Customer Discovery Research
## Corporate Customer Journey Analysis

---

## Executive Summary

Three wedge segments offer paths to market that avoid head-on competition with established staffing agencies:

1. **Fringe Projects** - Too small, niche, or short-term for traditional staffing
2. **Budget-Constrained** - Startups and small teams priced out of Toptal/agencies
3. **OSS Foundations** - Grant-funded projects with non-traditional procurement

Each segment has distinct discovery patterns, watering holes, pain points, and trust signals. This research maps the customer journey for each.

---

## Segment 1: Fringe Projects

### Who Is This Buyer?

**Profile:**
- Engineering manager or tech lead at Series B+ company
- Has project budget (not headcount budget)
- Needs short-term specialized help (2-12 weeks)
- Internal team lacks specific skills or capacity

**Trigger Events:**
- "We need to do X but nobody on team knows Y"
- "Leadership approved budget but not headcount"
- "Our usual agency said project is too small"
- "Need this done in 3 months, can't wait for hiring"

**Examples:**
- One-time migration (legacy system, cloud, database)
- Security audit or penetration test
- Performance optimization
- Technical debt cleanup
- Prototype/proof of concept
- Documentation overhaul

### Discovery Journey

**Step 1: Ask Network First**
- Slack communities (see Communities below)
- Former colleagues
- Internal Slack: "Anyone know a good contractor for X?"
- Twitter/X technical community

**Step 2: Google Search**
If network fails, they search. High-intent queries:
```
"hire [technology] contractor"
"freelance [skill] developer"
"[technology] consulting"
"find contractor for [specific task]"
"[technology] expert for hire"
```

**Step 3: Evaluate Options**
| Option | Perception |
|--------|------------|
| Network referral | Best but limited options |
| Upwork | Cheap but risky, have to vet myself |
| Toptal | Quality but expensive ($150-200/hr) |
| Staffing agency | Will they even take this? |
| Consulting firm | Way too expensive for scope |

**Step 4: Decision Factors**
- Speed to start (days not weeks)
- Confidence they can actually do it
- Risk mitigation (what if they disappear?)
- How much of my time will this take?

### Pain Points (Research Findings)

From DEV.to article "The Dirty Secrets of IT Staffing":
- "Adding a middleman... can have the effect of depressing the wages"
- "There is often a SECOND middleman in the mix"
- "I got mocked for learning the technology, being responsive to candidates"

From LinkedIn article "Why Hiring Managers Hate Staffing Agencies":
- "Overwhelmingly disappointed with their quality of service"
- "They're money hungry, they don't fully understand your hiring needs"
- "Sending you way too many resumes hoping one will close the deal"

From iDEAL Hire "10 Reasons Companies Dislike Staffing Agencies":
1. Ignoring HR and filling directly with hiring manager
2. Only spending 5 minutes screening candidates
3. "Spaghetti Recruiting" - sending 10 resumes hoping one sticks
4. Not following up after placement
5. High turnover within agency itself
6. Hybrid recruiter/sales roles spreading staff thin
7. Not running proper background checks
8. Treating companies as "just another number"
9. Claiming to be expert in every industry
10. Sending unqualified candidates to interview

### Communities (Where They Congregate)

**Slack Communities:**
- Engineering Managers Slack (engmanagers.github.io) - new EMs, safe space
- Rands Leadership Slack - general leadership, very active
- CTO Craft - first-time CTOs
- alphalist - experienced tech leaders, curated
- SweetOps - DevOps focus, hosted by Cloud Posse
- Kubernetes Slack - k8s specific

**Other Channels:**
- Hacker News "Who is Hiring?" threads
- Reddit: r/experienceddevs, r/cscareerquestions
- Twitter/X tech community
- Local tech meetups

### Trust Signals Needed

- Track record of similar projects
- Recommendation from someone they know
- Clear scope and timeline
- Risk mitigation (escrow, milestones)
- Fast start capability
- Low management overhead promise

---

## Segment 2: Budget-Constrained (Startups)

### Who Is This Buyer?

**Profile:**
- Startup founder or early eng lead
- Seed to Series A (limited budget)
- Or: team lead with small discretionary budget
- Can't afford $150/hr agency rates

**Trigger Events:**
- "Need to ship MVP but can't afford full-time hire"
- "Got sticker shock from Toptal"
- "Upwork feels too risky for important work"
- "Need specialized skill for 2-4 weeks"
- Budget: $10K-50K, not $100K+

### Discovery Journey

**Step 1: Upwork (Default)**
- Post job, get flooded with bids
- Race to bottom, quality concerns
- Hours spent vetting candidates

**Step 2: Explore Alternatives**
```
"Upwork alternative"
"hire part-time senior engineer"
"affordable developer for MVP"
"fractional CTO"
"startup-friendly contractors"
```

**Step 3: Community Search**
- Indie Hackers forum
- Twitter/X founder community
- Y Combinator network (if connected)
- Product Hunt discussions
- Reddit: r/startups, r/SaaS

**Step 4: Decision Factors**
- Can I actually afford this?
- Will this person be good enough?
- Am I getting ripped off on price?
- Flexibility if scope changes?

### Key Platforms They Evaluate

| Platform | Perception |
|----------|------------|
| Upwork | Race to bottom, have to vet heavily |
| Fiverr | Tasks only, not projects |
| Toptal | Quality but 50-100% markup, too expensive |
| Freelancer.com | Similar to Upwork |
| Gun.io | Dev-focused but limited |
| A.Team | Curated but expensive |
| Braintrust | 15% fee, better than most |
| Network | Best but limited |

### Communities

**Forums & Social:**
- Indie Hackers (indiehackers.com)
- Twitter/X startup community
- Y Combinator's Bookface (if YC)
- Product Hunt Makers
- Reddit: r/startups, r/Entrepreneur

**Slack/Discord:**
- Startup-focused Slack groups
- Product Hunt Discord
- Indie Hackers community
- Tech Masters Discord (founders + devs)

### Trust Signals Needed

- Transparent pricing (no hidden markups)
- Quality signal (better than Upwork bottom)
- Speed (don't have time for lengthy process)
- Flexibility (scope will change)
- Past startup experience
- "Gets it" - understands startup constraints

---

## Segment 3: OSS Foundations as Customers

### Who Is This Buyer?

**Profile:**
- Foundation executive director
- Project maintainer with grant funding
- CNCF/Linux Foundation/Apache project lead
- Grant recipient with deliverables

**Key Entities:**
- Cloud Native Computing Foundation (CNCF)
- Linux Foundation
- Apache Software Foundation
- Python Software Foundation
- Mozilla Foundation
- NumFOCUS
- Open Collective hosted projects
- Software Freedom Conservancy

**Trigger Events:**
- Grant requires specific deliverables
- Security audit mandated by funder
- Core maintainers burned out
- Documentation needs professional help
- Feature required but no volunteer capacity

### Discovery Journey

**Step 1: Internal Community**
- Ask in project Slack/Discord
- Check if contributors available for paid work
- Ask other foundation/project leads

**Step 2: Foundation Resources**
- LFX platform (Linux Foundation)
- CNCF mentoring programs
- Foundation-approved vendor lists

**Step 3: Specialized Search**
```
"open source security audit"
"[project] contractor"
"CNCF approved vendors"
"open source documentation writer"
```

**Step 4: Grant-Specific Requirements**
From opensource.guide:
- "Funds must be given to an individual contractor rather than an organization"
- "You may need to be a nonprofit or have a nonprofit fiscal sponsor"
- "Focus on project milestones or outcomes rather than paying a salary"

### Funding Sources They Use

**Grant Programs:**
- Sovereign Tech Fund (EU)
- Sloan Foundation
- Mozilla Open Source Support (MOSS)
- Chan Zuckerberg Initiative
- GitHub Secure Open Source Fund
- FLOSS/fund
- Open Technology Fund
- Ford Foundation
- NLNet Foundation

**Corporate Sponsors:**
- Google Summer of Code / Season of Docs
- Companies via Open Collective
- Tidelift subscriptions
- Enterprise support contracts

**Key Stats:**
- "95% of CNCF contributors/maintainers are affiliated with organizations"
- "60% of open-source maintainers are unpaid volunteers" (Tidelift)
- LFX has graduated 270+ mentees since 2019

### Procurement Characteristics

From Open Collective blog:
- "Big companies call the process for paying for stuff 'procurement'"
- "Contracts, invoices, purchasing order numbers, bureaucracy"
- "Practically a blocker for small amounts"
- "Much simpler to make one large payment, to one vendor"

**OSS-Specific Needs:**
- Understand how OSS governance works
- Can work with volunteer maintainers
- Transparent about work done
- Community will accept their contributions
- Respect project's code style and culture

### Communities

**Primary Channels:**
- CNCF Slack (#mentoring, project-specific channels)
- Kubernetes Slack
- Linux Foundation mailing lists
- Foundation-specific Discords
- GitHub Discussions on repos
- Open Source Summit conferences

**Key People:**
- CNCF TOC members
- Project TSC (Technical Steering Committee) members
- Foundation staff (community managers)
- Major contributors at sponsor companies

### Trust Signals Needed

- OSS credibility (contributions to projects)
- Mission alignment (not extractive)
- Work visible in public
- Other foundations using successfully
- Understand async/distributed collaboration
- Community references

---

## Cross-Segment Patterns

### Common Pain Points Across All Segments

| Pain Point | Evidence |
|------------|----------|
| Opacity on pricing | "Workers don't know their bill rate" |
| Markup extraction | 35-75% typical agency markup |
| Quality uncertainty | "Spaghetti recruiting" |
| No reputation portability | "Locked to platform" |
| Speed | Weeks to get started |
| Accountability gap | "Often lose touch after placement" |

### What They All Want

1. **Transparency** - See what they're paying, what worker gets
2. **Quality signal** - Know contractor can actually do it
3. **Speed** - Start in days not weeks
4. **Low overhead** - Don't become my management problem
5. **Accountability** - Someone to call if it goes wrong
6. **Flexibility** - Scope will change, need to adapt

### Trust Hierarchy

```
Most trusted → Least trusted:
1. Personal network referral
2. Former colleague
3. Community recommendation (Slack/Discord)
4. Platform with verified reviews
5. Curated marketplace (Toptal)
6. Open marketplace (Upwork)
7. Cold outreach from agency
```

---

## GTM Implications

### Entry Points by Segment

| Segment | Entry Point | Why |
|---------|-------------|-----|
| Fringe Projects | Engineering manager Slack communities | Where they ask for recommendations |
| Budget-Constrained | Indie Hackers, Twitter startup community | Where they discuss hiring challenges |
| OSS Foundations | CNCF/LF channels, contribute to projects first | Trust comes from community membership |

### Positioning by Segment

| Segment | Message |
|---------|---------|
| Fringe Projects | "TEKsystems said no. We say yes." |
| Budget-Constrained | "Toptal quality without Toptal markup" |
| OSS Foundations | "Contractors who understand how OSS works" |

### Content Strategy

**Fringe Projects:**
- Case studies: "How X company shipped a migration in 4 weeks"
- Blog posts: "Why agencies won't touch your project (and we will)"
- Presence in eng manager Slacks

**Budget-Constrained:**
- Transparent pricing calculator
- "Upwork vs Toptal vs Guild" comparison
- Founder testimonials
- Indie Hackers posts

**OSS Foundations:**
- Contribute to projects first (walk the walk)
- Case studies with foundation names
- Speak at OSS conferences
- Published in foundation newsletters

---

## Research Gaps (Need More Info)

1. **Actual search volume** - What are high-intent keywords and monthly search volumes?
2. **Buyer decision timeline** - How long from trigger to purchase?
3. **Budget authority** - Who can approve $10K vs $50K vs $100K?
4. **Procurement process** - What's minimum viable for different company sizes?
5. **OSS foundation contacts** - Who specifically at CNCF/LF would pilot?
6. **Competitor positioning** - How do A.Team, Braintrust, etc. actually go to market?

---

## Recommended Next Steps

1. **Join key communities** - Engineering Managers Slack, Rands Leadership, CNCF Slack
2. **Interview 5-10 buyers** - Engineering managers who recently hired contractors
3. **OSS pilot identification** - Which projects have grant money and need help?
4. **Keyword research** - SEO analysis of contractor-hiring search terms
5. **Competitive positioning** - Deep dive on Braintrust, A.Team go-to-market

---

*Research compiled January 2026*
