# SMACSS_IT

Cmdline tool that creates Sass/Scss folders and files structure for SMACSS.

This tool is great for adding order, structure and cleanliness to your web project.
If you are using HTML & CSS inside of your project. Installing and creating boiler plates over <span><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/72/facebook/230/man-gesturing-ok-type-4_1f646-1f3fd-200d-2642-fe0f.png" alt="smile" height="40" width="40"/> and over ...<img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/72/facebook/230/man-pouting-type-4_1f64e-1f3fd-200d-2642-fe0f.png" alt="" height="45" width="45"> and over...<img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/72/facebook/230/man-frowning-type-4_1f64d-1f3fd-200d-2642-fe0f.png" alt= ":confused:" height="45" width="45">and over again makes me <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/72/facebook/230/man-facepalming-type-4_1f926-1f3fd-200d-2642-fe0f.png" alt="anger" height="45" width="45"/> ! **<span><h3>Dont't Get Mad <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/72/facebook/230/man-gesturing-not-ok-type-4_1f645-1f3fd-200d-2642-fe0f.png" alt="no more" height="45" width="45"/>... Just Smacss It !!!** </span>

# WHAT IS SMACSS?

<center><a href="http://smacss.com/"><img src="http://smacss.com/img/book-covers.png" alt="Smaccs_Image" width=50% height=300/></a></center>

### <center> Scalable and Modularclass Architecture for CSS</center>

<p>SMACSS (pronounced “smacks”) is more style guide than rigid framework. There is no library within here for you to download or install. There is no git repository for you to clone. SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS. And really, who isn’t building a site with CSS these days?!</p>

- <font size="2"> **For more information about SMACSS:** &nbsp; &nbsp; [SMACSS Documentation](http://smacss.com/)
  </font>

## Requirements

- Requires **`python`** - python 3.5>= greater.

## Getting Started

- Open linux terminal.

- Clone this repo using **`sudo git clone https://github.com/cbderoid/smacss_it.git`**

  ```bash
  sudo git clone https://github.com/cbderoid/smacss_it.git
  ```

- Navigate to repo folder by typing **<span>`cd "path-to-this-repo-folder"`</span>**

  ```bash
  cd "path-to-this-repo-folder"
  ```

- Move **`smacssit`** file to **`/usr/bin`** by typing **`sudo mv smacssit /usr/bin/`**

  ```bash
  sudo mv smacssit /usr/bin/
  ```

- Make sure file is executable through system - **`sudo chmod +x /usr/bin/smacssit`**

  ```bash
  sudo chmod +x /usr/bin/smacssit
  ```

## How To Use SmacssIt

#### Now that smacssit is installed , Lets go over how to use it! :+1:

Right out the box, smacssit is configured to created the basic folders and filesystem.

Following SMACSS Guide Rules , SmacssIt will create the following folders and files.

<pre>

</pre>

To run **`smacssit`**, first cd to your project SASS's directory. **<span>`cd "your-project-sass-folder"`</span>**

```bash
cd "path-to-your-project-sass-folder"
```

Lastly, Let's create the SMACSS folder structure, now type **`sudo smacssit`**

```bash
sudo smacssit
```

```bash
usage: makesmacss [-h] [-l] [-m MODULAR [MODULAR ...]] [-s]
                  [-e EXCLUDE [EXCLUDE ...]]

        *********************************************************
        *             SMACSS BOILER PLATE                       *
        *                                                       *
        *      Create SASS/SCSS files and folders               *
        *-------------------------------------------------------*
        *                                                       *
        * A flexible guide to developing sites small and large. *
        *          Documentations:                              *
        *         ------------------                            *
        *     SMACSS: https://smacss.com                        *
        *     SASS:   https://sass-guidelin.es                  *
        *                                                       *
        *********************************************************

optional arguments:
  -h, --help            show this help message and exit
  -l, --list            list all smacss dirs
  -m MODULAR [MODULAR ...], --modular MODULAR [MODULAR ...]
                         Add additional smacss modulars.
					      * Modulars can be place in a specific order by
					         adding a number followed by a dash (-).
                          * Example:
	                         [number]-[name_of_modular] --> 6-icons
  -s, --scss            Use scss format ( default: .sass)
  -e EXCLUDE [EXCLUDE ...], --exclude EXCLUDE [EXCLUDE ...]
                        excludes creating a smacss dir folder
```

<pre>

</pre>

#### Congratulations.. The finally results should now look similiar to this structure ...

```bash
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

<pre><b><small><font color="#0EC7FF">For more details on this file structure, visit: </small>
     <a href ="https://www.youtube.com/watch?v=c3fwnwSRGU0"><img src="https://cdn.fastly.picmonkey.com/content4/previews/social/social_33_550.png" alt="" width="35" height="35"/><font size="3" color="#00"> <b>BRAD HUSSEY</b> - Sass Best Practices </font></a></pre>

## Thanks & Resources

- [Codes](https://github.com/cbedroid/Smacss-It)
- [SMACSS Documentation](http://smacss.com/)
- [Sass Documentation](https://sass-guidelin.es/)
- [Issues & Bugs](https://github.com/cbedroid/Smacss-It/issues)
