# Refactoring Challenge

## Horiseon needs help! 

Horiseon, a marketing agency, wants a codebase that follows accessibility standards so that their site is optimized for search engines. 

Great news! I've been learning about refactoring websites for better accessibility, and I made a few updates to the code which I hope they like.

I updated so many things
* When I viewed the source code, I found most HTML elements were generic. I updated these to follow semantic conventions.
* When I viewed the structure of the HTML elements, I found that logical structure was hard to follow without seeing the styling and positioning, so I grouped elements logically and used ARIA attributes.
* When I veiwed the image elements, I did not find accessible alt attributes, so I added some crisp descriptions of the images. 
* When I viewed the heading attributes, I realized they did not fall in sequential order. This was an easy fix, I just changed the h2 in the footer to h4 in the .html and .css files.
* When I viewed the title element, I found that I needed to update the text to a consise, more descriptive title. 
 
I learned that there are even more ways to make websites more accessible! I was able to address a few extra concerns that horiseon didn't even realise could help. 
* I updated contrast ratio between the text and the background by in teh sidebar section. 
* Where there were icons I used aria-hidden='true' so that web readers would not get bogged down. 
* I applied my aria learinings to attribute the most important HTML elements, which will enhance the screen reader's understanding of the HTML structure.
* I discovered that a line height of at least 1.6 is easiest for sighted viewers, and so is a bit more space around each letter, so I fixed these right up.
* It can be hard to know which elements are links for some viewers, so I added underline styling to the navigation links. 
* Some fonts are easier on the eyes for sighted readers, so I changed teh font family to "Ariel, Helvetica, san-serif" which was recomended by most websites I referenced.

Technology used
* HTML
* CSS
* GitHub

## Installation & Usage

To use this, all you need to do is click this link: 

[https://michellebaker1129.github.io/accessibility-challenge/](https://michellebaker1129.github.io/accessibility-challenge/)]

And my [https://github.com/michellebaker1129/accessibility-challenge](https://github.com/michellebaker1129/accessibility-challenge)

This shows my work

![website after my work](https://github.com/michellebaker1129/accessibility-challenge/blob/main/Develop/assets/images/readme-image-before.png?raw=true)

And this is how it looked before

![website after my work](https://github.com/michellebaker1129/accessibility-challenge/blob/main/Develop/assets/images/readme-image-after.png?raw=true)

## Credits

I've learned everything I know from 
* Berkeley Coding Boot Camp https://bootcamp.berkeley.edu/codingbootcamp/officialsite 

I relied heavily on 
* W3Schools Online Web Tutorials https://www.w3schools.com
* MDN Web Docshttps://developer.mozilla.org
* Siteimprove Accessibility Checker https://chrome.google.com/webstore/detail/siteimprove-accessibility/djcglbmbegflehmbfleechkjhmedcopn/related?hl=en
* WAVE Chrome, Firefox, and Edge Extensions https://wave.webaim.org › extension 

And I studied with the best learning partners
* Jedd Javier [https://github.com/jeppjeppjepp0](https://github.com/jeppjeppjepp0)


## License

[LISCENSE.md](LISCENSE.md)

MIT License

Copyright (c) [2023] [TiaBakerBrown]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
