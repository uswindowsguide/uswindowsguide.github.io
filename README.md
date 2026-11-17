# Windows Help Center — GitHub Pages Project

This project contains a responsive static website with **80 Windows educational articles**.

## Files and folders

- `index.html` — homepage with searchable article cards.
- `style.css` — shared responsive styling and header navigation.
- `articles/` — individual HTML article pages. Each filename is a readable title-based slug without a serial number.
- `README.md` — this setup guide.

## Navigation

The shared header appears on the homepage and every article page. It contains:

- Home
- Login
- Support

As requested, all three navigation targets are currently set to `#`. They are visual navigation placeholders and do not open separate login or support destinations.

## Publish on GitHub Pages

1. Create or open the GitHub repository you want to use for the website.
2. Extract this ZIP file on your computer.
3. Upload the contents of the extracted `windows_support_github_pages` folder to the repository's publishing root. Upload `index.html`, `style.css`, `README.md`, and the complete `articles` folder. Do not upload only the ZIP file.
4. Commit the uploaded files to the branch used for GitHub Pages.
5. In the repository, open **Settings → Pages**.
6. Under the build and deployment section, choose **Deploy from a branch**.
7. Select the publishing branch (commonly `main`) and folder (`/root`), then save.
8. Wait for the Pages deployment to finish and open the website address shown in the Pages settings.

For a project site, the address normally follows the pattern `https://USERNAME.github.io/REPOSITORY/`. For a user or organization site, the repository is normally named `USERNAME.github.io`.

## Editing articles

Open any HTML file inside `articles/` and edit its article content. All article pages load the shared `style.css` file from the parent folder. Keep the relative stylesheet path `../style.css` in article pages.

## Content and safety notes

These pages are independent educational guides and are not an official Microsoft support service. Windows is a trademark of its respective owner. No phone number is invented or presented as an official support number. Always verify contact details through a trusted official source that you navigate to yourself. Never share passwords, PINs, one-time verification codes, product keys, or recovery keys with an unsolicited caller.

The Login navigation item is a placeholder as requested. Windows sign-in uses a Microsoft account, local account, or work/school account depending on the device; a separate universal "Windows Support account" is not a standard Windows requirement.

## Local preview

Open `index.html` in a modern web browser. The homepage search filters article cards in the browser without a server.
