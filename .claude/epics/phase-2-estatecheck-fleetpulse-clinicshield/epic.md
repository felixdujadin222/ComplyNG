---
name: phase-2-estatecheck-fleetpulse-clinicshield
status: backlog
created: 2026-05-17T00:00:00Z
progress: 0%
github: (pending)
---

# Epic: Phase 2 — EstateCheck + FleetPulse + ClinicShield

## Overview

Launch 3 new products using Phase 1 revenue. Products: EstateCheck (M7), FleetPulse (M9), ClinicShield (M11). MRR target: ₦2,500,000.

## Timeline

- **Months 7-8**: Launch EstateCheck, hire EstateCheck sales rep, target 20 agents
- **Months 9-10**: Launch FleetPulse, build WhatsApp driver bot, target 15 logistics companies
- **Months 11-12**: Launch ClinicShield, hire rep with healthcare background, target 20 clinics

## Products

### EstateCheck

Industry: Estate agents, landlords, property managers (500,000+)  
Core Problem: LASRERA licensing, compliant tenancy agreements under Lagos Tenancy Law 2011

**Features:**
- Tenancy agreement generator (Claude creates 8-clause agreement in 30 seconds)
- Rent due date calendar with WhatsApp reminders
- Lease renewal tracker (3-month advance alert)
- Landlord-tenant dispute log
- LASRERA licence status and renewal alert
- CAC annual returns deadline calendar
- NDPA compliance checklist for tenant data
- Property inspection checklist (30-point)
- Commission invoice generator (PDF)

**Claude AI Use Case:**
- Input: Landlord name, tenant name, property address, rent amount, duration
- Output: Full 8-clause tenancy agreement (Lagos Tenancy Law 2011), WhatsApp rent reminder schedule, stamp duty calculation
- Delivery: Single response, all in one

**Pricing:**
- Free: ₦0/mo (1 agreement/mo, watermarked)
- Agent: ₦25,000/mo (unlimited, LASRERA, CAC, disputes, WhatsApp)
- Agency/CaaS: ₦40,000/mo (+ multi-agent, eviction notices, quarterly call)

**Target:** 30+ clients = ₦700,000+ MRR

### FleetPulse

Industry: SME logistics, courier, haulage, delivery fleets (200,000+)  
Core Problem: Expired driver licences, unserviced vehicles, no fuel tracking

**Features:**
- Driver registry (licence number, category, expiry, photo)
- Licence expiry WhatsApp alerts (60/30/7 days)
- Vehicle roadworthiness certificate tracker
- FRSC/LAMATA compliance checklist per vehicle
- Driver performance scorecard
- **WhatsApp driver bot** — drivers log trips by chat/voice (no app download!)
- Fuel expense tracker with trend charts
- **Claude trip analyzer** — flags fuel overspend, route inefficiency
- Vehicle maintenance schedule by mileage
- Claude-generated incident reports + driver warning letters

**Claude AI Use Case:**
- Input: Fleet manager sends WhatsApp message/voice note with trip update
- Output: Trip logged, fuel vs fleet average, anomalies flagged (e.g., 48% overspend), maintenance check, structured report

**Pricing:**
- Starter (5 vehicles): ₦25,000/mo
- Growth (20 vehicles): ₦50,000/mo
- Pro/CaaS: ₦70,000/mo

**Target:** 20 companies = ₦700,000 MRR

### ClinicShield

Industry: Private dental and medical clinics (15,000+)  
Core Problem: MDCN renewal, HEFAMAA inspections, NDPA patient data compliance

**Features:**
- MDCN licence expiry tracker per doctor (60/30/7-day WhatsApp alerts)
- CME hours log (training sessions tracking)
- **HEFAMAA inspection checklist** — 47-point readiness with traffic-light status
- Facility accreditation renewal calendar
- Staff registration status (MDCN, Nursing Council, MLSCN)
- **NDPA self-assessment** — auto-score compliance with recommended actions
- Patient consent form generator (per procedure type)
- Data breach incident log with 72-hour NDPC guide
- DPO appointment record
- **Claude-generated annual NDPC audit report**

**Claude AI Use Case:**
- Input: Clinic owner inputs practice type, patient count, data types stored
- Output: NDPA gap report showing risk level, missing requirements, penalty in naira, numbered action list with deadlines

**Pricing:**
- Solo Practice (3 doctors): ₦25,000/mo
- Clinic (10 staff): ₦45,000/mo
- CaaS Premium: ₦150,000/mo

**Target:** 20 clinics = ₦500,000–₦700,000 MRR

## Architecture Decisions

- **Bubble.io** for all 3 products
- **WhatsApp-first design** — core product philosophy
- **No app download** for FleetPulse drivers
- **Lead magnets**: Free agreement for EstateCheck, free NDPA scan for ClinicShield

## Technical Approach

- **Month 7**: EstateCheck MVP + sales rep
- **Month 9**: FleetPulse MVP + WhatsApp driver bot
- **Month 11**: ClinicShield MVP + healthcare rep

## Dependencies

- Phase 1 revenue funding Phase 2 hiring
- First 2 staff managing Phase 1 products while launching new ones

## Success Criteria

- [ ] EstateCheck launched with agreement generator
- [ ] FleetPulse launched with WhatsApp driver bot
- [ ] ClinicShield launched with NDPA gap report generator
- [ ] Phase 2 MRR: ₦2,500,000 total

## Estimated Effort

- Development: 6 months
- Target MRR: ₦2,500,000
- Team size: 8–10