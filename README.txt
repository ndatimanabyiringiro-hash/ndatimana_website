NDATIMANA BYIRINGIRO - GITHUB PAGES PORTFOLIO
==============================================

THIS VERSION IS PREPARED FOR GITHUB PAGES
The original upload was a PHP website. GitHub Pages does not run PHP, so
the pages have been converted into static HTML files. The separate Ollama
PHP backend is provided in the sibling folder `ollama-php-backend`.

PUBLISH ON GITHUB
1. Open https://github.com/bdassise/ndatimana_website
2. Upload the CONTENTS of this folder (not the enclosing folder) to the
   repository root. Ensure index.html is directly beside assets/.
3. Commit the uploaded files to the main branch.
4. Open Settings > Pages.
5. Choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
6. Open Actions and wait for the Pages deployment to finish successfully.
7. Your expected URL is https://bdassise.github.io/ndatimana_website/

INCLUDED
- Separate static HTML pages for Home, About, Skills, Projects, Education,
  AI Assistant, CV and Contact
- Six static skill-detail pages
- Responsive CSS and mobile navigation JavaScript
- Profile photo and CV PDF
- 404 page
- Configurable AI chat frontend

AI ASSISTANT
The portfolio itself will work on GitHub Pages, but the AI chat will not
answer until a separate PHP/Ollama backend is deployed. GitHub Pages cannot
run PHP or Ollama. See the `ollama-php-backend/README.txt` file in the
downloaded project. Set the backend HTTPS URL in assets/js/config.js.

CHECKS
- Homepage filename must be exactly index.html (lowercase).
- index.html must be in the repository root.
- Keep assets/, bdassise.jpeg and Ndatimana_Byiringiro_CV.pdf in the root.
- GitHub repository must be Public for a public portfolio.
- After committing changes, wait for the Pages deployment to complete.
