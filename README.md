# Aldersgate Municipal Library — browser prototype

A responsive, single-page library management demo based on the supplied screenshots.

## Run locally
Open `index.html` in a modern browser. No build tools are required.

## Demo accounts
- Student: `c.firth@yahoo.co.uk` / `student123`
- Teacher: `j.horacek@academy.cz` / `teacher123`
- Admin: `a.lister@aldersgate.lib` / `admin123`

Select the role, enter the demo credentials, then use the displayed verification code. The demo code for sign-in is `273549`. Account creation generates a demo code on screen.

## Features
- Role-specific sign in and student/teacher account creation
- Six-digit prototype verification screen
- Searchable catalog with genre filters and volume availability
- Personal loans and overdue filter
- Teacher reservations and cancellation
- Admin member management, book inventory editing, checkout and return workflows
- Browser-local persistence using `localStorage`
- Responsive layout inspired by the reference screenshots

## Publish on GitHub Pages
1. Create a new repository on GitHub, e.g. `aldersgate-library`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the deployment. GitHub will show the public URL in the Pages section, usually `https://YOUR-USERNAME.github.io/aldersgate-library/`.

## Important limitations
This is a functional front-end prototype, not a production-secure library system. Accounts and transactions are stored only in the current browser's local storage and are not shared between devices or users. Verification codes are simulated and no real email is sent. Google sign-in is a placeholder. For real public deployment with secure authentication, shared data, and email verification, connect a backend/database and an identity provider (for example Supabase or Firebase), and do not use the demo passwords for real accounts.
