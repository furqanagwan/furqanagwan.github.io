# My Website
Welcome to my Website. The website acts as a CV/Resume for myself and was designed as part of one of my University Assignments.
This website will be updated and maintain by self as soon as new information about me is released. Information such as current job or projects I am currently working on or contributing to, further more new technologies I have learned will be updated on my website.

This Website is also optimized well for mobile users. The aim was to keep the website simple as it is not a big project, or requires any server-side interaction. The information below shows all the API's, references and technologies used to create this website. Information regarding challenges and Website thought and design process
## Assessment
Links to this GitHub pages website and the project repository are below. A txt file has also be added to the project file structure which includes student information such as p-number and name (Assessment Purposes).
[link:](https://fugster101.github.io/)
[link:](https://github.com/fugster101/fugster101.github.io)
A link to all my other projects is displayed below
[link:](https://github.com/fugster101?tab=repositories)

## Hand-drawn Tree Structure
### Initial Design
### Final Design
# Responsive Web Design
As part of my assessment responsive design was an essential marking criteria for the website. The website was design mobile first in mind making transition to the desktop version of website was smooth and easy. Responsive design also includes responsive images, multimedia and responsive text making sure they fit any browser.
## Mobile First
All CSS for mobile is written first with no media query rule defines making the styles default for the given webpage. Media queries have been defined for screen sizes with a minimum width of 800px or more. This allows me to write further CSS for specific screen sizes in the future. In total there is only one breakpoint defined although more can be implemented for example:
* *iPhone Specific*
* *iPad Specific*
* *4K/5K Monitors and iMac's*
Upon resizing the users windows the website will automatically kick in the different CSS stylesheets.
## SiteMap
The following section shows the XML markup and HTML site structure (Tree Form) of my website. The XML is particular useful for Search engine optimization for Google and Bing. A xml file of the sitemap is provided in the sitemap folder which is also indented and formatted correctly.
### XML Version
```xml
<?xml version="1.0" encoding="UTF-8"?>
-<urlset xsi:schemaLocation="http://www.sitemaps.org/schemas/sitemap/0.9 http://www.sitemaps.org/schemas/sitemap/0.9/sitemap.xsd" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
-<url>
<loc>https://fugster101.github.io/</loc>
<lastmod>2017-12-12T21:58:30+00:00</lastmod>
<priority>1.00</priority>
</url>
-<url>
<loc>https://fugster101.github.io/about.html</loc>
<lastmod>2017-12-12T21:58:30+00:00</lastmod>
<priority>0.80</priority>
</url>
-<url>
<loc>https://fugster101.github.io/work.html</loc>
<lastmod>2017-12-12T21:58:30+00:00</lastmod>
<priority>0.80</priority>
</url>
-<url>
<loc>https://fugster101.github.io/documents/FurqanSakirAgwan-CVWebsiteEddtion.docx</loc>
<lastmod>2017-12-12T21:58:30+00:00</lastmod>
<priority>0.64</priority>
</url>
</urlset>
```
### HTML Version
# Cross-Compatibility
Due to the nature of the Assessment cross-Compatibility was not part of the making criteria and was told not to worry about it. Although future implementations of the website will accommodate for other browsers except for internet explorer because its rubbish.

Animations may not work due to no web kit CSS prefixes.
# Additional Notes
## For the Marker
Please make sure the browser is chrome with the latest update for Compatibility reason chrome works bests and this website was designed and tested using chrome and its inspector feature to point out any errors and element position's and their respective styles.

I have tried to remove redundant code and resources to keep webpage request time from GitHub servers as fast as possible. I have also resized all images to 1080p and nothing more as I felt that would have been an optimal image size and is not too resources intensive.

External files provided on a CDN have to contribute to the loading speed of the website. I am pulling various CSS and JavaScript files from 3rd party libraries hosted on GitHub such as Animate on Scoll (AOS) and Fontawesome. Information regarding these 3rd party libraries are in the references section.

For the most part of working on this website most of the commits have been pushed to the master branch and so live website was also update, but more recently I have created a new branch to push commits to. The new branch "websitetestbranch" contains all the same code and markdown but acts as a testing project and so when I feel I have made major changes I will merge the branch back to the master branch.

All multimedia and images used in this website were provided by Pixelbay and all authors have released their images under the Creative Commons (CC0) license.

The design thought and process regarding this website was simple. The idea was to create a simple CV webiste that showcased the normal things you would expect to see on a regular CV. This includes interest and hobbies, technologies I am interested in etc. The website does contain a downloadable cv that user can download if they wish to , however the document is password protected and so editing and copying on the document is not possible.

Feel free to download any files located on the repository if you wish to keep them locally.

## Validation and Verification

All webpage pass the W3C CSS and HTML validator, there are some warnings when some of the HTML pages are validated.

## *References*
(2017) W3Schools Online Web Tutorials. [Online] Available from: [](https://www.w3schools.com/) [Accessed 1/11/2017]
(2017) CSS-Tricks. [Online] Available from: [](https://css-tricks.com/) [Accessed 1/11/2017]
(2017) Create your Google Sitemap Online - XML Sitemaps Generator. [Online] Available from: [](https://www.xml-sitemaps.com/) [Accessed 2/11/2017]
