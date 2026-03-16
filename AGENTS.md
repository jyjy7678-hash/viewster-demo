# AGENTS.md

## Project
This repository is a mobile-first Viewster demo page.
The main file is `index.html`.
The `assets/` folder contains images, icons, and visual assets used by the demo.

## Goal
Build and maintain a clean mobile web app style demo for Viewster that works well on phones.
Keep the demo easy to understand and easy to edit for a non-developer.

## Priority
When making changes, prioritize in this order:
1. Do not break the existing demo
2. Keep the UI mobile-friendly
3. Keep code simple and readable
4. Explain changes clearly
5. Reuse existing assets when possible

## File rules
- Prefer editing `index.html` directly unless splitting code is clearly necessary
- Do not create unnecessary files
- Use assets from `assets/` when available
- Do not rename files unless absolutely required
- Preserve existing working structure as much as possible

## Coding style
- Write beginner-friendly HTML, CSS, and JavaScript
- Add comments for important sections
- Keep CSS organized by section
- Keep JavaScript simple and avoid overengineering
- Avoid large frameworks unless explicitly requested
- Prefer plain HTML/CSS/JS for this demo

## UI guidance
- Mobile-first layout
- App-like appearance
- Clean cards, rounded corners, subtle shadows
- Blue-based accent color unless another color is requested
- Clear CTA buttons
- Readable text size on phones
- Avoid cluttered layouts

## Viewster demo structure
Try to preserve or improve these areas when relevant:
- top header
- video area
- watch reward/progress area
- random box action area
- optional chat/demo side area
- bottom navigation or mobile action area

## QA / bug-fix rules
When fixing bugs:
- Find the root cause first
- Make the smallest safe change possible
- Do not redesign unrelated parts
- After fixing, explain:
  - what caused the issue
  - what was changed
  - what the user should test next

## Current QA focus
High-priority issues may include:
- video sound not playing
- PIP close button not working
- PIP movement not working
Treat these as important product issues.

## PIP handling rule
If true browser/native PIP cannot be controlled due to platform limitations,
explain that clearly and propose the closest practical fallback,
such as a custom movable mini-player inside the page.

## Before making major UI changes
Before large edits:
- inspect current structure first
- preserve working behavior where possible
- avoid replacing everything unless necessary

## Output expectations
When completing a task:
1. summarize what you changed
2. list which file(s) changed
3. explain how to test it
4. mention any limitations clearly
5. keep the explanation understandable for a non-developer

## Git / change discipline
- Keep diffs scoped to the requested task
- Avoid unrelated cleanup unless it helps the task directly
- Prefer safe incremental changes over large rewrites

## Important
This project owner is a non-developer.
Always optimize for clarity, safety, and easy manual review.
