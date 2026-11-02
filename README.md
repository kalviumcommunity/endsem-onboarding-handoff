# End Semester Examination, Set 3, Question 1
# Handle an Urgent Correction Without Losing Unfinished Work

**Total: 30 marks | Submit one PDF**

## Problem

You are updating an onboarding guide when an urgent correction arrives for the help desk contact. Pause unfinished work safely, complete the urgent correction, then resume the onboarding update. Keep the two changes in separate, meaningful commits and deliver them through one pull request.

Starter: https://github.com/kalviumcommunity/endsem-onboarding-handoff

Use your assigned repository. Editable files: onboarding.txt and contact.txt. Do not edit README.md. No application code is needed.

## Requirements

Add a reminder in onboarding.txt that developers should inspect Git status before committing. Correct the help desk email in contact.txt to helpdesk@campus.example. Preserve every other original line. The urgent contact correction must be committed first, followed by the resumed onboarding reminder in a separate commit. Both commits must be on one delivery branch from main. Use one stash cycle to preserve unfinished tracked work, not an early placeholder commit or a discarded/retyped replacement.

## Task 1: Start the planned update

Show clean main, files and history. Create a delivery branch from main. Add the Git-status reminder to onboarding.txt without staging or committing it. Show unstaged diff and status. Explain what is unfinished and why it is not yet a commit.

Evidence: initial state/files/history, branch creation, reminder diff/status and short explanation.

## Task 2: Pause safely

Shelve the unfinished tracked edit using Git stash. Show the saved stash entry, clean working tree and onboarding.txt without the unfinished reminder. Explain why the work is preserved even though it is absent from the working file.

Evidence: actual stash operation, stash list, clean status, working file and explanation.

## Task 3: Finish urgent and resumed work

Correct only the contact email, inspect the diff, stage that file and create a meaningful urgent-fix commit. Restore the saved onboarding work on the same branch. Capture the restored unstaged reminder and contact file before committing resumed work. Inspect and commit only the onboarding update as a second meaningful commit. Verify both final files, the two separate commit patches in required order, empty stash list and clean state. Explain how the sequence preserves unfinished work and keeps each commit focused.

Evidence: contact diff/staging/first commit, actual stash restoration, restored diff/contact content, second commit, both commit patches/history, final files, stash list/status and explanation. No destructive reset, force push or extra branch switching is needed.

## Task 4: Review and deliver

Push delivery branch and open PR into main in the same repository. Capture open state/title/direction and description explaining urgent correction, resumed reminder, separate commits and checks performed. Leave an ordinary self-review comment confirming both requirements and unchanged unrelated lines. Merge PR, pull main locally and capture final files and clean status, plus actual comment and merged state. Self-review is not independent approval.

Evidence: push, open PR/description/direction, actual self-review, merged state, successful pull and final files/status.

## Submission

Submit one PDF containing solutions for all four tasks. Organise it into Task 1 to Task 4. Include screenshots requested in each task, with a one- or two-sentence label explaining the result and answering any requested short question. Multiple readable screenshots per task are allowed. Do not include credentials.

