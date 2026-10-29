# Publish the Jobdesk preview on GitHub Pages

1. Create or open the GitHub repository you want to use.
2. Unzip Jobdesk-GitHub-Pages.zip on your computer.
3. In GitHub, choose Add file > Upload files. Upload the CONTENTS of the extracted folder, with index.html at the repository root (not inside another folder).
4. Commit the files.
5. Open repository Settings > Pages.
6. Under Build and deployment choose Deploy from a branch.
7. Select main and / (root), then Save. If your default branch has a different name, select that branch.
8. Wait for GitHub to finish deployment; the Pages settings will show the website link.

This package is a static SAMPLE PREVIEW of the existing Jobdesk interface. No build command or dependencies are needed. It works under a repository subpath. Use a repository suitable for sharing this frontend source; a public repository exposes its code.

Sample edits are temporary and reset on reload. Some controls require the real backend and will explain that they are unavailable. Sign-in, permanent saved records, WhatsApp, live lead fetching, file storage and payment processing are not connected. Do not enter real customer data. Existing contact/map links may open external apps; no messages are sent automatically.

This is not the production app or a replacement for the full source backup. Continue development from Jobdesk-Code-and-Handover.zip. This preview was extracted from source commit 705d25e589237378abea1a4b05b14e67a75ed401. It preserves the current screens and sample workflows. Basic JavaScript syntax was checked; browser visual and interaction QA was not performed for this export.
