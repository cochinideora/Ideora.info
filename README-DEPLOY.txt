IDEORA WEBSITE — DEPLOYMENT PACKAGE

This folder contains the static website. The homepage is index.html at the root.

PUBLISH WITH NETLIFY
1. Open https://app.netlify.com/drop in a browser and sign in.
2. Upload the extracted folder named Ideora-website (or a ZIP containing its contents).
3. Netlify will publish the static site and provide a temporary URL.

PUBLISH WITH GITHUB PAGES
1. Upload all files and folders in this folder to the root of your GitHub repository.
2. In repository Settings > Pages, choose Deploy from a branch, select the main branch and /(root), then Save.

NOTES
- The site loads Bootstrap, Font Awesome, Google Fonts, jQuery and some video/image resources from external hosts, so internet access is required for those resources.
- The enquiry form opens WhatsApp with the enquiry details; it does not send email automatically.
- Check the displayed WhatsApp number and all business details before publishing.


LOGO UPDATE
- The supplied Ideora logo is installed at assets/img/logo.png. All supplied HTML pages already reference this shared path for the navbar and favicon.
- Copy/merge these files into your existing website repository, replacing the matching HTML files and assets/img/logo.png.
- This update package contains only the HTML files supplied in this chat and the replacement logo. Keep your existing assets/css, assets/js, and other image/media assets; they were not included in this upload.
