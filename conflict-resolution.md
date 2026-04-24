# Merge Conflict Resolution Process

## Problem
A conflict occurred while merging feature2 into main because both branches modified file.txt differently.

## Steps Taken
1. Identified conflict using git merge output.
2. Opened conflicting file using nano.
3. Reviewed conflict markers:
   - <<<<<<< HEAD
   - =======
   - >>>>>>> feature branch
4. Manually edited file to keep required changes.
5. Removed conflict markers.
6. Added file using git add.
7. Committed resolved changes.
8. Pushed updated code to GitHub.

## Result
Merge conflict successfully resolved and repository is now consistent.
