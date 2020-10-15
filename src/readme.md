.
```
├── readme.md
└── src
    ├── content
    │   ├── instructions.md
    │   ├── post-__21.07.2019.md.md
    │   ├── post-__22.07.2019.md
    │   ├── post-__23.07.2019.md
    │   ├── _post-__25.07.2019.md.md
    │   ├── _post-__26.07.2019_.md
    │   ├── post-__27.07.2019.md
    │   ├── post-__29.07.2019.md
    │   ├── post about the latest tech news -__24.07.2019.md
    │   └── readme.md
    ├── fonts
    │   ├── adventpro-bold-webfont.woff
    │   ├── adventpro-bold-webfont.woff2
    │   ├── adventpro-extralight-webfont.ttf
    │   ├── adventpro-extralight-webfont.woff
    │   ├── adventpro-extralight-webfont.woff2
    │   ├── adventpro-light-webfont.woff
    │   ├── adventpro-light-webfont.woff2
    │   ├── adventpro-medium-webfont.woff
    │   ├── adventpro-medium-webfont.woff2
    │   ├── adventpro-regular-webfont.woff
    │   ├── adventpro-regular-webfont.woff2
    │   ├── adventpro-semibold-webfont.woff
    │   ├── adventpro-semibold-webfont.woff2
    │   ├── adventpro-thin-webfont.woff
    │   └── adventpro-thin-webfont.woff2
    ├── images
    │   ├── casey-horner-wVjoNpcTHxM-unsplash.jpeg
    │   ├── chang-qing-2YQoKbyGvDc-unsplash.jpg
    │   ├── FoReSt-GReeN-hd-wallpaper-129105.jpg
    │   ├── forest-light-nature-   70365.jpg
    │   ├── icons
    │   │   ├── computer__iconfinder_Streamline-05_185024.svg
    │   │   ├── database__iconfinder_Streamline-77_185097.svg
    │   │   ├── network__iconfinder_Streamline-08_185027.svg
    │   │   └── server__iconfinder_storage_1370034.svg
    │   ├── joey-kyber-sFLVTqNzG2I-unsplash.jpg
    │   ├── john-fowler-aaIN3y2zcMQ-unsplash.jpg
    │   ├── john-fowler-bgGr1eKlYNw-unsplash.jpg
    │   ├── milada-vigerova-pQMM63GE7fo-unsplash.jpeg
    │   ├── patrick-langwallner-Nv-rPPW_LBc-unsplash.jpg
    │   ├── raychan-eJSN4mBkhVY-unsplash.jpg
    │   ├── sarah-dorweiler-9Z1KRIfpBTM-unsplash.jpg
    │   ├── vincent-guth-uhoILl3HUZM-unsplash.jpeg
    │   └── wil-stewart-pHANr-CpbYM-unsplash.jpg
    ├── index.html.html
    ├── scripts
    │   └── index.js
    ├── styles
    │   ├── grid_12-825-55-15.css
    │   ├── index.css
    │   ├── specimen_stylesheet.css
    │   └── stylesheet.css
    └── webfontkit-20190825-182014
        ├── adventpro-bold-demo.html
        ├── adventpro-extralight-demo.html
        ├── adventpro-light-demo.html
        ├── adventpro-medium-demo.html
        ├── adventpro-regular-demo.html
        ├── adventpro-semibold-demo.html
        ├── adventpro-thin-demo.html
        └── generator_config.txt

```

8 directories, 57 files

# Steps for "uscrambling the eggs"

1. Add all files using "git add ." command

2. Commit the above-mentioned action using "git commit -m "Initial commit"" command

3. Rename the "master" branch into "main" one according to the GitHub's new policy

4. Rename all markdown files only to lowercase style using "rename 'y/A-Z/a-z/' *.md" command

5. Add all files using "git add ." command

6. Commit the changes using "git commit -m "Rename all markdown files only to lowercase style""

7. Create "images" folder using "mkdir images" command

Jump into "images" folder using "cd images/" command

Create "icons" folder in the "images" folder using "mkdir icons" command

Find all .svg files using "find *.svg" command

Move all found .svg files only into "images" folder using "mv *svg images/" command

Move all found .svg files only into "icons" folder inside the "images" folder using "mv *svg icons/" command

Add all files using "git add ." command

Commit the above-mentioned action using "git commit -m "Move all .svg files to /images/icons/""  command

Move all .jpeg .jpg files only into "images" folder using "mv *jpeg *jpg images/" command

Create a "content" folder in "scrambled-eggs" folder

Move all .md files only into "content" folder using "mv *md content/" command

Add all files using "git add ." command

Commit the above-mentioned action using "git commit -m "Move all .md files only to scrambled-eggs/content/" command

Create "fonts" folder using "mkdir fonts" command 

Move all font files only to /scrambled-eggs/fonts/ using "mv *woff *woff2 *ttf ~/Documents/DCI_Course/15.10.2020/scrambled-eggs/scrambled-eggs/fonts/" command

Add all files using "git add ." command

Commit the above-mentioned action using "git commit -m "Move all .woff .woff2 .ttf files only to scrambled-eggs/fonts/" command

Rename all remained files into lower-case style for unity purpose using "rename 'y/A-Z/a-z/' *" command

Add all files using "git add ." command

Commit the changes using "git commit -m "Rename all left files to lowercase style"" command

Create "scripts" folder using "mkdir scripts" command

Find all .js files only using "find *.js" command

Move all .js files only using "mv *js scripts/" command

Add all files using "git add ." command

Commit the above-mentioned action using "git commit -m "Move all ""

Move all existing .css fiels from all folders to scrambled-eggs/styles/ using "mv *.css ~/Documents/DCI_Course/15.10.2020/scrambled-eggs/scrambled-eggs/styles" command

Create a src folder using "mkdir src" command 

Copy all folders to src using "mv <folder name> src/" command

Use "tree" command to print the folder structure

Add the structure to the readme file using "tre > readme.md" command

Move the readme.md from src/ to src/content/ folder using "mv readme.md content/"
