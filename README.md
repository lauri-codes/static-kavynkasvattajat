# static-kavynkasvattajat
Static website for kavynkasvattajat.fi

## Building
Use the SimplyStatic plugin to export the static site. Use the option for
"offline"-use. In the generation logs you will see if some files could not be
included: you can include them manually:

 - The production build of the theme may not be included: copy the folder
   "theme/dist" into "wp-content/themes/theme/"
 - Copy "html/wp-includes/js/wp-emoji-release.min.js" into "wp-includes/js/"

Some links may end up being invalid. You can fix these easily with a script or
vim.
