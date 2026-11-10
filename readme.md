# JudyCare™

**Tagline:** Your 24/7 Healthcare Administrative & Support Assistant  
**Idea Formation Date:** November 10, 2026  
**Owner:** NOFA Business Consulting LLC / NOFA AI Factory™  
**Stage:** Interactive Prototype

## Purpose
JudyCare™ is a patient-controlled AI healthcare administrative assistant concept. Doctors manage medical care; JudyCare™ manages the administrative work surrounding it.

## Prototype Features
- Patient dashboard
- Ask Judy scripted administrative assistant
- JudyCare™ BillGuard
- Simulated duplicate-charge and adjustment-discrepancy detection
- Insurance claim tracking and editable appeal drafting
- Simulated healthcare Gmail inbox
- Administrative tasks and cases
- Appointments and reminders
- Documents & Uploads tab: sample document library, temporary local PDF/image/text preview, file categorization, and session-only case linking
- Caregiver Mode
- localStorage persistence
- Demo JSON export and reset
- Light, mobile-responsive interface suitable for elderly users

## Demonstration Scenarios
1. **Medical Billing Error:** A fictional $850 hospital bill contains a duplicated laboratory charge and an adjustment discrepancy. JudyCare explains the comparison and prepares an inquiry.
2. **Insurance Claim Denial:** Claim CLM-8842 is denied pending documentation. JudyCare prepares an editable appeal draft and tracks the case.
3. **Appointment Administration:** A medical-office message requests forms before a visit. JudyCare identifies the deadline and creates a task.

## Technical Architecture
This proof of concept is a standalone browser application built with HTML5, CSS3, vanilla JavaScript and localStorage.

It has no backend, database, API keys, Google OAuth, Gmail API, payer integration, EHR integration, or payment processing.

## Safety and Privacy
The prototype does not provide diagnoses, treatment recommendations, legal advice, or guaranteed insurance/billing determinations. It does not claim HIPAA compliance. All included patient, billing, insurance and message data is fictional.

A production version would require secure authentication, role-based access, consent controls, audit trails, encryption, appropriate HIPAA/security analysis, and explicit human approval for outbound communications and financial actions.

## Repository Description
JudyCare™ is an AI-powered healthcare administrative assistant that helps patients and caregivers manage medical bills, insurance claims, appointments, correspondence, paperwork, and administrative follow-ups.

## Documents & Uploads Privacy

Only use fictional or test files. The Documents & Uploads tab accepts PDF, PNG, JPG, and TXT (maximum 5 MB). Selected files remain in browser memory for the current session and can be previewed locally and linked to a demo administrative case. Uploaded file bytes and metadata are not persisted in localStorage, transferred to a server, or processed by a real AI. Refreshing the page removes temporary uploads.
