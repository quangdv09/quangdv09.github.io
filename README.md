## Instruction to create your own academic website

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/quangdv09/quangdv09.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below)
1. Upload any files (like PDFs, .zip files, etc.) to the **files/** directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section


## Locations of key files/directories

1. Basic config options: **_config.yml**
    * Define the content in the sidebars and other site-wide features.
    * Replace the default variables with ones about yourself and your site’s github repository.
1. Top navigation bar config: **_data/navigation.yml**
1. Single pages: **_pages/**
1. Footer: **_includes/footer.html**
1. Static files (like PDFs): **/files/**
1. Profile image (can set in _config.yml): **images/profile.png**


## How to edit your site's Github repository

1. You can edit these configuration and markdown files directly in the **github.com** interface.
1. You can also install **Github Desktop**. 
    - Clone your site's repository to your desktop.
    - Edit configuration files using your chosen editor, such as **notepad**.
    - Commit changes to the repository using Github Desktop.
1. You can also you **Visual Studio Code** together with the **Github Repositories extension**, see [here](https://code.visualstudio.com/docs/editor/github).


## How to make changes to the sidebar author profile

- The sidebar author profile can be edited by modifying **_config.yml** and **_includes\author-profile.html**.
- Check free icons at [Font Awesome v5](https://fontawesome.com/v5/search) and [Academicons](https://jpswalsh.github.io/academicons/).
- Tips for styling and coloring icons (https://jpswalsh.github.io/academicons/usage)
- You can use Color picker tool in Paint application of windows to look for the color code of icons.

## How to edit the content of your site

1. Edit file **_pages\home.md** to change the content of your homepage.
1. Add a new page 
    - Create a new .md file in **_pages** folder.
    - Remember to set its `permalink` and `title`. For an example please see **_pages\publications.md**.
    - Customize site navigational menu by adding titles and urls under the `main` key in **_data\navigation.yml**.


## Other guides

- Markdown Guide (https://www.markdownguide.org/)
- See more information at Academicpages site (https://academicpages.github.io/).
- For a full explanation of every setting be sure to read [this guide](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) at Minimal Mistakes page.

