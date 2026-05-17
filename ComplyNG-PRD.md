# ComplyNG — Product Requirements Document

**Version:** 1.0  
**Date:** May 17, 2026  
**Status:** Approved  
**Owner:** ComplyNG Founder  
**Classification:** Confidential

---

## 1. Executive Summary

### 1.1 Product Vision

ComplyNG is a Nigerian compliance SaaS platform that provides vertical-specific regulatory compliance software for 7 industries. Every product helps Nigerian businesses track regulatory deadlines, generate compliance documents, and avoid fines — all powered by Claude AI and delivered through web dashboards with WhatsApp alerts.

### 1.2 Product Mission

To make enterprise-grade compliance management accessible to Nigerian SMEs by combining industry-specific software, AI-powered document generation, and WhatsApp-first notifications.

### 1.3 Strategic Objectives

- Launch 7 industry-specific compliance products over 18 months
- Achieve ₦5,000,000+ MRR by Month 18
- Establish "Powered by Claude AI" as a trust signal in Nigerian enterprise
- Build Compliance-as-a-Service (CaaS) as the primary revenue model

---

## 2. Problem Statement

### 2.1 Market Problem

Nigerian businesses operate in a heavily regulated environment but have no affordable software to manage compliance. While large companies maintain compliance departments, SMEs have no tools. This creates:

- **Missed deadlines** — MDCN renewal, TRCN certification, CAC annual returns
- **Non-compliant documents** — tenancy agreements, legal contracts, patient records
- **Audit failures** — CBN examinations, HEFAMAA inspections, FRSC checks
- **Financial exposure** — fines, licence revocations, business closure

### 2.2 Specific Industry Pain Points

| Industry | Primary Pain |
|---|---|
| Private Schools | TRCN 2027 deadline (75% compliance by Dec 2026) |
| Lawyers | CAC returns by June 30, contract review inefficiency |
| Estate Agents | LASRERA licensing, compliant tenancy agreements |
| Logistics | Driver licence expiry, vehicle roadworthiness, NSITF |
| Clinics | MDCN renewal, HEFAMAA inspections, NDPA patient data |
| Hotels | Fire safety, tourism licence, VAT filing, guest data |
| Fintechs | CBN cybersecurity audit, NDPA GAID registration, AML/KYC |

### 2.3 Competitive Landscape

**Current Alternatives:**
- Generic compliance tools (no industry specificity)
- Manual spreadsheet tracking
- Consultants (expensive, inconsistent)
- No affordable SaaS solution exists in Nigeria

**ComplyNG Differentiation:**
- Industry-specific — one deep product per industry
- Claude AI does the actual work (drafts, generates, analyses)
- WhatsApp-first — alerts where Nigerian business owners already live
- CaaS — premium tier bundles software with quarterly human advisory

---

## 3. Target Market

### 3.1 Primary Market Segments

| Product | Industry | Target Users | Market Size |
|---|---|---|---|
| SchoolGuard | Private Schools | School owners, administrators | 60,000+ schools |
| LexTrack | Legal | Lawyers, law firms | 170,000+ lawyers |
| EstateCheck | Real Estate | Estate agents, landlords, property managers | 500,000+ landlords |
| FleetPulse | Logistics | Logistics companies, courier firms, delivery fleets | 200,000+ operators |
| ClinicShield | Healthcare | Private dental and medical clinics | 15,000+ clinics |
| HotelComply | Hospitality | Boutique hotels, guesthouses | 5,000+ hotels |
| FintechReady | Technology | CBN-licensed fintech startups | 3,360+ startups |

### 3.2 Customer Profiles

**Primary Persona: Nigerian SME Owner**

- Age: 30–50
- Location: Lagos, Abuja, Port Harcourt
- Tech comfort: WhatsApp-native, web-dashboard comfortable
- Pain: Cannot afford compliance department, fears regulatory fines
- Buying trigger: Fear of penalty, peer recommendation, deadline urgency

**Secondary Persona: Compliance Manager**

- Age: 25–40
- Role: In-house compliance lead at mid-size company
- Pain: Manual tracking, no reporting, audit preparation burden
- Buying trigger: Upcoming inspection, audit failure, staff turnover

---

## 4. Product Roadmap

### 4.1 Phase Overview

| Phase | Timeline | Products | MRR Target |
|---|---|---|---|
| Phase 1 | Months 1–6 | SchoolGuard, LexTrack | ₦640,000 |
| Phase 2 | Months 7–12 | EstateCheck, FleetPulse, ClinicShield | ₦2,500,000 |
| Phase 3 | Months 13–18 | HotelComply, FintechReady | ₦5,000,000+ |

### 4.2 Phase 1 Details (Months 1–6)

**Product 1: SchoolGuard**

- Launch: Month 1
- Target: 20 paying schools
- MRR: ₦400,000

**Product 2: LexTrack**

- Launch: Month 2
- Target: 20 paying clients
- MRR: ₦240,000

### 4.3 Phase 2 Details (Months 7–12)

**Product 3: EstateCheck**

- Launch: Month 7
- Target: 30+ clients
- MRR: ₦700,000+

**Product 4: FleetPulse**

- Launch: Month 9
- Target: 20 companies
- MRR: ₦700,000

**Product 5: ClinicShield**

- Launch: Month 11
- Target: 20 clinics
- MRR: ₦500,000–₦700,000

### 4.4 Phase 3 Details (Months 13–18)

**Product 6: HotelComply**

- Launch: Month 13
- Target: 20 hotels
- MRR: ₦600,000

**Product 7: FintechReady**

- Launch: Month 15
- Target: 20 clients
- MRR: ₦1,600,000

---

## 5. Product Requirements

### 5.1 SchoolGuard (Product 1)

#### 5.1.1 Core Features

| Feature | Priority | Description |
|---|---|---|
| Staff Registry | P0 | Every teacher's name, subject, TRCN status, certificate number, expiry date |
| TRCN Compliance Calculator | P0 | Auto-calculate compliance percentage with real-time deadline countdown |
| WhatsApp Alerts | P0 | Notifications to uncertified teachers and school management |
| Claude TRCN Report | P0 | Generate full TRCN gap report for Ministry inspection |
| Ministry of Education Tracker | P1 | Approval status and renewal calendar |
| WAEC/NECO Deadline Tracker | P1 | Exam centre accreditation deadline |
| CAC Returns Calendar | P1 | Annual returns with 90/30/7-day alerts |
| NDPA Checklist | P2 | Student and parent data compliance checklist |
| Fire Safety & Health Permit | P2 | Status board for building compliance |

#### 5.1.2 Claude AI Use Case

**Input:** School owner inputs teacher count and certified count  
**Output:** Compliance percentage, gap analysis, deadline projection, recommended actions  
**Delivery:** Instant dashboard report + WhatsApp summary

#### 5.1.3 User Stories

| ID | Story | Acceptance Criteria |
|---|---|---|
| SG-001 | As a school owner, I want to add all teachers to a registry so that I can track TRCN certification status | User can add, edit, delete teacher records; all fields captured |
| SG-002 | As a school owner, I want to see real-time TRCN compliance percentage so that I know if I'm on track for 75% by Dec 2026 | Dashboard displays accurate % based on certified/total ratio |
| SG-003 | As a school owner, I want to receive WhatsApp alerts when a teacher's TRCN is expiring so that I can take action | Alert triggers at 90, 30, 7 days before expiry |
| SG-004 | As a school owner, I want Claude to generate a TRCN gap report so that I can prepare for Ministry inspection | Report includes compliance %, gaps, deadline projection, recommendations |
| SG-005 | As a school owner, I want to track CAC annual returns deadlines so that I avoid penalties | Calendar shows June 30 deadline with advance alerts |

#### 5.1.4 Pricing Tiers

| Tier | Price | Features |
|---|---|---|
| Starter | ₦20,000/month | Up to 20 teachers, TRCN calculator, WhatsApp alerts, CAC tracker |
| School | ₦35,000/month | Unlimited teachers, full TRCN engine, MoE checklist, NDPA module, Claude reports |
| CaaS Premium | ₦120,000/month | All features + quarterly advisory call, inspection preparation, document drafting, priority support |

---

### 5.2 LexTrack (Product 2)

#### 5.2.1 Core Features

| Feature | Priority | Description |
|---|---|---|
| CAC Return Deadline Tracker | P0 | Filing deadline with 90/30/7-day WhatsApp alerts |
| Court Date Calendar | P0 | Case hearing and filing deadline tracking |
| NBA Dues Reminder | P1 | Annual dues and RPC 2007 compliance |
| Client Matter Registry | P1 | Case, client, status, next action, billing stage |
| Contract Risk Analyzer | P0 | Upload PDF, Claude flags risky clauses |
| Plain-English Contract Summary | P1 | Generate summaries for non-lawyer clients |
| Standard Legal Letter Drafts | P2 | Demand letters, cease and desist, eviction notices |
| CAC Compliance Checklist | P1 | Per business type (Ltd, Business Name, NGO) |
| Secure Document Vault | P2 | NDAs, agreements, court filings |

#### 5.2.2 Claude AI Use Case

**Input:** Lawyer uploads shareholders agreement PDF (42 pages)  
**Output:** Risk report flagging 5 dangerous clauses (un enforceable non-compete, jurisdiction risks, missing NDPA consent, drag-along with no floor price)  
**Delivery:** Under 2 minutes, saves 2–3 hours manual review

#### 5.2.3 User Stories

| ID | Story | Acceptance Criteria |
|---|---|---|
| LT-001 | As a lawyer, I want to track CAC annual returns deadline so that I avoid the ₦10,000/month penalty | Calendar shows June 30 with alerts |
| LT-002 | As a lawyer, I want to manage court dates across multiple cases so that I never miss a hearing | Calendar displays all case dates with reminders |
| LT-003 | As a lawyer, I want to upload a contract and get AI risk analysis so that I can quickly identify dangerous clauses | Claude returns structured risk report with specific clauses flagged |
| LT-004 | As a lawyer, I want to generate plain-English summaries of contracts for clients so that non-lawyers understand their obligations | Summary generated in accessible language |
| LT-005 | As a lawyer, I want to draft standard legal letters so that I can save time on routine correspondence | Templates available for demand, cease & desist, eviction |

#### 5.2.4 Pricing Tiers

| Tier | Price | Features |
|---|---|---|
| Solo Lawyer | ₦12,000/month | CAC tracker, court calendar, 5 contract analyses/month, NBA reminder |
| Small Firm | ₦30,000/month | Team access (5 lawyers), 20 analyses/month, document vault, invoice tracker, SCUML checklist |
| CaaS Premium | ₦100,000/month | Unlimited analyses, quarterly advisory call, NDPA full module, custom branded reports |

---

### 5.3 EstateCheck (Product 3)

#### 5.3.1 Core Features

| Feature | Priority | Description |
|---|---|---|
| Tenancy Agreement Generator | P0 | Inputs → full legally-worded agreement via Claude in 30 seconds |
| Rent Due Date Calendar | P0 | WhatsApp reminders to tenants |
| Lease Renewal Tracker | P1 | 3-month advance alert |
| Landlord-Tenant Dispute Log | P2 | Communication timeline |
| LASRERA License Tracker | P0 | Licence status and annual renewal alert |
| CAC Returns Reminder | P1 | Deadline calendar |
| NDPA Compliance Checklist | P1 | Tenant data handling requirements |
| Property Inspection Checklist | P2 | 30-point pre-tenancy condition report |
| Commission Invoice Generator | P2 | PDF format |

#### 5.3.2 Claude AI Use Case

**Input:** Agent inputs landlord name, tenant name, property address, rent amount, duration  
**Output:** Full 8-clause tenancy agreement (Lagos Tenancy Law 2011 compliant), WhatsApp rent reminder schedule, stamp duty calculation + payment instructions  
**Delivery:** Single response, all in one

#### 5.3.3 User Stories

| ID | Story | Acceptance Criteria |
|---|---|---|
| EC-001 | As an estate agent, I want to generate legally compliant tenancy agreements so that I avoid void contracts | Agreement generated in under 30 seconds, compliant with Lagos Tenancy Law 2011 |
| EC-002 | As an estate agent, I want to send automatic rent reminders to tenants so that I reduce payment delays | WhatsApp reminders sent at scheduled intervals |
| EC-003 | As an estate agent, I want to track my LASRERA licence renewal so that I avoid operating illegally | Dashboard shows licence status with advance alerts |
| EC-004 | As a landlord, I want to track lease renewal dates so that I can negotiate early | Calendar shows 90/60/30-day advance notice |

#### 5.3.4 Pricing Tiers

| Tier | Price | Features |
|---|---|---|
| Free | ₦0/month | 1 agreement/month, basic rent tracker, watermarked PDF |
| Agent | ₦25,000/month | Unlimited agreements, LASRERA tracker, CAC returns, dispute log, invoice PDF, WhatsApp reminders |
| Agency/CaaS | ₦40,000/month | Multi-agent accounts, eviction notice generator, quarterly advisory call, NDPA full module |

---

### 5.4 FleetPulse (Product 4)

#### 5.4.1 Core Features

| Feature | Priority | Description |
|---|---|---|
| Driver Registry | P0 | Licence number, category, expiry date, photo upload |
| Licence Expiry Alerts | P0 | 60/30/7-day WhatsApp alerts to driver and manager |
| Vehicle Roadworthiness Tracker | P0 | Per plate number certificate status |
| FRSC/LAMATA Compliance Checklist | P1 | Per vehicle compliance status |
| Driver Performance Scorecard | P2 | Trips, incidents, punctuality metrics |
| WhatsApp Driver Bot | P0 | Drivers log trips by chat message or voice note (no app) |
| Fuel Expense Tracker | P1 | Per-trip cost, monthly trend chart |
| Claude Trip Analyzer | P0 | Flags fuel overspend, route inefficiency |
| Vehicle Maintenance Schedule | P1 | Mileage-based with advance alerts |
| Incident/Accident Reports | P2 | Claude-generated reports + driver warning letters |

#### 5.4.2 Claude AI Use Case

**Input:** Fleet manager sends WhatsApp message/voice note with trip update  
**Output:** Trip data logged, fuel cost compared to fleet average, anomalies flagged (e.g., 48% fuel overspend), maintenance check, structured dashboard report  
**Delivery:** From casual WhatsApp message

#### 5.4.3 User Stories

| ID | Story | Acceptance Criteria |
|---|---|---|
| FP-001 | As a fleet manager, I want to track driver licences so that I avoid FRSC impoundment | Dashboard shows all driver licence status with expiry countdown |
| FP-002 | As a fleet manager, I want drivers to log trips via WhatsApp so that I don't need them to install an app | WhatsApp bot accepts messages/voice notes and logs trips |
| FP-003 | As a fleet manager, I want Claude to analyze fuel spending so that I can identify waste | Claude flags anomalies vs fleet average |
| FP-004 | As a fleet manager, I want maintenance alerts so that I avoid breakdowns | Alerts trigger based on mileage thresholds |

#### 5.4.4 Pricing Tiers

| Tier | Price | Features |
|---|---|---|
| Starter (5 vehicles) | ₦25,000/month | Licence and roadworthiness tracker, trip log, fuel tracker, WhatsApp alerts |
| Growth (20 vehicles) | ₦50,000/month | WhatsApp driver bot, Claude trip analyzer, fuel efficiency, maintenance scheduler, driver warning letters |
| Pro/CaaS | ₦70,000/month | Unlimited vehicles, NSITF payroll tracker, accident report generator, quarterly advisory call |

---

### 5.5 ClinicShield (Product 5)

#### 5.5.1 Core Features

| Feature | Priority | Description |
|---|---|---|
| MDCN Licence Tracker | P0 | Per doctor with 60/30/7-day WhatsApp alerts |
| CME Hours Log | P1 | Training sessions tracking |
| HEFAMAA Inspection Checklist | P0 | 47-point readiness check with traffic-light status |
| Facility Accreditation Calendar | P1 | Renewal tracking |
| Staff Registration Status | P1 | MDCN, Nursing Council, MLSCN |
| NDPA Self-Assessment | P0 | Auto-score compliance with recommended actions |
| Patient Consent Form Generator | P1 | Procedure-specific templates |
| Data Breach Incident Log | P2 | 72-hour NDPC reporting guide |
| DPO Appointment Record | P2 | Contact management |
| Annual NDPC Audit Report | P0 | Claude-generated template |

#### 5.5.2 Claude AI Use Case

**Input:** Clinic owner inputs practice type, number of patients, data types stored  
**Output:** NDPA gap report showing risk level, missing requirements, penalty exposure in naira, numbered action list with deadlines  
**Delivery:** Under 60 seconds

#### 5.5.3 User Stories

| ID | Story | Acceptance Criteria |
|---|---|---|
| CS-001 | As a clinic owner, I want to track doctor MDCN licences so that I avoid criminal offence | Dashboard shows all doctor licence status with expiry alerts |
| CS-002 | As a clinic owner, I want to prepare for HEFAMAA inspection so that my clinic doesn't get shut down | 47-point checklist with traffic-light status |
| CS-003 | As a clinic owner, I want Claude to generate NDPA compliance report so that I know my risk exposure | Gap report generated with specific actions and penalties |
| CS-004 | As a clinic owner, I want to generate patient consent forms so that I comply with National Health Act | Templates available per procedure type |

#### 5.5.4 Pricing Tiers

| Tier | Price | Features |
|---|---|---|
| Solo Practice | ₦25,000/month | Up to 3 doctors, MDCN tracker, NDPA self-assessment, WhatsApp alerts |
| Clinic | ₦45,000/month | Up to 10 doctors/nurses, HEFAMAA checklist, NDPA module, CME tracker, Claude reports |
| CaaS Premium | ₦150,000/month | Multi-branch, quarterly advisory call, inspection preparation, priority support |

---

### 5.6 HotelComply (Product 6)

#### 5.6.1 Core Features

| Feature | Priority | Description |
|---|---|---|
| Tourism Licence Calendar | P0 | Pre-renewal alerts |
| Fire Safety Certificate Tracker | P0 | Inspection date history |
| Hygiene Inspection Record | P1 | Next-due date alerts |
| Environmental Permit (NESREA) | P1 | Tracker |
| VAT Return Calendar | P0 | 21st of each month reminders |
| PAYE Remittance Tracker | P1 | Per employee |
| Staff NSITF/Pension Board | P1 | Compliance status |
| Claude FIRS Audit Checklist | P0 | Generated preparation checklist |
| Guest Privacy Policy | P0 | NDPA-compliant template via Claude |
| Free Hotel Compliance Score | P0 | Lead magnet audit PDF |

#### 5.6.2 Claude AI Use Case

**Input:** Hotel manager inputs property type, staff count, services, current permits  
**Output:** Compliance status report with traffic-light indicators for each regulation, next 5 deadlines, penalty exposure, prioritised action plan  
**Delivery:** Single comprehensive report

#### 5.6.3 User Stories

| ID | Story | Acceptance Criteria |
|---|---|---|
| HC-001 | As a hotel manager, I want to track fire safety certificate so that I avoid immediate closure | Dashboard shows certificate status with renewal alerts |
| HC-002 | As a hotel manager, I want to track VAT filing deadlines so that I avoid FIRS penalties | Calendar shows 21st of month with WhatsApp reminders |
| HC-003 | As a hotel manager, I want Claude to generate compliance report so that I know my status across all regulations | Comprehensive report generated with traffic lights |
| HC-004 | As a hotel manager, I want a free compliance audit so that I can see my gaps | PDF audit generated as lead magnet |

#### 5.6.4 Pricing Tiers

| Tier | Price | Features |
|---|---|---|
| Guesthouse | ₦30,000/month | Licence and fire certificate tracker, VAT calendar, WhatsApp alerts |
| Hotel | ₦55,000/month | Full compliance suite, Claude AI tools, NDPA guest module, staff compliance board |
| CaaS Premium | ₦150,000/month | Multi-property, quarterly advisory call, inspection preparation, priority support |

---

### 5.7 FintechReady (Product 7)

#### 5.7.1 Core Features

| Feature | Priority | Description |
|---|---|---|
| CBN Cybersecurity Self-Assessment | P0 | Questionnaire mapped to 2024 framework |
| Annual Audit Checklist | P0 | All CBN documentation requirements |
| Incident Response Plan | P0 | Claude-generated template |
| 24-Hour Breach Workflow | P0 | NDPC and CBN report templates |
| Quarterly CBN Report Calendar | P0 | Deadline tracking |
| NDPC DCPMI Tracker | P0 | Registration status dashboard |
| Annual Data Protection Audit | P0 | Claude-generated report |
| KYC Policy Suite | P0 | Onboarding, transaction limits, enhanced due diligence |
| AML Transaction Policy | P1 | Templates |
| Data Subject Rights System | P2 | Request management |

#### 5.7.2 Claude AI Use Case

**Input:** Fintech founder inputs licence type, staff count, monthly transaction volume, infrastructure  
**Output:** Full CBN self-assessment report with compliance score, critical gaps (fix before next exam), moderate gaps (90 days), estimated fine exposure, 12 required policy documents generated  
**Delivery:** Comprehensive report with actionable documents

#### 5.7.3 User Stories

| ID | Story | Acceptance Criteria |
|---|---|---|
| FR-001 | As a fintech founder, I want to prepare for CBN cybersecurity audit so that I don't get fined | Self-assessment with gap analysis and document generation |
| FR-002 | As a fintech founder, I want to track NDPC registration so that I comply with NDPA GAID | Dashboard shows DCPMI status |
| FR-003 | As a fintech founder, I want Claude to generate all required policy documents so that I'm audit-ready | 12 policy documents generated |
| FR-004 | As a fintech founder, I want breach response workflow so that I can meet 24-hour CBN requirement | Workflow with templates for NDPC and CBN |

#### 5.7.4 Pricing Tiers

| Tier | Price | Features |
|---|---|---|
| Early Stage | ₦80,000/month | CBN self-assessment, NDPC tracker, quarterly report calendar, KYC templates |
| Licensed Fintech | ₦150,000/month | Full CBN audit suite, AML/KYC module, incident response plan, NDPA module, Claude reports |
| CaaS Enterprise | ₦400,000/month | Dedicated compliance specialist, monthly advisory, CBN exam preparation, board-ready reports, security trust documentation |

---

## 6. Cross-Product Requirements

### 6.1 Platform Features (All Products)

| Feature | Description |
|---|---|
| WhatsApp Alerts | All deadline notifications go to WhatsApp |
| Claude AI Integration | Document generation, analysis, reporting |
| Dashboard | Web-based user interface |
| Mobile Responsive | Accessible on mobile devices |
| PDF Export | Compliance reports as downloadable PDFs |
| Multi-tier Pricing | Standard, Pro, CaaS Premium tiers |
| Lead Magnet Tools | Free AI-powered tools for each product |

### 6.2 Technical Infrastructure

| Component | Technology |
|---|---|
| App Builder | Bubble.io |
| AI Engine | Claude API (Sonnet 4) |
| Payments | Paystack |
| WhatsApp Alerts | Twilio |
| Database | Supabase |
| Authentication | Firebase Auth |
| Email | Resend |
| PDF Reports | Puppeteer |
| Website | Framer/Webflow |
| Analytics | PostHog |
| CRM | HubSpot Free |
| Support | WhatsApp Business API |

### 6.3 Brand Requirements

| Element | Specification |
|---|---|
| "Powered by Claude AI" Badge | Displayed on every dashboard, report, and website |
| Anthropic Partnership | Referenced in About page and marketing materials |
| Nigerian Phone Number | Displayed on all product pages |
| WhatsApp Chat Button | Primary contact method on all pages |
| Privacy Statement | Displayed on all product pages |
| Security Statement | Displayed on all product pages |

---

## 7. User Experience Requirements

### 7.1 Design Principles

1. **WhatsApp-first** — Every alert goes to WhatsApp; interactions start there
2. **Simple onboarding** — No training required; intuitive for non-technical users
3. **Mobile-optimized** — Primary access via mobile; responsive design
4. **Clear hierarchy** — Compliance status visible at a glance (traffic lights)
5. **Action-oriented** — Every alert includes the next action to take

### 7.2 Product Page Requirements

Every product landing page must include:
- "Powered by Claude AI (Anthropic)" badge
- Client count and testimonials
- Nigerian phone number
- WhatsApp chat button
- Privacy and security statement
- Free Claude-powered tool as lead magnet
- Demo video (Loom walkthrough)
- 3-tier pricing with CaaS clearly separated

---

## 8. Analytics & Success Metrics

### 8.1 Product Metrics

| Metric | Target |
|---|---|
| MRR | ₦5,000,000+ by Month 18 |
| Total Clients | 200+ by Month 18 |
| Churn Rate | <5% (CaaS tier near-zero) |
| NPS Score | >50 |
| Lead-to-Customer Conversion | >20% |

### 8.2 Growth Metrics

| Metric | Phase 1 | Phase 2 | Phase 3 |
|---|---|---|---|
| MRR | ₦640,000 | ₦2,500,000 | ₦5,000,000+ |
| Clients | 40 | 100+ | 200+ |
| Team Size | 2 | 8–10 | 21 |
| Products Live | 2 | 5 | 7 |

---

## 9. Revenue Model

### 9.1 Pricing Architecture

Each product follows this tier structure:

| Tier | Type | Purpose |
|---|---|---|
| Tier 1 (Entry) | Standard SaaS | Software, dashboard, WhatsApp alerts |
| Tier 2 (Mid) | Professional SaaS | Unlimited features, Claude AI reports, full modules |
| Tier 3 (Premium) | CaaS | Software + quarterly advisory + document drafting + priority support |

### 9.2 CaaS Differentiation

- **Software** is the entry point
- **Quarterly advisory relationship** creates lifetime clients
- Priced at 3–5× standard tier
- Near-zero churn — embedded in how clients run their business

---

## 10. Timeline & Milestones

### 10.1 Phase 1 Milestones (Months 1–6)

| Milestone | Target Date |
|---|---|
| SchoolGuard MVP Launch | Month 1 |
| LexTrack MVP Launch | Month 2 |
| 5 beta schools onboarded | Month 3 |
| 5 beta lawyers onboarded | Month 3 |
| Paid tiers live (both products) | Month 4 |
| 20 paying schools | Month 5 |
| 20 paying lawyers | Month 6 |
| First 2 hires (CSM, Sales) | Months 5–6 |
| Phase 1 MRR: ₦640,000 | Month 6 |

### 10.2 Phase 2 Milestones (Months 7–12)

| Milestone | Target Date |
|---|---|
| EstateCheck Launch | Month 7 |
| FleetPulse Launch | Month 9 |
| ClinicShield Launch | Month 11 |
| Phase 2 MRR: ₦2,500,000 | Month 12 |

### 10.3 Phase 3 Milestones (Months 13–18)

| Milestone | Target Date |
|---|---|
| HotelComply Launch | Month 13 |
| FintechReady Launch | Month 15 |
| Phase 3 MRR: ₦5,000,000+ | Month 18 |

---

## 11. Appendix

### 11.1 Regulatory References

| Product | Regulations |
|---|---|
| SchoolGuard | TRCN, National Policy on Non-State Schools, MoE inspections, CAC returns, NDPA 2023 |
| LexTrack | CAC Annual Returns, NBA RPC 2007, SCUML, NDPA 2023 |
| EstateCheck | LASRERA Law 2021, Lagos Tenancy Law 2011, FIRS stamp duty, NDPA 2023 |
| FleetPulse | FRSC, Roadworthiness, LAMATA, NSITF |
| ClinicShield | MDCN, CME, HEFAMAA, NDPA 2023, National Health Act 2014 |
| HotelComply | Tourism Licensing, Fire Safety, FIRS VAT, NESREA, NDPA 2023, NSITF |
| FintechReady | CBN RBSCF 2024, NDPA GAID, EFCC AML, CBN Open Banking, CBN licence maintenance |

### 11.2 Competitor Analysis

| Competitor | Strength | Weakness |
|---|---|---|
| Generic compliance tools | Multi-industry | Not tailored to Nigerian regulations |
| Manual spreadsheets | Free | No automation, error-prone, no alerts |
| Compliance consultants | Expert guidance | Expensive, inconsistent, not scalable |
| International SaaS | Feature-rich | Not built for Nigeria, no WhatsApp, expensive |

### 11.3 Risk Factors

| Risk | Mitigation |
|---|---|
| Delayed product development | Build waitlist first, validate demand |
| Low adoption | WhatsApp-first, lead magnet tools |
| Regulatory changes | Build flexible, modular system |
| Competition | First-mover in vertical-specific |
| Team scaling | Hire after revenue, not before |

---

*End of Document*