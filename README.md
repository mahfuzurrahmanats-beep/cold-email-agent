# Cold Email Agent Instruction System

This repository contains reusable markdown instruction files for creating and managing AI agents for cold email marketing operations.

These files are built for Accord Tech Solutions' cold email workflow, including data enrichment, ICP matching, campaign setup, and brand voice control.

## Purpose

The purpose of this repository is to make AI agents work with a clear, repeatable, and professional process.

Instead of writing the same instructions again and again, these `.md` files can be added to any AI Agent, Claude Project, ChatGPT Project, or internal workflow.

## File Structure

- `master-agent-instruction.md`  
  Main controller file. It explains which instruction file should be used for each task.

- `data-enrichment-agent.md`  
  Used for checking, cleaning, filtering, and preparing lead data files.

- `icp-match-agent.md`  
  Used for checking whether leads match the target ICP and campaign requirements.

- `campaign-setup-agent.md`  
  Used for campaign planning, sequence setup, A/B testing, sending strategy, and launch checklist.

- `brand-voice.md`  
  Used for cold email writing style, tone, subject lines, CTAs, and reply-focused messaging.

## Recommended Workflow

Use the files in this order:

1. Data Enrichment
2. ICP Match
3. Campaign Setup
4. Brand Voice

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