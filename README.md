# "The Monkees" Web page

Milestone Project: User-Centric Frontend Development - Code Institute

This is a website for a rock band called "The Monkees".
It introduce all the band`s members, some of them tracks, photos and video clip.
It also gives a user opportunity to download either Android or iOS app for their mobile device to access latest news and information.
They can also find information regarding tours and concerts a swell as contact them throe a form.

## Wireframe

A live demo can be found [here](https://balsamiq.cloud/s20a0gj/pek4zod).

![wireframe](https://user-images.githubusercontent.com/47479588/57972072-b412ee80-798d-11e9-8ae1-2e19fd8c4742.jpg)

## Demo
A live demo can be found [here](https://rafaljanos.github.io/the-monkees/).

![demo](https://user-images.githubusercontent.com/47479588/57892232-1c4ebc80-7836-11e9-860d-2851e1bda3d3.jpg)

## UX

My aim in the design was to easy access and navigate to desired information on the site. 

For users, I was aiming to outline general information about the bands history its members. On the home page I gave users opportunity to download mobile app to have access to latest news and information if they like.
There is a gallery page to give them a glimpse of how the band looked when they started and also how they look now. They can find tracks and video clip to check out their music.
And for those who wish to see them live a page with upcoming concerts and gigs which include addresses and dates. And on the last page I`m giving users chance to contact bands management team if they wish to organize a gig.
From every page there is an access to bands Tweeter, Facebook and YouTube account.

## Technologies

#### 1.HTML

![](http://www.iconarchive.com/download/i73026/cornmanthe3rd/plex/Other-html-5.ico)

#### 2.CSS

![](https://cdn.iconscout.com/icon/free/png-256/css-118-569410.png)

#### 3.Bootstrap (4.3.1)

![](https://pkp.sfu.ca/wp-content/uploads/2016/09/bootstrap-logo.png)

## Software

#### Software used to create this website:

Wireframe was created on Balsamiq:

![](https://media.balsamiq.com/files/company/balsamiq-logo-print.png)

The bands logo was custom made by me using Corel Draw:

![](http://global.ingrammicrocloud.com/uk/wp-content/uploads/sites/22/2018/02/app-icon-cdgs.png)

All photos and backgrounds ware edited using Corel Photo-Paint:

![](https://www.coreldraw.com/static/cdgs/product_content/cdts/2018/app-icons/app-icon-pp.png)

## Features

This site uses Bootstrap Grid system.
Navigation bar is fixed and stays on top of the screen, it uses Bootstrap font-awesome. Navbar also stays 
collapsed in mobile view to free some room for content.

## Features Left to Implement

In the future, I am planning to add more photos and links to external sources for more music, track and video clips. 
I wish also to add Google maps for each concert address for easy gps navigation.
Add slide shows to gallery and animated background to home page. 

## Supporting sources :

- Code Institute Training Materials
- Slack
- YouTube Tutorials
- Several Coding Forums
- Wikipedia
- Mentor

## Testing

The home page achieved the intended outcome by providing the user with short introduction of the band and also 
quick access to a download site with the original band`s app.
All of the pages give user quick and easy access to band social media accounts like Facebook, Tweeter and 
Youtube channel via Font Awesome icons. User can also get the exact time, date and place of any upcoming 
venues this year. On the mobile view navbar is collapsed and let the user to navigate throe all websites 
quickly and without compromising on content that fits on their screens.

If you try to submit the contact form with an invalid email address, there will be an error noting the 
invalid email address. There is also the "required" attribute added to all fields, so in case one of them 
is skipped the form will not submit.
Only when all the fields will have a correct content, the form will go through.

All provided links will open in a new tab using "target=_blank" attribute. They all have been manually 
tested to ensure they all go to the correct destination.

All the navbar Font Awesome icons are in the same position across all pages, they all grow on hover by using "hvr-grow-shadow" class.
Navbar in mobile view will turn in to a hamburger menu at screen resolution smaller than 992px  using a "@media" media queries. 
And will stay the same across all pages, all pages links will also grow on hover like on big screen but will have no Font Awesome 
icons with them to minimise taken space. All navbars links are in the same order on a big screen and small screen collapsed bar.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on 
multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. 

During the testing phase I came across several errors and warnings on each page:

##### HOME page:
- Warning: Consider adding a Lang attribute to the html start tag to declare the language of this document.
 (helps search engines return language specific results)
- Warning: Section lacks heading. Consider using h1-h2 elements to add identifying headings to all sections.
 (heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading)
- Error: Element div without attribute label must not be empty.
- Error: Bad value 100px for attribute width on element img: Expected a digit but saw p instead.
 (HTML5 supports only px as default)

##### GALLERY page:
- 10x Error: An img element must have an alt attribute, except under certain conditions. 
 (alt attribute is used in HTML documents to specify alternative text that is to be rendered when the element to which it is applied cannot be rendered)
- 10x Error: Bad value 100px for attribute width on element img: Expected a digit but saw p instead.
- Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.
  (heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading)
- Warning: Consider adding a lang attribute to the html start tag to declare the language of this document.
 (helps search engines return language specific results)

##### TRACKS page:
- Warning: Consider adding a lang attribute to the html start tag to declare the language of this document.
 (helps search engines return language specific results)
- Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.
  (heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading)
- Error: Bad value 100px for attribute width on element img: Expected a digit but saw p instead.
 (HTML5 supports only px as default)

##### SHOWS page:
- Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.
 (heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading)
- Error: Bad value 100px for attribute width on element img: Expected a digit but saw p instead.
- Warning: Consider adding a lang attribute to the html start tag to declare the language of this document.
 (helps search engines return language specific results)

##### BOOK page:
- Error: Element option without attribute label must not be empty.
- Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.
  (heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading)
- Warning: Consider adding a lang attribute to the html start tag to declare the language of this document.
 (helps search engines return language specific results)

### Validation 

#### CSS
[Done here](https://jigsaw.w3.org/css-validator/)

#### HTML
[Done here](https://validator.w3.org/)

#### Spelling
[Done here](https://www.jspell.com/public-spell-checker.html)

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. 
The deployed site will update automatically upon new commits to the master branch. 
In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.
To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone
https://github.com/rafaljanos/the-monkees.git` into your terminal. To cut ties with this GitHub repository, 
type `git remote rm origin` into the terminal.

The wireframe is hosted using Balsamiq page, deployed directly from the master branch. 
To run the demo copy this link: `https://balsamiq.cloud/s20a0gj/pek4zod` directly in to your web browser.

## Credits

#### Content

All content in "Home" page was taken from [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees) website.

All content in "Shows" page was taken from [Songkick](https://www.songkick.com/artists/485568-monkees/calendar) website.

#### Media

Bands photos and a video clip were provided by Code Institute and the rest was taken from [monkees.net](https://www.monkees.net/category/photos/) website.

All the background images and also "SHOWS" page images were taken from Google search images. 

#### Acknowledgements

The hamburger navigation bar was found and customized through [MDB](https://mdbootstrap.com/docs/jquery/navigation/hamburger-menu/) website.

#### This is for educational use.

## Author

Rafal Janowski