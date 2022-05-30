# Website Testing

## HTML and CSS Validation Testing

###  W3C HTML Validator
- All pages were passed through either the W3C CSS validator or W3C Markup Validator (depending on relevance).
- Any issues found have been rectified and all pages now pass with no errors or warnings to show.  

#### index.html
![Feedback from run through the W3 HTML validator for Homepage](/assets/images/index-w3c-result.png)

#### contact.html
![Feedback from run through the W3 HTML validator for Contact page](/assets/images/contact-w3c-result.png)

#### sign-up.html
![Feedback from run through the W3 HTML validator for Sign Up page](/assets/images/sign-up-w3c-result.png)

#### thank-you.html
![Feedback from run through the W3 HTML validator for Thank you page](/assets/images/thank-you-w3c-result.png)

###  W3C CSS Validator

#### style.css
![Feedback from run through the W3 CSS validator for style.css](/assets/images/css-w3c-result.png)

---
## Lighthouse
- All pages were ran through Lighthouse on Chrome Devtools for both desktop and mobile device display. Ran in incognito mode. Any issues were dealt with and all now have a high passing mark.

#### index.html
- Desktop

![Screenshot of Lighthouse score for index.html on desktop](/assets/images/index-desktop.png)

- Mobile

![Screenshot of Lighthouse score for index.html on mobile](/assets/images/index-mobile.png)

#### contact.html
- Desktop

![Screenshot of Lighthouse score for contact.html on desktop](/assets/images/contact-desktop.png)

- Mobile

![Screenshot of Lighthouse score for contact.html on mobile](/assets/images/contact-mobile.png)

#### sign-up.html
- Desktop

![Screenshot of Lighthouse score for sign-up.html on desktop](/assets/images/sign-up-desktop.png)

- Mobile

![Screenshot of Lighthouse score for sign-up.html on mobile](/assets/images/sign-up-mobile.png)

#### thank-you.html
- Desktop

![Screenshot of Lighthouse score for thank-you.html on desktop](/assets/images/thank-you-desktop.png)

- Mobile

![Screenshot of Lighthouse score for thank-you.html on mobile](/assets/images/thank-you-mobile.png)

---
## Manual testing

### Homepage
- All links tested manually ***date*** and found to be working as intended
- Interactive elements tested manually on ***date*** and found to be working as intended

### Contact page
- All links tested manually ***date*** and found to be working as intended
- Interactive elements tested manually on ***date*** and found to be working as intended
- Form validation tested manually on ***date*** and found to be working as intended

### Sign-up page
- All links tested manually ***date*** and found to be working as intended
- Form validation tested manually on ***date*** and found to be working as intended

### Thank you page
- All links tested manually ***date*** and found to be working as intended

---
## Different browsers
- Tested and found to be working as intended on the following browsers :
    - Chrome
    - Firefox
    - Microsoft Edge
- Unable to test on Safari as unble to download on my Windows PC
- Certain features such flexbox are not supported on Internet Explorer and therefore some feature are not displaying properly. However, Internet Explorer was retired by Microsoft in August 2021 and is no longer supported.

---
## Different devices with Chrome Devtools
- Tested on the following devices via Chrome Devtools and found to be working as intended:
    - iPhone SE
    - iPhone XR
    - iPhone 12 Pro
    - Pixel 5
    - Samsung Galaxy S8+
    - Samsung Galaxy S20 Ultra
    - iPad Air
    - iPad Mini
    - Surface Pro 7
    - Surface Duo 
    - Samsung Galaxy A51/71
    - Nest Hub
    - Nest Hub Max

---
## Media Queries
- Media queries were introduced at the below break points:
    - 1765px
    - 1300px
    - 1100px
    - 950px
    - 840px
    - 730px
    - 690px
    - 525px
    - 406px

---
## Bugs
### Resolved Bugs
- Issues with flexbox forcing non-active FAQs to open along with active ones, solved with help from [Techstacker](https://techstacker.com/prevent-flexbox-child-element-height-stretch-css/)
- Issue with select element and required attribute solved with help from [Jibin and Adhan Timothy Younes (users on Stack Overflow)](https://stackoverflow.com/questions/44322824/select-required-not-working)
- Issue where footer would appear above the bottom on the page on the thank you page solved with help from [CSS Tricks](https://css-tricks.com/couple-takes-sticky-footer/)
- Issues where transparent overlay of header would show elements with 'position: relative' attribute through when scrolling, even after  adding sticky opaque backing div solved by removing backing div from section that was not sticky and increasing z-index value.
- Issue with summary elements showing a single-pixel-wide line of white between the background colour and the border solved by applying separate styling to '[open]' and closed details elements

### Unresolved Bugs
- Phone simulation on [Am I Responsive?](https://ui.dev/amiresponsive) shows gradient fade div over hero image in an undesirable position. This is not the case when simulating on Devtools and I have been unable to emulate it, and have therefore struggled to resolve it at this stage
- Number input element in sign-up form sometimes sticks as focused, even when another input it clicked, leaving the element with a white background. I have tried researching ways to fix this but this does not seem to be a problem that other coders often face/notice so have been unable to find guidance on how to prevent it.




