
#       << [[Diary/DailyNote/<% tp.date.now("YYYY", 0, tp.file.title, "YYYY-MM-DD ddd") %>/Q1 | Q1]] —— [[Diary/DailyNote/<% tp.date.now("YYYY", 0, tp.file.title, "YYYY-MM-DD ddd") %>/Q2 | Q2]] —— [[Diary/DailyNote/<% tp.date.now("YYYY", 0, tp.file.title, "YYYY-MM-DD ddd") %>/Q3 | Q3]]  —— [[Diary/DailyNote/<% tp.date.now("YYYY", 0, tp.file.title, "YYYY-MM-DD ddd") %>/Q4 |   Q4]] >>

### < [[Diary/DailyNote/<% tp.date.now("YYYY", -1, tp.file.title, "YYYY-MM-DD ddd") %>/<% tp.date.now("MM_MMMM", -1, tp.file.title, "YYYY-MM-DD ddd" ) %>/<%tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD ddd" ) %> <% tp.date.now("ddd", -1, tp.file.title, "YYYY-MM-DD ddd" ) %>|<% tp.date.now("ddd DD-MM-YYYY", -1, tp.file.title, "YYYY-MM-DD.  .  dd" ) %>]] |<% tp.date.now("ddd DD-MM-YYYY", 0, tp.file.title, "YYYY-MM-DD ddd") %> | [[Diary/DailyNote/<% tp.date.now("YYYY", 1, tp.file.title, "YYYY-MM-DD ddd") %>/<% tp.date.now("MM_MMMM", 1, tp.file.title, "YYYY-MM-DD ddd" ) %>/<%tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD ddd" ) %> <% tp.date.now("ddd", 1, tp.file.title, "YYYY-MM-DD ddd" ) %> |<% tp.date.now("ddd DD-MM-YYYY", 1, tp.file.title, "YYYY-MM-DD ddd" ) %>]] >

---
## 📝 Planning:


---
## ✅ Tasks:

**Scheduled today:**
```tasks  
scheduled on <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD ddd") %>
sort by urgency
short mode
hide task count
```
**Due today:**
```tasks  
due on <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD ddd") %>
sort by urgency
short mode
hide task count
```
**Due this week:**
```tasks  
due before <% tp.date.weekday("YYYY-MM-DD", 7, tp.file.title, "YYYY-MM-DD ddd") %>
due after <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD ddd") %>
not done
sort by urgency
short mode
hide task count
```
---
## 💼 Happenings:
- 

- [[Diary/DailyNote/<% tp.date.now("YYYY", 0, tp.file.title, "YYYY-MM-DD ddd") %>/<% tp.date.now("MM_MMMM", 0, tp.file.title, "YYYY-MM-DD ddd" ) %>/<%tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD ddd" ) %>-Meeting-1| Meeting-1]]

---
## 💭 Reflection:


---
created: <% tp.file.creation_date() %>
Location: 
tags: #Daily

<% tp.web.daily_quote() %> 