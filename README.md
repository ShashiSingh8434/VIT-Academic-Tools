# Academic Tools

Two small, single-file web tools I built to plan and track my B.Tech at VIT Bhopal. Both are plain HTML, CSS and JavaScript. There is no build step and nothing to install.

## Live pages

| Tool | Link |
|---|---|
| Degree Ledger | https://shashisingh8434.github.io/VIT-Academic-Tools/Curriculum_Progress.html |
| Slot Picker | https://shashisingh8434.github.io/VIT-Academic-Tools/Slot_picker.html |

## Degree Ledger

**File:** `Curriculum_Progress.html`

A curriculum tracker that shows how far along the degree is.

- Credits completed against the 169 required, with a progress bar
- Courses registered this term, with faculty names
- Requirement-wise breakdown (Programme Core, Electives, University Core, and so on). Tap a row to see completed, registered and remaining courses
- Courses still awaiting grades are marked "Grade awaited"
- Grade distribution summary

All data lives in one `categories` array inside the file. To update it, change a course's `status` to `"completed"`, `"current"` or `"remaining"`, add a `grade`, or mark `pending:true` while a grade is awaited. The totals and charts recalculate automatically.

## Slot Picker

**File:** `Slot_picker.html`

A weekly timetable grid for planning slots. Tap a slot to highlight it in green and tap again to undo it. A counter shows how many slots are selected, and **Clear all** resets the grid.

## Run locally

Download the repo and open either HTML file in a browser.

## Hosting

Hosted with GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

## Disclaimer

The Degree Ledger is unofficial and built from VTOP data by hand. Verify anything important against VTOP.
