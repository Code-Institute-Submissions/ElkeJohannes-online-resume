# My Online Resume
The intention of this website is to provide prospective employers and potential collaborators with information about me, my work experience and how to contact me. The site also provides a showcase for my portfolio. 

---

## UX

### User stories
- As a potential employer, I want to be able to see what Elke has done in the past, to help me decide if I want to hire him.
- As a recruiter, I want to be able to see Elke's resume, to determine his marketability to my clients. 
- As someone with a great idea, I want to get a feel for Elke's personality, to determine if I would want to collaborate with him. 

### Strategy
The goal of the UI of this website is to be clear, beautiful and something special. A visitor should feel good when visiting the site to improve the chance of them feeling good toward me, it's creator.

### Scope
In order to be of use to both me and it's users, the site will contain the following pages:
- Home
- Work history
- About me
- Contact

To make it visually interesting there will be a clickable timeline on the work history page.  

### Structure
Being a simplistic site in terms of content, the lay-out will be matching that simplicity. There will be a seperate menu item for each feature. At the bottom there will be an area with links to LinkedIn and Github and an option for downloading my CV. At the home page there will be a testimonials section.

### Skeleton
- [Home](https://github.com/ElkeJohannes/online-resume/blob/master/assets/wireframes/Home.png)
- [Work History](https://github.com/ElkeJohannes/online-resume/blob/master/assets/wireframes/Work%20History.png)
- [About Me](https://github.com/ElkeJohannes/online-resume/blob/master/assets/wireframes/About%20Me.png)
- [Contact](https://github.com/ElkeJohannes/online-resume/blob/master/assets/wireframes/Contact.png)

### Surface
In terms of look and feel the website will feature nature backgrounds, some with myself in them. These will be set to a fairly high transparancy to not distract from the main content. 
The fonts will be Yeon Sung for the headlines with Song Myung for the main texts, to give a hint of asian affinity. 
The chosen color scheme:
![Color scheme](assets/images/color-scheme.png)
is based on the green nature backgrounds, with good contrasting colors for the menu and text.
All colors, fonts and images are chosen to be somewhat in line with things I am passionate about (Nature/permaculture, Japan) to aid in the "getting to know me" aspect of the website. Added to this is a shade of darkgrey that is also in line with the above.

---

## Features

### Existing features
- On the Work History page you can click on the dates in the timeline so jump to the appropriate section in the text. On Mobile this function sits behind a circular button on the bottom right. 

### Features Left to Implement
- 
---

## Technologies Used

HTML5 and CSS3 were used as the languages in which this site was made. Additionally the following frameworks/libraries were used:
- [Bootstrap 4.5](https://getbootstrap.com/)
    - The project uses **Bootstrap 4.5** to quickly setup mobile first design, and uses some features as described above in the features section.

---

## Testing
* Tested for valid code using [w3 validator](https://validator.w3.org/nu/#textarea)
* Tested for accessibility using [achecker](https://achecker.ca/checker/index.php)

## Bugs encountered
1. The job text dissapears when you click on an item in the side-navigation. 
    * Fixed by assigning static heights. Explanation for the problem found in [this stackoverflow question](https://stackoverflow.com/questions/16094785/have-a-fixed-position-div-that-needs-to-scroll-if-content-overflows)
2. At the larger screen sizes the columns on the work history page no longer allign.
    * Fixed by removing the number of columns in the class name. This enables it to just fill up the remaining space besides the first column.
3. At mobile screen size, the background overlay does not display all the way down the page (stops after assigned height)
    * Fixed by adding the property overflow: auto and rearranging the order of elements in the css.
    
---

## Deployment

---

## Credits

### Content
* All text is written by myself

### Media
* Testimonial images taken from [Unsplash](www.unsplash.com)
    * Man1 from [shipnorth](https://unsplash.com/@shipnorth)
    * Man2 from [rodreis](https://unsplash.com/@rodreis)
    * Woman1 from [matfelipe](https://unsplash.com/@matfelipe)
* Background image is a photo taken by myself

### Acknowledgements
- Tips and links provided by my mentor: Nishant Kumar (used links provided below)
- Inspiration for a good README file taken from the [Code Institute example README project](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive)
- Looked for inspiration on design ideas on [Colleinfogeek](https://collegeinfogeek.com/personal-website-examples/)