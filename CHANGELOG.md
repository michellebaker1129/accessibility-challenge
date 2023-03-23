## 2023-03-01 

## CSS
- Text and background color should have sufficient contrast - update aside background color to body background color
- Font family updated to more accessible "Ariel, Helvetica, san-serif" using CSS universal selector
- Links should be visually identifiable: update text-decoration in header
- Font size is above 16px (12pt) throughout - verified


## HTML
- Use descriptive section headings: <div> change to <header>, <section>, <aside>, etc

- Page content should be contained by ARIA landmarks: 
    banner (added to class="header")
    navigation (added to first div)
    main (added to class="content")
    contentinfo (added to class="footer")

        In HTML5, you should use elements like header, nav, main, and footer. Their ARIA counterparts are role="banner", role="navigation", role="main", and role="contentinfo", in that order. By using both HTML5 and ARIA markup, you make the webpage more robust and functional no matter what screen reader technology is used.
            - Siteimprove Accessibility Checker https://chrome.google.com/webstore/detail/siteimprove-accessibility/djcglbmbegflehmbfleechkjhmedcopn/related?hl=en

- Images should have meaningful alternative text, updated for 3 .jpg and 3 .png images

- Use a descriptive title tag: "website" changed to "Horiseon"

## Credits
  - Siteimprove Accessibility Checker https://chrome.google.com/webstore/detail/siteimprove-accessibility/djcglbmbegflehmbfleechkjhmedcopn/related?hl=en
  - https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh
