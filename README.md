# Instructions to create your own academic website

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [the academicpages repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below)
1. Upload any files (like PDFs, .zip files, etc.) to the **files/** directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/


## Locations of key files/directories

1. Basic config options: **_config.yml**
    * Define the content in the sidebars and other site-wide features.
    * You will need to replace the default variables with ones about yourself and your site’s github repository.
1. Top navigation bar config: **_data/navigation.yml**
1. Single pages: **_pages/**
1. Footer: **_includes/footer.html**
1. Static files (like PDFs): **/files/**
1. Profile image (can set in _config.yml): **images/profile.png**


## How to edit your site's Github repository

1. You can edit these configuration and markdown files directly in the **github.com** interface.
1. You can also install **Github Desktop**. 
    - Clone your site's repository to your desktop.
    - Edit these files using your chosen editor, such as **notepad**.
    - Commit the changes using Github Desktop.
1. You can also you **Visual Studio Code** together with the **Github Repositories extension**, see [here](https://code.visualstudio.com/docs/editor/github).


## Markdown guide

* [Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
* [Basic Syntax](https://www.markdownguide.org/basic-syntax/)
* [Extended Syntax](https://www.markdownguide.org/extended-syntax/)

## Configuration

For a full explanation of every setting be sure to read [this guide](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) at Minimal Mistakes page.
