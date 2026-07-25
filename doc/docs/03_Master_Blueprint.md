# BizMate AI

# Master Blueprint

**Version:** 1.0

**Status:** Approved

**Project:** BizMate AI

**Last Updated:** July 2026

---

# Purpose

The Master Blueprint is the single source of truth for BizMate AI.

It consolidates the product vision, engineering principles, architecture, AI philosophy, governance, and development standards into one document.

Every contributor, AI coding assistant, and future developer must treat this document as the authoritative reference for the project.

---

# Product Vision

BizMate AI is an AI-powered Business Assistant designed for African SMEs.

It enables business owners to manage customers, products, sales, credit sales, payments, expenses, and business insights using natural language and voice.

The application must remain simple enough for a first-time smartphone user while providing enterprise-grade reliability.

---

# Mission

Empower businesses to keep accurate business records with minimal effort through intelligent automation, multilingual AI, and offline-first technology.

---

# Vision

To become Africa's most trusted AI-powered Business Operating System.

---

# Core Objectives

BizMate AI shall:

- Simplify business record keeping.
- Eliminate paper notebooks.
- Reduce bookkeeping errors.
- Improve debt tracking.
- Provide actionable business insights.
- Support offline operation.
- Support multilingual voice interaction.
- Scale without architectural redesign.

---

# Target Users

Primary users include:

- Computer accessory dealers
- Electronics retailers
- Phone dealers
- Pharmacies
- Fashion businesses
- Spare parts dealers
- Grocery shops
- Supermarkets
- Service businesses
- General SMEs

---

# Guiding Principles

Every decision must follow these principles.

## Simplicity

Keep workflows short and intuitive.

---

## AI Assistance

AI recommends.

Users decide.

---

## Offline First

The application must continue functioning without internet connectivity.

---

## Mobile First

Every screen is designed for smartphones before larger devices.

---

## Security First

Security is built into every layer.

---

## Performance

Fast interactions take priority over unnecessary visual effects.

---

## Auditability

Financial actions must always be traceable.

---

## Extensibility

Future modules must integrate without redesigning Version 1.

---

# Product Scope

## Version 1

- Authentication
- Dashboard
- Customers
- Product Catalogue
- Sales
- Credit Sales
- Payments
- Expenses
- AI Assistant
- AI Business Memory
- Daily Brief
- Business Timeline
- Notifications
- Audit Trail
- Offline Synchronisation

---

## Future Versions

- Inventory
- Suppliers
- Purchase Orders
- CRM
- Payroll
- POS
- Receipt OCR
- Barcode Scanning
- Banking Integration
- WhatsApp Business
- Multi-Branch Support
- Predictive Analytics

---

# Architecture Principles

BizMate AI uses:

- Layered Architecture
- Event-Driven Architecture
- Offline-First Architecture
- Modular Design
- Service-Oriented Components
- Rules Engine
- AI Orchestration Layer

Every module must respect these architectural boundaries.

---

# Technical Stack

## Frontend

- React
- TypeScript
- Tailwind CSS
- shadcn/ui

## Backend

- Supabase
- PostgreSQL
- Edge Functions

## AI Layer

- AI Gateway
- Language Detection
- Speech-to-Text
- Intent Recognition
- Entity Extraction
- Confidence Engine
- AI Business Memory

---

# Core Services

- Authentication Service
- Customer Service
- Product Service
- Sales Service
- Payment Service
- Expense Service
- Dashboard Service
- Notification Service
- Synchronisation Service
- Audit Service
- AI Orchestration Service
- Rules Engine

Each service has a single responsibility.

---

# AI Principles

The AI must:

- Understand English.
- Understand Yoruba.
- Understand Hausa.
- Understand Igbo.
- Understand Nigerian Pidgin.
- Support mixed-language conversations.
- Ask for clarification when uncertain.
- Require confirmation before saving financial records.

The AI must never:

- Invent financial information.
- Override business rules.
- Save transactions automatically.
- Modify historical financial records.

---

# Rules Engine

Every financial operation must pass through the Rules Engine.

Responsibilities include:

- Validation
- Duplicate detection
- Business rule enforcement
- Financial calculations
- Approval checks

No service may bypass the Rules Engine.

---

# Event-Driven Architecture

Important business events publish system events.

Examples include:

- CustomerCreated
- CustomerUpdated
- ProductCreated
- SaleRecorded
- PaymentReceived
- ExpenseRecorded
- SyncCompleted
- NotificationSent

Subscribers include:

- Dashboard
- Timeline
- Audit
- AI Business Memory
- Notification Engine
- Synchronisation Engine

---

# Database Principles

- UUID primary keys.
- Row Level Security.
- Soft deletes where appropriate.
- Immutable audit records.
- Indexed search fields.
- Calculated balances.
- Offline synchronisation metadata.

---

# Security Standards

The application shall use:

- JWT Authentication
- Row Level Security
- HTTPS
- PIN protection
- Biometrics
- Secure local storage
- Principle of Least Privilege

---

# User Experience Principles

The application shall provide:

- Mobile-first layouts.
- One-handed usability.
- Light Mode.
- Dark Mode.
- Accessible typography.
- Consistent spacing.
- Responsive design.
- Smooth animations.

---

# Design System

Brand:

**BizMate AI**

Primary Color:

Deep Blue

Secondary Color:

Sky Blue

Success:

Green

Warning:

Orange

Error:

Red

Neutral backgrounds.

Rounded corners.

Modern SaaS appearance.

---

# Offline Strategy

The application must:

- Queue offline transactions.
- Synchronize automatically.
- Detect conflicts.
- Prevent data loss.
- Retry failed synchronisations.

---

# Coding Standards

All code must:

- Be modular.
- Be strongly typed.
- Avoid duplication.
- Reuse components.
- Follow consistent naming.
- Include error handling.
- Include loading states.
- Include empty states.

---

# Quality Standards

Every feature must include:

- Functional testing.
- Responsive testing.
- Offline testing.
- Error handling.
- Performance verification.
- Accessibility review.

---

# Development Workflow

Every implementation follows this sequence:

1. Review documentation.
2. Audit existing code.
3. Reuse existing components.
4. Implement feature.
5. Test.
6. Optimize.
7. Commit.
8. Review.

---

# Governance

Before implementing any feature, confirm:

- Does it solve a genuine business problem?
- Does it align with the product vision?
- Does it preserve architectural integrity?
- Does it keep the application simple?
- Does it avoid duplicate functionality?
- Does it maintain security?
- Does it preserve offline capability?

If the answer to any question is "No", redesign before implementation.

---

# Definition of Success

BizMate AI succeeds when a business owner can:

- Record transactions quickly.
- Retrieve information instantly.
- Trust AI suggestions.
- Operate offline confidently.
- Understand business performance.
- Grow without changing applications.

---

# Change Management

Every architectural change shall:

- Be documented.
- Be reviewed.
- Preserve backward compatibility where practical.
- Update related documentation.
- Include migration guidance when required.

---

# References

This blueprint should always be read together with:

- 01_Context_Pack.md
- 02_PRD.md
- 04_Architecture.md
- 05_Sprint_Roadmap.md
- 06_Technical_Decisions.md

---

# Document Control

**Document:** Master Blueprint

**Project:** BizMate AI

**Version:** 1.0

**Status:** Approved

This document is the governing reference for the BizMate AI project and supersedes any conflicting implementation decisions unless formally updated.
