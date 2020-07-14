[http://smacss.com/img/book-covers.png](http://smacss.com/img/book-covers.png)

# SMACSS_IT

Automatically create Sass/Scss folders and files structure for SMACSS

# WHAT IS SMACSS?

<span><img src="http://smacss.com/img/book-covers.png" alt="Smaccs_Image" width=250 height=250/>

<p>SMACSS (pronounced “smacks”) is more style guide than rigid framework. There is no library within here for you to download or install. There is no git repository for you to clone. SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS. And really, who isn’t building a site with CSS these days?!</p>

**For more information about SMACSS:** &nbsp; &nbsp; [SMACSS Documentation](http://smacss.com/)

## Requirements

- Requires **`python`** - python 3.5>= greater.

## Getting Started

- Open linux terminal.
- Clone this repo using **`git clone https://github.com/cbderoid/smacss_it.git`**
- Navigate to repo folder by typing **<span>`cd "path-to-this-repo-folder"`</span>**
- Move **`smacssit`** file to **`/usr/bin`** by typing **`sudo mv smacssit /usr/bin/`**
- Make sure file is executable through system - **`sudo chmod +x /usr/bin/smacssit`**

## How To Use SmacssIt

### Now that smacssit is installed , Lets go over how to use it!

Right out the box, smacssit is configured to created the basic folders and filesystem.

- Following the SMACSS Rules Guide , smacss will create the following folder and files.

![youtube](http://i3.ytimg.com/vi/c3fwnwSRGU0/hqdefault.jpg#youtube)

img[src*="#youtube"] {
width:150px;
height:100px;
border-radius:50%;
}

> <small>For more details on this file structure, visit
> [https://www.youtube.com/watch?v=c3fwnwSRGU0](https://www.youtube.com/watch?v=c3fwnwSRGU0)</small>

```

├── 0-plugins
│   ├── _plugin.sass
│   └── _plugins-dir.sass
├── 1-bases
│   ├── _base.sass
│   └── _bases-dir.sass
├── 2-layouts
│   ├── _layout.sass
│   └── _layouts-dir.sass
├── 3-modules
│   ├── _module.sass
│   └── _modules-dir.sass
├── 4-states
│   ├── _state.sass
│   └── _states-dir.sass
├── 5-themes
│   ├── _theme.sass
│   └── _themes-dir.sass
├── _animations.sass
├── app.sass
├── _breakpoints.sass
├── _mixins.sass
└── _vars.sass
```
