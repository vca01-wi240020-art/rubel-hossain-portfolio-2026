# Rubel Hossain — Portfolio

A bilingual, responsive single-page portfolio for Rubel Hossain, web designer and front-end developer based in Japan. The site is implemented with semantic HTML, CSS, and vanilla JavaScript inside the existing Vite artifact—no React application layer is used.

## Run in this workspace

From the workspace root:

```sh
pnpm install
pnpm --filter @workspace/rubel-portfolio run dev
```

Create a production build with `pnpm --filter @workspace/rubel-portfolio run build`.

## Before publishing

Replace the clearly labeled editable placeholders in `index.html`:

- Replace `images/rubel.jpg` with the approved profile photo, keeping the same file name and path.
- Project artwork with actual screenshots or approved project images.
- Each disabled project demo and GitHub control with its real destination URL.
- The disabled GitHub profile controls and email placeholders with verified contact details.
- The disabled resume control with its “add file” label, once an actual resume file and approved resume content are available.

Project copy and education details are based on the supplied project brief. The skills list is an editable list of learning areas, not a proficiency scale or claim of professional experience. The development journey describes learning, not employment history.

## Contact form

The form validates name, email, subject, and message in the browser. It does not send or store data. Its confirmation explicitly explains that email delivery is not configured. Connect a real, secure backend or email service before representing it as a working contact channel.

## Language and accessibility

Use the EN / 日本語 control to switch the page copy. Navigation supports keyboard use, mobile menu state, active-section indication, and reduced-motion preferences. Update translations in the `copy` object in `script.js` when editing page text.
