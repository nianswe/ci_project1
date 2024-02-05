# The Treetop Bungalows

The Treetop Bungalows web page, homepage for a fictitious hotel with bungalows located up in the pine trees, and to make it easy to find for people who love the nature and whould like to stay temot in the forest but with full service and amenities. 

![Responsice Mockup](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_mockup.png)

## Features 

- Background image behind navigation bar, footer and the content in the pages, makes a visiable effect when content is little transparent.

- Booking schedule in booking form macke it easy to choose from and to dates you will stay

- Information with description about your stay and photos what you can do in the area. 

- The Book Now Banner on landing page and about page is easy to inactivate or edit with information content for temporary campains.

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_navbar.png)

- __The landing page image__

  - The landing have one information teaser and a Book Now! button
  

![Landing Page](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_landing.png)

- __The Treetop Bungalows About__

  - The Treetop Bungalows About page

![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_about.png)

![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/about1.png)
![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/about2.png)
![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/about3.png)
![The Treetop Bungalows](https://github.com/nianswe/ci_project1/blob/main/assets/images/about4.png)

- __Book Now __

  - This page allows the user to check the availability to stay by filling the form with date, name and email address and submit.

![Book Now](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_booknow.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites. The links will open to a new tab to allow easy navigation for the user. 
  - The footer social media links will be available on the bottom except for screens with height smaller than 720px.

![Footer](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_footer.png)

- __About__

  - The about page will provide information to the user about the bungalows. 
  
![About](https://github.com/nianswe/ci_project1/blob/main/assets/images/the_treetop_bungalows_about.png)

## Testing 

- All links in navigation menu and nav-toggle tested and verified.
- Social networks links in footer ar tested, opens in new tab in browser, noopener rel attribute added.
- Google Chrome Development Tools are used for responsive page testing.
    - All availabe screen resolutions are tested on all pages.

    - Navigation toogle menu, will be present on screens with width up to 768px.
    - Horizontal navigation nenu will be present on screens wider than 768px.

    - Book Now! button on landing page, will be present on screens with width up to 768px.
    - Book Now Banner will be present and replace Book Now botton on screens wider than 768px.

    - Footer with Social media links and Copyright will be hidden on screen height up to 768px, needs to scroll down to be viewed, because form on Book now page will take up all space.
  
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

I created a local git repository using 'git init' and added it to the staging area with git 'add .', I committed to the local repository  using 'git commit -m 'message'' and pushed to the remote repository at GitHub with 'git push'.

The live link can be found here - https://nianswe.github.io/ci_project1/index.html 

## Credits 

### Content 
    - The photos used on the home and sign up page are from [Pexels] https://www.pexels.com/:
    - The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
    - Fonts on all pages ar from [Google Fonts] (https://fonts.googleapis.com/)

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