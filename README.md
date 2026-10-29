# NotCooked

A student-first planner that turns scattered coursework into a clear next step.

![NotCooked on iPhone: the Today, Plan and Schoolwork screens](assets/hero.png)

**Status:** currently in private beta. NotCooked's source code is private; this repository contains documentation and screenshots only. All screenshots use fictional demo data.

## The problem

- Assignments are scattered across systems: a learning platform, Google Classroom, a teacher's announcement, a photo of a worksheet.
- Long overdue lists create noise. When everything is flagged, nothing stands out.
- Students need help choosing what to do next, not another place to store everything.

## What NotCooked does

NotCooked answers one question: what do I need to do right now? Three screens, each with one job:

- **Today** is for immediate work. It recommends a next task, shows why, and lists what is due today and what you planned for today.
- **Plan** is for dated work. A week and month view with due counts, and a place to set when you will do something.
- **Schoolwork** is the full inventory, including undated work, organized by due date, by course, or by what you added recently.

## Features

- **Imports from Canvas and Google Classroom.** Canvas through your school calendar link, Google Classroom through a read-only connection. Nothing is saved until you review it.
- **Capture from text, files and photos.** Paste a syllabus or announcement, upload a file, or photograph a worksheet, then check the results before they are added.
- **Next-task recommendations.** Today picks a next task and shows the reasons behind the choice.
- **Focus sessions.** Choose a task and a session length, then work against a timer.
- **Due dates and courses.** Color-coded courses, due times, estimated time and notes for every assignment.
- **Completion with Undo.** Mark work done, and take it back if you tapped too soon.
- **Reminders and planning tools.** Reminders before work is due, a plan date for each assignment, and an optional AI planning suggestion that you opt into and can turn off, with a basic plan as the alternative.

## Screenshots

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/screens/today.png" width="230" alt="The Today screen. A Next Up card recommends the overdue Chem lab correction sheet with a Start focus button, followed by tasks due today and planned for today."><br><sub>Today</sub></td>
    <td align="center" width="33%"><img src="assets/screens/plan.png" width="230" alt="The Plan screen in week view for October 25 to 31, with the number of assignments due on each day and the list of work for the selected day."><br><sub>Plan</sub></td>
    <td align="center" width="33%"><img src="assets/screens/schoolwork.png" width="230" alt="The Schoolwork screen listing all open assignments grouped by due date, starting with Overdue and Today."><br><sub>Schoolwork</sub></td>
  </tr>
  <tr>
    <td align="center" width="33%"><img src="assets/screens/schoolwork-by-course.png" width="230" alt="The Schoolwork screen grouped by course, with Algebra II, AP Chem and AP Lang each showing their assignments."><br><sub>Schoolwork by course</sub></td>
    <td align="center" width="33%"><img src="assets/screens/import-options.png" width="230" alt="The Import assignments sheet offering Google Classroom, a school calendar, scanning an assignment, and uploading a file."><br><sub>Import options</sub></td>
    <td align="center" width="33%"><img src="assets/screens/import-review.png" width="230" alt="The import review screen after reading a school calendar, showing five assignments ready, two past due, one already imported and one event skipped, with an Import 5 assignments button."><br><sub>Import review</sub></td>
  </tr>
  <tr>
    <td align="center" width="33%"><img src="assets/screens/focus-setup.png" width="230" alt="The Focus Mode setup sheet with a focus target and session lengths of 15, 25, 45 and 60 minutes, recommending a 25 minute session on AP Lang reading notes."><br><sub>Focus setup</sub></td>
    <td align="center" width="33%"><img src="assets/screens/focus-timer.png" width="230" alt="A running focus session showing a circular timer at 24 minutes 56 seconds for AP Lang reading notes, with Pause and Finish early buttons."><br><sub>Focus timer</sub></td>
    <td align="center" width="33%"><img src="assets/screens/assignment-details.png" width="230" alt="The assignment details screen for AP Lang reading notes, showing its due time, plan, reminder, notes, and Start focus and Mark done buttons."><br><sub>Assignment details</sub></td>
  </tr>
</table>

## Beta testing

NotCooked has been beta-tested with 25+ students and has been iterated using their feedback.

## Technology

NotCooked is an Expo (React Native) app that uses Firebase for authentication and data. Sensitive credentials, such as the connection to Google Classroom, are kept in the device's secure storage. The core logic is covered by automated tests.

## More

- [PRODUCT.md](PRODUCT.md): what NotCooked is for and how it is designed.
- [PRIVACY.md](PRIVACY.md): how NotCooked handles student data.

## Author

Created by Julian Gonzalez, founder and developer. [GitHub profile](https://github.com/juliangonzalez-tech)

## Copyright

© 2026 Julian Gonzalez. All rights reserved. The NotCooked name, brand and the screenshots in this repository may not be reused without permission. NotCooked's source code is private and is not licensed for use.
