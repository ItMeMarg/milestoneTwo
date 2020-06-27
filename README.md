# **Brew It Right ☕️** 
Thanks for stopping by my Interactive Frontend Development project! Please read through this README for some background. Reach out with questions, comments, or suggestions through my Github page. Enjoy! 🤓 

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
    + [Example Variables](#example-variables)
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
    + [Using Github](#using-github)
    + [Ran Locally](#ran-locally)
- [Credits](#credits)

# UX
## Project Goals
The goal of this project is to give coffee-lovers a chance to brew in a barista's shoes. This untimed memory-style interactive game allows users to mark increasingly difficult orders and see if their memory's served them right, or if they're in need of some caffeine themself! The site has to echno the look of modern coffee shops with minimalist, clean design, and provide enough instruction for users to successfully move through the game.

### User Goals
- A game that is straightforward enough to enjoy while maintaining a sense of challenge. 
- Design that is neither distracting nor bland, but that keeps an attractive balance. 
- A toggle button so users can reference instructions/links as needed and then hide elements to limit distractions during gameplay.
- Gameplay capability on different devices. 
- A contact button so users can submit feedback.  

### User Stories
- As a user, I expect an entertaining game.
- As a user, I expect an appropriately designed game.
- As a user, I expect to be able to play this game on different devices. 

- Susan, Seattle
   > "Sure, I make my own coffee every day now that we can't leave the house with everything that's going on. But it's just not the same. As a user, I want to feel the same fear of memory loss as the sweet baristas who mark my small hazelnut breve americano."

- Soo-ah, Seoul
   > "Every year I visit Seattle to experience coffee culture. Since I'm not able this year, it is important for me, as a user of this game, to have the visuals of a coffee shop." 

- Eike, Frankfürt 
   > "Sometimes I want to use my phone to play memory games while I'm enjoying my coffee on the couch. Sometimes I like to play a game while taking a break from work at my desk. As a user, I need to be able to seamlessly enjoy this game on my phone or laptop, without major changes to the game flow."
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

![Slate Coffee Roasters logo](https://github.com/ItMeMarg/milestoneTwo/blob/master/assets/images/slatecoffeelogoFont.jpg?raw=true)

![Victrola Coffee Roasters logo](https://github.com/ItMeMarg/milestoneTwo/blob/master/assets/images/victrolalogoFont.jpg?raw=true)

I found [Yanone Kaffeesatz](https://fonts.google.com/specimen/Yanone+Kaffeesatz?preview.text=brew+it+right&preview.text_type=custom&vfonly&category=Sans+Serif&selection.family=Montserrat|Yanone+Kaffeesatz:wght@300#standard-styles), of which Google Fonts notes the "Bold is reminiscent of 1920s coffee house typography, while the rather thin fonts bridge the gap to present times." By using differing weights within the project, I'm able to provide user experience consistancy through the site while maintaining a visually attractive design. 

### Icons
Industry standard icons for navigation are used in this project, in order to keep things simple for users. 

### Colors
![Brew It Right color palette](https://github.com/ItMeMarg/milestoneTwo/blob/master/assets/images/brewItRight.jpg?raw=true) 
- **Default Background Color**, *#F9F9F9* This off-white allows the other colors to pop without adding busyness to the design. 
- **Accent Color**, *#CAD2C5* This muted mossy green will be used for outlines, where necessary.  
- **Interactive Element Color**, *#84A98C* Clickable interactive elements, including buttons and links, will be this "Dark Sea Green" color. A similiar color can be seen in a newly remodeled Starbucks and an independent local shop.
- **Font color**, *#222725* This soft black allows for a less glaring user experience. Because reading is an important aspect of this game, an easy-to-read color font is necessary. 


![Analog Coffee](https://github.com/ItMeMarg/milestoneTwo/blob/master/assets/images/analogcoffeeColors.jpg?raw=true)

![1st and Pike Starbucks](https://github.com/ItMeMarg/milestoneTwo/blob/master/assets/images/1standpikestarbucksFont.jpg?raw=true)

### Example Variables
- Colors
```
$background: #f9f9f9ff;
$accent: #cad2c5ff;
$interactive: #84a98cff;
$mainfont: #222725ff;
```

- Styling
```
$default-text-shadow: 1px 1px #000;
$default-transition: all 0.2s ease-in-out;
$default-box-shadow: 1px 1px 1px rgba(0,0,0,0.4);
```
# Wireframes
In the early stages of this project, I found drawing a rough sketch of layout and elements to be the most productive. The wireframes for this project live [here](https://github.com/ItMeMarg/milestoneTwo/tree/master/wireframes).

To further improve wireframes, I plan to utilize [Moqups](https://moqups.com/).
# Features
### Already Developed
- eg
- eg
### Future Implementation
- eg
- eg
# Technologies Used
### Languages
- [HTML]()
- [CSS]()
- [JavaScript]()
- [JSON]()
### Tools and Libraries
- [Git]()
- [Bootstrap]()
- [Font-Awesome]()
- [jQuery]()
- [TinyPng]()
- [Coolors](https://coolors.co/u/marg_lundg) - developed color palette
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
### Using Github
### Ran Locally
# Credits 
- [Table of Content generator](https://ecotrust-canada.github.io/markdown-toc/)
- eg