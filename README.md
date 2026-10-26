# Oasis Volleyball Club website

Live at https://oasisvolleyball.github.io/website/

## Updating the site on GitHub (important)
All files sit in ONE folder, with no subfolders. When you update:
1. Open the repository on github.com and click Add file > Upload files.
2. Open this folder on your computer, select ALL files (Ctrl+A or Cmd+A) and drag them into the upload box.
   Check the list shows all the photos (.jpg), the fonts (.woff2) and fonts.css before you commit.
3. Click Commit changes. The live site updates within a minute or two.

## Moving to your own domain later
1. Settings > Pages > Custom domain: type the domain (for example www.oasisvolleyball.ae) and Save.
2. At your domain provider, add a CNAME record for www pointing to oasisvolleyball.github.io
3. Tick Enforce HTTPS once available.
4. Ask Claude to rebuild the site with the new address (it appears in index.html, sitemap.xml, robots.txt and llms.txt).

## SEO launch checklist
1. Replace `https://www.YOUR-DOMAIN.com` everywhere (index.html, robots.txt, sitemap.xml, llms.txt).
2. Google Search Console: add the domain, verify, submit `sitemap.xml`, then use "URL inspection > Request indexing" for the home page.
3. Bing Webmaster Tools: import from Search Console (Bing also feeds ChatGPT search and Copilot).
4. Test the structured data at https://search.google.com/test/rich-results and the speed at https://pagespeed.web.dev
5. Google Business Profile: create it, then link the website (see the main SEO notes).

## Updating the chatbot (Noor)
All of Noor's answers are in `index.html`, inside the list called `KB`. Each topic has English (`en`) and Arabic (`ar`) text. Edit the text and upload the file again.
