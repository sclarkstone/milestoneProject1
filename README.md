# TOPDOGS

This site is targeted at dog lovers to view photos and brief profiles of other dogs from around the world. The site also offers the opportunity for users get involved and to submit their own dog to be published on the site for other users to admire. 

## Features

### Home page

* Navigation bar

    * Featured on all three pages, the full responsive bar includes Logo (links to homepage), home page, gallery and contact page and is identical in each page to allow for easy navigation.
    * This section will allow the user to easily navigate between pages without having to revert back to the previous page via the browsers back button.
    * The navigation bar uses a collapsed 'hamburger' style for the link on mobile devices and smaller screen sizes. 

* Header top (home page main image)

    * The home page main image is a photograph made up of dogs so that users can immediatly visualise the context of the site.
    * The image has an overlay with text that describes the exact purpose of the site
    * the image is repeated horizontally so that on larger screens it gives the illusion of more dogs. 

* Header bottom

    * The header bottom provides details on how a user can get involved with the site with a button directing them to the contact page.
    * Another image of a dog provides further context of what the site is about.
    * The header bottom is responsive to screen size and will adjust accordingly.

* Footer

    * The footer section is repeated across all 3 pages for consistancy so the user can become comfortable with the layout no matter which page they are on.
    * The footer contains links to social media accounts that open in new windows so that they can easily go back to the page they were on.

### Gallery page


### Contact page

## Potential future features

## Testing

* ['https://material.io/resources/color/#!/?view.left=1&view.right=1&primary.color=557a95&secondary.color=33691E'] used to check accessibility of text colours on background colours. Also used to find complemetary colours. This is where i decided on my 2 shades of blue with white text. As the result was that black was not legible on these shades of blue. 


### Validator testing

* HTML using W3C validator - index.html

    * 'Warning: Attribute <title is not serializable as XML 1.0.' - on reviewing code there was a missing closing tag for the custom style sheet. corrected this by adding the closing tag '/>', re run through validator and issue was resolved. 

    * 'Error: End tag nav seen, but there were open elements.' - on looking at the code i had a div that was opened inside of the nav but closed outside. so i moved the closing div inside of the nav. re run through validator and the issue was resolved.

    * 'Error: Stray start tag script'. after looking at code i noticed that the script tag was outside of the body tag. moved the script tag to be inside the body closing tag so still at the bottom of the page. re run validator and the issue was resolved.

    * After correcting the above errors and re running the w3c validator the following message came 'Document checking completed. No errors or warnings to show'.

* HTML using W3C validator - gallery.html

    * 'Error: Stray end tag head.' on looking at the code i could see a duplicate closing head tag. i removed the duplicate. re run the validator and the issue was resolved. 

    * 'Error: Duplicate ID card.' 

* CSS

    * No errors were found when passing through the offical (Jigsaw) validator

### Bugs

* font awesome was not loading images and giving an error of 'Failed to load resource: the server responded with a status of 404'. On further investigation i found that i was using the CSS link (<link href="/your-path-to-fontawesome/css/fontawesome.css" rel="stylesheet">) with a non existant pathway, rather then the hosted CDN link. I was able to correct this issue by taking out the incorrect CSS link and replaing it with the CDN link.

* After publishing the site to github pages none of the images loaded and gave an error of 'Failed to load resource: the server responded with a status of 404 ()'

* After publishing the site to github pages none of the images loaded and gave an error of 'Error with Permissions-Policy header: Unrecognized feature: 'interest-cohort'.'

* After publishing the site to github pages on the developer tools an error was present. 'Failed to load resource: /favicon.ico:1 the server responded with a status of 404 ()'. After reading about the error on GitHub comminity i found the issue to be that a favicon needed to placed in the header

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:

* In the GitHub repository, navigate to the Settings tab
* Select Pages on left side menu
* Select the Master Branch
* Click save
* The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://sclarkstone.github.io/milestoneProject1/

## Credits

### Layout
* git hub - code institute/gitpod-full-template

* bootstrap V5

    * nabar
    * grid layout with rows and columns
    * form controls
    * gallery cards
    
* Code institute course. Specially the 'Love Running' tutorial gave me the inspiration and guidance for the layout of this site.

### Content

* The icons in the footer were taken from Font awesome

* google fonts was used to give the project a more professional and unique feel. Google fonts gave fonts that go together and as i had already seen the Lanto font in use on the Code institute 'love running' project and felt it fit in well with my project i went with Lant and Oswald. 

### Media

* The photos used throughout the site are of my own dog (Groot) and Friends dogs from Andys woodland walks where my dog attends. Permission form the Owner, Andrew was granted before use. 
