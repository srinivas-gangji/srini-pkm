# Personal Tasks Management

A structured system for organizing weekly personal tasks.

## 📁 Folder Structure

- **`Active/`** - Current week's tasks (only one file should be here at a time)
- **`Upcoming/`** - Future weeks' tasks that haven't started yet
- **`Completed/`** - Archive of finished weeks

## 📝 Workflow

1. **At the start of each week:** Move the current week's file from `Upcoming/` to `Active/`
2. **During the week:** Update tasks in the `Active/` folder
3. **At the end of the week:** Move the completed file from `Active/` to `Completed/`

## 🗓️ File Naming Convention

Files are named: `Week-YYYY-MM-DD.md` (using the Monday date of that week)

**Location:** 
- New weeks → `Upcoming/` folder
- Current week → `Active/` folder (only ONE file here)
- Finished weeks → `Completed/` folder

### ✅ Correct Examples:
- `Upcoming/Week-2025-10-21.md` ← Week of October 21-25, 2025
- `Active/Week-2025-10-28.md` ← Current active week
- `Completed/Week-2025-10-14.md` ← Finished week

### ❌ Incorrect Examples:
- `Week-10-21-2025.md` ← Wrong date format (should be YYYY-MM-DD)
- `Week-2025-10-23.md` ← Not a Monday (should use Monday of that week)
- `2025-10-21_Week.md` ← Wrong format (should be Week-YYYY-MM-DD)

## 🤖 AI Assistant Instructions

When user asks to "create weekly personal tasks" or "create personal tasks for [week]":

1. **Determine the week's Monday date:**
   - If user specifies a date, find the Monday of that week
   - If user says "this week", use the Monday of current week
   - If user says "next week", use the Monday of next week
   - If not specified, assume they want the upcoming Monday
   - Format as YYYY-MM-DD

2. **Calculate the full week date range:**
   - Start: Monday date
   - End: Friday date (Monday + 4 days)
   - Format for title: "October 21 to October 25, 2025" style

3. **Determine the folder:**
   - Default to `Upcoming/` for future weeks
   - User can specify if it should be in `Active/`
   - Never create directly in `Completed/`

4. **Calculate individual dates for daily tasks:**
   - Monday: MM/DD
   - Tuesday: MM/DD
   - Wednesday: MM/DD
   - Thursday: MM/DD
   - Friday: MM/DD

5. **Create the file:**
   - Path: `/Users/sgangj200/Documents/SRINI-HOME/srini-pkm/_PersonalTasks/[Folder]/Week-YYYY-MM-DD.md`
   - Use the Weekly Template below
   - Fill in all dates and the week date range

### Example Requests & Actions:

| User Request                                | Monday Date                      | Week Range      | Folder   | File Path                     |
| ------------------------------------------- | -------------------------------- | --------------- | -------- | ----------------------------- |
| "Create weekly personal tasks"              | Next Monday (2025-10-28)         | Oct 28 - Nov 1  | Upcoming | `Upcoming/Week-2025-10-28.md` |
| "Create personal tasks for this week"       | This Monday (2025-10-21)         | Oct 21 - Oct 25 | Active   | `Active/Week-2025-10-21.md`   |
| "Create weekly personal tasks for next week"| Next Monday (2025-10-28)         | Oct 28 - Nov 1  | Upcoming | `Upcoming/Week-2025-10-28.md` |
| "Create personal tasks for Nov 4"           | Monday of that week (2025-11-04) | Nov 4 - Nov 8   | Upcoming | `Upcoming/Week-2025-11-04.md` |

### Important Notes:
- Always use Monday as the week start date in the filename
- Only one file should exist in `Active/` at a time
- Fill in all MM/DD dates for Monday through Friday in the template
- Status should be "Upcoming" for new weeks, "Active" for current week

## 📋 Weekly Template

Use this template to create new weekly task files:

```markdown
# Weekly Personal Tasks - Week of [Start Date] to [End Date]

**Week:** YYYY-MM-DD  
**Status:** Upcoming / Active / Completed

---

## 🔴 High Priority

- [ ] Task description here
  - **Due Date:** YYYY-MM-DD
  - **Notes:** Additional details

## 🟡 Medium Priority

- [ ] Task description here
  - **Due Date:** YYYY-MM-DD
  - **Notes:** Additional details

## 🟢 Low Priority

- [ ] Task description here
  - **Due Date:** YYYY-MM-DD
  - **Notes:** Additional details

---

## 📅 Daily Tasks

### Monday (MM/DD)
- [ ] Task
- [ ] Task
- [ ] Task

### Tuesday (MM/DD)
- [ ] Task
- [ ] Task
- [ ] Task

### Wednesday (MM/DD)
- [ ] Task
- [ ] Task
- [ ] Task

### Thursday (MM/DD)
- [ ] Task
- [ ] Task
- [ ] Task

### Friday (MM/DD)
- [ ] Task
- [ ] Task
- [ ] Task

### Saturday (MM/DD)
- [ ] Task
- [ ] Task
- [ ] Task

### Sunday (MM/DD)
- [ ] Task
- [ ] Task
- [ ] Task

---

## 🏠 Home & Family

### Task Category 1
- **Status:** In Progress / On Hold / Planning
- **Description:** Brief description
- **This Week's Tasks:**
  - [ ] Task 1
  - [ ] Task 2
  - [ ] Task 3

### Task Category 2
- **Status:** In Progress / On Hold / Planning
- **Description:** Brief description
- **This Week's Tasks:**
  - [ ] Task 1
  - [ ] Task 2

---

## 💪 Health & Wellness

- [ ] Exercise goal
- [ ] Meal planning
- [ ] Doctor appointments
- [ ] Self-care activities

---

## 📚 Learning & Growth

- [ ] Books to read
- [ ] Courses to complete
- [ ] Skills to practice
- [ ] Articles to review

---

## 💰 Financial Tasks

- [ ] Bills to pay
- [ ] Budget review
- [ ] Financial planning
- [ ] Expense tracking

---

## 📝 Notes & Updates

### Accomplishments
- 

### Challenges
- 

### Next Week Planning
- 

---

## 🔗 Related Links

- [Daily Notes](../_DailyNotes/)
```

## 📊 Quick Stats

At the end of each week, you can add a quick summary:
- Total tasks completed: X
- High priority completed: X
- Carry-over to next week: X

---

**Last Updated:** October 22, 2025
