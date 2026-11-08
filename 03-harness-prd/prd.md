[harness-sketch (2).md](https://github.com/user-attachments/files/34542893/harness-sketch.2.md)

# Harness Sketch

Describe Juno's role and task: Generate a feature request ticket per issue for the past week based on slack threads, jira tickets (especially bugs), support tickets and Notion docs. Prioritise these tickets based on impact, effort and risk.

_Rough first pass, Module 3 Lab 1. Not the AI PRD._

## 01 · Context
Slack threads, jira tickets, support tickets, Notion.

## 02 · Tools
It can generate feature request tickets and amend feature request tickets that have been created in the last 4 weeks.

## 03 · Loop
Twice.

## 04 · Memory
It remembers previously generated feature request tickets so as to not generate duplicates. It can reprioritise a previous feature request ticket or refine it.

## 05 · Permissions
No feature request tickets move beyond the "To Triage" column in Jira. The tickets are assigned to the product manager. It can reference client data in the support ticket.

## 06 · Verification
It adds the links to the slack threads, emails, or Jira tickets at the end of the ticket.
