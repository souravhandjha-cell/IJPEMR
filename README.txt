IJPEMR Manuscript Tracking Setup

1. Open the Google Sheet: MPJPR Manuscript Database.
2. Extensions > Apps Script.
3. Replace the existing Apps Script with apps-script-code.txt.
4. Deploy > New deployment > Web app.
   Execute as: Me
   Who has access: Anyone
5. Copy the Web app URL.
6. In submit.html and track.html replace:
   PASTE_YOUR_APPS_SCRIPT_WEB_APP_URL_HERE
   with that Web app URL.
7. Upload submit.html and track.html to GitHub, replacing the existing files.
8. Test with a new submission. The submission first registers the ID in the Sheet, then sends the FormSubmit email.
9. Use the generated ID and the same author email on Track Manuscript.

Sheet headers in row 1:
Manuscript ID | Email | Title | Status | Submitted | Updated | Editorial Message
