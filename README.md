# FirstContact
FistContact is a simple "get in touch" page. Nothing much just some information, your social media, 
a contact form and beatuiful design that looks amazing on any screen size.
It's written using jekyll so the content can be easily changed in data files without even touching the code 
and it can be hosted on GitHub pages for free.

Just fork this repo, enable github pages and you are good to go!

## Demo
The newest version is always build to: https://devleoko.github.io/FirstContact/

## Setup
1. Fork this repo
2. Enable github pages in your repo settings
3. Place your logo in `/assets/images/`
4. Put in your favorite color and other preferences in the `_config.yml`
5. Adjust any text you want in the `_data/` config files
6. Push the changes and check out your page

### Contact-Form
As this is a static site, the contact form can't send you any notification by itself. 
You need a backend server for that. Lukily [Formspree](https://formspree.io/) provides exactly that. 
They have a free tier: just sign up, create a new form and paste the form link into the `_config.yml`.
