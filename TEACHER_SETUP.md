# StackBlitz Teacher Starter — Bootstrap 5.3.8

## What this is
A static HTML/CSS/JavaScript website using the **official Bootstrap 5.3.8** CSS and bundled JavaScript from the teacher-provided distribution ZIP. There are **no Bootstrap CDN references** and the sample images are local SVG files.

## Set up in StackBlitz
1. Unzip this package on your computer.
2. Open https://stackblitz.com/fork/web-platform in a browser on the **school network**.
3. Import/drag the project files and folders into the editor, preserving `css/`, `js/`, and `assets/` paths. If your StackBlitz interface provides **Import Project**, use that option to import the extracted folder.
4. Open `index.html` and check the preview. You should see a blue navbar, a green badge, three styled cards, and a green button.
5. Narrow the preview. Cards should stack on mobile; the navigation menu should collapse and open when clicked.
6. Save the project using your account. Use StackBlitz's **Fork** or **Share** workflow to provide a student-copy link, after checking sharing settings and district student-account policies.
7. Have one student test the project on the school network before distributing it to the class.

**If importing a ZIP directly is not offered in your interface**, extract the ZIP and import the files/folders, or create a project from a local folder using the import controls available to your account. Do not assume every StackBlitz account/interface offers the same import buttons.

## File structure
- `index.html` — starter site and student TODOs
- `css/bootstrap.min.css` — official Bootstrap 5.3.8, DO NOT EDIT
- `css/style.css` — student custom styling
- `js/bootstrap.bundle.min.js` — local interactive Bootstrap components
- `assets/highlight-1.svg` through `highlight-3.svg` — local sample images
- `STUDENT_ASSIGNMENT.md` — 100-point project instructions

## Quick test
- `btn btn-primary` should be blue.
- `row` / `col-md-6` / `col-lg-4` should adjust at different widths.
- `.card` should have Bootstrap card styling.
- Mobile navbar should open/close (requires bundled JavaScript).
- Placeholder images should display; no external image host is used.

## Important
This package removes the **Bootstrap CDN dependency**, not StackBlitz's own internet requirement. StackBlitz and its preview services still must be accessible on the school network. Some editor environments also load other resources remotely. Test from a student device.

## Classroom workflow
Students fork their own copy, change the content and design, test mobile/desktop layouts, and submit a StackBlitz link and brief test notes in Google Classroom. Require an exported code ZIP as a backup if supported.
