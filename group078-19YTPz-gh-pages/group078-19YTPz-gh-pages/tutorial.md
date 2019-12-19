# Tutorial

Welcome to tutorial where you'll learn how to use the pre-built website to present your project. You'll only need a **basic level of computer skills** to be able to follow this tutorial.

## Let's get started!

Your website is powered by your Github repository for which you have received an invitation to collaborate. We suggest you to assign **one member** of your group to be **in charge of managing this repository and your website**. 

To get started this _tech representative_ of your group needs to have signed up for a free account on Github and to have accepted an invitation to collaborate. Now you have access to your group’s repository.

Your repository is at `https://github.com/TheGreatTransition/[group_id]` and your website is at `https://thegreattransition.github.io/group[group_id]` where `[group_id]` is your group's secret ID.

**Do not share this ID (and your website's address) with others if you wish to protect your project material before the final submission.**


Go to your Github repository and you'll find the following folders & files:

_Layout  
Assets  
.gitignore  
README.md  
config.yml  
about.md  
cheatsheet.md  
FAQ.md  
index.md  
tutorial.md  

A schema of the files in your repository is as follows:

```
[group_id]/
|
|__  _layout/
|    |__  default.html
|__  assets/
|    |__  css/
|    |    |__ style.scss
|    |__  images/
|    |    |__ cover.jpg
|    |    |__ logo.jpg
|    |    |__ profile1.png
|    |    |__ profile2.png
|    |__  pdf/
|    |    |__ a4.pdf
|    |    |__ powerpoint.pdf
|__  .gitignore
|__  README.md
|__  _config.yml
|__  about.md
|__  cheatsheet.md
|__  FAQ.md
|__  index.md
|__  tutorial.md
```

## Claim your project's name and image!
To start, click on `_config.yml` and click **edit** (the diagonal pencil icon). 

Once in the edit mode change `title`, `subtitle`, and `description` to a title (up to 5 words) and subtitle (around 10 words) and short description (up to 280 characters) for your project. For now, leave `menu` as is. 

To save your changes scroll down the page and click **Commit changes**.

> **NOTE: Any commit (change in your repository) might take up to a minute to become effective, so be patient :)**


Meanwhile, go to the `assets/images/` folder. Once there click on **Upload files** and upload your own cover and logo images to replace the existing ones. **The file names MUST be `cover.jpg` and `logo.jpg`**.


## Change your first page!

Now go back to the root of your repository. You'll notice there are by default a few files with names ending with `.md`. **Each of these files contain the content of one of your website's pages with the same name** (except `README.me`). For example `tutorial.md` is the file behind this current page you are seeing.

Start by editing the `index.md` to change the home page of your website. Head down to:
*   [Cheat sheet](cheatsheet.md) to learn how to put different media on your page and style your page content.  
You can write text and use pdfs, images or videos in your home page.
Go to cheatsheet.md and copy the codes related to uploading pdf, images or videos. Paste it in your index.md(home page) and customize it by your resources.

## Change About us page!
Why not also change `about.md` to personalize your [About us](about.md) page.
Before editing the image links in there, you need to upload your group members' images in `assets/images/` as you did for cover and logo.


## Create a new page!

You can add and remove as many such files/pages as you like.

To create a new page, you simply need to create a new `.md` (or if you're familiar with HTML `.html`) file in the root of your repository.

There, click on **Create new file** and enter a name (without any space) ending with `.md`: for example `vision.md` which will be accessible at [vision](vision)


## Change the menu!

To change your website's **menu** (the top navigation bar), open the `_config.yml` file and edit `menu: [...]`.

Look at the existing entries to learn how to create a new one. Each entry is represented by a `{...}`, where `display_name` is the label of the entry and `page_name` is the name of the page that it links to (which is the same as the name without `.md` of a file in the root of your repository).

For example, `{"display_name": "Home", "page_name": "index"}` adds Home to the menu which links to the `index` page (created by `index.md` file)



## Important!

**Eventually you should delete  `Tutorial`, `Cheat Sheet`, and `FAQ` from your website's menu. You can also delete the corresponding files (`tutorial.md`, `cheatsheet.md`, and `FAQ.md`) from your repository.**


## Feeling stylish?
If you wish to change some basic style elements of your website in `assets/css/style.scss`. There you can change the colors of your headers and text by changing the corresponding variables at the top of the file.
```
// Headers
$header-title-color: white !default;
$header-subtitle-color: #e6142d !default;
$header-bg-color: #e6142d !default;
$header-logo-border-color: black;

// Text
$section-headings-color: #e6142d !default;
$body-text-color: #606c71 !default;
$body-link-color: #1e6bb8 !default;
$blockquote-text-color: #819198 !default;
```
You can use [google](https://www.google.fr/search?q=web+color+picker)'s color picker to get the color codes that you want.

## Feeling like a Pro?
Only if you feel comfortable enough with web development, you may change the structure of the pages in `_layouts/default.html` and/or make more stylish changes in `assets/css/style.scss`.

