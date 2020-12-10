# Code Refactor Example
### This is my README file. There are many like it, but this one is mine

-----------------------
## Description
This site is an example in refactoring HTML and CSS code.  My 'employer' tasked me with cleaning up Horiseon webpage. While the site was functional from a users perspecive, the underlying code could be cleaned up to make it easier to read for future developers looking to make changes.

-----------------------
## Site Picture
![Site](assets/readme-assets/site-picture-example.png)

-----------------------
## Code Snippet
Changed div tags to section and article semantic elements and made necessary adjustments to css file. Added alt tags to all images.

NEW CODE
```
<section>
    <article id="search-engine-optimization" class="search-engine-optimization">
        <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="Search engine optimization"/>
        <h2>Search Engine Optimization</h2>
        <p>
            ...
        </p>
    </article>
</section>
```
OLD CODE
```
<div>
    <div id="search-engine-optimization" class="search-engine-optimization">
        <img src="./assets/images/search-engine-optimization.jpg" class="float-left"/>
        <h2>Search Engine Optimization</h2>
        <p>
            ...
        </p>
    </div>
</div>
```
-----------------------
## Prerequisites
A computer with an active internet connection

-----------------------
## Installing instructions
None

-----------------------
## Built with
- HTML
- CSS
- Git
- Github

-----------------------
## Deployed Link
https://akhalid88.github.io/code-refactor-example/ 

-----------------------
## Licenses
This Project is licensed under MIT license

-----------------------
## Author: Muhammad A Khalid

[LinkedIn](https://www.linkedin.com/in/abdullahkhalid/)
<br>
[GitHub](https://github.com/akhalid88)

-----------------------
## Acknowledgements
- Jerome Chenette (Instructor)
- Manuel Nunes (TA)
- Mahisha Manikandan (TA)