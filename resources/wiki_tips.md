# 2021 RULES
* WIKI FREEZE: OCTOBER something
1. Do not alter iGEM login bar (grey bar at the top)
2. Use standard url pages for the main pages
    * judges can easily access the various pages
    * will not be considered for medal without it
    * https://2021.igem.org/Judging/Pages_for_Awards
3. No Adobe Flash
4. ALL content must be hosted on 2021.igem.org
5. iFrames can be used to only show content from iGEM servers
    * no youtube
6. No copyrighted material
    * can use things licensed for reuse, open-source, creative commons licensed images
7. No changing after wiki freeze

# HTML
* no need to use head tag when writing new html files
* should start and end with html tags
    * mediawiki will take all the different html groups and put them together

# CSS
* when trying to use a stylesheet you cannot do it the traditional way of using the link tag
and linking to stylesheet
* you need to make a new template
    * syntax for making a new template:
        * type in standard website url: https://2021.igem.org/Team:TEAM_NAME
        * follow with Template:TEAM_NAME/TEMPLATE_NAME
        * end url looks like:
            * https://2021.igem.org/Template:TEAM_NAME/TEMPLATE_NAME
        * you can then edit the template by clicking the edit page button
* when trying to use a template for a css stylesheet you need to use html and style tags
    * example css stylesheet:
        <html>
        <style>
            p {
                color: red;
            }
        </style>
        </html>
    * ALL CSS STYLES NEED TO BE BETWEEN STYLE TAGS
* to use the stylesheet you need to insert the template into the page you want BEFORE THE HTML TAG
* to use template:
    * {{Template:TEAM_NAME/TEMPLATE_NAME}}
* rest of the html can go after the template call

# MISC
* the standard interface is very cumbersome to edit the wiki with
    * when making a change to ex. a stylesheet, it will take several minutes to update the main page
    * if it does not update when you refresh, you can press edit on the page you want to see the change on, then save
    * site should be updated now
* Only one person should edit the site through the iGEM server, at a time

# Uploading files
* Go to wiki tools --> upload files
* choose the file you want to upload and MAKE SURE ITS A DECENT SIZE IF ITS AN IMAGE NOT 5000x3000 pixels
	* if you need to change the image size you could go to paint and resize it if it's not a transparent photo
	* or use illustrator/inkscape and make sure to have the "maintain aspect ratio" box marked
* after choosing your file then under destination file write "T--UCSC--filename.extension"
  * make sure filename is descriptive and extension is one of the permitted file types
* In summary add which page the image will end up in
* Click upload file 

# Using files
* go to special pages and down to file list
* you could search for media name and click on the "(file)" link
* Copy the url the file link takes you to and paste it into an image tag or whatever tag of the media you're trying to insert

# USEFUL LINKS
* https://2020.igem.org/Team:BITSPilani-Goa_India/Software#iGEMWikiSyncGithubAction
* https://2019.igem.org/Team:Tec-Chihuahua/Wiki
* http://2016.igem.org/Team:Peshawar/Wiki
* https://github.com/iGEM-QSF/igem-wiki
* https://2019.igem.org/Team:US_AFRL_CarrollHS/WikiGuide
