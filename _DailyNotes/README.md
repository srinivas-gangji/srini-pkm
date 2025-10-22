# Daily Notes

A simple system for capturing daily thoughts, ideas, and observations.

## 📁 Folder Structure

- **`YYYY/`** - Yearly folders (e.g., 2025, 2026)
  - **`Month/`** - Monthly folders within each year (e.g., October, November)
    - Daily note files

## 📝 Workflow

1. **Each day:** Create a new note file using the naming convention below
2. **During the day:** Capture thoughts, ideas, learnings, and observations
3. **End of day:** Review and add any final notes
4. **Weekly/Monthly:** Review past notes for insights and patterns

## 🗓️ File Naming Convention

Files are named: `YYYY-MM-DD.md` (ISO date format)

**Location:** Place file in the `YYYY/Month/` folder matching the date

### ✅ Correct Examples:
- `2025/October/2025-10-20.md` ← October 20, 2025
- `2025/November/2025-11-15.md` ← November 15, 2025
- `2025/December/2025-12-25.md` ← December 25, 2025
- `2026/January/2026-01-05.md` ← January 5, 2026

### ❌ Incorrect Examples:
- `10-20-2025.md` ← Wrong date format (should be YYYY-MM-DD)
- `2025-10-20-notes.md` ← Extra text in filename (should be just date)
- `October-20-2025.md` ← Month name instead of number

## 🤖 AI Assistant Instructions

When user asks to "create daily notes" or similar:

1. **Determine the date:**
   - If user specifies a date, use it
   - If not specified, use today's date
   - Format as YYYY-MM-DD

2. **Determine the year and month folder:**
   - Extract year (YYYY) and full month name from the date
   - Month names: January, February, March, April, May, June, July, August, September, October, November, December
   - File goes in `_DailyNotes/YYYY/MonthName/` folder

3. **Determine the day of week:**
   - Calculate or determine: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
   - Use for the title line in the template

4. **Create the file:**
   - Path: `/Users/sgangj200/Documents/SRINI-HOME/srini-pkm/_DailyNotes/YYYY/MonthName/YYYY-MM-DD.md`
   - Use the Daily Note Template below
   - Fill in the date, day of week, and month in the template

### Example Requests & Actions:

| User Request                       | Date to Use            | Year | Month    | Day of Week | File Path                     |
| ---------------------------------- | ---------------------- | ---- | -------- | ----------- | ----------------------------- |
| "Create daily notes"               | Today (2025-10-22)     | 2025 | October  | Wednesday   | `2025/October/2025-10-22.md`  |
| "Create daily notes for tomorrow"  | Tomorrow (2025-10-23)  | 2025 | October  | Thursday    | `2025/October/2025-10-23.md`  |
| "Create daily notes for Nov 15"    | 2025-11-15             | 2025 | November | Saturday    | `2025/November/2025-11-15.md` |
| "Create daily notes for yesterday" | Yesterday (2025-10-21) | 2025 | October  | Tuesday     | `2025/October/2025-10-21.md`  |

## 📋 Daily Note Template

Use this template to create new daily notes:

```markdown
# Daily Note - [Day of Week], [Month] [DD], [YYYY]

**Date:** YYYY-MM-DD  
**Weather:** ☀️ / ⛅ / 🌧️ / ❄️  
**Mood:** 😊 / 😐 / 😔 / 🤔 / 🎉

---

## 💭 Quick Thoughts

- 
- 
- 

---

## 💡 Ideas

- 
- 
- 

---

## 📚 Today I Learned

- 
- 
- 

---

## ✅ Wins & Accomplishments

- 
- 
- 

---

## 🤔 Challenges & Problems

- 
- 
- 

---

## 📝 Notes & Observations

### Work


### Personal


### Technical


---

## 🔗 Related Links

- [Weekly Tasks](../WorkTasks/Active/)
- [Infrastructure Bookmarks](../Notes/Infrastructure.md)

---

## 🎯 Tomorrow's Focus

- 
- 
- 
```

## 💡 Tips

- **Keep it simple** - Don't overthink it, just capture what comes to mind
- **Be consistent** - Try to write something every day, even if brief
- **Use tags** - Add #tags to make searching easier later
- **Link notes** - Reference other daily notes or documents when relevant
- **Review regularly** - Look back at past notes to spot patterns and insights

## 🔍 Finding Notes

- Browse by year and month in the folder structure
- Use VS Code's search (Cmd+Shift+F) to find specific content across all notes
- Search by date, tags, or keywords

---

**Last Updated:** October 22, 2025
