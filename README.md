# BLACKROCK CASTLE

In this section, you will include one or two paragraphs providing an overview of your project. Essentially, this part is your sales pitch. At this stage, you should have a name for your project so use it! Don’t introduce the project as a Portfolio project for the diploma. In this section, describe what the project hopes to accomplish, who it is intended to target and how it will be useful to the target audience.

This page is based on my local Castle in Co. Cork Ireland.
I have gathered information and put together a brief history of the castle and what it is being used for now.
![assets/readmeImages](<Screenshot(30).png>)

### Features

![assets/readmeImages](<Screenshot(31).png>)

- **Fixed Navigation Bar**

  - Featured on both pages, the full responsive navigation bar includes links to Home, Location, Reviews, Contact and Gallery and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

- **The hero page**

  - The Hero includes a photograph with text overlay.
  - I took the idea for the overlay from the love running project as it adds that little bit extra.

- **A Brief History**

  - The history page will give the user all the basic history of the castle.
    ![assets/readmeImages](<Screenshot(32).png>)

- **Blackrock Castle Observatory**

  - This section is all about the Observatory.
  - This includes the 10th year anniversary video and a link to the official Blackrock Castle Obsevatory website.
    ![assets/readmeImages](<Screenshot(33).png>)

- **Blackrock Castle Cafe**

  - This section is for the Castle Cafe.
  - In here we have a link to the Blackrock Castle Cafe website and a stinning picture of the front of the cafe.
    ![assets/readmeImages](<Screenshot(38).png>)

- **Blackrock Castle Location**

  - This section is for the location of the Castle.
  - In this section we have a lovely picture off all the Cultural sites around the City and an embeded google maps location.
    ![assets/readmeImages](<Screenshot(34).png>)

- **Trip Advisor Reviews**

  - The reviews section has reviews with 3 star or more from trip advisor.
  - The is valuable to anybody who is thinking of visiting the castle.
  - This widget was made on elfsight.com.
    ![assets/readmeImages](<Screenshot(35).png>)

- **Contacts**

  - The contacts section includes a Contact Form and links to the my email and LinkedIn profile.
  - I used formspree as the backend for this.
    ![assets/readmeImages](<Screenshot(36).png>)

- **Gallery**
  - The gallery will provide the user with supporting images to see what the the castle look like foom many different angles.

### Features I would like to Implement

- Flexbox: I spent most of my time trying to get the responsiveness of my page right. I think with a bit more knowledge of flexbox this could have been easier.
- Hamburger Menu: Again using Overflow and Float made keeping the Nav Bar clean a problem. A hamburger menu would have gotten rid of this for smaller screens.

## Testing

    ![assets/readmeImages](<Screenshot(37).png>)

- I had a big problem withe the media queries. I had most of the pages widths done in PX instead of %. When I corrected that I restarted the media queries. I got most sizes done well but I could easily put another day into getting every size perfect.
- Made a silly mistake and forgot to link the index.css to the gallery.
- Forgot to add font size to nav-title
- Left a space in the mailto which through an error in W3 Validation.
- I had Duplicate ID's for nav-list and href. (25 errors returned when passing through the official W3C validator. There were all for Duplicate ID's)
- I need to remove a value of (relative) on line 82.

- Tested the responsiveness of my site on [Am I Responsive?] (<https://ui.dev/amiresponsive?url=https://josephoconnell.github.io/Blackrock-Castle/>)
-
-

### Validator Testing Working on fixing the issues

- HTML

  - 0 errors returned when passing through the official W3C validator[W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjosephoconnell.github.io%2FBlackrock-Castle%2F)
    ![assets/readmeImages](<Screenshot(28).png>)

- CSS
- 0 errors was found when passing through the official W3C validator for CSS.[(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjosephoconnell.github.io%2FBlackrock-Castle%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
  ![assets/readmeImages](<Screenshot(29).png>)

### Unfixed Bugs

As of yet I have not found any bugs.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - <https://josephoconnell.github.io/Blackrock-Castle/>

### Content and Media Credits

- The text for the Home page was taken from many different websites and reworded to suit my page [Wikipedia] [https://www.bco.ie/] [https://www.castlecafe.ie/] [https://castrumtocastle.com/republic-of-ireland-castles/county-cork-cork-blackrock-castle/] [https://irishhistory.com/architecture-and-monuments/castles/history-of-blackrock-castle-co-cork/]
- For the video I got permition of the videos owner to use on the page [BCO] <https://www.youtube.com/watch?v=97oZNFzkzcM>
- For my Nav Bar I took help from the Love Running Code and made it my own. <https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode>
- For the widet I used elfsight. I used the free version and it comes with a add and watermark [elfsight]<https://elfsight.com/>
- Contact Form: I watched a youtube video on forms and used some of what I learned from the Love Running also. [Bro-Code](https://www.youtube.com/watch?v=HGTJBPNC-Gw) and used <https://formspree.io/> for the backend.

- The icons were taken from [Font Awesome](https://fontawesome.com/)
- The fonts were taken from [Google Fonts](https://fonts.google.com/)
- All images were taken of Google images <https://www.google.com/search?q=blackrock+castle&tbm=isch&source=lnms&sa=X&sqi=2&ved=2ahUKEwj21N3I5qqAAxWjU0EAHWVQAI0Q0pQJegQIDRAB&biw=1920&bih=929&dpr=1>
