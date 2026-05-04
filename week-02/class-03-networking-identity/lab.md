# Lab: Network Check and New Employee Access Ticket

**Points:** 20  
**Submit in:** Brightspace, if instructed  
**Estimated time:** 70 to 85 minutes

## Scenario

You receive two beginner help-desk tickets:

```text
Ticket 1: The user says the internet is not working.
Ticket 2: A new employee needs the correct account access.
```

Your job is to gather safe evidence and complete an access request simulation.

## Part 1: Create Your Work Folder

On the Desktop, create this folder:

```text
Class3_LastName
```

Inside it, create:

```text
Screenshots
Network_Notes
Identity_Table
Writeup
```

Take a screenshot of the folder structure.

## Part 2: Open Network Settings

1. Open Settings with `Windows + I`.
2. Go to `Network and internet`.
3. Take a screenshot showing whether the PC is connected.

Do not change network settings.

## Part 3: Run Safe Network Commands

Open Command Prompt:

1. Press `Windows + S`.
2. Search for `Command Prompt`.
3. Open it normally.

Run:

```powershell
ipconfig
```

Take a screenshot.

Then run:

```powershell
ping 8.8.8.8
```

Take a screenshot.

Then run:

```powershell
ping example.com
```

Take a screenshot.

Optional, if allowed by your instructor:

```powershell
tracert example.com
```

If a command is blocked, write:

```text
The command was blocked on this computer.
```

Then ask your instructor for sample output.

## Part 4: Answer Network Questions

Answer in your write-up:

1. What does an IP address identify?
2. What does DNS help with?
3. If `ping 8.8.8.8` works but `ping example.com` fails, what might be the problem?
4. What is one difference between `ping` and `tracert`?

## Part 5: Complete The Identity Simulation

Use this fictional company:

```text
Company: Campus Support Services
Username format: first initial + last name
MFA required: yes, for all users
```

Complete this table in your write-up.

| Employee | Department | Suggested Username | Groups Needed | Shared Resources | MFA Required |
| --- | --- | --- | --- | --- | --- |
| Maria Rivera | Accounting | | | | |
| Jamal Chen | Help Desk | | | | |
| Aisha Patel | Student Services | | | | |

Available groups:

- Accounting-Team
- HelpDesk-Team
- StudentServices-Team
- All-Staff
- Printer-Access

Available shared resources:

- Accounting shared folder
- Ticketing system
- Student records system
- Staff printer

## Part 6: Write Your Support Note

Create a file named:

```text
class3_support_note_LastName.docx
```

If Word is not available, use Notepad and save:

```text
class3_support_note_LastName.txt
```

Write two short paragraphs:

1. Network ticket: explain what you checked and what the results suggest.
2. Access ticket: explain why groups are safer than giving one person random direct access.

## Required Screenshots

- [ ] Folder structure
- [ ] Network settings
- [ ] `ipconfig` output or sample output
- [ ] `ping 8.8.8.8` output or sample output
- [ ] `ping example.com` output or sample output
- [ ] Completed identity table

## Rubric

| Category | Points |
| --- | ---: |
| Screenshots or sample evidence are complete | 6 |
| Network command steps are correct | 6 |
| Identity table and writing are clear | 5 |
| Files are named and organized properly | 3 |

## Exit Question

Answer in your support note:

```text
What is the difference between a user account and a group?
```

