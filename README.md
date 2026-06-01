# Cold Email Agent Instruction System

This repository contains reusable markdown instruction files for creating and managing AI agents for Accord Tech Solutions' cold email marketing operations.

These files are built to make cold email work repeatable, organized, and approval-based — from domain setup to data enrichment, ICP matching, offer routing, email writing, campaign launch, monitoring, and positive reply engagement.

## Purpose

The purpose of this repository is to make AI agents follow a clear, professional, and repeatable cold email workflow.

Instead of writing the same instructions again and again, these `.md` files can be added to any AI Agent, Claude Project, ChatGPT Project, or internal workflow.

## Current Agent Files

- `master-agent-instruction.md`  
  Main controller file. It explains which instruction file should be used for each task.

- `domain-infrastructure-agent.md`  
  For domain setup, DNS authentication, SPF, DKIM, DMARC, CNAME, tracking domain, mailbox setup, warmup, and infrastructure readiness.

- `data-enrichment-agent.md`  
  For lead data cleaning, First Name fixing, generic email detection, company name cleaning, employee count filtering, and final clean file creation.

- `icp-match-agent.md`  
  For ICP matching, lead qualification, employee size fit, geography fit, persona fit, business type, tech/non-tech classification, scoring, and campaign eligibility.

- `b2b-cold-email-service-routing.md`  
  For matching each lead/company with the right B2B cold email service offer or campaign angle.

- `email-writing-agent.md`  
  For cold email sequence writing, subject lines, CTAs, follow-ups, breakup emails, QA, and approval before campaign setup.

- `campaign-setup-agent.md`  
  For campaign launch readiness, MillionVerifier good email check, mailbox capacity, deliverability review, risk review, and CEO/ED approval.

- `brand-voice.md`  
  For writing tone, voice, banned words, CTA style, email messaging style, and reply-focused communication rules.

- `positive-reply-engagement.md`  
  For Instantly positive reply handling, master database lookup, lead report PDF creation, reply variant preparation, approval flow, and approved reply sending.

## Recommended Workflow

Use the files in this order:

1. `domain-infrastructure-agent.md`
2. `data-enrichment-agent.md`
3. `icp-match-agent.md`
4. `b2b-cold-email-service-routing.md`
5. `email-writing-agent.md`
6. `campaign-setup-agent.md`
7. `positive-reply-engagement.md`

`brand-voice.md` should be followed for all writing tasks, including cold emails, follow-ups, CTAs, subject lines, and reply messages.

## How To Use With An AI Agent

When creating or using an AI agent, upload or attach the required `.md` file and give a short task prompt.

Example:

```txt
Use data-enrichment-agent.md as the main instruction.

Process this uploaded lead file.
Work only on the specified columns.
Keep all original columns unchanged.
Add the required enrichment/status columns.
Create a final cleaned file.