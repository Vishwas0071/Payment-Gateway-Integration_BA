# Project 03 — Payment Gateway Integration
### Domain: Payments / Fintech | Role: Business Analyst

---

## Overview
A fintech startup's merchant portal supported only basic net banking, 
causing high checkout abandonment due to limited payment options. 
This project covers BA documentation for a multi-method payment 
gateway integration targeting a 95%+ checkout success rate and 
full T+1 settlement automation.

---

## Business Objective
- Enable UPI, Cards, Net Banking, and Wallet payment methods
- Achieve checkout success rate above 95%
- Automate merchant settlement within T+1 business day
- Achieve 100% settlement reconciliation accuracy

---

## Scope
- Multi-method checkout: UPI, Visa/Mastercard/RuPay, Net Banking, Wallets
- Real-time merchant transaction dashboard
- Automated daily settlement to merchant bank accounts
- Full and partial refund processing with status tracking
- Daily reconciliation report generation (PDF and CSV)
- Merchant onboarding and KYC module

---

## Epics Covered
| Epic | User Stories |
|------|-------------|
| Payment Checkout | PG-001 |
| Payment Confirmation | PG-002 |
| Merchant Dashboard | PG-003 |
| Refund Processing | PG-004 |

---

## Key Business Rules
- Settlement to merchants within T+1 business day
- Transactions above Rs.2 Lakhs require OTP authentication
- Failed transactions auto-retried once after 30 seconds
- MDR: 1.8% for cards, 0% for UPI per RBI mandate
- No card data stored on servers — tokenization only

---

## UAT Coverage
8 test cases covering UPI payments, card validation, 2FA triggering, 
auto-retry on failure, refund initiation, and settlement reporting.

---

## Compliance
PCI-DSS | RBI Payment Aggregator Guidelines | MDR Regulations

---

## Tools Used
Jira | Figma | Lucidchart | Agile Scrum

---

## Document
[View Full BA Document (PDF)](./Project03_Payment_Gateway.pdf)
