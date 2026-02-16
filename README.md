# EA Operating System for Claude Cowork

**A complete system for Executive Assistants to work with AI and support their executives more effectively.**

---

## What This Is

This is an EA-focused "second brain" and operating system designed specifically for Executive Assistants using Claude Cowork. It helps you:

* **Start each day with a structured morning routine** - Prep your executive's day proactively
* **Prep for and debrief meetings** - Create comprehensive briefs with stakeholder context
* **Track projects, decisions, and delegations** - Nothing falls through the cracks
* **Run weekly reviews and planning sessions** - Stay ahead of priorities
* **Draft communications in your executive's voice** - Emails, updates, messages
* **Build custom skills** - Automate YOUR unique EA workflows
* **Maintain executive context** - Goals, preferences, stakeholders, calendar rules

---

## Requirements

**Claude Cowork requires a paid Claude account** . 

---

## Quick Start

### Step 1: Select Your Workspace Folder

In Claude Cowork, select a folder for your workspace (or create a new one called `ea-cowork`).

### Step 2: Copy this entire prompt and send it to Claude:

```
I want to set up the EA Operating System from this GitHub repo: https://github.com/lamya-Work/EA-Support-OS
Please:
1. Clone the repo using git, then copy all the template files directly into the ROOT of my currently selected workspace folder (not into a subfolder — build the structure at the top level of my folder).

2. Create any missing folders:
   - work-with-me/ (with briefings/, drafts/, research/, projects/ subfolders)
   - second-brain/
   - executive-operations/
   - skills/
   - inbox/
   - outbox/ (with SOD/, weekly/, drafts/ subfolders)
   - logs/

3. The files to copy are:
   - CLAUDE.md (root)
   - ea-profile.md (root)
   - second-brain/ (entire folder)
   - executive-operations/ (entire folder)
   - skills/ (entire folder)

4. After setting up the files, ask me questions to personalize the system:

   **About Me (EA):**
   - My name, role, company, contact info
   - My strengths and what makes me uniquely good as an EA
   - My work style, communication preferences, peak productivity hours
   - What I own entirely vs. where I need executive input
   - What I'm currently learning and working to improve
   - Red flags I watch for with my executive

   **About My Executive:**
   - Their name, role, company, contact
   - Their 2026 goals and current Q1 objectives
   - Their zone of genius (what work they should focus on)
   - Their personality/work style (assessments if available)
   - How they work best, what drains them
   - Their communication preferences and decision-making style
   - What they need delegated to EA/Claude

   **About the Company:**
   - Company mission, vision, values
   - 2026 company objectives and key initiatives
   - What the company does, who they serve
   - Current stage, team size, recent context

   **About the Team:**
   - My role as EA and how I work with my executive
   - Their direct reports (names, roles, responsibilities, 1:1 cadence)
   - Board members, advisors, key collaborators
   - Key meeting rhythms for the executive

   **About Calendar & Communication:**
   - Protected time blocks and no-meeting days
   - Meeting preferences (length, buffer time, best times)
   - Meeting acceptance criteria and calendar rules
   - Email voice, tone, and structure
   - Communication style for different audiences

   **About Stakeholders:**
   - Key stakeholders and VIP relationships
   - Communication preferences for important people
   - Relationship context and priorities
   - Important dates and personal notes

   **About Current Priorities:**
   - Active projects and initiatives
   - Upcoming deadlines and key dates
   - What's currently taking focus
   - Delegations and waiting-for items

5. After interviewing me, populate ALL template files with my specific information. Don't leave generic placeholders - use the actual information I provide to customize each file.

6. When done:
   - Show me the complete folder structure
   - Confirm all files are populated with my information
   - Explain how to use the system
   - Remind me to attach CLAUDE.md to start any session
```

### Step 3: Answer Claude's personalization questions

Claude will interview you to fill in your EA profile, executive context, company information, and operational preferences.

### Step 4: You're set!

Attach `CLAUDE.md` to start any new session and begin using your EA workflows.

---

## How to Use It

**This system is designed for YOU to build custom skills for YOUR unique workflows.**

The template includes one core skill to get you started:

| Say This | What Happens |
|----------|--------------|
| "build a skill" | Create a new custom workflow for any repeating task |

**After you populate your system context, build skills for your workflows:**

**Example skills you might build:**
- "let's start our day" — Morning routine to prep your executive's day
- "prep me for [meeting]" — Meeting preparation with stakeholder intel
- "debrief" — Post-meeting capture and action items
- "draft a message to [person]" — Communication drafting in executive's voice
- "weekly review" — Friday planning and next week prep
- "wrap up" — End of day wrap-up
- "prep my 1:1 with [name]" — 1:1 meeting preparation

**Each EA's role is unique. Build the skills that match YOUR executive's needs and YOUR workflows.**

---

## File Structure

```
ea-cowork/
├── CLAUDE.md                           ← Attach this to start sessions
├── ea-profile.md                       ← Your work style & strengths
│
├── work-with-me/                       ← EVERYTHING Claude creates goes here
│   ├── drafts/                         ← Message drafts, communications
│   ├── briefings/                      ← SOD briefings, meeting prep docs
│   ├── research/                       ← Research outputs, analysis
│   └── projects/                       ← Project work, deliverables
│
├── second-brain/                       ← Executive context files
│   ├── executive-profile.md            ← Executive's goals, work style, zone of genius
│   ├── company.md                      ← Company mission, strategy, objectives
│   ├── support-ecosystem.md            ← Key stakeholders & team structure
│   ├── executive-priorities.md         ← Active projects & initiatives
│   └── decisions.md                    ← Key decisions log
│
├── executive-operations/               ← How the executive operates
│   ├── rhythm-map.md                   ← Weekly schedule & meeting rhythms
│   ├── email-style.md                  ← Communication voice & writing style
│   ├── call-brief-templates.md         ← Meeting brief formats
│   ├── meeting-standards.md            ← Calendar rules & protocols
│   └── stakeholder-intel.md            ← VIP context & relationship notes
│
├── skills/                             ← Your custom workflow scripts
│   └── build-skill.md                  ← Tool to create new skills
│
├── inbox/                              ← Drop files for processing
├── outbox/
│   ├── SOD/                            ← Daily briefings
│   ├── weekly/                         ← Weekly reviews
│   └── drafts/                         ← Message drafts
└── logs/                               ← Session logs
```

---

## Building Your Custom Skills

**This is the core of the system.** The template doesn't include pre-built skills because every EA's role is different.

**Your first step after setup:** Build skills for YOUR repeating workflows.

Say **"build a skill"** and Claude will walk you through:
1. Defining what the skill does
2. Setting trigger phrases
3. Mapping out the step-by-step workflow
4. Creating the skill file
5. Updating CLAUDE.md to recognize the new triggers

**Example skills EAs commonly build:**

**Daily workflows:**
- "let's start our day" — Morning routine to prep executive's day
- "wrap up" — End of day review and tomorrow prep
- "weekly review" — Friday planning and week-ahead prep

**Meeting support:**
- "prep me for [meeting]" — Create meeting brief with stakeholder context
- "debrief" — Post-meeting notes and action items
- "prep my 1:1 with [name]" — Prep for recurring 1:1s

**Communication:**
- "draft a message to [person]" — Draft emails in executive's voice
- "draft [type] update" — Weekly team updates, board updates, etc.

**Project management:**
- "process inbox" — Triage files dropped in inbox folder
- "check on projects" — Review active projects and flag blockers
- "delegation review" — Check on delegated tasks and follow-ups

**Your unique workflows:**
- Build skills for whatever YOU repeat regularly in YOUR role

---

## Customization

* **Build new skills**: Say "build a skill" to create workflows for your repeating tasks
* **Modify existing skills**: Edit any skill file in `skills/` to change the steps
* **Update your context**: Keep `second-brain/` and `executive-operations/` files current for better Claude responses
* **Add trigger phrases**: Edit `CLAUDE.md` to add new ways to activate skills

---

## Sharing with Your Executive (Optional)

Claude Cowork works from a local folder on your computer. If you want to share your workspace with your executive or team member, you can sync your local folder to a cloud platform.

**How to set it up:**
1. Create your `ea-cowork` folder locally (this is where Cowork will read/write files)
2. Sync that folder to a cloud platform like Google Drive, Dropbox, or OneDrive
3. Share the synced folder with your executive

**What this enables:**
* Your executive can see your daily briefings in `outbox/SOD/`
* Your executive can drop files into `inbox/` for you to process
* You can share delegation queues and project updates in real-time
* Your second brain stays in sync across your workflow

**Example with Google Drive:**
1. Install Google Drive for Desktop
2. Move your `ea-cowork` folder into your Google Drive folder (or create it there)
3. In Google Drive, right-click the folder → Share → Add your executive's email
4. Select the synced folder when starting Claude Cowork

---

## What Makes This EA-Focused?

Unlike executive-focused personal OS systems, this system is built from the **EA's perspective**:

* **EA Profile (1st person)** - About YOU as the EA
* **Executive Profile (3rd person)** - About WHO YOU SUPPORT
* **Team = Their Team** - The executive's direct reports and stakeholders
* **EA Mindset Throughout** - Protecting executive time, maintaining relationships, anticipating needs

This is an EA tool to make you more effective at supporting your executive.

---

## Credits

Built by the team at **[Atlas Assistants](https://www.atlasassistants.com)** — we match executives with elite Executive Assistants trained on AI tools and systems to help executives operate more in their zone of genius.

**Created by:** Lamya (EA to CEO) for the Atlas EA community

For more tips on leveraging your EA skills with AI: **[Subscribe to our newsletter](https://atlas-executive.beehiiv.com/)**
