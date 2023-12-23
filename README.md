# Marketing Website Refactored

## Description

I built this project beginning with starter code, and I refactored the code in order to improve its quality, accessibility, and sustainability. Originally, the code included multiple bugs which impeded its functioning. Furthermore, the starter code did not follow a logical structure with semantic HTML elements and thoughtfully organized CSS selectors. The code was not very highly customizable or easy to maintain as it was first received, and it needed improvements to become more sustainable long-term. So, it was essential to refactor the code to improve its quality and functionality; to ensure the website would be accessible to browsers, devices, and people, in all their variations; and to increase its ability to be modified and well-maintained over time. 

In order to understand the changes made when refactoring the code, as well as their importance, please see the below descriptions of some of the modifications to the code:

* The original code included multiple bugs. 


  * A closing tag was used for the cost-managment.png image element, which was problematic as the image element is self-closing. I changed the syntax to follow the proper syntax of an image element.


  * The content on Search Engine Optimization (SEO), Online Reputation Management (ORM), and Social Media Marketing (SMM) wes referred to inconsistenty in the HTML versus CSS, sometimes using id attributes and sometimes using classes, with a lack of coherent logic on the whole. I ultimately used id attributes to identify and select the content on SEO, ORM, and SMM for styling (in addition to using a classes to style the images in these sections).


* The code was not very semantic or accessible originally. 


  * The code used many `<div>` elements in a way that did not effectively show the purposes of the different parts of the code to the developer, browser, or screenreaders. I replaced the `<div>` elements with semantic elements including `<header>`, `<nav>`, `<section>`, `<main>`, `<aside>`, and `<footer>`.


  * The images did not have alt attributes when I received the starter code. I added alt attributes so that a description of the image is accessible even if the actual image is not accessible for the user for any reason.


* The codebase needed updates in order to improve its long-term sustainability.


  * Several CSS selectors had the same style definitions---in order to update the styling in the future, it would have been necessary to update the style definition in each place. I used the CSS Grouping Selector to consolidate, so that the code would need to be modified in fewer places in order to update styling. Where possible, I used only one class to select and style content needing the same styling.


  * The code did not originally take advantage of variables in order to quickly assign colors and modify them easily in the future. With my updates, the colors used for styling can be changed in all of their instances by simply modifying the color stored in the appropriate variable under the Universal Selector.


The refactored code allows us to view the web page with its intended functionality, provides increased accessibility, and allows smoother updates in the long-term.

## Installation

No installation is required to view this project. 

## Usage and Features

* In order to use this project, navigate to the website at [sara-hines.github.io/marketing-agency-website-refactored](sara-hines.github.io/marketing-agency-website-refactored 'GitHub Pages Link').


* When the user navigates to the web page, it will have the following appearance:


  * When the page loads, the user will be able to view the header, which includes the name of the marketing agency (Horiseon), and a navigation bar. The hero image of a marketing meeting will display below the header. The sections on SEO, ORM, and SMM will appear below the hero image, each with their own heading, text description, and image (or alt attribute text, if the image is inaccessible). A sidebar will also be viewable to the right of those sections. The sidebar will display headings, text descriptions, and icons corresponding to the following topics: Lead Generation, Brand Awareness, and Cost Management. A footer with the centered text, with black font color, "Made with ❤️️ by Horiseon" and "© 2023 Horiseon Social Solution Services, Inc." will appear at the bottom of the page. 


  * The header will have a dark blue background color and light off-white text, with the exception of the "seo" within "Horiseon," which will have a medium-light grey color. 


  * The page will have a background color of a medium-light grey. 


  * The boxes containing information on SEO, ORM, and SMM will have a dark blue background color and light off-white text.


  * The sidebar box containing the information on Lead Generation, Brand Awareness, and Cost Management will have a dark blue background and light off-white text.


  * When hovering over the tab for the web page in the browser, the user will be able to view the title of the page.


  * When the user clicks on the Search Engine Optimization, Online Reputation Management, or Social Media Marketing text within the header, the web page will navigate to the Search Engine Optimization, Online Reputation Management, or Social Media Marketing section of the page, respectively. 


  * See the screenshots below to view the alignment and positioning of the boxes, headings, text, and images.
 
  

<img width="960" alt="screenshot-1" src="https://github.com/sara-hines/marketing-agency-website-refactored/assets/90005274/5a3b53e8-eb10-462e-be76-25c7d654ecc6">

<img width="960" alt="screenshot-2" src="https://github.com/sara-hines/marketing-agency-website-refactored/assets/90005274/e1685304-2a9c-4851-92b4-31c7a76fceb8">

<img width="960" alt="screenshot-3" src="https://github.com/sara-hines/marketing-agency-website-refactored/assets/90005274/a8c0131d-963f-40ec-bc3d-fec3714831d1">



### The Funtionality of the Hyperlinked List Items in the Navigation Bar

When a user clicks on "Search Engine Optimization" in the navigation bar, the page will jump to the section on Search Engine Optimization, as seen in the below screenshot.



<img width="960" alt="screenshot-nav-to-seo" src="https://github.com/sara-hines/marketing-agency-website-refactored/assets/90005274/7f3471ef-3032-4dc1-9ec4-412c67ec1337">



When a user clicks on "Online Reputation Management" in the navigation bar, the page will jump to the section on Online Reputation Management, as seen in the below screenshot. 



<img width="960" alt="screenshot-nav-to-orm" src="https://github.com/sara-hines/marketing-agency-website-refactored/assets/90005274/9efb384d-f8a7-450d-a789-567b59854e2a">



When a user clicks on "Social Media Marketing" in the navigation bar, the page will jump to the section on Social Media Marketing, as seen in the below screenshot. (This may appear a bit different from device to device and browser to browser.)



<img width="960" alt="screenshot-nav-to-smm" src="https://github.com/sara-hines/marketing-agency-website-refactored/assets/90005274/122241d2-5384-4c71-8c08-08ae76c3dd32">




### The Functionality of the Image Alt Attributes

If the images are unable to be accessed for some reason, the web page will display text descriptions of the images instead, as seen in the below screenshots.



<img width="960" alt="screenshot-img-alt-1" src="https://github.com/sara-hines/marketing-agency-website-refactored/assets/90005274/a3eb4578-54e4-4ca5-b5f2-f437c1c92867">

<img width="960" alt="screenshot-img-alt-2" src="https://github.com/sara-hines/marketing-agency-website-refactored/assets/90005274/d1b2df12-a9f7-4745-be20-8570cba217f0">



## Credits 

I reached out to the TA of my Full Stack Coding Bootcamp at University of Denver, who provided helpful advice on starting the refactoring project with the HTML rather than the CSS, and had the idea to use id attributes for some of the unique content. I appreciate his help starting me on the right track!

In these first weeks of my bootcamp, I have been learning a large volume of introductory material from [MDN Web Docs,](https://developer.mozilla.org/en-US/) [W3Schools,](https://www.w3schools.com) and materials provided as part of the bootcamp. I used these sources to reference concepts and to troubleshoot while creating this project, but my words and work are my own. 

## License

This project is licensed under the [MIT license](https://opensource.org/license/mit/). The license can be accessed in the repository. 
