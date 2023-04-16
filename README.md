# DocuMemo (Debian)

## SetUp: https://github.com/yforku/docusaurus/ (CHECKED)

## Install debian package nodejs and npm:
```
sudo aptitude install nodejs npm -y

```

## Check if NODE version > v.8
```
node -v

```

## Install Docusaurus-Init
```
sudo npm install --global docusaurus-init
sudo npm install --global yarn

```

## New WebSite
```
docusaurus-init
cd website
npm start

```

## See localhost:3000

## XX

* website/pages/en/hello-world.js
* docs/doc9.md
  * website/sidebars.json

## docusaurus-tutorial/website/siteConfig.js
```
const siteConfig = {
  ...
  title: 'Selamat Imlek 2024', // Title for your website.
  tagline: 'Mudah-mudahan rampung sebelum Imlek 2024, Amin.',
  url: 'https://yforku.github.io',
  baseUrl: '/docusaurus/',
  projectName: 'docusaurus',
  organizationName: 'yforku',
  ...
}

```

## npm run build

## XYZZY

```
GIT_USER=cbkadal CURRENT_BRANCH=master USE_SSH=true npm run publish-gh-pages

```

##### Yes, Fork You (yforku)! --- Revisi 19d 16-Apr-2023

