# Musicmag 2026

A small web project to learn the basics of Craft CMS by Pixel&Tonic.

## Install project

- install DDEV (project name should be musicmag)
- run `ddev composer install` in your terminal to install Craft CMS
- create and modify your local `.env` file (use `.env.example` as a template)
- if you need an app-id, run `ddev craft setup/app-id`
- if you need a security key, run `ddev craft setup/security-key`
- import a database backup from production
- import assets in `/web/uploads` from production

## TODOS

- [x] Missions of a CMS: routing (url), templating (Twig), Database CRUD (templates, API, Control Panel)
- [x] install DDEV and Craft
- [x] Craft configuration using `.env` and `config/general.php`
- [x] First sections (home and stories), entry types, fields and entries
- [x] Introduction to Twig (3 types of tags)
- [x] Retrieving some entries and displaying fields
- [x] Add CSS, JS and non user uploaded asssets
- [x] Modular DRY approach: includes and template inheritance
- [ ] Add SEO variables: metaTitle, metaDescription, metaImage
- [ ] Header and navigation
- [x] Footer
- [x] Home page fields and template
- [x] Story detail page main fields and template
- [ ] Story detail page Matrix field (modular body) and template
- [ ] Story archives template
- [ ] Magazine page fields and template
