# Lt. Suman — Personal Portfolio Website

A responsive single-page portfolio website for an educator and Associate NCC Officer.

## Files
- `index.html` — complete website (HTML, CSS and JavaScript in one file).

## Preview on your computer
1. Download and unzip the folder.
2. Open `index.html` in Chrome, Safari, or another browser.

## Important note about photo uploads
The gallery's **Add Photos** control works, and photos are saved in the browser on the device that added them. This is useful for previewing and personal use, but those photos are **not uploaded to the public website and will not appear for other visitors**. A public shared upload feature needs a secure online storage service and access controls. Do not make a public upload endpoint without protection, especially for photos of students/cadets.

## Publish free with GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a new **public** repository, for example `lt-suman-portfolio`.
3. Upload `index.html` to the top level of the repository.
4. Open **Settings → Pages**.
5. Under build/deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish and use the URL shown in Settings → Pages. It will usually look like `https://YOUR-USERNAME.github.io/lt-suman-portfolio/`.

GitHub's interface may change. The site is public if the repository and Pages site are public; do not add private documents or personal information.

## Before publishing
- Replace the placeholder hero/profile area with a photo you have permission to publish.
- Review the About Me text and achievements; edit them to match your actual experience.
- Add a public email address in the contact section and in the JavaScript `email` variable if you want the contact form to open an email draft.
- Add your social-media profile links.
- Get consent before posting identifiable photos of cadets, students, colleagues, or family.

## Make uploads public for everyone
For the exact feature requested—upload a photo yourself and have it appear to all visitors—you need a backend such as Supabase Storage (with secure sign-in and policies) or another hosted CMS. The current static version intentionally does not expose an unprotected public upload system.
