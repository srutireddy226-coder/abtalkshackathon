MASTER BUILD PROMPT — ABTalks 60-Day Student Command Center

Build a polished, modern, responsive web application called “ABTalks 60-Day Student Command Center” for a 60-day coding challenge.

1. PRODUCT GOAL

Redesign the student experience of the ABTalks 60-day coding challenge.

The application should make students feel that they are progressing through a personal coding journey rather than simply completing daily tasks.

The core experience should include:

- Challenge progress
- Daily challenge/task
- Streak tracking
- Achievements/badges
- Proof-of-work submission
- Challenge calendar
- Personalized recovery mode when a student misses a day
- Motivational progress visualization

The project must feel like a real startup-quality product, not a basic college dashboard.

2. IMPORTANT HACKATHON CONSTRAINT

This is being built during a 48-hour hackathon.

Prioritize:

1. Working features
2. Excellent UI/UX
3. Fast performance
4. Responsive design
5. Easy deployment
6. A smooth live demo

Do NOT waste time building unnecessary authentication, complex backend infrastructure, payment systems, or production-level database architecture.

Use realistic mock data / local JSON / localStorage where appropriate.

Every important interaction should actually work in the browser.

3. TECH STACK

Use:

- React
- Vite
- JavaScript or TypeScript
- Tailwind CSS
- Lucide React icons
- Recharts for charts where useful
- LocalStorage for persistence
- Mock JSON data for challenge information

Keep the architecture clean and easy to modify.

4. VISUAL DESIGN

Create a premium modern developer-product aesthetic.

Design principles:

- Clean
- Minimal
- Professional
- Youthful
- Slightly futuristic
- Excellent typography
- Strong visual hierarchy
- Generous spacing
- Beautiful cards
- Smooth micro-interactions
- Subtle gradients
- Soft shadows
- Rounded corners

Use a dark/light visual system or a polished dark-first interface, but maintain excellent readability.

Do NOT make it look like a generic Bootstrap dashboard.

Use subtle animations for:

- Progress bars
- Streak counters
- Achievement unlocks
- Page transitions
- Hover states
- Challenge completion

Make the UI responsive for:

- Desktop
- Tablet
- Mobile

5. LANDING PAGE

Create an impressive landing page.

Hero:

“60 Days.
One Challenge.
One Transformation.”

Supporting text:

“Turn consistent coding into a habit, build real projects, and prove your progress every day.”

Include:

- Start Your Journey button
- View Challenge button
- 60-day progress visualization
- Participant statistics
- Feature cards

Show statistics such as:

- 60 Days
- Daily Coding Challenges
- Projects Built
- Student Progress

Use realistic mock values.

6. STUDENT DASHBOARD

Create the main dashboard.

Header:

- ABTalks branding
- Student name
- Profile/avatar
- Notifications
- Theme toggle

Main dashboard should show:

Current Progress

“Day 18 of 60”

Large animated progress indicator.

Show:

- 30% completed
- Current streak
- Challenges completed
- Projects completed

Today's Mission

Example:

“Day 18 — Build a Responsive Portfolio”

Show:

- Difficulty
- Estimated time
- Skills practiced
- Short description

Buttons:
“Start Challenge”
“View Details”

Current Streak

Example:

🔥 17 Day Streak

Display a 7-day activity visualization.

Weekly Progress

Create a beautiful chart showing challenge completion during the current week.

7. UNIQUE FEATURE — RECOVERY MODE

This should be one of the main differentiators.

If the student misses a challenge day, DO NOT simply show “Missed”.

Instead display:

“Looks like you missed Day 12.
Let's get you back on track. 💪”

Create a Recovery Mode card.

Example:

RECOVERY PLAN

Day 12
Quick Recovery Task
30 minutes

Day 13
Today's Challenge
90 minutes

Then show:

“Complete today's recovery task to continue your journey.”

Button:

“Start Recovery”

The recovery system should dynamically react to the mock student's progress.

If there are no missed days, show:

“You're on track! Keep the streak alive 🔥”

8. CHALLENGE PAGE

Create a dedicated page for each challenge.

Show:

DAY 18 / 60

Challenge title

Difficulty:
Easy / Medium / Hard

Estimated time

Skills:

- HTML
- CSS
- JavaScript
- React

Description

Learning objectives

Challenge requirements

Resources

Acceptance checklist:

□ Requirement 1
□ Requirement 2
□ Requirement 3

Buttons:

“Start Challenge”

“Mark Complete”

“Submit Proof”

9. PROOF OF WORK

Create a proof submission interface.

Allow the student to enter:

- GitHub repository URL
- LinkedIn post URL
- Optional project/demo URL

Also provide a visual upload area for a screenshot/mock proof.

After submission, show:

“Proof submitted successfully ✓”

Save submission state using localStorage.

10. CHALLENGE CALENDAR

Create a 60-day calendar.

Each day should visually indicate:

🟢 Completed
🔵 Today
🟡 Recovery
⚪ Upcoming
🔴 Missed

Clicking a day should open its challenge details.

Make this visually impressive.

11. ACHIEVEMENTS

Create an achievement system.

Example badges:

🔥 7-Day Streak
🏆 10 Challenges Completed
💻 First Project
🚀 30-Day Warrior
🎯 Halfway There
👑 60-Day Finisher

Show:

- Unlocked badges
- Locked badges
- Progress toward next achievement

When a badge is unlocked, show a subtle celebration animation.

12. PROGRESS PAGE

Create a detailed progress analytics page.

Display:

- Overall completion %
- Current streak
- Longest streak
- Challenges completed
- Challenges missed
- Projects completed

Include a clean chart.

Also show:

“Your Journey”

Day 1 → Day 18 → Day 30 → Day 45 → Day 60

13. MOTIVATIONAL EXPERIENCE

Add contextual messages based on progress.

Examples:

Early stage:
“Every expert started with Day 1.”

Good streak:
“You've built a habit. Keep going!”

Milestone:
“You're halfway there! 🚀”

Missed day:
“One missed day doesn't define your journey.”

Near completion:
“Only 5 days left. Finish strong!”

Do not make these messages repetitive.

14. NAVIGATION

Desktop sidebar:

🏠 Dashboard
📅 Challenges
📊 My Progress
🏆 Achievements
🔥 Streak
⚙️ Settings

Mobile:
Use a bottom navigation or responsive menu.

15. DATA

Create realistic mock challenge data for all 60 days.

Each challenge should contain:

{
id,
day,
title,
description,
difficulty,
estimatedTime,
skills,
requirements,
status
}

The dashboard should use this data dynamically.

Do not hard-code the same information in multiple components.

16. FUNCTIONALITY

Make these interactions actually work:

- Navigation between pages
- Challenge selection
- Start challenge
- Complete challenge
- Submit proof
- Streak calculation
- Achievement unlocking
- Recovery mode
- Calendar status
- Progress calculations
- LocalStorage persistence
- Theme toggle
- Responsive navigation

Use mock data where backend functionality is unnecessary.

17. DEMO EXPERIENCE

The application should be optimized for a hackathon judge.

When the judge opens the application, they should immediately understand:

1. What the product is
2. What the student is currently doing
3. How much progress they have made
4. What makes this redesign different

The first 30 seconds of the demo should be visually impressive.

Create a realistic demo student state:

- Day 18
- 17-day streak
- Several completed challenges
- One missed day
- Some unlocked achievements

This allows the Recovery Mode feature to be demonstrated immediately.

18. CODE QUALITY

Use reusable components.

Suggested structure:

src/
components/
pages/
data/
hooks/
utils/
assets/

Create reusable components such as:

- ProgressCard
- ChallengeCard
- StreakCard
- AchievementCard
- RecoveryCard
- ChallengeCalendar
- ProofSubmission
- Navbar
- Sidebar
- ProgressChart

Avoid one huge component.

Keep code readable and maintainable.

19. README

Create a professional README explaining:

- Project name
- Problem
- Solution
- Key features
- Unique feature
- Tech stack
- How to run locally
- How the application works
- Screenshots section
- Future improvements

20. HACKATHON AUTHENTICITY

Do not fabricate external integrations or claim that features exist if they do not.

Keep the implementation consistent with the actual application.

The project should be easy to explain during judging.

FINAL REQUIREMENT

Before finishing:

1. Make sure the application runs without errors.
2. Test every navigation link.
3. Test the main interactions.
4. Test mobile responsiveness.
5. Remove placeholder lorem ipsum.
6. Make the UI polished.
7. Make sure there are no broken buttons.
8. Make sure mock data is realistic.
9. Make sure the project can be deployed easily.
10. Give me the final project structure and instructions to run it.

Do not build unnecessary features that could make the project unstable.

Focus on making this one experience exceptionally polished.
