# Learning Outcomes Grade Tracker

A free grade tracker for courses graded by learning outcomes (RLO -> CLO -> course grade).
Everything runs in the browser. Grades are stored on the student's own device and are never uploaded.

## Put it on GitHub Pages

1. Create a new **public** repository (for example `grade-tracker`).
2. Upload these files to the top level of the repository (not inside a folder):
   `index.html`, `.nojekyll`, `manifest.webmanifest`, `sw.js`, `icon.svg`
3. Go to **Settings -> Pages**. Under "Build and deployment" choose **Deploy from a branch**,
   branch **main**, folder **/ (root)**, then Save.
4. After a minute the site is at `https://YOUR-USERNAME.github.io/grade-tracker/`.

### If you see the "Build with Jekyll" error

GitHub Pages runs Jekyll by default and Jekyll fails on some files. This site does not need Jekyll.
The empty file named **`.nojekyll`** in this folder tells GitHub to skip it.
To add it by hand: **Add file -> Create new file**, type `.nojekyll` as the name, and commit.
If the error continues, open the failed run under the **Actions** tab and send the red error line.

## Do not upload

- `owner-demo.html` (it contains the GE 122 example and is meant to stay on your computer).
- The course syllabus PDFs. Course materials belong to the instructors and should not be posted publicly.

## Updating

Replace `index.html` in the repository. Students get the new version the next time they open the site online
(the offline copy refreshes automatically).

## Notes for students (you can paste this on the site)

- Your data lives in your browser only. Use **Settings -> Save backup file** now and then.
- Clearing browser data, or opening the site on another device, starts you with an empty tracker until you restore a backup.
- On a phone, use "Add to Home Screen" to open it like an app, even without internet.
