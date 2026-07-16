
#image sources:

https://i0.wp.com/post.medicalnewstoday.com/wp-content/uploads/sites/3/2021/06/GettyImages-1305552472_header-1024x575.jpg?w=1155&h=1528 {one to one therapy}

https://media.post.rvohealth.io/wp-content/uploads/sites/4/2021/06/men-support-group-talking-1200x628-facebook.jpg {group therapy}


https://media.post.rvohealth.io/wp-content/uploads/sites/4/2021/06/men-support-group-talking-1200x628-facebook.jpg  {group fitness}


##hero image

https://media.istockphoto.com/id/1133003132/photo/three-millennial-male-hipster-friends-on-a-bench-in-a-city-street-smiling-to-camera-close-up.jpg?s=612x612&w=0&k=20&c=qVlre8SQVPGGzizHmsiLIQChakxfaFjNBXcJlkyn5Xs=




















# Live Health

A student project to create a single page website espousing a multi-faceted health approach that combines to tackle physical and mental wellbeing.

[See the website here] ==__

## Design Brief

### External User’s Goal

The user wants a basic introduction to the site and what the aim of the site is and what their values are.

### Site Owner’s Goal

The site owner’s goal is to create an informative webpage that introduces the brand and the help they can offer. The content should be well-organised and easy to digest, with a focus on simplicity and clarity through the use of HTML and CSS with Bootstrap.



## Design & Planning

### User Stories and Acceptance Criteria

1.  **As a visitor, I want to see the main wellbeing advices clearly on the homepage so I can quickly understand what is being promoted.**

The homepage displays sections for group therapy, group coaching, individual therapy, and one-to-one coaching.
Each service has a short description.
The layout is visually clear and easy to scan.

2. **User story: As a visitor, I want to contact the team easily so I can ask questions or request support.**

A contact section includes an email address, phone number, or contact form.
The form includes required fields and validates input.
A confirmation message is shown after submission.



### Wireframes


Mobile/Tablet | Desktop | 
-- | -- | --
![Wireframe for a mobile/tablet] | ![Wireframe for a laptop/desktop]| ![Wireframe for a confirmation window]

### Typography

For headers I have used the Margarine font.  It is a friendly appealing font.

### Colour Scheme

I chose a  blue and pink palette to be warm and welcoming to appeal to a wide variety of people.



## Features:
Explain your features on the website,(navigation, pages, links, forms.....)
### Navigation
### Footer
### Other features
## Copilot AI Assistance

Copilot came up with:

* The hero image of hands.  This required a lot of work (and several day's worth of free tokens!) to get something natural looking.
* The user stories and acceptance criteria.  I edited them down.
* The idea to use a shield for the logo.  Copilot provided some examples from around the web.  I asked it to render the shield emoji from the Google Noto font as an svg but it did a poor job, so I asked it for advice on a better conversion tool.  The online tools weren't happy with emoji fonts so I searched for a pre-converted svg and hand-edited it to match the site's palette.
* Code for the Radicalisation section.  The code worked but Copilot added a bunch of gratuitous styles, which I cleaned up.

My takeaway is that Copilot is good at coming up with a bunch of ideas, but if you have something in mind it is hard to get exactly what you want.

## Technologies Used
List of technologies used for your project...
HTML
CSS
Bootstrap
Github
## Testing
Important part of your README!!!
### Google's Lighthouse Performance
Screenshots of certain pages and scores (mobile and desktop)
### Browser Compatibility
Check compatability with different browsers
### Responsiveness
Screenshots of the responsivness, pick few devices (from 320px top 1200px)
### Code Validation
Validate your code HTML, CSS (all pages/files need to be validated!!!), display screenshots
### Manual Testing user stories or/and features
Test all your user stories, you an create table 
User Story |  Test | Pass
--- | --- | :---:
paste here you user story | what is visible to the user and what action they should perform | &check;
- and attach screenshot

## Bugs

* The hero image displayed repeatedly across the screen after I added the background gradient.  I read the [MDN page on using multiple backgrounds](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Backgrounds_and_borders/Using_multiple_backgrounds) to understand that I needed to double-up the background image properties.
* Copilot wrote the code to display the confirmation modal but it attached it to the wrong event so it didn't work.  I read the [MDN page on form submission using javascript](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Sending_forms_through_JavaScript) and fixed the problem.
* Following the advice in the project statement I used a Jumbotron for the header without realising it was a Bootstrap 4 feature and didn't do anything.  Unfortunately, the boilerplate that came with it introduced an unwanted margin but when I noticed that I fixed it and removed the Jumbotron cruft.
* After clicking on an internal link the heading was hidden under the navbar.  I added `scroll-margin-top` using the browser dev tools and it fixed the problem, but when I added it to the project it didn't.  After reading this [Stack Overflow question and answer](https://stackoverflow.com/questions/72581132/how-does-the-css-property-scroll-margin-top-and-scroll-padding-top-really-wo) I realised that I had initially tested it with javascript disabled, but it didn't work in production because the navbar collapser handles the scrolling.  This code has a bug calculating the height of the navbar, which I have fixed.
* The default bootstrap link colour had contrast problems against the light section background so I used the darker blue matching the shield border.

## Deployment

#### Creating Repository on GitHub
- First make sure you are signed into [Github](https://github.com/) and go to the code institutes template, which can be found [here](https://github.com/Code-Institute-Org/gitpod-full-template).
- Then click on **use this template** and select **Create a new repository** from the drop-down. Enter the name for the repository and click **Create repository from template**.
- Once the repository was created, I clicked the green **gitpod** button to create a workspace in gitpod so that I could write the code for the site.
#### Deloying on Github
The site was deployed to Github Pages using the following method:
- Go to the Github repository.
- Navigate to the 'settings' tab.
- Using the 'select branch' dropdown menu, choose 'main'.
- Click 'save'.

## Credit and Thanks

* [Code Institute](https://codeinstitute.net/) and its tutors for teaching, support and the navbar collapser
* [West Midlands Combined Authority](https://www.wmca.org.uk/) for funding
* [Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/) *et al* for the web
* [GitHub](https://github.com/) for hosting the repository, the project plan and the site
* [Bootstrap](https://getbootstrap.com/) for the CSS framework
* [Font Awesome](https://fontawesome.com/) for icons
* [Fort Awesome](https://github.com/FortAwesome/Font-Awesome/releases) for collating the Font Awesome assets
* [Bunny CDN](https://fonts.bunny.net/) for font hosting
* [The Rubik authors](https://github.com/googlefonts/rubik) for the Rubik font
* [Microsoft](https://www.microsoft.com/) for [Visual Studio Code](https://code.visualstudio.com/)
* [Copilot](https://copilot.microsoft.com/) for illustrations, brainstorming and copy
* [Google](https://github.com/googlefonts/noto-emoji) for the Noto Emoji font, which provided the basis for the shield logo
* [Action Counters Terrorism](https://actearly.uk/) for Prevent guidance
* [His Majesty's Government](https://www.gov.uk/government/publications/prevent-duty-guidance/prevent-duty-guidance-for-england-and-wales-accessible#prevents-objectives) for the Prevent objectives
* [Balsamiq](https://balsamiq.com/) for trying to upsell me export after I'd completed the wireframes