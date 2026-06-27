---
name: bounty-task-analyzer
description: Analyzes Web3 bounty task descriptions and returns a structured 
breakdown of requirements, deliverables, action plan, and rejection risks. 
Use when a user pastes a bounty task and wants to know exactly what to build 
and submit to avoid rejection.
license: MIT
metadata:
  author: mimisola0808
  version: "1.0"
---

## Overview
Web3 contributors — especially newcomers in communities like NEAR Legion and 
IronClaw — often misread bounty tasks and get rejected for missing requirements 
or submitting the wrong deliverables. This skill parses any bounty description 
and returns a clear, actionable breakdown so contributors know exactly what to do.

## How To Use
Paste any bounty task description directly into the IronClaw agent.
The skill will automatically analyze it and return a structured report.

## What The Skill Does
When activated, analyze the bounty description and return:

### 1. REQUIREMENTS CHECKLIST
List every requirement from the task as a checkbox.
Nothing should be missed or assumed.

### 2. DELIVERABLES
List the exact items the contributor must submit.
Be specific — links, screenshots, file types, word counts, etc.

### 3. ACTION PLAN
Write a numbered step-by-step plan for completing the task.
Order steps logically from start to submission.

### 4. REJECTION RISKS
List 3 common mistakes that lead to rejection for this type of task.
Be direct and specific to Web3/crypto bounty contexts.

## Example Input
"Create a functional and practical custom skill using your IronClaw agent, 
then submit: skill name, working demo, and GitHub PR link."

## Example Output
**Requirements Checklist:**
- [ ] Build an original skill (not copied from existing sources)
- [ ] Skill must solve a real, meaningful problem
- [ ] GitHub link must show your own contribution

**Deliverables:**
1. Skill name + one paragraph explanation
2. Screenshot or video of skill working
3. GitHub repo or PR link

**Action Plan:**
1. Pick a real problem to solve
2. Build the skill inside IronClaw
3. Test it with real input and screenshot the output
4. Push to GitHub and submit all three deliverables

**Rejection Risks:**
- Submitting a skill copied from DCA.space or another registry
- Missing the GitHub proof link
- Building a demo skill with no real-world use case
