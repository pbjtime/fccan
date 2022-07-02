# Fccan Fort Collins Colorado Website

[![Netlify Status](https://api.netlify.com/api/v1/badges/077425e5-d667-4fee-afb2-aac79195beea/deploy-status)](https://app.netlify.com/sites/fccan/deploys)

This is the repo for https://fccan.com. Fccan is an organization based in community focused on furthering economic, social, and environmental justice, sustainability, human rights, and peace for all by building coalitions, developing strategies and actions, and supporting existing progressive organizations.

This site functions off the following technologies:
 [Jekyll](https://jekyllrb.com/)
 [netlify-cms](https://www.netlifycms.org/).
 [netlify](https://app.netlify.com/) (team page: https://app.netlify.com/sites/fccan/overview)

Using these technologies, we can obtain the following:
 - static site generation (no backend servers)
 - absolutely free hosting (some restrictions apply)
 - in page editing via the admin page, so non-technical users can contribute to webpage

## How to run Website // CMS locally for development purposes
 - Install ruby/jekyll (https://jekyllrb.com/docs/installation/)
 - Obtain access to repo, contact info@fccan.org
 - `git clone https://github.com/pbjtime/fccan.git`
 - `cd fccan`
 - `bundle exec jekyll serve --host 0.0.0.0`
 - You can now access the site: http://0.0.0.0:4000 (replace 0.0.0.0 with the local-link if hosting locally http://127.0.0.1:4000 or public address of your computer.)

**Optional:** In another terminal (to run the cms locally):
 - `cd fccan`
 - `PORT=8076 npx netlify-cms-proxy-server`