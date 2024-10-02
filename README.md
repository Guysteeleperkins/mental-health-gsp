# Mental Health Awareness

## Overview

### Purpose
The purpose of this project, Mental Health Awareness, is to create an easy to naviagte and appealing website to create a positive user experience which in turn will make it as easy as possible for everyone, espeically beginners, to access information on mental health, recognising common issues and manage stress.

**Guidance:** Begin filling out this section during Phase 1: Ideation & Initial Setup. Clearly articulate the main goal of your project, what it aims to achieve, and how it will provide value to your target audience.

### Target Audience
The main target for this website will be people who are first looking into mental health, however it will also include useful and imporant links for all kinds of users to access information on mental health. Having an easy to navigate, simple but effective layout and colour pallet to draw users in and make it easier to learn about the subjects present on the website. The easy to navigate and attractive layout will encourage users to stay on the page and therefore encourage users to learn more.

## User Stories

### Must-Have User Stories

- **User Story 1:** CLEAR NAVIGATION: As a user, I want the website to have an intuitive and easy-to-use navigation bar, so that I can quickly access mental health topics.

**Acceptance Criteria:** 
  - When the user is on any page the navigation bar should display links to the main sections of the site (e.g., "Common Issues," "Stress Management," "Resources").
  - When the user clicks on a link on the naviagtion bar it should take them to relevant section/page with the correct information.
  - The user should always be able to access the nav bar and therefore the navbar should be "sticky"
  
- **User Story 2:** BASIC INFORMATION: As a user, I want access to beginner-friendly descriptions of common mental health issues, so I can understand them without feeling overwhelmed.

**Acceptance Criteria:** 
  - When the user clicks on a link in the nav bar it should take them to the page which displays a variety of easy-to-read and short paragraphs with concise and clear format.
  - When the user navigates through the page/section there must be a "read more" link that can take them to external sources for more informtion

- **User Story 3:** RESPONSIVE DESIGN: As a user, I want the website to adjust for mobile, tablet, and desktop devices, so that I can read and navigate comfortably on any device.

**Acceptance Criteria:** 
  - Using a mobile first design the user should be able to navigate the website without having to side scroll or zoom in.
  - When the user uses larger devices such as a tablet and desktop the website should be responsive and remain aligned and   easy to read

### Should-Have User Stories

- **User Story 1:** STRESS MANAGMENT TECHNIQUES: As a user, I want tips on how to manage stress that I can apply to my daily life to help manage stress.
**Acceptance Criteria:** 

  - When the user clicks on "Stress Management," when they view the page, then they should see at least three techniques (e.g., mindfulness, breathing exercises, physical activity) with step-by-step instructions.
  - When the user scrolls in this section there should be visual help e.g. images to help guide them.
  - "Learn more" link

- **User Story 2:** MENTAL HEALTH RESOURCES: As a user, I want quick access to external mental health resources and helplines, so that I can seek professional help if needed.

**Acceptance Criteria:** 
  - when the user is on any mental health page then they should see a "Get Help" section with links to helplines and support websites either at the top or the bottom. (warning bar)
  - When the user clicks on "Get Help" it should open a new tab.


### Could-Have User Stories

- **User Story 1:** SEARCH BAR: As a user, I would like a search bar to make naviation through the site even easier and the information more accessable.

**Acceptance Criteria:**
  - When the user enters a key word and presses enter it should list the relevant sections/pages so they can shortcut to the desired area of the site.
  - When a keyword is not found on the site the search bar should return "No results found"

- **User Story 2:** PERSONAL STORIES: As a user, I would like a section/page dedicated to personal stories that would help me feel reassured and less isolated in my own experienes.

**Acceptance Criteria:** 
  - When the user clicks on this link there should be a few personal stories for them to read.
  - At the bottom there should be an area (E.g. form) so the user can upload their own personal story.

## Design Decisions

Due to time pressures my Wireframes desgn was very basic. However having a basic layout prepared and using this as guidance was a huge benefit to beginning to code the main structure of the website. 

<img src="/assets/screenshots/balsamiq.png" alt="A basic Wireframes desgin/sketch used as a guideline">

Using mind.org.uk for ideas on colour and layout I used dev tools to obtain one of the colours which I added to a colour pallet created by coolors.com : #fecb4e. A quick google search gave me an idea of what colours are associated with good mental health and positivity. With this guide I asked ChatGPT to adjust my colour pallet so the colours would work better with each other. This resulted in these colours: Persian orange, Tomato, Rebecca purple, Xanthous, Bleu de France. 

<img src="/assets/screenshots/coolors-screenshot.png" alt="A colour pallet consisting of the 5 main colours I used">



### Accessibility Considerations
I used two images in this project, however the images were asigned to the HTML via my CSS styles, and therefore I could not add an alt atribute.
This will be considered in future projects and using an "img" tag would be more suitable for Accessibility.


## AI Tools Usage

### ChatGPT
I used ChatGPT for general bug fixes and to help with some flexbox properties. A quick google search gave me an idea of what colours are associated with good mental health and positivity. With this guide I asked ChatGPT to adjust my colour pallet so the colours would work better with each other. This resulted in these colours: Persian orange, Tomato, Rebecca purple, Xanthous, Bleu de France. 

## Features Implementation

### Core Features (Must-Haves)
- **Feature 1:** CLEAR NAVIGATION: In this project there is a clear navigation bar for all screen sizes. This makes it easy for users to naviagte through the different pages and access different information. 
- **Feature 2:** BASIC INFORMATION: The website contains a minimalistic approach without too much detail, this stops users feeling overwhelmed and gives information on mental health in a "bite-sized" format.
- **Feature 3:** RESPONSIVE DESIGN: The website uses bootstrap, flex and media querys to keep the CLEAR NAVIGATION and BASIC INFORMATION features intact on different screen sizes.

### Advanced Features (Should-Haves)
- **Feature 1:** Description of the implemented feature.
- **Feature 2:** Description of the implemented feature.

- **Feature 1:** STRESS MANAGMENT TECHNIQUES: The website displays simple and clear tips and techniques on how to manage stress
  - When the user clicks on "Stress Management," when they view the page, the user sees 6 tips/techniques with a brief description.
  - When the user scrolls in this section there is no images to help with guidance, however due to a minamalist approach to stay inline with my Should-Haves this works well. Small images could be added in the future.

- **Feature 2:** MENTAL HEALTH RESOURCES: On the resources page, there is clear and obvious cards which contain the name of a website and a breif description and a button to that opens a new tab to the website.

  - when the user is on any mental health page there is a "Get Help" button with NHS: 111 number in the display box. 
  - "When the user clicks on "Get Help" it should open a new tab." - I did not add this feature as the resources page provides a a variety of resource websites with helplines.

### Optional Features (Could-Haves)
- **Feature 1:** PERSONAL STORIES: I did not include any personal stories, however there is a section on the stress management page with uplifting quotes.

## AI Tools Usage

### GitHub Copilot
Describe how GitHub Copilot assisted in coding, including any challenges or adjustments needed.  
**Guidance:** Reflect on how GitHub Copilot assisted in coding, particularly any challenges or adjustments that were needed to align with project goals.

Github Copilot helped massively when there time pressure is time pressure, it made coding quick and easy for HTML elements. However it did cause a few bugs as when pasting code it will add an end tag (usually to the top element). Beautify was used very often and was extremely helpful in keeping my code clean and tidy.

## Testing and Validation

### Testing Results
Throughout the project I used Devtools resposinve feature to test how the website would look on different screen sizes. This lead to many bug fixes despite trying to keep a mobile first design in mind.

### Validation
After completing my HTML and and CSS I put my index.html, stress.html and resources html into https://validator.w3.org/, all three brought back some minor errors which were easily fixed. I then valiadted my CSS which returned no errors, just minor warnings. 
<img src="/assets/screenshots/css-validator-warnings.png" alt="index.html page HTML validator screenshot showing no erros">
<img src="/assets/screenshots/css.png" alt="index.html page HTML validator screenshot showing no erros">
<img src="/assets/screenshots/index.png" alt="index.html page HTML validator screenshot showing no erros">
<img src="/assets/screenshots/stress.png" alt="index.html page HTML validator screenshot showing no erros">
<img src="/assets/screenshots/resources.png" alt="index.html page HTML validator screenshot showing no erros">
For the warnings on my CSS I did not change any code as in a walkthrough video from the LMS in code-instutute these items were included.

### Lighthouse
First Performance: BAD

<img src="/assets/screenshots/lighthouse-test-1.png" alt="First lighthouse performace picture displaying 56/100 Performce">

Using https://towebp.io/ to convert my images to WEBP , After converting and changing the .jpg to .webp on the images I discovered a large class in my CSS that was unused and removed it.

Second Performance

<img src="/assets/screenshots/lighthouse-test-2.png" alt="First lighthouse performace picture displaying 56/100 Performce">


## Deployment

### Deployment Process
I used the love runnning walkthrough project to guide me on deployment, this resulted in smooth deployment.

### Reflection on Development Process and Final Thoughts
ChatGPT was helpful for debugging and giving fast answers to minor questions (e.g what bootstrap or flexbox properties to use). However it caused problems a few times by completely rewriting my code and wasting a lot of time. On reflection it was usually the prompts that caused these errors.

Time managment and knowing when to move on to a different part of the project was sometimes difficult, I always like to solve a problem there and then but this lead to too much time being spent on minor styling details. In the future I will create the very basic HTML structure first and create the MUST-HAVE features before styling.


## Resources
https://www.gitpod.io/
https://favicon.io/emoji-favicons/
https://validator.w3.org/
https://jigsaw.w3.org/css-validator/
https://coolors.co/
https://www.nhs.uk/every-mind-matters/mental-health-issues/stress/
https://www.mind.org.uk/
https://getbootstrap.com/
https://unsplash.com/ - used for free images
https://www.who.int/news-room/feature-stories/mental-well-being-resources-for-the-public
https://css-tricks.com/perfect-full-page-background-image/
https://www.mentalhealth.org.uk/
https://www.samaritans.org/

## Future Improvements

 - When the user clicks on this link there should be a few personal stories for them to read.
 - At the bottom there should be an area (E.g. form) so the user can upload their own personal story.
 - Search Bar
 - Improved Styling
 - Less messy CSS
 - Reactive numbers so a user can call a number from their phone
 - Feedback form