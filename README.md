# Comments on Refactored Code

Please see below for a description of the changes made to the code and  following deployed page https://languagebytes.github.io/Horiseon-Social-Solution-Services/ 

![Test Image 1](screenshots/test.png)
![Test Image 2](screenshots/test2.png])

## Semantic HTML elements and SEO

 In order to make the webpage more informative and adaptable, I have substituted div elements for semantic elements, e.g nav, section, article, figure, and aside, where possible in the HTML file. This should improve its readability for other developers and enhance SEO by allowing browsers and search engines to better interpret its content. To improve SEO, I added in a meta description tag so which will appear when the website is featured in search results or sent as a link. I chose to display the name of the organisation as the site's title to be consistent with the rest of the site.

## Adding Comments  

To provide clarity for other developers accessing the code, I added comments to the HTML and CSS files and rearranged the structure in order of appearance on the site. Originally, the class for the Cover Image was called 'hero', I changed this to 'services'.

## Alt Text and Accessibility

 To meet accessibility standards, I added alt text to the images. I tried to be descriptive whilst keeping under 125 characters. Adding details about the image could provide a richer, more inclusive experience for those with visual imparements using screen readers. I also increased the font size slightly in the benefits section.

## An attempt... :) at Responsive Design

In order to make sure that the website would fit all browsers I added in a meta viewport tag in the head section and attempted :) to add in media queries to the CSS. In theory, this should help prevent the formating from becoming corrupted on smaller screens. However, I did not succeed this time with flexbox and if. I also added in a reset.css file to try to counteract any default formatting in the browser.

## Checking Links 

The first link "Search Engine Optimisation" was missing an id. I added an id so that when clicked it should direct the user to the section in the article about SEO. 

## Thoughts on Task

Overall, feel I may have missed some important details. I am not fully confident in what the standards are for SEO and limitations of google. This is something that I would like to do further research into after completing this task. Should a header tag also be used for the h2 tags? Although adding details about the image could provide a richer experience for those visual imparements using screen readers, on the other hand, I read that alt text needs to be consise as keyword stuffing leads to Google Penalties? Some clarification on this would be great.  I was not sure how to best to describe the icon images, do we need to describe the icons literally or what they represent? For example, . When it came to responsive design, I struggled to create the columned design for smaller devices, so went with zoomable screen.

