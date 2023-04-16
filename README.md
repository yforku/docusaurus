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
  url: 'https://USERNAME.github.io', // Replace USERNAME with your GitHub username.
  baseUrl: '/base/', // The name of your GitHub project.
  projectName: 'base',  // The name of your GitHub project. Same as above.
  organizationName: 'USERNAME' // Your GitHub username.
  ...
}

```

## npm run build

##### Yes, Fork You (yforku)! --- Revisi 19a 16-Apr-2023

