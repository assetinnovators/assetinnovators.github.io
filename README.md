# Asset Innovators Website

This is the static website for Asset Innovators Co., prepared for deployment on GitHub Pages.

## Deployment Instructions

1. Create a new public repository on GitHub.
2. Push this codebase to the repository.
3. Go to Settings > Pages in the repository.
4. Set source to "Deploy from a branch" and select "main" branch (or master).
5. The site will be available at `https://yourusername.github.io/repositoryname/`

## Contact Form Setup

The contact form uses Formspree for handling submissions.

1. Sign up at [Formspree](https://formspree.io/).
2. Create a new form and get the form ID (looks like `abc123`).
3. In `contact.html`, replace `YOUR_FORM_ID` in the form action with your actual form ID.
4. Commit and push the change.

Form submissions will be emailed to the address associated with your Formspree account.

## Notes

- All links are relative and should work on GitHub Pages.
- The site is fully static and does not require a backend.
- WhatsApp widget and other external scripts are included but optional.