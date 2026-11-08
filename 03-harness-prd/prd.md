[harness-sketch (2).md](https://github.com/user-attachments/files/34542893/harness-sketch.2.md)

# Harness Sketch

Describe Juno's role and task: Generate a feature request ticket per issue for the past week based on slack threads, jira tickets (especially bugs), support tickets and Notion docs. 

_Rough first pass, Module 3 Lab 1. Not the AI PRD._

## 01 · Context
Slack threads, jira tickets, and Notion documnents.

## 02 · Tools
It can generate feature request tickets and amend feature request tickets that have been created in the last 4 weeks. It can flag feature requests. It can pull and synthesize data from slack threads, jira tickets, and notion documents. 

## 03 · Loop
Twice.

## 04 · Memory
It remembers previously generated feature request tickets from the last 4 weeks so as to not generate duplicates. 

## 05 · Permissions
No feature request tickets move beyond the "To Triage" column in Jira. The tickets are assigned to the product manager. It can reference client names, contact at the company, ARR, description of the company, and the company-specific workflow in which our product is embedded. 

## 06 · Verification
It adds the links to the slack threads, notion documents, or Jira tickets at the end of the ticket as a reference. 
