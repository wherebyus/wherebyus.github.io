Agency Jekyll theme
====================

Agency theme based on [Agency bootstrap theme ](http://startbootstrap.com/templates/agency/)

# How to use

###Portfolio 

Portfolio projects are in '/_posts'

Images are in '/img/portfolio'

###About

Images are in '/img/about/'

###Team

Team members and info are in '_config.yml'

Images are in '/img/team/'


# Demo

View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

=========
For more details, read [documentation](http://jekyllrb.com/)


# Managing the team section
Here's how to update the 'Our Team' section of the site.

###General prep
1. Install the [Export Sheet Data](https://chrome.google.com/webstore/detail/export-sheet-data/bfdcopkbamihhchdnjghdknibmcnfplk?hl=en) Chrome extension
2. Mozy on over to the [Staff Directory form responses spreadsheet](https://docs.google.com/a/whereby.us/spreadsheets/d/1NxR7CFAmgq12faulZE-hoSwmddhUfxm_Yf5Pm9Xc0Q0/edit?usp=sharing)

###Crop and upload images
1. For any new staff members, click links in the img column of **Form Responses 1** sheet and download their headshot image from Drive. 
2. Crop the image to 300px x 300px at 144dpi and save as a jpg.
3. Rename the image as the respondent's first and last name, title-case, no spaces. (Example: `JonSnow.jpg`)
4. Put the file in the team images directory at `img/team/` 

###Prepare and upload new directory data
For the rest of the steps, you will work on the **directory_clean** sheet

1. Drag down columns to autofill new respondents
2. Give new respondents an order position
3. Sort sheet by order to ensure it seems logical
4. In the menu, Select `Add-Ons > Export Sheet Data > Open Sidebar`
5. In the Export Sheet Data Sidebar, under *JSON Options*, check "Export Cell Arrays."
6. Click the *Export* button in the sidebar.
7. Download the json file
8. Change file name to `directory.json`
9. Upload to the `_data` directory

### Check your work
1. If something looks off, check the team section layout at `_includes/team.html` to see how the data is being called, and then double check your data and photo names.
2. If all is well, push it! (Push it real good.)