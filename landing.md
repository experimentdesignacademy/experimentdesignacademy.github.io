# Building a Landing Page
## GitHub
* [Sign in](https://github.com/)

## Organization
* [Create an organization account](https://github.com/account/organizations/new)

### Example
* Organization name: currencyconverters
* Billing email: travis@l4m.co

## Create web site
* [Github Pages](https://pages.github.com/)

1. Create a repository

Head over to [GitHub](https://github.com/) and [create a new repository](https://github.com/new) named *username*.github.io, where *username* is your username (or organization name) on GitHub.
### Example
* Repository name: currencyconverters.github.io

2. Clone the repository

Go to the folder where you want to store your project, and clone the new repository:

```
git clone https://github.com/username/username.github.io
```

### Example
* Create local directory: currencyconverters.github.io

```
git clone https://github.com/currencyconverters/currencyconverters.github.io.git
```

3. Hello World

Enter the project folder and add an index.md file:

```
cd username.github.io

echo "#Hello World" > index.md
```

4. Push it

Add, commit, and push your changes:

```
git add --all

git commit -m "Initial commit"

git push -u origin master
```
5. …and you're done!

Fire up a browser and go to **https://username.github.io**

### Example
* [https://currencyconverters.github.io/](https://currencyconverters.github.io/)

## [Adding a theme to your GitHub Pages site](https://help.github.com/articles/adding-a-jekyll-theme-to-your-github-pages-site-with-the-jekyll-theme-chooser/)

1. Navigate to your GitHub Pages site's repository
### Example
* [Currency Converters](https://github.com/currencyconverters/currencyconverters.github.io)

2. Under your repository name, click Settings.
3. Scroll down to GitHub Pages section
4. Click Choose a theme
5. Pick a template
6. Click Select theme

### Example
* [Currency Converters](https://currencyconverters.github.io/)

## Add Content
* Pull changes from GitHub
* Copy markdown from [template](https://raw.githubusercontent.com/pages-themes/minimal/master/index.md)
* Update index.md
* Push changes to GitHub

### Example
* [Currency Converters](https://currencyconverters.github.io/)
