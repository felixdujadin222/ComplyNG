---
name: phase-1-schoolguard-lextrack
status: backlog
created: 2026-05-17T00:00:00Z
progress: 0%
github: (pending)
---

# Epic: Phase 1 — SchoolGuard + LexTrack

## Overview

Launch first two products: SchoolGuard (Month 1) and LexTrack (Month 2). Target: 20 paying clients per product. MRR target: ₦640,000.

## Timeline

- **Months 1-2**: Build both MVPs on Bubble, connect Claude API, set up Paystack and WhatsApp alerts
- **Months 3-4**: Onboard 5 free beta users per product, fix bugs, launch paid tiers
- **Months 5-6**: Scale to 40 total clients, hire first 2 employees

## Products

### SchoolGuard

Industry: Private schools (60,000+ in Nigeria)  
Core Problem: TRCN 2027 deadline (75% compliance by Dec 2026), 85%+ teachers unregistered

**Features:**
- Staff registry (teacher name, subject, TRCN status, certificate number, expiry date)
- Auto-calculate TRCN compliance percentage with deadline countdown
- WhatsApp alerts (90/30/7 days before expiry)
- Claude generates TRCN compliance report for Ministry inspection
- Ministry of Education approval status and renewal calendar
- WAEC/NECO exam centre accreditation deadline tracker
- CAC annual returns calendar with alerts
- NDPA compliance checklist

**Claude AI Use Case:**
- Input: Teacher count + certified count
- Output: Gap report showing compliance %, teachers needing certification, deadline projection, recommended actions

**Pricing:**
- Starter: ₦20,000/mo (20 teachers, TRCN calc, WhatsApp alerts, CAC tracker)
- School: ₦35,000/mo (unlimited, full TRCN engine, MoE checklist, NDPA, Claude reports)
- CaaS Premium: ₦120,000/mo (+ quarterly advisory, inspection prep, document drafting)

**Target:** 20 schools = ₦400,000 MRR

### LexTrack

Industry: Lawyers and law firms (170,000+ registered)  
Core Problem: CAC annual returns by June 30, contract review inefficiency

**Features:**
- CAC return deadline tracker (90/30/7-day alerts)
- Court date calendar with WhatsApp alerts
- NBA dues renewal reminder
- Client matter registry
- Contract risk analyzer (Claude flags risky clauses)
- Plain-English contract summary generator
- Standard legal letter drafts
- CAC compliance checklist per business type
- Secure document vault

**Claude AI Use Case:**
- Input: Lawyer uploads 42-page shareholders agreement PDF
- Output: Risk report flagging 5 dangerous clauses (un enforceable non-compete, jurisdiction risks, missing NDPA consent, drag-along with no floor price)
- Time: Under 2 minutes

**Pricing:**
- Solo Lawyer: ₦12,000/mo (CAC tracker, court calendar, 5 analyses/mo, NBA reminder)
- Small Firm: ₦30,000/mo (team 5 lawyers, 20 analyses/mo, vault, invoice, SCUML)
- CaaS Premium: ₦100,000/mo (+ unlimited analyses, quarterly call, NDPA full)

**Target:** 20 clients = ₦240,000 MRR

## Architecture Decisions

- **App Builder**: Bubble.io
- **AI Engine**: Claude API (Sonnet 4)
- **Payments**: Paystack
- **WhatsApp**: Twilio
- **Database**: Supabase
- **Auth**: Firebase Auth

## Technical Approach

1. **Week 1-2**: Register domains (ComplyNG.com, SchoolGuard.ng, LexTrack.ng)
2. **Week 3-4**: Build SchoolGuard MVP on Bubble with Claude integration
3. **Week 5-6**: Build LexTrack MVP on Bubble with Claude integration
4. **Week 7-8**: Set up Paystack payments and Twilio WhatsApp
5. **Week 9-12**: Beta testing (5 free users per product)
6. **Month 4**: Launch paid tiers
7. **Months 5-6**: Scale to 20 per product, hire CSM + Sales

## Dependencies

- Claude API keys for both products
- Paystack merchant account
- Twilio WhatsApp Business API
- Supabase database setup
- Framer for waitlist pages

## Success Criteria

- [ ] SchoolGuard MVP live with Claude TRCN calculator
- [ ] LexTrack MVP live with Claude contract analyzer
- [ ] 5 beta schools onboarded
- [ ] 5 beta lawyers onboarded
- [ ] Paid tiers launched for both products
- [ ] 20 paying schools (₦400,000 MRR)
- [ ] 20 paying lawyers (₦240,000 MRR)
- [ ] First 2 hires (CSM + Sales)

## Estimated Effort

- Development: 6 months
- Target MRR: ₦640,000
- Team size: 2 (founder-led)