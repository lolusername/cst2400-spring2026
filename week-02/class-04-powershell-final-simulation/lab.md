# Lab: Mini Help Desk Final Simulation

**Points:** 30  
**Submit in:** Brightspace, if instructed  
**Estimated time:** 75 to 90 minutes

## Scenario

You are working an entry-level help-desk shift. You receive three tickets:

```text
Ticket 1: My computer is slow.
Ticket 2: My internet is not working.
Ticket 3: I need access to the correct shared resources.
```

Your job is to collect evidence and write a professional support report.

## Part 1: Create Your Work Folder

On the Desktop, create this folder:

```text
Class4_LastName
```

Inside it, create:

```text
Screenshots
PowerShell_Evidence
Ticket_Notes
Final_Report
```

Take a screenshot of the folder structure.

## Part 2: Open PowerShell Safely

1. Press `Windows + S`.
2. Search for `PowerShell`.
3. Open it normally.
4. Do not run as administrator.

Run these commands one at a time.

```powershell
Get-Date
```

```powershell
Get-Process
```

```powershell
Get-Service
```

Take screenshots of at least two command outputs.

Optional, if allowed:

```powershell
Get-ComputerInfo
```

If a command is blocked, write that it was blocked and continue with the rest of the lab.

## Part 3: Ticket 1 - Slow Computer

Collect one piece of evidence:

- Task Manager screenshot, or
- Storage screenshot, or
- Startup apps screenshot

Write 2 to 3 sentences explaining what you checked.

## Part 4: Ticket 2 - Network Problem

Collect one piece of evidence:

- Network settings screenshot, or
- `ipconfig` output, or
- `ping example.com` output

Write 2 to 3 sentences explaining what the evidence suggests.

## Part 5: Ticket 3 - Access Request

Use this request:

```text
Employee: Diego Santos
Department: Help Desk
Needs: ticketing system, staff printer, general staff announcements
MFA: required
```

Complete this access table in your final report.

| Item | Answer |
| --- | --- |
| Suggested username | |
| Department | |
| Groups needed | |
| Shared resources needed | |
| MFA required | |
| What should be escalated, if anything? | |

Available groups:

- HelpDesk-Team
- All-Staff
- Printer-Access

## Part 6: Final Support Report

Create a file named:

```text
class4_final_report_LastName.docx
```

If Word is not available, use Notepad and save:

```text
class4_final_report_LastName.txt
```

Write one paragraph for each ticket.

Each paragraph should include:

1. What the user reported.
2. What evidence you collected.
3. What the evidence suggests.
4. A safe next step.
5. A user-friendly explanation.

## Required Screenshots

- [ ] Folder structure
- [ ] At least two PowerShell command outputs
- [ ] Slow computer evidence
- [ ] Network evidence
- [ ] Access table in final report

## Rubric

| Category | Points |
| --- | ---: |
| Evidence screenshots and command output | 8 |
| Correct troubleshooting process | 8 |
| Final support report quality | 8 |
| Organization and completion | 6 |

## Exit Question

Answer at the end of your final report:

```text
What is one IT support skill from this boot camp that belongs on a resume?
```

