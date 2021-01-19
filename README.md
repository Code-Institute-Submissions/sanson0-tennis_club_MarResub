# tennis_club
tennis club website for milestone 1 project

## User Experience

### Why make this tennis club website?

* There is a need for FAB tennis club to attract new members, both adults and children.
* The club also wishes to retain its members and encourage participation in events.
* The club would like to improve members' skill level (this helps improve position in league tables).
This enhances club reputation and improving reputation will attract more members.
* Increasing membership is important to cover costs to maintain the club and facilities 
and pay for recent expensive improvements to the club (overhaul of courts). 
* The building is also available for hire which helps to generate revenue.

The wireframe view of the website is provided in Tennis_club.pdf [Link to wireframes](assets/docs/Tennis_club.pdf)

## Features

### Which features should be included in the website's design?

### Generic features
* Consistent headers and footers must be used across all pages to allow easy use of the website.
* Headers contain links to the other pages in the website.
* Footers contain links to the head coach's website, membership secretary, weather plus social media.
* Responsive design is included for all pages to allow good display of the website on desktop, tablet and mobile phone.
* There are separate pages for adult and junior players because training and competition events are different.
* Consistency is needed between events page (for adult members) and juniors page making it easier for families to join.

1. Home page
* Introduction -question
* Hero image
* Ethos statements
* Explanations of ethos statements
* Main events this week
2. Events pages
* Members must be kept informed of practice times.
* New members must be able to sign up for membership.
* Information on competition and social events must be accessible or displayed.
* Contact information should be accessible with a link to the head coach's and membership secretary's website.
* Information on typical player numbers must be included as it encourages participation (barchart).
* Membership prices should be available including a free month's trial.
* A link to the membership secretary
* A link to enquire about building hire.
3. Juniors page
* Junior members must be kept informed of practice times and contact details.
* New junior members' parents or guardians must be able to sign up/ sign children up for membership.
* Junior membership prices should be available including a free month's trial.
* Information on competitions and other childrens' events must be accessible or displayed.
4. Gallery page
* Pictures of the new courts:- an investment made by the club.
* Social events pictures (This is a bit difficult at the moment due to the pandemic and weather conditions!)
* Pictures of the clubhouse
* Pictures of the older courts, too, to show there are plenty to play on.

### Features left to implement
* Google maps can be included at a later date to show tennis club location.
* Links to external websites for coaching, membership and venue hire (see footers on all pages) websites can be made. Links 
to coaching, membership and venue hire open onto blank pages for now.
* Sign up forms' information is posted to the Code Institute form dump and a correct set of inputs to field results in a
message from The Code Institute. This would be changed in order to implement the website properly.

## Technologies used
* HTML
* CSS 
* Bootstrap 4.1
* Github
* Gitpod


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
2. git commit -m (leaving an additional commments on what was created or changed in ""s)
3. git push (this command transfers code fro Gitpod to the repository in Github)
4. On the Github site, the settings menu was selected, this displayed a new screen.
5. In the section called 'Github Pages' where it says 'Source', the main branch was selected (the default branch).
6. 'Save ' was clicked to display the URL of the website.
There is often a delay of up to 20 minutes before the website becomes available.
The address of this website is https://sanson0.github.io/tennis_club/
### Making changes to the website
Whenever new changes to the code are made (within the main branch), once these changes are saved, and commands git add, git commit and git push are used,
the changes to the website are automatically deployed (so they appear at the address https://sanson0.github.io/tennis_club/). Currently there is only one branch.
## Testing
### UX requirements vs website
UX feature | website page | Complete?
-----------|--------------|---------
Headers | All | done
Footers | All | done
Intro question | Home | done
Hero image | Home | done
Ethos statements | Home | done
Ethos paragraphs | Home | done
This week's main events | Home | done
Dropdown menu (Social) | Events | done
Practice times | Events | done
Sign-up Form | Events | done
Contact information | Events | done
Bar chart | Events | done
Membership fees | Events | done
Venue hire link | Events | done
Dropdown menu (Social) | Juniors | done
Practice times | Juniors | done
Sign up form | Juniors | done
Dropdown membership fees | Juniors | done
Contact information | Juniors | done
New courts photos | Gallery | done
Social events photos | Gallery | done
Older courts photos | Gallery | done
Clubhouse photos | Gallery | done

### Links
links to website pages 
links to social media
link to weather page
links to external websites should open into a blank page (sites for coaching, membership secretary and venue hire)
These all function correctly
### Sign-up forms
Submit an empty form and verify that an error message comes back.
Submit an incorrect email address and verify an error message comes back.
Submit a form with correct entries and verify a success message appears.
These actions all have the correct response.
### hoverable dropdown menus
The dropdown menus should all display additional information (there are three in the website)
### Responsive design
The website should adapt for different widths of devices eg. desktop, tablet and mobile.

* Text should be easy to read and stand out from any background images.
* Photos should be sharp and should resize if necessary for different screen widths (not left with almost blank part of image)
* Features of the website shoould not start to overlap each other or drop off the edges of the screen.
* Website should be simplified for narrow width devices.
* Website should not appear cluttered, dropdown menus utilised to help with this.
* Website should adapt smoothly when changing between different screen widths.
* Is the website easy and enjoyable for others to use?

The code and website was improved by grouping together each ethos statement with its associated
paragraph. The statements and paragraphs were separate when the website was first put together. 
This caused problems when adapting the website for responsive design.

The layout was improved by completely moving the position of ethos statements and paragraphs at smaller
screen sizes so that they sat underneath the background hero-image instead of being inside the hero-image.
If this was not done, the website looked messy.

A bug was found in the code related to the tennis balls on the home page. This caused them to move out of vertical
alignment when the website was displayed at different widths (on different devices). The code was simplified with 
help from mentor Nishant.
## Credits:
### Content
The Albert Lawn Tennis Club three ethos statements - fitness, fun and competition - were used in this website

css-tricks.com bar chart code was used in the Events page.

w3 schools for the hoverable dropdown menu using HTML and CSS only.
www.w3schools.com/howto/howto_css_dropdown.asp 
the dropdown menu was adapted to display information instead of links, with changes to colours.
This was necessary because a lot of information needed to be present on the website without crowding it.

Mentor Nishant for simplifying part of code on the index page relating to the tennis balls

Fontawesome
### Media
Thanks to the Albert Lawn Tennis Club for allowing photos of the club and its members to be used in this website.
Opportunities for photos of club members playing and enjoying social events were limited due to the Covid-19 pandemic.
Thanks to Freeimages for the photo on the Home page, and to Pixabay for photos on the Events page and Juniors page.

