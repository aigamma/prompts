# General Prompts
These prompts transcend categories and can be used on any platform tactically.

## Autonomous Buildout
 1. Read CLAUDE.md, LESSONS_LEARNED.md, docs/ROADMAP.md.
  2. Take the top unblocked item from docs/ROADMAP.md (skip anything under "Needs Eric").
  3. Implement it end to end; fan out parallel subagents on disjoint files for independent sub-tasks.
  4. Verify before done: npm test (>=77 green), the three gate scripts (exit 0), npx vite build (clean). Never commit red.
  5. Commit verbosely but reserve pushes for major milestones or an exhaustion of the task list.   
  6. Check the item off in docs/ROADMAP.md, add anything discovered, append a LESSONS_LEARNED.md entry if durable.
  7. Keep going to the next item. Do not stop between items; stop only on a hard blocker or an empty unblocked list.

## Warm-up Prompt
Take some time to explore the site and learn its structures and agentic scaffolding between its MD files and Python scripts and how everything interrelates.

## Curious Sweep
/plan Look for areas to improve. Fix obvious things, but otherwise make a report of recommendations. 

## Deep Sweep
Run a Deep Health Check. Fix obvious errors, investigate the warnings, but most importantly find a list of ways to improve the site and make it more useful and have enduring value for repeat visitors. Make a list of recommendations for what seems risky, otherwise start building it and see how it looks.

## Sweep for Unpushed Commits
Confirm that everything has been pushed. 

## Full Strength not Weaker Subagents
This chat is selected for /effort max on Opus 4.8 and that is the writing strength that I am looking for here. There 
is no rush: Be slow and meticulous over rushing through the tasks.


## Commit Liberally
As another reason to commit liberally. I have had overnight hardware fault crashes about two-thirds of the time, and likewise about every other day it seems that I get a hardware crash. Some kind of instant fault that closes everything.
I'm about to re-image Windows because I keep being told that nobody can run a dev server, so I think I have an over-scripted image. I'm going to download a fresh one for Microsoft and be out of it for a couple of days, so I'd like a good start here.
The reason I'm going out anyway is just to be thinking about how to shape things next. Even though it looks like I'm making you do all the work, I am actually putting 100% of my energy into thinking about where it should go.

## Ruthless Boss
Do not pause if you know of valid tasks in the queue ahead.

## The Conditional Order
... Therefore, proceed with XYZ unless you disagree.
