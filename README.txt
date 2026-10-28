AWS / ECC webinar EDM — GitHub Pages edition

1. Create a PUBLIC GitHub repository (e.g. aws-webinar-edm).
2. Upload index.html and the assets folder to the repository root. You can upload the extracted ZIP contents via Add file > Upload files.
3. Go to Settings > Pages > Build and deployment > Deploy from a branch. Select main and /(root), then Save.
4. Wait for GitHub to show your published URL, typically https://USERNAME.github.io/REPOSITORY/ .
5. Open that exact URL in Google Chrome. Check that every image is visible.
6. Click 'Copy EDM for Outlook'. Chrome may ask permission to access clipboard; allow it.
7. In Outlook, create a new HTML-format email, click into its blank body, and press Ctrl+V. Avoid Insert > Pictures or manually re-adding assets.
8. Send test messages to Gmail and Outlook accounts; inspect desktop and mobile.

IMPORTANT:
- Do not open index.html locally for copying. Copy only from the published HTTPS URL.
- The copy button is a preview-only control; it is not copied into the email.
- All image URLs are rewritten to absolute public HTTPS URLs at copy time.
- Email clients may block remote images until recipients choose 'Display images'.
- GitHub Pages requires a public repo on the Free plan; avoid uploading private credentials or contact lists.
- Browser copy/paste can still be modified by Outlook. This workflow improves reliability but cannot guarantee identical rendering in every client.
- The registration link remains https://forms.gle/kwM4ZsxpoY8N1nkc9 .
- If Outlook paste remains broken, use an HTML-capable email sender rather than rich-text paste.
