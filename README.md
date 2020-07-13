# **BrewRight ☕️** 
Thanks for stopping by my Interactive Frontend Development project! Please read through this README for some background. Reach out with questions, comments, or suggestions through my GitHub page. Enjoy! 🤓 

# Content 🗂
- [UX](#ux)
  * [Project Goals](#project-goals)
    + [User Goals](#user-goals)
    + [User Stories](#user-stories)
    + [Site Owner Goals](#site-owner-goals)
  * [User Expectations and Requirements](#user-expectations-and-requirements)
  * [Design Choices](#design-choices)
    + [Fonts](#fonts)
    + [Icons](#icons)
    + [Colors](#colors)
- [Wireframes](#wireframes)
- [Features](#features)
    + [Already Developed](#already-developed)
    + [Future Implementation](#future-implementation)
- [Technologies Used](#technologies-used)
    + [Languages](#languages)
    + [Tools and Libraries](#tools-and-libraries)
- [Testing](#testing)
    + [Test Planning](#test-planning)
    + [Testing Stories](#testing-stories)
  * [Overall](#overall)
    + [Responsiveness](#responsiveness)
    + [Design](#design)
    + [Features](#features-1)
- [Bugs](#bugs)
    + [Already Found and Squashed](#already-found-and-squashed)
      - [error type](#error-type)
    + [Currently Known and Hunting](#currently-known-and-hunting)
      - [error type](#error-type-1)
- [Deployment](#deployment)
    + [Using GitHub](#using-gitHub)
    + [Running Locally](#running-locally)
- [Credits](#credits)

# UX
## Project Goals
The goal of this project is to give coffee-lovers a chance to brew in a barista's shoes. This untimed memory-style interactive game allows users to mark increasingly difficult orders and see if their memory's served them right, or if they're in need of some caffeine themselves! The site has to echo the look of modern coffee shops with minimalist, clean design, and provide enough instruction for users to successfully navigate the game.

### User Goals
- A game that is straightforward enough to enjoy while maintaining a sense of challenge. 
- Design that is neither distracting nor bland, but that keeps an attractive balance. 
- A toggle button so users can reference instructions/links as needed and then hide elements to limit distractions during gameplay.
- Gameplay capability on different devices. 
- A contact button so users can submit feedback.  

### User Stories
- As a user, I expect an entertaining game.
    > Susan, Seattle: *Sure, I make my own coffee every day now that we can't leave the house with everything that's going on. But it's just not the same. As a user, I want to feel the same fear of memory loss as the sweet baristas who mark my small hazelnut breve americano.*

- As a user, I expect an appropriately designed game. 
   > Soo-ah, Seoul: *Every year I visit Seattle to experience coffee culture. Since I'm not able this year, it is important for me, as a user of this game, to have the visuals of a coffee shop.*

- As a user, I expect to be able to play this game on different devices. 
   > Eike, Frankfürt: *Sometimes I want to use my phone to play memory games while I'm enjoying my coffee on the couch. Sometimes I like to play a game while taking a break from work at my desk. As a user, I need to be able to seamlessly enjoy this game on my phone or laptop, without major changes to the game flow.*
### Site Owner Goals
- Ensure users enjoy flexing their memory skills while playing barista.
- Receive feedback via page contact form to hear from users. 
- Create an online space that mimics the coffee shop environment. 
## User Expectations and Requirements 
Expectations | Requirements
------------ | -------------
Play instructions are thorough and make sense | Write and present instructions in a  clear, concise manner
Game maintains user interest | Include interactive elements, such as buttons and scrollbars
Contact Form works properly | Contact Form validation allows contact from users yet limits spam
Content is appealing and useful | Design is thoughtful, tested on various devices before deployment

## Design Choices
From font design to color palette, I aimed to mimic the design choices users enjoy when stopping for their favorite caffinated beverage at Seattle coffee shops. 

### Fonts
What's the first thing folks notice before even entering a shop? How the building presents its name--is the logo under- or over-stated, out-of-date ironically or unironically? To pull users in, I searched for a font that strikes a good balance between the two below examples. 

![Slate Coffee Roasters logo](https://github.com/ItMeMarg/milestoneTwo/blob/master/wireframes/fontInspo1.jpg?raw=true)

![Victrola Coffee Roasters logo](https://github.com/ItMeMarg/milestoneTwo/blob/master/wireframes/fontInspo2.jpg?raw=true)

I found [Yanone Kaffeesatz](https://fonts.google.com/specimen/Yanone+Kaffeesatz), of which [Google Fonts](https://fonts.google.com/specimen/Yanone+Kaffeesatz) notes the *Bold is reminiscent of 1920s coffee house typography, while the rather thin fonts bridge the gap to present times.* By using differing weights within the project, I'm able to provide user experience consistancy through the site while maintaining a visually attractive design. 

### Icons
Industry standard icons for navigation are used in this project, in order to keep things simple for users. 

### Colors
![Analog Coffee](https://github.com/ItMeMarg/milestoneTwo/blob/master/wireframes/colorInspo2.jpg?raw=true)

![1st and Pike Starbucks](https://github.com/ItMeMarg/milestoneTwo/blob/master/wireframes/colorInspo1.jpg?raw=true)

![BrewRight color palette](https://github.com/ItMeMarg/milestoneTwo/blob/master/wireframes/colorPalette.jpg?raw=true) 
- **Default Background Color**, *#F9F9F9* This off-white allows the other colors to pop without adding busyness to the design. 
- **Accent Color**, *#CAD2C5* This muted mossy green will be used for outlines, where necessary.  
- **Interactive Element Color**, *#84A98C* Clickable interactive elements, including buttons and links, will be this Dark Sea Green color. A similiar color can be seen in a newly remodeled Starbucks and an independent local shop.
- **Font color**, *#222725* This soft black allows for a less glaring user experience. Because reading is an important aspect of this game, an easy-to-read color font is necessary. 

# Wireframes
In the early stages of this project, I found drawing a rough sketch of layout and elements to be the most productive. The wireframes for this project live [here](https://github.com/ItMeMarg/milestoneTwo/tree/master/wireframes).

Before putting code to IDE, I used [Moqups](https://moqups.com/) to create example pages of features on [mobile](https://github.com/ItMeMarg/milestoneTwo/blob/master/wireframes/mobile-moqupwireframe.png?raw=true), [tablet](https://github.com/ItMeMarg/milestoneTwo/blob/master/wireframes/tablet-moqupwireframe.png?raw=true), and [desktop](https://github.com/ItMeMarg/milestoneTwo/blob/master/wireframes/desktop-moqupwireframe.png?raw=true).

# Features
### Already Developed
- eg
- eg
### Future Implementation
- eg
- eg
# Technologies Used
### Languages
- [HTML5](https://www.w3schools.com/html/html_intro.asp)
- [CSS3](https://www.w3schools.com/css/css_intro.asp)
- [JavaScript](https://www.w3schools.com/js/js_intro.asp)
- [JSON](https://www.w3schools.com/js/js_json_intro.asp)
### Tools and Libraries
- [Git](https://github.com/) - project hosting and deployment
- [Bootstrap v4.5](https://getbootstrap.com/docs/4.5/getting-started/introduction/) - basic formatting and layout
- [Font Awesome v5.13.1](https://fontawesome.com/)
- [GIMP 2.10.20](https://www.gimp.org/) - used to crop and resize images
- [jQuery](https://www.w3schools.com/jquery/jquery_intro.asp)
- [Coolors](https://coolors.co/u/ItMeMarg) - developed color palette
- [Favicon Generator](https://realfavicongenerator.net/)
- [Table of Content generator](https://ecotrust-canada.github.io/markdown-toc/)
# Testing
### Test Planning
### Testing Stories
- eg
- eg
- eg 
- eg
## Overall
### Responsiveness
-  Plan
-  Implementation 
-  Result
-  Verdict
### Design
-  Plan
-  Implementation 
-  Result
-  Verdict
### Features
-  Plan
-  Implementation 
-  Result
-  Verdict
# Bugs 
### Already Found and Squashed
#### error type
- description
- fix
- verdict
### Currently Known and Hunting
#### error type
- description
- fix
- verdict
# Deployment
### Using GitHub
This project resides in [GitHub](https://github.com/ItMeMarg/milestoneTwo); [GitPages](https://itmemarg.github.io/milestonetwo/) hosts the master repository.


To deploy this project, I followed [these steps](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site): 
1.  Selected the *Settings* tab within the project repository.
2.  In the *GutHub Pages* tab, I used the *Source* drop-down menu to select *master branch* as the publising source. 

### Running Locally
After loading the [project repository](https://github.com/ItMeMarg/milestoneTwo) select the *Clone* button to *Open in Desktop* or *Download ZIP*. After opening the unzipped file, execute index.html to load the homepage. 

# Credits 
- eg