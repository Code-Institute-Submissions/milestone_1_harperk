# Harpoon Illustrations

![Different Screen Resolutions](https://github.com/H4RP3RK/milestone_1_harperk/blob/c3e8f8eff46311cfaf4292052ed704a53fc5cc4e/wireframes/milestone_1_screens.pdf)

## Aim

The client is an illustrator who requested a website to showcase illustrations she creates 
for friends and family. The purpose of the website is to increase her client base and invite users
to submit their own ideas for unique illustrations.

The client has set the following criteria for the website:
1. The design should be professional with an element of fun.
2. The main focus should be the illustrations.
3. The user should be able to contact the illustrator.
4. There should be clear instructions as to how the user can contact the illustrator.

---

## UX

Harpoon Illustrations is a newly established company that currently has a very small client base 
consisting mainly of the illustrator's friends and family. The website is aimed at the wider public,
who are unlikely to be familiar with the illustrator's work. It is hoped that the users will
be potential clients, who will commission the illustrator to create bespoke illustrations for them, their
friends or family.

In order to attract users and build the client base, the website will:
1. Look aesthetically pleasing.
2. Draw the user in with humour.
3. Look simple and uncluttered to focus the attention on the illustrations.
4. Have clear instructions to easily allow the user to contact the illustrator.

### User Stories

"As a user of the Harpoon Illustrations site, I want the website to look stylish as this instills confidence about the quality of the illustrations."

"As a user of the site, I want to see the illustrator's previous work to get ideas for potential work I can request."

"As a user of the site, I want an easy way to get in touch with the illustrator directly so I can discuss potential ideas."

---

## Wireframes

[Balsamiq](https://balsamiq.com/) was used for the initial design phase of the website.
Some changes were made during the implementation stage for aesthetic and usability reasons.

### Large Screen

<img src="https://github.com/H4RP3RK/milestone_1_harperk/blob/83064aed06514109c29f727354b9a19ce20613f6/wireframes/milestone_1_large.png"
     alt="Large Screen Wireframe"
     style="text-align: center;" />

### Medium Screen

<img src="https://github.com/H4RP3RK/milestone_1_harperk/blob/83064aed06514109c29f727354b9a19ce20613f6/wireframes/milestone_1_medium.png"
     alt="Medium Screen Wireframe"
     style="text-align: center;" />

### Small Screen

<img src="https://github.com/H4RP3RK/milestone_1_harperk/blob/83064aed06514109c29f727354b9a19ce20613f6/wireframes/milestone_1_small.png"
     alt="Small Screen Wireframe"
     style="text-align: center;" />

---

## Features

### Home

Welcomes the user with some information about the illustrator, which invites users to get in touch to request personalised illustrations.
A GIF version of an illustration introduces the user to the illustrator's work and doubles as a link to the contact page.
The footer is permanently displayed. It also invites the user to get in touch with ideas for their personalised illustration and 
provides links to instagram, github and linkedin.

### Illustrations

A carousel showcases the illustrations and captions give information about the inspiration for each.
The footer is permanently displayed. It invites users to get in touch to request their own illustrations
and it provides links to instagram, github and linkedin.

### Collages

A very similar format to the illustrations page, but the carousel shows collages rather than illustrations.

### Contact Me

A contact form allows the user to get in touch with the illustrator to request their own personalised illustration.

---

## Further Development

* Form linked to Email - The contact form allows an email to be sent to the illustrator's email account.
* Photo Uploading - The contact form allows the user to attach photo inspiration to their email suggestions.
* Online Shop - Users will be able to purchase the illustrator's merchandise on the site.

---

## Technology

### Website Creation

* HTML
* CSS
* [Bootstrap](https://getbootstrap.com/) - used for multiply features, including the container/grid structure of the web pages, the carousel, contact form and navigation bar.
* [GoogleFonts](https://fonts.google.com/) - Amatic SC and Oswald were used for website fonts.
* [jQuery](https://jquery.com/) - Javascript needed for the navigation bar.
* [Hover.css](https://ianlunn.github.io/Hover/) - used to animate the GIF link on the home page.
* [Gitpod](https://gitpod.io/workspaces/) - used to write the code.
* [Github](https://github.com/) - used to host the repository.

### Illustrations and Collages

* [Gimp](https://www.gimp.org/) - free, open source software used to create all collages and earlier illustrations.
* [Adobe Illustrator](https://www.adobe.com/uk/products/illustrator.html?sdid=88X75SKT&mv=search&s_kwcid=AL!3085!10!79371087385139!79371161872161&ef_id=XlhCtwAAAXYYDhTJ:20200316211929:s) - used to create later illustrations.

---
## Testing

### Tools

The following tools were used to test the website code and layout throughout the development.
* [Google Chrome Developer Tool](https://developers.google.com/web/tools/chrome-devtools/) - used throughout the project to test code and scalability.
* [W3C Markup Validation](https://developers.google.com/web/tools/chrome-devtools/) - used to validate HTML code.
* [W3C CSS Validation](https://jigsaw.w3.org/css-validator/) - used to validate CSS code.
* [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) - used to resolve layout issues with web pages.
* [Contrast Ratio](https://contrast-ratio.com/) - used to ensure that colours meet readability guidelines.

### User Testing

The following scenarios were tested on all screen resolutions available through Google Developer Tools.

* General
    1. Hover over all header and footer links on all web pages to ensure that the appropriate colour changes occur.
    2. Click on on all header and footer links to ensure that it directs to the appropriate page.
    3. For social media links, click to ensure that external web pages open as a new link.
    
* Home Page
    1. Hover over illustration to check that hover animation occurs.
    2. Click on illustration to check that it directs to the contact page.

* Illustrations/Collages
    1. Use mouse and keyboard arrows to navigate through the carousel.
    2. Check that picture dimensions work on all screen resolutions.

* Contact
    1. Try to submit an empty form.
    2. Try to submit a form with some but not all fields empty.
    3. Try to submit a form without an @ in the email field.
    4. Try to submit a form with all fields filled in appropriately.

---
## Problem Solving

During the development of the website, there were some bugs identified.

* The footer did not reach to the bottom of the screen - this was resolved by changing the position to fixed.
* Applying styles only to the drop down navigation bar - Bootstrap code was examined through Chrome Developer Tools to identify the appropriate ID/class.
* Removing the transition animation on the Bootstrap navigation bar - this was resolved with the help of a Stackoverflow workaround. Link details in the CSS file.
* The illustrations/collages do not neatly fit with all screen resolutions - media enquiries were used to change from 100% width, auto height to 100% height, auto width to mitigate the issue.
* Logo and navigation bar do not remain within header bar when screen is stretched - this problem was not solved but the issue was mitigated by adding a background colour to the text, so it was more easily visible when it covered the main body of the page.

---

## Deployment

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/H4RP3RK/milestone_1_harperk), the following steps were taken: 

1. From the menu items near the top of the page, select **Settings**.
2. Scroll down to the **GitHub Pages** section.
3. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
4. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
5. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
 
### How to run this project locally

To clone this project from GitHub:

1. Under the repository name, click "Clone or download".
2. In the Clone with HTTPs section, copy the clone URL for the repository. 
3. In your local IDE open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/H4RP3RK/milestone_1_harperk.git
```
6. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

---

## Credits

### Content

Thanks to [Stack Overflow](https://stackoverflow.com/questions/13119906/turning-off-twitter-bootstrap-navbar-transition-animation) for helping 
me solve issues with the transition animation on my Bootstrap navigation bar.

### Illustrations and Collages

All images and collages were created by Kirsty Harper

### Acknowledgements

Thanks to my mentor, Jonathan Munz, for his invaluable support, advice and tips.
Thanks to all the Code Institute tutors for teaching me the skills I need to build the website.
Thanks to my partner, Dominic, for giving me cups of tea and encouragement whilst I shouted at the screen.
