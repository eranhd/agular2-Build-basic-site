# Angular2 build basic site
**Sumbission rules:**<br>
all files should be in the github assignment repository. you should include a link to Firebase url in README.md file.

## wireframe
look at [this](https://wireframe.cc/N7lR5G) wireFrame,<br>
this site contain 3 major element:
* Header
* Paragraph about your self
* Gallery

for each element create component and design your component like the wireframe.

### Header
to header component add:
* title - the site title 
* logo - some picture
* decription of your site
* create another comonent which describe the nav elements(button) and service for nav array. each nav contain text and description

### Main
to the main section add hat you want

### Aside
create new service which contain array of image url and title (e.g {url: "", title:""})  <br>
For aside section,  add 2 pictures (<img> tag) that switched every 10 seconde. the picture contain image and above of picture write the picture title's

<hr>
the navigation menu template should iterate on the array and make the navigation items, pass the object to nav-item with @Input() decorator. Style the app as you wish.

deploy app into firebase and commit your change.<br>
push your code (this repository) and add the firebase url into readme file
.<br>good luck
