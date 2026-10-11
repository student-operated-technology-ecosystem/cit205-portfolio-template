# CIT-205 Student Portfolio Starter

This is a **starter template**, not a completed student portfolio. Start with [**Use this template**](https://github.com/student-operated-technology-ecosystem/cit205-portfolio-template/generate) to copy `index.html`, `style.css`, and the `artifacts/` directory into the root of your own public repository.

## Editing your portfolio without breaking the code

Open `index.html` in your own repository and choose the pencil icon (on mobile, check the file's three-dot menu for **Edit file**). Use Find to search for `EDIT YOUR NAME`, `EDIT YOUR INTRODUCTION`, `EDIT THIS PROJECT`, `EDIT YOUR PROFESSIONAL REFLECTION`, and `EDIT YOUR GITHUB`.

**Change the words between the tags, not the tags themselves.** For example, change `<h1>YOUR NAME</h1>` to `<h1>Jordan Student</h1>`. For a paragraph, keep `<p>` and `</p>` and replace only the sentence between them. Text between `<!--` and `-->` is an instructor note that does not appear on the website.

Start with one small change: replace your name, select **Commit changes**, then open your published website to confirm the result. Repeat for the introduction and projects. A commit saves your revision to GitHub; Pages may take a few minutes to publish it.

Each artifact's PDF link begins with `hidden`. Upload the matching reviewed, redacted PDF to `artifacts/` first. Then remove **only** `hidden` from that artifact's `<a hidden href="...">` link and commit. Do not remove the surrounding HTML tags. If something goes wrong, use GitHub's commit history to compare or restore earlier work.

## Student publishing checklist

1. Follow the [ACE Portfolio Publication Mission](https://github.com/student-operated-technology-ecosystem/CIT-205-classroom/blob/main/assignments/ACE-portfolio-publication-mission.md).
2. Select **Use this template → Create a new repository**, set Owner to **your own account**, choose **Public**, and name it `YOUR-GITHUB-USERNAME.github.io` using your exact GitHub username (example: `alexmorgan.github.io`). Leave **Include all branches** unchecked. If this repository already exists, preserve it and copy the starter files into it without overwriting existing work.
3. Confirm `index.html`, `style.css`, and `artifacts/` are in your repository **root**. The template includes them automatically. Complete your document in Word, save the editable original, then use **File → Save As / Export → PDF**. Review the PDF for confidential information. Open `artifacts/`, choose **Add file → Upload files**, upload the public-safe PDF, and **Commit changes**. Follow `artifacts/README.md` for exact filenames.
4. Replace every `YOUR NAME`, introductory paragraph, sample explanation, GitHub URL, and LinkedIn URL. **To show an artifact after uploading its PDF**, edit `index.html`, locate that artifact's `<a hidden href="artifacts/FILENAME.pdf">` link, remove only the word `hidden` (and the following space), then **Commit changes**. Make sure the `href` filename matches the uploaded PDF exactly. Leave unfinished links hidden. This means a newly published starter has no clickable missing-PDF links.
5. Open **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, and Folder to **/(root)**, then select **Save**.
6. Wait several minutes for deployment, refresh **Settings → Pages**, and select **Visit site**. Open `https://YOUR-GITHUB-USERNAME.github.io/` in a private window and test all links. Commits to `main` automatically republish your site.
7. Submit the live URL and repository URL (`https://github.com/YOUR-GITHUB-USERNAME/YOUR-GITHUB-USERNAME.github.io`) to Blackboard.

**Important:** PDF links are hidden in the starter because the PDFs are not yet included. Upload your own artifacts first, then unhide only the matching links. Do not copy Alex Morgan's work or present placeholders as finished evidence.

The [Alex Morgan example](https://github.com/student-operated-technology-ecosystem/CIT-205-classroom/tree/main/examples/exemplary-portfolio) is a fictional quality reference, not student work to copy.

## Instructor classroom demonstration
Walk through account/repository creation, show `index.html` and `style.css` in the root, upload one safely redacted artifact, publish via Pages, and open the resulting website in a private window. Then show how to replace a broken link and verify the repair.
