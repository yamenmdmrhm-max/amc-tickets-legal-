AMC Tickets legal pages

Files:
- index.html
- terms.html
- privacy.html
- style.css

IMPORTANT BEFORE PUBLISHING:
1. Replace [ADD A SUPPORT EMAIL OR SUPPORT SERVER LINK] in terms.html and privacy.html with a real contact method that you monitor.
2. Review the retention wording in privacy.html. Make sure it accurately describes what your bot actually does with SQLite records, ticket deletion, and backups. If deleted tickets remain in the database, change the wording to explain the real behavior and retention period.
3. Confirm the listed identifiers and ticket fields match what your code actually stores. Remove anything the bot does not collect and add anything it does.
4. Publish the files on a public HTTPS website. These local files are not public URLs by themselves.

GitHub Pages quick publishing:
1. Create a new public GitHub repository, for example: amc-tickets-legal.
2. Upload all four files to the repository's root.
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. After GitHub Pages publishes the site, use:
   https://YOUR-GITHUB-USERNAME.github.io/amc-tickets-legal/terms.html
   https://YOUR-GITHUB-USERNAME.github.io/amc-tickets-legal/privacy.html
Replace YOUR-GITHUB-USERNAME with your GitHub username.
6. Paste the two public URLs into the Terms of Service and Privacy Policy fields in Discord Developer Portal.

Discord requires public, accessible policy links for App Discovery eligibility. Adding these links does not guarantee verification or approval.
