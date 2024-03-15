# IntelliDose - your intelligent pill companion

This semester we have IoT device design for PBL, so I decided to create a webpage presenting the idea we are working on. In the future, it is planned to add at least two new pages: the first is a list of offered products/models, the second is a page with a contact form (navbar items are already added but currently redirect at the top of the landing page).

## Link

https://starlight-crusader.github.io/

## Responsiveness

* The webpage supports both mobile and desktop devices.<br>
* The desktop version <b>responds adequatelly to changes in browser window size</b>.<br>
* In mobile version elements that were arranged in a row, <b>rearrange themselves in columns</b>.<br>
* In mobile version sliding header that by click allows users to jump at the top of the page is <b>replaced with a button in the bottom-left corner</b>.

## Mascot

* For the desktop version, a <b>mascot character</b> was added in the bottom-left corner. And I mean it, you <b>won't find it in the mobile version</b>. I've hid it on purpose, because I think it is unsuitable element in the context of mobile web-design. <b>If it is necessary for him to be there, I'll add it in the next version.</b>
* It <b>appears on the screen in its entirety after a certain period of time</b>, follows the user as they scroll and <b>bounces</b>, and displays <b>a welcoming message</b> when hovering over it.

# CSS Framework Integration

For the CSS framework to be integrated into this project, I've picked the Bootstrap framework. The first thing I've had to deal with is fixing my container usage. Then I've decided to refactor all the navbars and buttons on the page by using.nav and a bunch of button styles to fix the structure and add additional functionality, like, for example, buttons disabling (since currently I have a bunch of buttons on the page that are supposed to redirect to other pages that at the moment do not exist). The second thing is the feature cards. The bootstrap provides a lot of predefined styles for giving this element any visual imaginable; for me, it made the structure of cards more complex and pretty. Also, I've found the fixed-top style very useful for my "sliding" header.