# Today’s Class Sheet: Week 2 Day 1

## What We Are Doing Today

Today is a combined catch-up and new-skill lab.

Because many students missed the previous class, we are folding the missed file/search/security lab into today. After that, we will start networking and identity basics.

You will work on one combined help-desk scenario:

```text
Ticket 1: I lost my assignment.
Ticket 2: I downloaded something that might be suspicious.
Ticket 3: My internet is not working, and a new employee needs access.
```

## Main Goal

Practice a real entry-level support habit:

```text
Check evidence. Take screenshots. Explain the next safe step.
```

This is not about memorizing every button.

## What To Open

Open the class GitHub repo:

```text
https://github.com/lolusername/cst2400-spring2026
```

Then open:

```text
week-02 / class-03-networking-identity / lab.md
```

Direct class folder:

```text
week-02/class-03-networking-identity
```

## Today’s Timeline

| Time | What Happens | What You Should Be Doing |
| --- | --- | --- |
| 0-10 min | Class reset and safety rules | Open today’s lab |
| 10-20 min | Instructor shows folder + practice file + Properties | Watch, then start your folder |
| 20-45 min | File recovery catch-up | Create file, check Properties, copy/delete/restore |
| 45-60 min | Search evidence | Search by name, type, and date/sort |
| 60-75 min | Windows Security | Screenshot security status screens |
| 75-95 min | Network starter | Screenshot Network settings, run `ipconfig`, try `ping` if allowed |
| 95-110 min | Identity starter | Complete the user/group/access table |
| 110-120 min | Finish and submit | Complete write-up and checklist |

There is enough lab work to take most of class. If you finish early, complete the “strong submission” section near the end of this sheet.

## Safety Rules

- Do not delete personal files.
- Do not download anything.
- Do not open suspicious links or attachments.
- Do not change Windows Security settings.
- Do not change network settings.
- Do not run commands as administrator.
- If something is blocked, document that it was blocked and keep going.

## Quick Windows Help

| Need | Use This |
| --- | --- |
| Open File Explorer | `Windows + E` |
| Open Settings | `Windows + I` |
| Open Search | `Windows + S` |
| Take a screenshot snip | `Windows + Shift + S` |
| Open Command Prompt | `Windows + S`, type `Command Prompt` |
| Open Windows Security | `Windows + S`, type `Windows Security` |
| Find Recycle Bin | Desktop, or `Windows + S`, type `Recycle Bin` |

## Part 1: File Recovery Catch-Up

Create this folder on the Desktop:

```text
Week2_Day1_LastName
```

Inside it, create:

```text
File_Recovery
Security_Check
Network_Evidence
Identity_Table
Writeup
```

Create a Notepad file named:

```text
lost_assignment_LastName.txt
```

Save it inside `File_Recovery`.

Right-click the file and open `Properties`.

Record:

- file name
- type of file
- opens with
- location
- size
- date modified

## Part 2: Restore Practice

Copy your practice file.

Rename the copy:

```text
lost_assignment_copy_LastName.txt
```

Delete only the copy.

Open Recycle Bin and restore it.

Take screenshot evidence.

## Part 3: Search Evidence

Try these searches in File Explorer:

```text
lost_assignment
```

```text
*.txt
```

Then try:

```text
datemodified:today
```

If that does not work, sort by `Date modified`.

## Part 4: Security Check

Open Windows Security.

Screenshot:

- Virus and threat protection
- Firewall and network protection

Do not change settings.

## Part 5: Network Starter

Open Network settings:

```text
Windows + I > Network and internet
```

Take a screenshot.

Open Command Prompt and run:

```powershell
ipconfig
```

Take a screenshot.

If allowed, run one:

```powershell
ping 8.8.8.8
```

or:

```powershell
ping example.com
```

If it is blocked, write:

```text
The ping command was blocked on this computer.
```

## Terms You Need Today

| Term | Simple Meaning |
| --- | --- |
| File Properties | Information about a file, such as type, location, size, and date modified |
| Recycle Bin | Where many deleted local files go before permanent deletion |
| File extension | The ending of a file name, such as `.txt`, `.docx`, `.pdf`, or `.exe` |
| `.exe` | A Windows executable program file; unexpected `.exe` files should be treated carefully |
| `ipconfig` | A command that shows basic network information |
| IP address | A number that identifies a device on a network |
| DNS | A system that turns names like `example.com` into network addresses |
| Ping | A command that tests whether a network address responds |
| User account | One person’s login |
| Group | A collection of users who can be given access together |
| MFA | Multi-factor authentication; a login protection beyond just a password |

## Identity Starter

Fictional company:

```text
Company: Campus Support Services
Username format: first initial + last name
MFA required: yes, for all users
```

Complete this table in your write-up:

| Employee | Department | Suggested Username | Groups Needed | Shared Resources | MFA Required |
| --- | --- | --- | --- | --- | --- |
| Jamal Chen | Help Desk | | | | |
| Aisha Patel | Student Services | | | | |

Available groups:

- HelpDesk-Team
- StudentServices-Team
- All-Staff
- Printer-Access

Available shared resources:

- Ticketing system
- Student records system
- Staff printer

## What To Submit

Submit screenshots and a short write-up if your instructor asks for Brightspace submission.

Your write-up file:

```text
week2_day1_support_note_LastName.docx
```

If Word is not available:

```text
week2_day1_support_note_LastName.txt
```

## Required Screenshot Checklist

- [ ] Folder structure
- [ ] File Properties window
- [ ] Recycle Bin or restore step
- [ ] Restored file in `File_Recovery`
- [ ] Search result or date sorting evidence
- [ ] Virus and threat protection
- [ ] Firewall and network protection
- [ ] Network settings
- [ ] `ipconfig` output or sample output
- [ ] `ping` output, blocked-message note, or sample output
- [ ] Completed identity table

## Write-Up Structure

Use this structure:

```text
Problem:
File recovery evidence:
Security advice:
Network evidence:
Identity/access recommendation:
Next safe step:
```

Write 8 to 10 sentences total.

## If You Finish Early

Add this section:

```text
My file organization recommendation:
```

Recommend:

- one folder naming rule
- one file naming rule
- where screenshots should go
- what to do before opening unexpected attachments

Then answer:

```text
Why is invoice.pdf.exe suspicious?
```

## Exit Question

Answer at the end of your write-up:

```text
What is one support habit you practiced today that would help in a real help-desk job?
```

