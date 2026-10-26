# Oasis Volleyball Club website

## Put it online with GitHub Pages
1. Create a new GitHub repository (for example `oasis-website`) and upload every file in this folder.
2. In the repository, go to Settings > Pages. Under "Build and deployment", choose "Deploy from a branch", pick `main` and `/ (root)`, then Save.
3. After a minute the site is live at `https://<your-username>.github.io/oasis-website/`.

## Connect your own domain
1. Buy the domain, then in Settings > Pages > Custom domain, type it (for example `www.oasisvolleyball.ae`) and Save. GitHub creates a CNAME file for you.
2. At your domain provider, add a CNAME record for `www` pointing to `<your-username>.github.io`.
3. Tick "Enforce HTTPS" once it becomes available.

## Before going live: set your web address
Replace `https://www.YOUR-DOMAIN.com` with your real address in these files:
`index.html`, `robots.txt`, `sitemap.xml`, `llms.txt`.

## Get found on Google
1. Add the site to Google Search Console (search.google.com/search-console) and submit `sitemap.xml`.
2. Create a free Google Business Profile for "Oasis Volleyball Club" in Abu Dhabi and link the website.
3. Add the website link to your Instagram and TikTok bios.

## SEO launch checklist
1. Replace `https://www.YOUR-DOMAIN.com` everywhere (index.html, robots.txt, sitemap.xml, llms.txt).
2. Google Search Console: add the domain, verify, submit `sitemap.xml`, then use "URL inspection > Request indexing" for the home page.
3. Bing Webmaster Tools: import from Search Console (Bing also feeds ChatGPT search and Copilot).
4. Test the structured data at https://search.google.com/test/rich-results and the speed at https://pagespeed.web.dev
5. Google Business Profile: create it, then link the website (see the main SEO notes).

## Updating the chatbot (Noor)
All of Noor's answers are in `index.html`, inside the list called `KB`. Each topic has English (`en`) and Arabic (`ar`) text. Edit the text and upload the file again.
