# CARRENT Car Rental and Leasing

CARRENT Car Rental and Leasing site is for those individuals and companies who need additional useful services while renting or leasig the car in a number of cities (Los Angeles, San Fransisco, Washington and Boston) in the US.

The site will be targeted to those who want to eliminate time-consuming process of renting or leasing a car, i. e. picking up a car, returning it to the desired location or filling up the tank before returning the car.
    ![Web Site on the common screen sizes](assets/img/media/screenshot.png)

## Features

- __Navigation Bar__

    -  Featured on all four pages, the full responsive navigation bar includes links to the Logo, Rent and Leasing pages, Why CARRENT? section of the Home Page and Sign Up page and is identical in each page.
    - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

    ![Nav Bar](assets/img/media/nav-bar.png)

- __The Footer__ 

    - The footer section includes links to the relevant social media sites for CARRENT. The links will open to a new tab to allow easy navigation for the user. It encourages them to keep connected via social media.
    - The footer also contains information about CARRENT address and openning hours.
    
    ![Footer](assets/img/media/footer.png)

- __Home Page__ 

    - the Main Image section
        - Contains Call to Action Section. 
        - Consists of two car images that are links to "Rent a Car" and "Lease a Car" site pages. These allows the user to choose between two optins, whether to rent or lease the car.

    ![Hero Image](assets/img/media/hero-image.png)

    - The firm ethos section
        - Contains the CARRENT hero image and slogan, which describes shortly the main goal of the firm.
        - Allows the user to see all the benefits of CARRENT service by clicking on "How it works button" which refers to appropriate section of the HOME PAGE.

    ![Firm Ethos](assets/img/media/firm-ethos.png)

    - Location section
        - Contains gallery of cities' images wehre CARRENT officies are presented.
        - This section is valuable to the users as they will be able to easily identify where they can use CARRENT service.

    ![Locations](/assets/img/media/locations.png)

    - How it works section
        - Allows the user to see the benefits of using CARRENT services as compared to other competitors. 
        - The user will see the value of signing up to CARRENT site.

    ![How it Works](assets/img/media/how-it-works.png)

    - Why CARRENT? section
        - Shows clearly why people choose CARRENT Car Rental and Leasing company.
        - Contains a number of customers reviews where the describe their experience whit CARRENT

    ![Why People Choose Our Company?](assets/img/media/why-carrent.png)

- __Cars For Rent Page__

    - Comprise a form for customers which intend to rent a car.
    - There are several mandatory and intuitively obvious fields that user have to fill in to book a car.

![Rent a Car](assets/img/media/rent-page.png)

- __Cars For Lease Page__

    - Comprise a form for customers which intend to lease a car.
    - There are several mandatory and intuitively obvious fields that user have to fill in to get lease proposal.

![Lease a Car](assets/img/media/lease-page.png)

- __The Sign Up Page__
    - This page will allow the user to get signed up to CARRENT to become a customer. 
    - The user will be asked to submit their full name and email address.
    - Also there is a possibility to quick register via visitor Facebook or Google account.

![Sign Up](assets/img/media/sign-up.png)

## Testing

### General

| **Feature**                    |                         | **Test**      | **Outcome**                                                                                                              | **Pass/Fail** |
|--------------------------------|------------------------------|---------------|--------------------------------------------------------------------------------------------------------------------------|---------------|
| Navigation bar                 | Main logo link               | Functionality | Clicking the link on any page redirects to the home page                                                                 | Pass          |
|                                | Menu items                   | Functionality | Clicking any menu link redirects to the appropriate page                                                                 | Pass          |
|                                |                              | Style         | Menu item of current page is underlined                                                                                  | Pass          |
|                                |                              | Style         | Hover effect makes menu item underlined on any page                                                                      | Pass          |
|                                | Navigation bar appearance    | Style         | Looks the same on any page                                                                                               | Pass          |
| Footer                         | Social media links           | Functionality | Clicking FB, Twitter, Youtube and Instagram links redirects to appropriate site and open in a new window                 | Pass          |
|                                | Footer appearance            | Style         | Looks the same on any page                                                                                               | Pass          |
| Main page                      | Call to action (cat) section | Functionality | Clicking RENT or LEASING link redirects to RENT or LEASING page respectively                                             | Pass          |
|                                | Main image section           | Functionality | Clicking HOW IT WORKS button redirects to HOW IT WORKS SECTION of the main page                                          | Pass          |
|                                | Embedded map section         | Functionality | Embedded Google map is interactive                                                                                       | Pass          |
| Rent, Leasing and Signup pages | Form field                   | Functionality | All form fields work correctly, in accordance with their type                                                            | Pass          |
|                                | Form field                   | Functionality | Each field requires entry before submitting the form                                                                     | Pass          |
|                                | Form field                   | Style         | Hover effect changes border color of any field from white to green                                                       | Pass          |
|                                | Submit button                | Functionality | Clicking submit button sends all the information provided by the user to dedicated server                                | Pass          |
|                                | Submit button                | Style         | Hover effect makes submit button more vivid                                                                              | Pass          |
| Gallery section                | Photos                       | Style         | The dimensions of the photos where chosen in such a way (no special css-style) that their set formed a regular rectangle | Pass          |
| Site                           | All pages                    | Functionality | All site functions work correctly and the same in browsers that have different engines, i.e. Chrome, Firefox and Safari  | Pass          |
|                                |                              | Style         | The site appearance is the same in browsers that have different engines, i.e. Chrome, Firefox and Safari                 | Pass          |
| Site responsiveness            | All pages                    | > 1200px      | Look good and function on the chosen screen size using the Chrome devtools toolbar                                       | Pass          |
|                                |                              | <= 1200px     | Look good and function on the chosen screen size using the Chrome devtools toolbar                                       | Pass          |
|                                |                              | <= 992px      | Look good and function on the chosen screen size using the Chrome devtools toolbar                                       | Pass          |
|                                |                              | <= 768px      | Look good and function on the chosen screen size using the Chrome devtools toolbar                                       | Pass          |
|                                |                              | <= 480px      | Look good and function on the chosen screen size using the Chrome devtools toolbar                                       | Pass          |


### Validator Testing

- HTML 
    - Main page - no errors were returned when passing through the official [W3C validator - index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgennadiy-gaysha.github.io%2Fportfolio_project_1%2Findex.html)
    - Rent page - no errors were returned when passing through the official [W3C validator - rent.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgennadiy-gaysha.github.io%2Fportfolio_project_1%2Frent.html)
    - Leasing page - no errors were returned when passing through the official [W3C validator - leasing.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgennadiy-gaysha.github.io%2Fportfolio_project_1%2Fleasing.html)
    - Gallery page - no errors were returned when passing through the official [W3C validator - gallery.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgennadiy-gaysha.github.io%2Fportfolio_project_1%2Fgallery.html)
    - Signup page - no errors were returned when passing through the official [W3C validator - signup.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgennadiy-gaysha.github.io%2Fportfolio_project_1%2Fsignup.html)
- CSS 
    - style.css - no errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fgennadiy-gaysha.github.io%2Fportfolio_project_1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accessibility
    - I confirmed that the colors and fonts chosen are easy to read and accessible by running it through Lighthouse in Devtools

![Lighthouse](assets/img/media/Lighthouse.png)

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found [here](https://gennadiy-gaysha.github.io/portfolio_project_1/)
     
## Credits

### Content

### Media
