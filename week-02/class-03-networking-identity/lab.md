# Lab: Week 14 Day 1 Catch-Up + Network Starter

**Points:** 20  
**Submit in:** Brightspace, if instructed  
**Estimated time:** 90 to 105 minutes

## Why This Lab Is Combined

Very few students attended Week 13 Day 2. Today combines that missed file/security lab with the next topic: networking and identity.

The goal is not to rush. The goal is to practice realistic entry-level IT support evidence gathering.

## Scenario

You receive three beginner help-desk tickets:

```text
Ticket 1: I lost my assignment.
Ticket 2: I downloaded something that might be suspicious.
Ticket 3: My internet is not working, and a new employee needs access.
```

Your job is to collect safe evidence and write a short support note.

## Part 1: Create Your Work Folder

On the Desktop, create this folder:

```text
Week14_Day1_LastName
```

Inside it, create:

```text
File_Recovery
Security_Check
Network_Evidence
Identity_Table
Writeup
```

Open the folder in File Explorer. Change the view to `Details` if you can:

```text
View > Details
```

Take a screenshot of the folder structure.

## Part 2: Catch-Up File Recovery

Open Notepad and type:

```text
Lost Assignment Practice
Today I practiced finding and recovering files in Windows 11.
This file is safe because I created it myself during class.
```

Save the file as:

```text
lost_assignment_LastName.txt
```

Save it inside the `File_Recovery` folder.

Right-click the file and open `Properties`.

In your write-up, record:

| Item | Answer |
| --- | --- |
| File name | |
| Type of file | |
| Opens with | |
| Location | |
| Size | |
| Date modified | |

Take a screenshot of the file Properties window.

## Part 3: Delete, Restore, And Verify

1. Copy `lost_assignment_LastName.txt`.
2. Paste the copy into `File_Recovery`.
3. Rename the copy:

```text
lost_assignment_copy_LastName.txt
```

4. Delete only the copy.
5. Open Recycle Bin.
6. Restore the deleted copy.
7. Confirm the file returned to `File_Recovery`.

Take screenshots showing:

- Recycle Bin or the restore step
- The restored file in `File_Recovery`

Do not delete personal files.

## Part 4: Search Evidence

Use File Explorer search to complete at least two searches.

Search by name:

```text
lost_assignment
```

Search by file type:

```text
*.txt
```

Then do one of these:

```text
datemodified:today
```

or sort the folder by `Date modified`.

Take screenshots of your search or sorting evidence.

## Part 5: Windows Security And File Safety

Open Windows Security.

Take screenshots of:

- Virus and threat protection
- Firewall and network protection

Do not change any settings.

In your write-up, classify each situation as `Safe`, `Suspicious`, or `Ask IT`.

| Scenario | Safe, Suspicious, or Ask IT | Reason |
| --- | --- | --- |
| A teacher posts a file in Brightspace for class. | | |
| An email says your account will close today unless you click a link. | | |
| A browser pop-up says your PC is infected and asks you to call a number. | | |
| A coworker sends an unexpected `.exe` file with no explanation. | | |
| A file is named `invoice.pdf.exe`. | | |
| A Word document from an unknown sender asks you to enable macros. | | |

## Part 6: Network Starter

Open Network settings:

1. Press `Windows + I`.
2. Go to `Network and internet`.
3. Take a screenshot showing whether the PC is connected.

Do not change network settings.

Open Command Prompt:

1. Press `Windows + S`.
2. Search for `Command Prompt`.
3. Open it normally.

Run:

```powershell
ipconfig
```

Take a screenshot.

Then run one of these, if allowed:

```powershell
ping 8.8.8.8
```

or:

```powershell
ping example.com
```

Take a screenshot. If the command is blocked, write:

```text
The ping command was blocked on this computer.
```

## Part 7: Identity Starter

Use this fictional company:

```text
Company: Campus Support Services
Username format: first initial + last name
MFA required: yes, for all users
```

Complete this table in your write-up.

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

## Part 8: Write Your Support Note

Create a file named:

```text
week14_day1_support_note_LastName.docx
```

If Word is not available, use Notepad and save:

```text
week14_day1_support_note_LastName.txt
```

Write 8 to 10 sentences using this structure:

```text
Problem:
File recovery evidence:
Security advice:
Network evidence:
Identity/access recommendation:
Next safe step:
```

Your response should explain:

1. How you recovered the practice file.
2. What search method helped you find it.
3. One clue that a file or email might be unsafe.
4. What network evidence you collected.
5. Why groups are safer than giving one person random direct access.

## If You Already Completed Week 13 Day 2

Still complete today’s combined submission, but you may use your previous file/security screenshots if they are clear.

Then improve your work by adding:

```text
My file organization recommendation:
```

Recommend a folder and file naming system for a student who keeps losing assignments.

## Required Screenshots

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

## Rubric

| Category | Points |
| --- | ---: |
| Screenshots and evidence are complete and clear | 6 |
| File recovery, search, and security steps are correct | 5 |
| Network and identity starter work is complete | 5 |
| Written support note is clear and professional | 4 |

## Exit Question

Answer in your support note:

```text
What is one support habit you practiced today that would help in a real help-desk job?
```

