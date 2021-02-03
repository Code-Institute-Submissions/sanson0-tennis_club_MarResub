# Lindale lawn tennis_club
A tennis club website for milestone 1 project

## User Experience
### Why make this tennis club website?

* There is a need for Lindale tennis club to attract new members, both adults and children.
* The club also wishes to retain its members and encourage participation in events.
* The club would like to improve members' skill level (this helps improve position in league tables).
This enhances club reputation and improving reputation will attract more members.
* Increasing membership is important to cover costs to maintain the club and facilities 
and pay for recent expensive improvements to the club (overhaul of courts). 
* The building is also available for hire which helps to generate revenue.

### Which features should be included in the website's design?
#### Generic features
* Consistent headers and footers must be used across all pages to allow easy use of the website.
* Headers contain links to the other pages in the website.
* Footers contain links to the head coach's website, membership secretary, venue hire, County League and social media.
* Responsive design is included for all pages to allow good display of the website on desktop, tablet and mobile phone.
* There are separate pages for adult and junior players because training and competition events are different.
* Consistency is needed between events page (for adult members) and juniors page making it easier for families to join.

1. Home page
* Introduction -question
* Hero image
* Ethos statements
* Explanations of ethos statements
* Invitation to potential new members
2. Events pages
* Members must be kept informed of practice times.
* New members must be able to sign up for membership.
* Information on social events must be easily accessible.
* Contact information should be accessible with a link to the head coach's and membership secretary's website.
* Membership prices should be available including a free month's trial.
* A link to enquire about building hire must be included.
* A bar chart of typical player numbers will encourage people to go to practices and New Members Night.
3. Juniors page
* Junior members must be kept informed of practice times and contact details.
* New junior members' parents or guardians must be able to sign up/ sign children up for membership.
* Junior membership prices should be available including a free month's trial.
* Information on childrens' events must be accessible or displayed.
4. Gallery page
* Pictures to be included of the new courts:- an investment made by the club.
* Social events pictures (This is a bit difficult at the moment due to the pandemic and weather conditions!)
* Pictures of the clubhouse
* Pictures to be included of the older courts, too, to show there are plenty to play on (important when booking a court for practice).

The initial wireframe view of the website can be accessed in [Link to wireframe 1](assets/docs/Tennis_club.pdf)
Changes have been made to the website since the initial wireframe view was produced. A second version of the wireframe view
was created and can be accessed in [Link to wireframe 2](assets/docs/Lindale_tennis_club_finish.pdf). Reasons for these changes
are explained in the testing section of this READme file.
#### Features left to implement
* Google maps can be included at a later date to show tennis club location.
* Links to external websites for coaching, membership, venue hire and County League (see footers on all pages) websites can be activated.
Links to coaching, membership, venue hire and County League open onto blank pages for now.
* Sign up forms' information is posted to the Code Institute form dump and a correct set of inputs to field results in a
message from The Code Institute. This would be changed in order to implement the website properly.

## Technologies used
* HTML
* CSS 
* Bootstrap 4.1
* Github
* Gitpod
* Chrome web developer tools

## Deployment
The process of deploying the website is described in this section and instructions are provided for deployment of changes to website.
Changes to the website are made easier by having the Gitpod extension installed in Firefox or Chrome browser.
### How to install the Gitpod extension in Firefox
To install the Gitpod extension in Firefox, from the create new repository screen:-
1. In the menu at the top right, click on 'Add-ons', from there search 'addons.mozilla'.
2. Type in 'Gitpod' and the first result is the correct extension.
3. Click on the extension, then click 'Add to Firefox'
4. Confirm permissions
Gitpod will appear in Github as a green button when a repository is opened.
### How to install the Gitpod extension in Chrome
To install the Gitpod extension in Chrome, from the create new repository screen:-
1. Click on the three dots menu.
2. Go to 'More Tools'>Extensions.
3. Click on the hamburger menu, then click 'Open Chrome Web Store'
4. search for Gitpod, this gives only one result.
5. Click on 'Gitpod' and click 'Add to Chrome', then 'Add Extension'
Gitpod will appear in Github as a green button when a repository is opened.
### Deploying the Website
The website code was created in Gitpod, then all the files were saved. At the Gitpod commmand line:-
1. Git add (files)
2. git commit -m "additional commments on what was created or changed"
3. git push (this command transfers code from Gitpod to the repository in Github)
4. On the Github site, the settings menu was selected, this displayed a new screen.
5. In the section called 'Github Pages' where it says 'Source', the main branch was selected (the default branch).
6. 'Save ' was clicked to display the URL of the website.

(There is often a delay of up to 20 minutes before the website becomes available.)
The address of this website is https://sanson0.github.io/tennis_club/
### Making changes to the website
Whenever new changes to the code are made (within the main branch), and these changes are saved, and commands git add, git commit and git push are used,
the changes to the website are automatically deployed (so they appear at the address https://sanson0.github.io/tennis_club/). Currently there is only one branch.
## Testing
Methods for testing of the website included:-
* clicking on page icon with magnifying glass within Gitpod screen to display website
* at the Gitpod comand line, typing 'python3 -m http.server' to display website in new screen
* when website deployed, opening it in Chrome and investigating it with web developer tools
* Web developer tools in Chrome have a device symbol, automatically scaling the screen for different widths of devices (responsiveness)
* checking HTML code using W3C HTML Validator
* checking CSS code using W3C CSS Validator
* checking performance of the website using Lighthouse
### UX requirements vs website
#### First impressions
First impressions of the website are good if:-
* The website must be inviting to new members and encourage current members to join practice sessions and social events.
* Each page of the website must be uncluttered.
* There must be plenty of opportunities to sign up for membership with a free trial period thrown in.
* Text must be easy to read as there is a lot of information to make available.
* Photos must be sharp, not stretched and appealing to the viewer.
* Contrasting colours should be used but not many of them.
* There should be consistency between website pages of headers/ footers/ style of presentation and colours.

Unfortunately, the first complete version of the website did not fulfil the criteria for a good first impression.
Many quite substantial changes were made, so a new wireframe was created to allow a comparison of old and new versions.
The wireframe view of the first complete version is provided in [Link to wireframe 1](assets/docs/Tennis_club.pdf)
The wireframe view of the second complete version is provided in [Link to wireframe 2](assets/docs/Lindale_tennis_club_finish.pdf)
Summary of differences:-
1. A smaller number of contrasting colours were used consistently across all pages of the website.
2. There were too many photos in version 1 for the Home, Events and Junior pages. Only one photo remained in version 2 for each page, all main background photos.
3. Social media icons were kept in one row for all screen widths. This saves the irritation of scrolling down a long way.
4. Number of colours reduced in header. Only the current page link was highlighted (in orange).
5. The question "Why Play Tennis?" on the Home page was moved to the top of the background image, out of this image.
6. Text on the Home page background image was given a contrasting background colour to allow easy reading of text.
7. Background images for Events and Junior pages were given 50% shading, to allow white overlaid text to be easy to read.
8. An invitation to New Members Night was added to the base of the background image as this was missing.
9. Each icon within the tennis balls was moved to the front of the text statement so that icons are easy to align with each other.
10. The weather link was replaced by the the County League link as it is more important to show the club's good standing in the league.

These changes resulted in positive responses from other people who saw the first and second versions of the website.

#### User Stories
Please refer to the file [user stories](assets/docs/user_stories.pdf) when reading the user story statements.

As a tennis club, we would like to:-
1. Attract plenty of new members so that we have strong finances and can cover the cost of our new courts (see Home and Gallery pages).
2. Retain current members so that we have long term supporters of the club contributing time, and money through membership fees
(see Events and Juniors pages).
3. See our new facilities fully utilised so that our investment (new courts) is even more worthwhile.
4. Improve the standard of play so that the club's reputation is enhanced and the club is more attractive to members and non-members
(see Events and Juniors pages list of weekly practices plus coaching link).
5. Attract a mixture of adult and junior players so that we have strong teams of players now and in the future (see Events and Juniors pages)
6. Advertise our great facilities so that more people will want to join the club (see Gallery page).
7. Hire out the clubhouse as a venue for celebrations/ parties and as a place for classes/ lectures so that we have an extra source of income
(see link to venue hire on every page of website).

As a tennis player I would like to:-
1. Play at a club with plenty of high standard courts so I can play all year round and can easily book a court. (See Gallery page.)
2. Join a club that is friendly so that I can make a new set of friends and enjoy social events with them. 
(See Social Event button on Events page, also friendship is part of ethos statement on Home page.)
3. Play at a club with a high standard of tennis so I can improve my game. (See coaching and County League links on every page.)
4. Play at a club where I can play competitively so I can play league matches (see Home page, competitive play is part of ethos statement).
5. Visit a club that will allow me a free trial membership so I can see if it is a club I’d like to join.

As a parent I would like my child to:-
1. Play at a club with plenty of high standard courts so he can play all year round (see Gallery page).
2. Join a club with regular coaching (See footer of each website page and Juniors page.)
3. Join a club that is friendly so that he can make a new set of friends and enjoy social events with them.
(See Social Event button on Juniors page, also friendship is part of ethos statement on Home page.)
4. Play where there is some competitive play so my child can progress to this level if this is something
he would like/ is able to do. (see Home page, competitive play is part of ethos statement).
5. Visit a club that will allow my child a free trial membership so we can see if it is a club he’d like to join.

#### Features
Testing included checking that all necessary features were present within the website.
UX feature | website page
-----------|-------------
Headers | All
Navigation links | All
Footers | All
Contact information links | All
Social media links | All
Intro question | Home
Hero image | Home
Ethos statements | Home
Ethos paragraphs | Home
Invitation - New Members Night| Home
Dropdown menu (Social) | Events
Practice times | Events
Sign-up Form | Events
Bar chart | Events
Membership fees | Events
Dropdown menu (Social) | Juniors
Practice times | Juniors
Sign up form | Juniors
Dropdown membership fees | Juniors
New courts photos | Gallery
Social events photos | Gallery
Older courts photos | Gallery
Clubhouse photos | Gallery
All these features were present within the website.
### Links
Links include:-
* links to pages within the website (Home, Events, Juniors, Gallery)
* links to social media, opening into a separate window
* links to external websites opening into a blank page (sites for coaching, membership secretary, venue hire and County League)
These all function correctly.
### Sign-up forms
Forms should do the following:-
* Error message comes back if fields are left empty in the form and submitted.
* Error message comes back if incorrect email address is entered and submitted.
* Success message appears if correct details are entered and submitted.
These actions all have the correct response.
### hoverable dropdown menus
The dropdown menus (there are three in the website) should do the following:-
* all display additional information only when curser is over the dropdown button
* display text that is easy to read 
### Responsive design
The website should adapt for different widths of devices eg. desktop, tablet and mobile.
* Text should be easy to read and stand out from any background images.
* Photos should be sharp and should resize if necessary for different screen widths (not left with almost blank part of image)
* Features of the website should not start to overlap each other or drop off the edges of the screen.
* Website should be simplified for narrow width devices.
* Website should not appear cluttered, dropdown menus are utilised to help with this.
* Website should adapt smoothly when changing between different screen widths.
* The website should be easy and enjoyable for others to use.

There are screenshots of responsive design testing [responsive design](assets/docs/responsive_design.pdf)
### Improvements to code
#### Testing with code validators
The website was tested using two code validators:-
* W3C Markup Validation Service
* W3C CSS Validation Service

The validators were very useful for finding small errors in HTML and CSS code. See the link for screenshots
of results from these validators [Code_validation](assets/docs/Code_validators.pdf).
#### Testing performance with Lighthouse
Testing of the website was done using developer tools within the Chrome browser. The Lighthouse tool was used to generate a
report. The report focussed on website performance, accessibility, best practices and search engine optimisation (SEO).
The results were used to improve the website in terms of its performance. Lighthouse highlighted a problem with file sizes
of the photos in the Gallery page. Large file sizes require a longer time to load and also cost the website user more in 
terms of data usage. The [ResizePixel](https://www.resizepixel.com) image editor was used to decrease file size of the photos by up to 90%.
The new versions of the photos were used in the website and the results for performance improved greatly.
The screenshots of results can be viewed in the link [Lighthouse](assets/docs/Lighthouse_testing.pdf).
#### Bugs
A bug was found in the code related to the tennis balls on the home page. This caused them to move out of vertical
alignment when the website was displayed at different widths (on different devices). The code was simplified with 
help from mentor Nishant Kumar. Open the link [Bug](assets/docs/Tennis_ball_bug.pdf).
## Credits:
### Content
The Albert Lawn Tennis Club three ethos statements - fitness, fun and competition - were used in this website.

css-tricks.com bar chart code was used in the Events page [bar chart](https://css-tricks.com/making-a-bar-chart-with-css-grid/).

w3 schools for the hoverable dropdown menu using HTML and CSS only [dropdown menu](https://www.w3schools.com/howto/howto_css_dropdown.asp)
The dropdown menu was adapted to display information instead of links, with changes to colours.

Thanks to mentor Nishant Kumar for all his help in improving this tennis website.

Fontawesome [Fontawesome](https://fontawesome.com) for icons.

A name generator was used to obtain a tennis club name using the place name option.
[Link to name generator](https://www.namegenerator.biz/)

Image editor [ResizePixel](https://www.resizepixel.com/). This editor was used to reduce file sizes of most photos significantly.

Code from The 'Love Running' website (The Code Institute) gallery page was used for the gallery page in this project.

Code from the 'Resume' website (The Code Institute) header navigation bar was adapted for this website.

### Media
Thanks to the Albert Lawn Tennis Club for allowing photos of the club and its members to be used in this website.
Opportunities for photos of club members playing and enjoying social events were limited due to the Covid-19 pandemic.
Thanks to [Freeimages](https://www.freeimages.com) for the photo on the Home page, and to [Pixabay](https://pixabay.com) for photos on the Events page and Juniors page.

