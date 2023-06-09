# Global Warning

## Code Institute: Milestone Project 1

### HTML/CSS Essentials: Static front-end website

![Responsive](/assets/docs/Responsive-Screenshot.png)

[Click here to view the live project.](https://pratimagurav.github.io/global-warning/)

[Click here to view the repository.](https://github.com/PratimaGurav/global-warning)

## Table of Contents:
- [User Experience (UX)](https://github.com/PratimaGurav/global-warning#user-experience-ux)  

- [Features](https://github.com/PratimaGurav/global-warning#features)

- [Technologies Used](https://github.com/PratimaGurav/global-warning#technologies-used)
  
- [Testing](https://github.com/PratimaGurav/global-warning#testing)

- [Deployment](https://github.com/PratimaGurav/global-warning#deployment)

- [Credits](https://github.com/PratimaGurav/global-warning#credits)

- [Acknowledgements](https://github.com/PratimaGurav/global-warning#acknowledgements)
    

## User Experience (UX)

-   ### Site Goals
     Global Warning is an informative front end website explaning the major causes and effects that everyone is facing due to Global Warming. It also describes few solutions which can help maintain the balance. 
     Additionally, it also provides a feature for interested users to signup and receive weekly notifications for any updates to the website. 
     The site is targeted towards everyone to create awareness of the consequences and the measures everyone can take to tackle this global issue. 

-   ### User stories

    -   #### First Time Visitor
        1. To easily understand the main purpose of the site.
        2. To be able to easily navigate throughout the site to find content.
        3. To locate their social media links to see their followings on social media.

    -   #### Returning Visitor
        1. Easy access to the information about the causes, effects and solutions about Global Warming.
        2. To instantly know the navigation.   

    -   #### Frequent User 
        1. To sign up to the Weekly Newsletter to receive updates to the website.
        2. To check to see if there is new information available.

-   ### Design
    -   #### Colour Scheme
        The main colours used are Dark Chocolate, Sinopia, Green Lizard, Deer, Black and White.  
    
    -   #### Typography     
        The Montserrat font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Merriweather font is used for headings with Sans Serif as the fallback.

    -   #### Imagery
        Images are important to strike and catch users attentions. Large background hero image is used. Also images are used to describe the causes, effects and solutions. 

*   ### Wireframes

    -   Landing (Home) Page Wireframe - [Landing-Page](assets/docs/Balsamiqa.pdf)

    -   Causes, Effects and Solution Pages Wireframe - [Causes,Effects,Solutions](assets/docs/Balsamiqb.pdf)

    -   Sign Up Page Wireframe - [Sign-up](assets/docs/Balsamiqc.pdf)
    
## Features

 ### Existing Features

   - __Navigation Bar__

     - Featured on all pages, the full responsive navigation bar includes links to the Logo, Home page, Causes, Effects, Solutions and Sign Up and is identical in each page to allow for easy navigation.
     - This section will allow the user to easily navigate from page to page across all devices without having to revert to the previous page via the ‘back’ button.
  
      ![Nav Bar](/assets/docs/nav-bar.png)

   - __The landing page image__

     - The landing includes a photograph with text below to allow the user to know about Global Warming.

      ![Landing Page](/assets/docs/Hero-Image-Content.png)

   - __The Grid__

     - The grid has images, brief information and responsive nagivation to the Causes, Effects and Solutions pages.

     ![The Grid](/assets/docs/grid.png)

   - __The Footer__ 

     - The footer section includes link to a short video giving more information about Global Warming. The link will open to a new tab to allow easy navigation for the user.    
     - It also includes links to the relevant social media sites for Global Warning. These links will also open to a new tab to allow easy navigation for the user. And is valuable to the user as it encourages them to stay connected via social media.
     - The footer is identical on each page for easy access.

     ![The Footer](/assets/docs/footer.png)

   - __The Causes__ 

     - This page inlcudes explanation and the major causes of Global Warming.
     - It also includes supportive images and short description about each making it easier for the user to understand.

     ![The Causes](/assets/docs/Causes-a.png)
     ![The Causes](/assets/docs/Causes-b.png)

   - __The Effects__ 

     - This page inlcudes explanation and the major effects of Global Warming.
     - It also includes supportive images and short description about each making it easier for the user to understand.

     ![The Effects](/assets/docs/Effects-a.png)
     ![The Effects](/assets/docs/Effects-b.png)

   - __The Solutions__ 

     - This page inlcudes explanation and few solutions of Global Warming.
     - It provides simplified ways to tackle the issue which can be followed by each one in their day to day life.

     ![The Solutions](/assets/docs/Solutions-a.png)
     ![The Solutions](/assets/docs/Solutions-b.png)

   - __The Sign Up Page__

     - This page will allow the user to get signed up for weekly newsletter. The user can sign up by providing basic details like full name, email address and comments.
     - Once signed up the user will be receive latest updates about the website.

     ![The Sign Up](/assets/docs/Sign-up.png)

- ### Future Enhancements 

    - Add blogs and live news for latest updates.
    - Add information about upcoming events to spread awareness and raise funds for affected areas/regions.

## Technologies Used

- ### Languages Used

  -   [HTML5](https://en.wikipedia.org/wiki/HTML5)
  -   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
  -   [MARKDOWN](https://en.wikipedia.org/wiki/Markdown)

- ### Frameworks, Libraries & Programs Used

  - [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the font into the style.css file which is used on all pages throughout the project.
  - [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
  - [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
  - [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.   
  - [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the wireframes during the design process. 
    
## Testing

  The [W3C Markup Validator](https://validator.w3.org/nu/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) were used to validate every page of the project to ensure there were no syntax errors in the project.

  - Following errors were found and fixed while validation:-  
    - (HTML) No space between aria label attributes and stray end tags.   
      - [Error](assets/docs/html-error.png) 
      - [Results](assets/docs/HTML-validator.png)
    
    - (CSS) Value Error : left only 0 can be a unit. You must put a unit after your number : 5    
      - [Error](assets/docs/css-error.png)
      - [Results](assets/docs/CSS-Validator.png)  

  - ### Lighthouse Results

    - __The Landing(Home) Page__
       - [Desktop](assets/docs/LHDindex.png)
       - [Mobile](assets/docs/LHMindex.png)

    - __The Causes__
       - [Desktop](assets/docs/LHDcauses.png)
       - [Mobile](assets/docs/LHMcauses.png)

    - __The Effects__
       - [Desktop](assets/docs/LHDeffects.png)
       - [Mobile](assets/docs/LHMeffects.png)

    - __The Solutions__
       - [Desktop](assets/docs/LHDsolutions.png)
       - [Mobile](assets/docs/LHMsolutions.png)

    - __The Sign-Up__
       - [Desktop](assets/docs/LHDsignup.png)
       - [Mobile](assets/docs/LHMsignup.png)

 - ### Further Testing

   -   The Website was tested on Google Chrome, Microsoft Edge, Safari and Mozilla Firefox browsers.
      - On Firefox browser, the form on Sign-Up page was distorted.
      *This was fixed by adjusting the height of the white background.* 
      [Commit message](/assets/docs/form-styling)
   -   The website was viewed on a variety of devices such as Desktop, Laptop, iPad, iPhone 6, 7 & 8.
       - On some mobile devices the Hero Image on home page and sign-up page pushes the size of screen out more than any of the other content on the page.
       *This was fixed by adjusting the height of the hero image.* 
       [Commit message](/assets/docs/hero-image)
   -   A large amount of testing was done to ensure that all pages were linking correctly.
   -   Friends and family members were asked to review the site to point out any bugs and/or user experience issues.

  - ### Known Bugs

    - There are no outstanding issues found.  

## Deployment

 - ### GitHub Pages

  The project was deployed to GitHub Pages using the following steps...

   1. Log in to GitHub and locate the [GitHub Repository](https://github.com/PratimaGurav/global-warning)
   2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
   3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
   4. Under "Source", click the dropdown called "None" and select "Main Branch".
   5. Click "Save".
   6. The page will automatically refresh and provide you with a link to the Live GitHub Page for the repository.

  The Page can sometimes take longer to load and go live. This is an expected behaviour. 


 - ### Making a Local Clone

    1. Log in to GitHub and navigate to the [GitHub Repository](https://github.com/PratimaGurav/global-warning.git)
    2. To clone the repository using HTTPS, click Code and copy the address. 
    ![Clone Repository](/assets/docs/Clone.png)
    3. Navigate to Git Bash and clone the repository. 
    ![Clone-Command](/assets/docs/git-clone.png)
    4. Press Enter and your local clone will be created. 
    ![Clone-Output](/assets/docs/Clone-output.png)

## Credits

  - ### Code
    - [Love Running](https://github.com/PratimaGurav/love-running) walkthrough project was referred for designing of the webpages and technical implementation.
    - [W3 Schools](https://www.w3schools.com/) was used throughout the project majorly for styling and alignment purpose.

  - ### Content
    The following websites were referred to gather information about the project.  
    - [National-Geograhic](https://www.nationalgeographic.com/environment/article/global-warming-overview)
    - [Wikipedia](https://en.wikipedia.org/wiki/Climate_change)
    - [Tree-Hugger](https://www.treehugger.com/how-to-reduce-global-warming-1203897)  

  - ### Media
    All images used within this site are free and do not incur any copyright issues. These images have been provided by following websites:
    - [Pexels](https://www.pexels.com/)
      - [Blue-Globe](https://www.pexels.com/photo/blue-globe-with-plastic-4167579/)
      - [Garbage](https://www.pexels.com/photo/photo-of-landfill-2768961/)
      - [Industrialization](https://www.pexels.com/photo/photography-of-factory-929385/)
      - [Oil-Driling](https://www.pexels.com/photo/gray-industrial-machine-during-golden-hour-162568/)
      - [Deforestation](https://www.pexels.com/photo/photo-of-person-using-chainsaw-4205989/)
      - [Hurricane](https://www.pexels.com/photo/big-waves-under-cloudy-sky-753619/)
      - [Wildfires](https://www.pexels.com/photo/forest-on-fire-51951/)
      - [Recycle](https://www.pexels.com/photo/green-star-on-white-paper-6990568/)
      - [Switch-Off](https://www.pexels.com/photo/man-turning-off-light-switch-8107167/)
      - [Cycling](https://www.pexels.com/photo/people-riding-bicycles-on-road-2361108/)
      - [Led-Light](https://www.pexels.com/photo/white-led-light-2249063/)
      - [Tree-Plantation](https://www.pexels.com/photo/person-holding-green-cactus-plant-4505161/)
      - [Classroom](https://www.pexels.com/photo/man-in-gray-dress-shirt-and-black-pants-standing-beside-boy-in-blue-long-sleeve-shirt-5212703/)
      - [Planet-Earth](https://www.pexels.com/photo/planet-earth-first-poster-on-a-concrete-post-3302183/)

    - [Stockvault](https://www.stockvault.net/)
      - [Earth-Protection](https://www.stockvault.net/photo/263920/earth-protection)
      - [Industry-Smoke](https://www.stockvault.net/photo/138017/global-warming-factory-pollution)
      - [Melting-iceberg](https://www.stockvault.net/photo/146012/icebergs)
      - [Earth-Friendly](https://www.stockvault.net/photo/229086/earth-friendly-shows-conservation-environmental-and-natural)
  
    - [Pixabay](https://pixabay.com/)
        - [Fertilization](https://pixabay.com/photos/tractor-fertilizer-pesticide-spray-4217686/)
        - [Climate-change](https://pixabay.com/illustrations/climate-change-global-warming-2063240/)
        - [Thermometer](https://pixabay.com/photos/thermometer-summer-hot-heat-sun-3581190/)
        - [Woolly-Mammoth](https://pixabay.com/photos/woolly-mammoth-animal-prehistoric-2722882/)

    - [Unsplash](https://unsplash.com/)
        - [Melting-Glaciers](https://unsplash.com/photos/SH_oYiwg224)

## Acknowledgements

  -   My Mentor for continuous helpful feedback and advises.
  -   Slack community and my fellow slackers for being available at any given time of the day.


## [BACK TO TOP](https://github.com/PratimaGurav/global-warning#global-warning)