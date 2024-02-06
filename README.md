# The Treetop Bungalows

Treetop Bungalows website, website for a fictional hotel with bungalows located up in the pine trees, and to make it easy to find for people who love nature and want to live in the forest but with full service and amenities.

![Responsice Mockup](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_mockup.png)

## Features 

- Background image behind navigation bar, footer and the content in the pages, makes a visiable effect when content is little transparent.

- Booking schedule in booking form make it easy to choose from and to dates customer will stay.

- Information with description about your stay and photos what you can do in the area. 

- The Book Now Banner on landing page and about page is easy to inactivate or edit with information content for temporary campains.

### Existing Features

- __Navigation Bar__

  - Navigation bar available in the header to the right on all pages, it includes links to Home, Book now and About pages.
  - On small screens with width up to 768px, the menu links are replaced by a menu toogle to make it easy to navigate between the pages across on all devices without having to revert back to the previous page via the 'back' button. 

![Nav Bar](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_navbar.png)

- __The landing page__

  - The landing have one information teaser and a Book Now! button on screens width up to 768px, on wider screens it's replaced by a larger Book Now Banner with more text informatin content. 
  
![Landing Page Mobile](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bunga_landing_m.png)
![Landing Page](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_landing.png)

- __The About page__

  - The Treetop Bungalows About page will provide information to the user about the bungalows, inspirational information and pictures of activities in the local area.

![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_about.png)

![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/about1.png)
![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/about2.png)
![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/about3.png)
![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/about4.png)

- __The Book Now page__

  - The Book now page allows the user to check the availability to stay by filling the form with date, name and email address and send, the function to send an email is not present, it may be developed in future release.

![Book Now](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_booknow.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites. The links will open to a new tab to allow easy navigation for the user. 
  - It will always be available at the bottom except for screens smaller than 720px in height, when it is available by scrolling down so as not to hide relevant content.

![Footer](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_footer.png)

## Testing 

All links in the navigation menu and toogle are tested and verified.
- Links to social networks in the footer are tested, open in a new tab in the browser, noopener rel attribute has been added.
- Google Chrome's development tools are used for responsive page testing.
  - All available screen resolutions are tested on all pages.

  - Navigation toogle menu, will be present on screens with width up to 768px.
  - Horizontal navigation will be present on screens wider than 768px.

  - Book now! button on the landing page, will be present on screens with width up to 768px.
  - The Book Now banner will be present and replace the Book Now button on screens wider than 768px.

  - Footer with links to social media and copyright information will be hidden at screen height up to 768px, must be scrolled down to see, as the form on the Book page now takes up all the space.
  
### Validator Testing 

- HTML
  - No errors were returned when passing through the official
  ![W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnianswe.github.io%2Fci_project1%2F)
  ![W3C Validator index.html](https://github.com/nianswe/ci_project1/blob/main/assets/images/w3_val1.png)
  ![W3C Validator index.html](https://github.com/nianswe/ci_project1/blob/main/assets/images/w3_val2.png)
  ![W3C Validator index.html](https://github.com/nianswe/ci_project1/blob/main/assets/images/w3_val3.png)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fnianswe.github.io%2Fci_project1&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
  ![W3C CSS Validator style.css](https://github.com/nianswe/ci_project1/blob/main/assets/images/w3_css_val.png)

- Lighthouse performance scoring
  - Lighthouse performance scoring: The Treetop Bungalows

  ![Lighthouse performance scoring](https://github.com/nianswe/ci_project1/blob/main/assets/images/lighthouse.png)

### Unfixed Bugs

No known bugs.

## Deployment

I created a local git repository using 'git init' and added it to the staging area with git 'add .', I committed to the local repository using 'git commit -m 'message'' and pushed to the remote repository at GitHub with 'git push'.

The live link can be found here - https://nianswe.github.io/ci_project1/index.html 

## Credits 

### Content 
- The photos used on the home and sign up page are from [Pexels] https://www.pexels.com/, the background image is borrowed from the existing commercial websitepage https://www.hyssnaforestresort.com/sv/
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Fonts on all pages are imported from [Google Fonts] (https://fonts.googleapis.com/)

  Photos: 
    https://www.hyssnaforestresort.com/sv/
      media-webDJI_0268.jpg
           
    https://www.pexels.com/:  
      pexels-darius-krause-2254030.jpg
      pexels-harrison-haines-7615952.jpg
      pexels-isaac-mitchell-15265020.jpg
      pexels-leon-natan-4549074.jpg
      pexels-life-of-pix-101533.jpg
      pexels-olof-nyman-988622.jpg
      pexels-sem-steenbergen-3621344.jpg

### Media

    Insperation and code:
        Love Running:   https://github.com/Code-Institute-Solutions/love-running-v3
            - Nav toggle menu, to hide menu on smaler screens.
            - Social Network section in footer.