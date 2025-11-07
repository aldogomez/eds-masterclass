# Hands-On Exercise: Design a Conference Schedule Block

## The Challenge

Design a content model for a block that displays a conference schedule with:

**Required Information:**
- Session title
- Speaker name
- speaker photo
- Session type (breakout, lab, keynote, etc.)
- Time (start/end or just start time)
- Room/track name
- description 

**Display Goals:**
- Show multiple sessions in an organized way
- Make it easy to scan and find sessions
- Work well on mobile and desktop
- let users sort/filter/search

## Your Task (20 minutes)

### Step 1: Design Your Content Model

Think through these architectural questions:

1. **Content Architecture**: How should the content be organized?
   - **Single Block**: All session data in one block table on the schedule page?
   - **Fragments**: Each session as a separate fragment, referenced from the schedule page? Or maybe author info as fragments?
   - **Sheets**: Session data in a spreadsheet (metadata), referenced by the schedule page?

2. **Author Workflow**:
   - How does an author add a new session?
   - How easy is it to change session details (time, room, speaker photo)?
   - Can authors easily see what's already scheduled?
   - Can session information be reused across multiple pages?

**Choose an approach** and sketch it out.

### Step 2: Create Example Content (8-10 minutes)

Create a simple schedule in the tool of your choice:
- DA
- Word/Excel
- Markdown

### Step 3 (Optional): Build the block

Go do the thing!
