# Refactoring Challenge

## Time to make this website more accessible! 

Horiseon, a marketing agency, wants a codebase that follows accessibility standards so that their site is optimized for search engines. 

Great news! I've been learning about refactoring websites for better accessibility, and I made a few updates to the code which I hope they like.

I updated so many things
* When I viewed the source code, I found most HTML elements were generic. I updated these to follow semantic conventions.
* When I viewed the structure of the HTML elements, I found that logical structure was hard to follow without seeing the styling and positioning, so I grouped elements logically and used ARIA attributes.
* When I veiwed the image elements, I did not find accessible alt attributes, so I added some crisp descriptions of the images. 
* When I viewed the heading attributes, I realized they did not fall in sequential order. This was an easy fix, I just changed the <h2> in the footer to <h4> in the .html and .css files.
* When I viewed the title element, I found that I needed to update the text to a consise, more descriptive title. 
 
I learned that there are even more ways to make websites more accessible! I was able to address a few extra concerns that horiseon didn't even realise could help. 
* I updated contrast ratio between the text and the background by in teh sidebar section. 
* Where there were icons I used aria-hidden='true' so that web readers would not get bogged down. 
* I applied my aria learinings to attribute the most important HTML elements, which will enhance the screen reader's understanding of the HTML structure.
* I discovered that a line height of at least 1.6 is easiest for sighted viewers, and so is a bit more space around each letter, so I fixed these right up.
* It can be hard to know which elements are links for some viewers, so I added underline styling to the navigation links. 
* Some fonts are easier on the eyes for sighted readers, so I changed teh font family to "Ariel, Helvetica, san-serif" which was recomended by most websites I referenced.


This is how my work looks now 

![website after my work](assets/readme-image-after.png)


## Installation

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.


## Usage 

Provide instructions and examples for use. Include screenshots as needed. 

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

```md
![alt text](assets/images/screenshot.png)
```


## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.


## License

The last section of a good README is a license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, use [https://choosealicense.com/](https://choosealicense.com/)


---

🏆 The sections listed above are the minimum for a good README, but your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

Badges aren't _necessary_, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, consider adding a heading called "Features" and listing them there.

## Contributing

If you created an application or package and would like other developers to contribute it, you will want to add guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them.

---

© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.