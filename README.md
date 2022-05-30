# GO!gym

![The GO!gym website features displayed on different devises](assets/images/responsive-test.png)

- GO!gym is a gym with the purpose of motivating it’s members to attend regularly by combining as many desirable gym features in one friendly and accessible place. With this motivation, gym-goers will be more likely to keep on track and achieve their fitness goals, whatever they may be.

- Their site exists to provide relevant information to anyone who is considering switching to GO!gym or would like some further information about what they have to offer. It has been built using HTML and CSS and can be viewed on a range of devices, including those with screen-widths as low as 310 pixels, so that users are able to research GO!gym whilst on-the-go.


## Links

[Link to the live project](https://beckyskel.github.io/html-css-project-1/)

[Link to the project repository](https://github.com/BeckySkel/html-css-project-1)

---
## Table of Contents
- [Strategy](##Strategy)
    - 
    - 
    - 
- [Scope](README.md##Scope)
    - 
- [Structure](##Structure)
    - 
- [Skeleton](##Skeleton)
    - 
- [Surface](##Surface)
    - 

---
## Strategy

### Target Audience
- The website is targeted towards active individuals around the UK cities of Birmingham, Oxford or London who either aren't satisfied with their current gym and are looking for a more affordable or convenient option, or those who are looking to join a gym for the first time and may need extra support to keep on track. 

### User Stories

#### Potential members – Regular gym-goers, looking to switch
*These are users who already have/have previously had a membership to another gym but are considering switching*
- As a regular gym-goer, I would like to know what features sets this gym apart from my current one.
- As a regular gym-goer, I would like to know the opening hours and available locations so that I can plan my routine.
- As a regular gym-goer, I would like to know the cost(s) of a membership.

#### Potential members – New gym-goers
*These are users who have potentially never had a gym-membership but are interested in signing-up for one*
- As a new gym-goer, I would like to view existing member’s experiences, including frequently asked questions and member reviews.
- As a new gym-goer, I hope to see information about the sign-up process and what to expect.
- As a new gym-goer, I would like the ability to contact the company to enquire about any information that I have not been able to find on the website.
- As a new gym-goer I hope to find a clear and easy way to sign up, should I choose to attend.

#### Current members
*These are users who are already members of GO!gym*
- As a current member, I would like to see the contact information of my local gym, should I need to contact them.
- As a current member, I may need to view information on altering or cancelling my membership.
- As a current member, I would like to see a timetable of the available classes.
- As a current member, I would like links to the social medias of the gym so that I can follow them and tag them in my posts.

---
## Scope

### Research
- Before any planning, I conducted research into other gym websites and took note of common features and layouts, as well as which features I thought were affective and would be good to include for GO!gym and my target audience.

### Future Features

#### Classes
- There could be a link to a classes calendar or booking page so that users can get themselves booked onto a class. Because this is a members-only gym, these features would most likely need to be hidden behind a member log in function and since this project is a static frontend site which focuses on using only HTML and CSS, this would not be possible to implement at this stage.

#### Member login
- A member login area would be a good way to invite existing members back to the site more often. As previously mentioned, this would not be possible using only HTML and CSS and without the use of other languages.

#### Payment
- To make the sign-up form functional, there would usually be a payment section included within the form itself. Or, after submitting the sign-up form, the user would be lead to an external payment page such as PayPal. There is no payment account connected to GO!gym and this would only be for effect. At this stage, there would also be no way to bring the user back to the site without having made payment, so they would not receive the thank you message with further instructions.

### Testing
- Throughout the project, I relied heavily on [Chrome Devtools]() to help me view this project on different screen sizes so that I could adjest elements and create media queries for different devices. 

---
## Structure


### Wireframes
- After looking at common themes and deciding what I would like to include, I mapped out the intended features of the website using [Balsamiq]() to create wireframes of each page
- [View the wireframes here](assets/documents/wireframes.pdf)

### Information architecture
- GO!gym is a landing site for a collection of gyms in 3 different cities across the UK. The website has a home page with key information about the membership-perks and gym sites themselves.
- The information is presented in a catchy, easy-to-digest way, with the information presented in a mix of informative paragraphs, graphic key-points and interactive elements. There is also a mix of official GO!gym-written material and user-submitted content.  (i.e. frequently asked questions [FAQs] and member reviews).
- The home page has been split in to 3 main sections (6 defined sections in total, but grouped by similarity for the sake of cleaner navigation) links to these can be found in the main navigation, alongside links to the other pages of the website; Contact page and Sign Up page.
- All forms on this site are currently dummy forms for presentation purposes only, the information does not get stored anywhere but each form displays a different thank you message on submission to feedback to the user that their submission was successful.

---
## Skeleton

### Current Features

#### Header/navigation
- The main navigation bar features a soft black background with a large logo to the far-left that links back to the homepage, 3 divider-separated links in white alongside it, and 2 bold button-style links to the far-right. The different formatting and separation of the navigation links is due to the different roles they play: the left links link to different sections on the main homepage and the right-hand links lead to different pages of the website.
- The header is sticky and consistent across all pages and screen sizes so the user can always easily return to all pages/sections.
- On the homepage, the header is transparent when over the hero image to provide a better view of the contents but opaque after scrolling as to reduce distractions and noise when scrolling. 
- I have used CSS to provide visual aid when hovering over each link but added no styling for the ‘active’ page as this may cause confusion when using the homepage links as you can scroll from one section to the next without the use of the links. The supporting pages are also a lot smaller with large headings so ‘active’ styling is unnecessary.

![Screenshot of the naivgation bar](assets/images/header.png)

#### Hero image
- The hero image takes up the majority of the viewport and shows a man running on a treadmill.
- The bottom of the image fades into a black div to harmonise with the transparent header and transition into the first section. There is a large slogan that spreads across the bottom of the hero image and onto the first section, taking up the rest of the screen-space and further aiding the transition. The overlapping, shadowed text of this slogan is carried throughout the site on headers.
- The image size and placement changes slightly based on the screen size so the subject is vertically-centred and can always been seen.

![Screenshot of the hero image](assets/images/hero.png)

#### Key points
- The key selling points are presented on 3 large cards in a line with single sentences and a large icon, relevant to the information
- These cards provide the user a good starting-point of the most desirable features that the gym has to offer, without having to scroll too far or read too much

![Screenshot of the key points section](assets/images/key-points.png)

#### About us
- The about us section consists of a large heading, an image and 3 paragraphs of the gym’s key principles and selling-points. There is also a large ‘Join now!’ link which leads to the sign-up page; the styling of this link is consistent with the same link in the navigation bar 
- There are 2 links within the text of the paragraphs which lead to the locations section of the contact page and the sign-up page respectively. The text within the link is relevant to the destination but aria labels have been added to avoid ambiguity and let the visually impaired know where the link will take them. These links will be highlighted with a yellow background when hovered over.
- As the screen size shrinks, the image will display on top of the text to provide more room.

![Screenshot of the about us section](assets/images/about-us.png)

#### Gym features
- The features section is split into 3 captions and their associated images.
- The caption is a short, single-sentence block of text with a heading. The images relate to what is said in the captions.
- As the viewport shrinks, the captions and images stack on top of each other to fit the screen.

![Screenshot of the gym features section](assets/images/features.png)

#### FAQs
- To save space, the FAQs have been placed in details elements which extend when clicked. This was a standard which I noticed when completing research towards this project.
- The summary of the element is the question, this is always visible, and the response is hidden until the element is clicked. 
- Styling has been applied when hovering over the summary and when the element is active in order to tell the user that this element can be interacted with and to provide clear definition between the questions and answers when open.
- There are 2 internal links within the answer paragraphs which lead to the contact and sign up pages. The text within the links is relevant to the destination but aria labels have been added to aid the visually impaired. The links are highlighted yellow when hovered over.

![Screenshot of the FAQs section - all elements closed/inactive](assets/images/faqs-closed.png)
![Screenshot of the FAQs section - one element open/active](assets/images/faqs-open.png)

#### Reviews
- 3 user reviews have been placed in a container that the user can use links to interact with in order to scroll along, left or right. This is replaced on smaller screens with a plain scrolling section to avoid crowding the screen.
- Each review has a heading with the reviewers name and a paragraph block with their review.
- A border with 2 quote icons is placed over the review window and links styled as round buttons with left and right chevrons on placed on either side. These control the direction of the scroll. A transition of XXX seconds has been applied so that there is a smooth scroll between the reviews.
- The yellow background is bright and eye-catching and the subtle shadows give the illusion that the review and buttons are floating over the background.

![Screenshot of the reviews section](assets/images/reviews.png)

#### Footer
- All pages require some scrolling on most screen sizes and therefore a ‘back to top’ button has been provided.  The button features an up arrow icon for illustration of the outcome. As the screen shrinks, the text is removed and the icon remains so the outcome is clear without visually crowding the footer.  
- Non sticky so that the user can see more of the site while scrolling through.
- External links to social medias, opening in a separate tab. Aria labels provided for visually impaired.
- The footer mirrors the layout of the header bar for visual balance.

![Screenshot of the footer](assets/images/footer.png)

#### Locations
- The contact page features 2 sections. The first is the current locations of the gyms, along with their addresses and contact information.
- The info is presented in floating cards with a google map iframe, a heading with the city name, and a table to present the contact info in an organised way. Clicking a link on the iframe opens a full-size google map in a new tab. 
- Icons are placed to the left of the contact info to act as bullet points and clues to the instruction of the following information.
- The 3 cards change shape and configuration on smaller screen sizes until stacked on top of each other.

![Screenshot of the locations section](assets/images/locations.png)

#### Contact
- The contact section is a query submission form for users who would like to contact the company in general instead of a specific location. It will validate that the required fields have been filled in before allowing the user to submit.
- On submission, the page will refresh and a pop-up thank you message will display letting the user know that their message has been sent and we will be in contact. Dummy form, info not actually processed.
- Single line of Javascript used to convey to the user that submission was successful.

![Screenshot of the locations section](assets/images/contact.png)

#### Sign-up
- The sign up page consists of a single section with a detailed sign-up for split into 2 fieldsets - "your details and "your membership".
- The user inputs their personal and contact info into the first section and then chooses their desired location and plan in the second. The required fields are validated before submitting and terms and conditions are available as a document that open on a new tab.
- After submitting, the user is directed to a thank you page to show that the submission was successfully sent, lets them know what to expect next and provides a link to the contact page if they have any questions.
- Another dummy form, info not actually processed

![Screenshot of the 'your details' fieldset of the sign-up form](assets/images/su-details.png)
![Screenshot of the 'your membership' fieldset of the sign-up form](assets/images/su-membership.png)
![Screenshot of the thank you message](assets/images/su-thankyou.png)

### Technologies used

#### Languages
- [HTML]()
- [CSS]()
- [Git]() for version control

#### Other resources
- [Gitpod]() to alter and manage website files
- [Github]() to create and store website files
- [Chrome Devtools]() to test site throughout process
- [Balsamiq]() to create wireframes
- [Coolers]() to choose a colour scheme
- [Google Fonts]() for the website font (Poppins)
- [Font Awesome]() used to add icons
- [MS Paint]() used to create the favicon
- [Pexels]() for images
- [Code Institute]() fullstack developer course to learn how to create
- [W3Schools]() for help with common coding issues
- [Flexbox Froggy]() to learn the basics of flexbox design

---
## Surface

### Design

#### Colour scheme

![The colour sheme I used](assets/images/colours.png)

- A bright and energising colour scheme has been used to elicit feelings of excitement and motivation.
- I used [Coolers]() to help pick a colour scheme.
- There are 3 base colours and 2 highlights. The base colours are off-white, warm grey and soft black. The highlights are neon yellow and blue. AThis vibrant palette represents the gym values of being enjoyable and unintimidating.

#### Imagery
- All images sourced from [Pexels]()
- The images were chosen with a similar saturation of colours to that of the website itself. The colour-scheme is vibrant and high contrast, so images were chosen that matched this.
- All images remain relevant to the website with the subjects interacting with either the exercise equipment or other gym features. Most subjects are smiling to further convey the message that this gym is an inviting place.

#### Typography
- All text is in the Poppins font. It is a geometric sans serif typeface that is clear and easily read. It’s playful style pairs well with the bold colours and curved edges used in the design of the site. 
- Sans serif has been used as the fallback option as it is the closest web-safe font.

#### Icons
- Font Awesome icons were used alongside key information to provide visual aid of the associated information .
- Also used for links and buttons to provide recognisable imagery of the outcome after clicking.

---
## Credits

### Content

### Media
- 

### Acknowledgements
- [Code Institute]() for providing excellent learning content 
- Reuben Ferrante as my mentor
- [W3Schools]() for quick and easy guidance on HTML and CSS
- The users of [Stack Overflow]() for asking and answering some of the harder HTML and CSS questions
- Other CI students for sharing their work and providing guidance on mine

