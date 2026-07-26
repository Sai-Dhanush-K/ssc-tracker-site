# SSC Helper Site

A single-file SSC prep dashboard for tracking syllabus topics, confidence, notes, and mock tests.

## Live site

Open the deployed version here:

https://sai-dhanush-k.github.io/ssc-helper-site/

If you are not comfortable with code or setup, use that link directly in your browser. It opens the app ready to use, with no install needed.

## What it does

- Syllabus tree with expandable subjects and subtopics
- Confidence tracking with color states
- Notes popup for each topic
- Add and delete subtopics
- Mock test logging with subject-wise marks
- Analytics charts for previous mock tests
- JSON export/import for backup and restore
- Data stored locally in the browser using `localStorage`

## How to use

1. Open `index.html` in a browser.
2. Use the **Syllabus Tree** tab to manage topics and notes.
3. Use the **Mock Tests & Analytics** tab to log scores and review charts.
4. Use the top-right **Data** menu to export or import your saved data.

## Files

- `index.html` - the full app UI and logic in one file
- `README.md` - project overview and usage notes

## Notes

- Your syllabus and mock data stay in the browser unless you export a JSON backup.
- Importing a JSON backup replaces the saved browser data with the file contents.
- The app is built to run without any build step or external install.
