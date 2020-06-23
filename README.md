Description
The project is based on a company specialising in 'friendly betting' games, that is; games where users play various
games against each other for money, but mainly for fun and enjoyment. This type of game is also known as pooled betting' 
as it is more similar to a lottery format than traditional betting/gambling, which in reality is against highly qualified 
risk analysts and probably experts.
This project's aim to give users an understanding of the games available, how they can play them, what the rules are
and what sports are covered. Users/fans can navigate by game type or sport. The project was slighly rushed due to only
receiving the 'hard date' for the projects two weeks before due date. Only high level planning (without code) had been done at
that point.
The pages in the project are:
index.html
gametypes.html
sports.html

Links
Wireframes: assets\friendly-bet-wireframes\bmpr
Live site:

UX
The brand colours of Friendly Bet are blue and orange, with a hint of white. The reason for the colour choice is 
that blue denotes trust (important for a site offering social betting games for the first time) and orange 
represents fun. Significantly from a design and UX perspective, blue and orange are complementary pairs on the 
color wheel. The branding colour combination is maintained in the logo and navbar of the header, as well as the 
footer via the branded blue background, white h5 headings and branded orange h4 headings. Users are never far
from branded navigation.

The images on the home page show groups of friends gathering, cheering and coming together to enjoy sport, which is precisely
what the brand is about. The images in the gametypes page are more representative of the games themselves - Last Man Standing
requires the winner to be the only player remaining, Sweepstakes are all about putting money in a kity/pot and watching the
action, while Prediction Competitions are more about studying the form, probabilities etc.

The footer section clearly defines (using branded links) where users can contact the company, keep in
touch via social channels or sign up to the newsletter for updates.

The benefits of playing games offered by 'Friendly Bet' are clearly dipicted with green tick icons, quickly drawing them
to the attention of users in the 'Why us?' section of index.html. 

User Stories
External users of the site have the following goals (including section of the website goals are achieved):
1	Find out about the website (index.html and sports.html)
2	Find out about the games (gametypes.html)
3	Determine whether the games will be fun / enjoyable (index.html/why us?)
4	Find out how the game works (gametypes.html)
5	Understand the rules (gametypes.html - Modals included for specific game rules)

The site owner has the following goals:
1	Generate user interest in playing the games (index.html/why us?)
2	Allow users to easily understand the games and why they are fun (index.html/why us? and gametypes.html)
3	Make them likely to tell their friends about the games and share them (index.html/why us?)
4	Users associate upcoming sporting events with the games themselves e.g. Premier League, Masters Golf, 
    Grand National etc (sports.html)


Features
The navbar uses a responsive collapseable Javascript plug-in. This allows users to toggle between the navigation
options, while keeping the brand logo at the top of the viewport at all times.

In the gametypes.html file, users are given a brief introdution to each game, details of how a game is played
and a more definitive set of rules for those looking for a deeper understanding. The rules can be accessed from 
a modal - this is the 'less fun', more serious content is not taking up large sections of a page that predominantly
aims to focus on the fun aspects of the games. The button type used from the Bootstrap framework is the button
'info' class which reprents what the users are accessing. The secondary button is used for closing.

Within sports.html, external links to sport fixtures and schedules are displayed with an arrow pointed right
to give clarity to users that they are leaving the site. 'target=_blank' is used to ensure users can easily 
navigate back to the Friendly Bet site.

In both gametypes and sports pages, collapse components are used to allow users to toggle their preferred choice without
having all options open at once. The show class is used to display the first option on each page for visual effect when 
users land on the gametypes/sport page.

Testing
Pingdom
BrowserStack

Issues and Bugs
Issues include the rushed nature of the project as mentioned in the description. It meant more detailed features
could not be tested or included. However, they can be for future projects.

Scalability
The project represents huge opportunities for scalability and future iterations. Live games could be added, 
based on the documented formats, which utilise JavaScript to bring the games alive for the user, add backend 
funtionality and manage databases to store customer data, connect to live data API's etc. Features may include
user accounts, live tables, share functionality and ultimately UX driven game development. Fixtures and blogs can
also be incorporated, reducing the need for users to access external websites and increasing 'quality' traffic - 
users already interested in the subject matter.


Technologies
The Bootstrap framework was frequently used throughout the side. The grid was used to layout the website. Many components
on the site were taken from Bootstrap and subsequently customised.
Jquery, popper and bootstrap cdn js plug-ins were copy and pasted to the site from w3schools.com.
Fontawesome was used for the icons in social links, external links, greens ticks and contact links.
Unsplashed.com was mostly used for the images on the site (total 7), as well as Google images (total 3).
Logopony.com was used to generated the logo, a screenshot was subsequently taken of it and uploaded.
Google Fonts was used and plugged-in for the 'Exo 2' font and expolration of other fonts.


Acknowledgements
CI Mentor - Felipe was excellent in giving advice around the planning and execution of the project, including several
useful tips and resources. He was always available for calls, emails or IMs.
Customer Care Support - provided useful advice and support throughout and kindly allowed a 5 day extension upon 
realsing I was not sent milestone project dates on time.