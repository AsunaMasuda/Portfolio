# Asuna Masuda Portfolio
Milestone Project #1 : User-Centric Frontend Development - Code Institute 

This is my portfolio website to present to prospective employers. The portfolio shows my career and education history and highlights my skills and several projects that cover a wide range of technologies in software development and data science. Also, it contains a contact form for the visiters who are interested in contacting me.

## Demo
[Live demo](https://asunamasuda.github.io/Portfolio/) is available here.

<p align="center"><img src = "https://github.com/AsunaMasuda/Portfolio/blob/master/images_readme/Screen%20Shot%202020-02-18%20at%2019.47.55.png" width=700></p>

## UX

### User stories
The users who would see this portfolio could be recruiters and managers of the prospective company and team.

For the recruiters, they would be curious about my education and career history.
<p align="center"><img src = "https://github.com/AsunaMasuda/Portfolio/blob/master/images_readme/Screen%20Shot%202020-02-18%20at%2019.49.15.png" width=700></p>


For the managers, they would be interested in my technologies skill sets and the projects I've completed so far. 
<p align="center"><img src = "https://github.com/AsunaMasuda/Portfolio/blob/master/images_readme/Screen%20Shot%202020-02-18%20at%2019.49.24.png" width=500><img src = "https://github.com/AsunaMasuda/Portfolio/blob/master/images_readme/Screen%20Shot%202020-02-18%20at%2019.49.30.png" width=500></p>


### UX Strategy

#### Structure
- Utilized a responsive navigation bar which makes it easy to navigate and recognize where the visiters are in the site. This navbar collapses with smaller screen sizes, so the navbar section does not get busy with letters.
- The footer section holds icons and links to my Github and LinkedIn accounts.

#### Design
- Chose moderate and beautiful backgrounds.
- Unified the colors using blue, yellow and pink with darker tones.
- When hovering over any links, they return a yellow colour so that they can unify the site.

#### Contents
- Kept the words as simple as possible as I wanted the visiters easily to glimpse of who I am.
- Visualized the skills with the filled & unfilled stars so they can easily grasp my skills at a glance.

#### Wireframes
- [Landing Page wireframe](https://github.com/AsunaMasuda/Portfolio/blob/master/mockups/LandingPage.pdf)
- [About Me wireframe](https://github.com/AsunaMasuda/Portfolio/blob/master/mockups/AboutMe.pdf)
- [Projects wireframe](https://github.com/AsunaMasuda/Portfolio/blob/master/mockups/ProjectWork.pdf)
- [Contact wireframe](https://github.com/AsunaMasuda/Portfolio/blob/master/mockups/ContactMe.pdf)


## Technologies
1. HTML
2. CSS
3. Bootstrap (v4.4.1)
4. JavaScript (Contactform, Tooltips, Navigation Bar)

## Features Left to Implement
- At the moment, submit button just replies and alerts message. In the future, I'd like to connect my email address so I can receive messages. 
- More animations when hovering over some parts of the site with JavaScript. E.g. the stars in the skill section could respond.

## Testing
This site was tested across multiple browsers for desktop PCs (Chrome, Safari, FireFox, Opera) and on multiple mobile devices using Google developer tool(iPad, iPad Pro, iPhone X, iPhone 6/7/8 (Plus), iPhone 5/SE, Pixel 2 (XL), Galaxy S5) to ensure compatibility and responsiveness. 
During the testing phase, I noticed the background image for the landing page was not fully displayed for bigger screens, so "height: 100vh; width: 100vw;" was added to the background class. Also, I noticed the layouts of containers in each section were not consistent as the screensize changes, so I added multiple media queries to keep layouts neat and beautiful. 

## Development
- I used Gitpod for a developer tool (IDE) in this project.

## Deployment
This site is using a custom domain with GitHub pages, deployed directly from the master branch. The deployed site will be updated upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

## Credits

### Content
All html and css files in the "AsunaMasuda/Portfolio" repository in Github were written by Asuna Masuda.

### Media
#### Icons
- The icons were provided by [Font Awesoms](https://fontawesome.com/)
- The favicon was made by [Freepik](https://www.flaticon.com/authors/freepik) from [Flaticon](https://www.flaticon.com/).

#### Background Photos
- The landing page: by Elizaveta Kozorezova from Pexels
- About Me section: by 邱韬 from Pexels
- Work History & Skills: by Asuna Masuda
- Project Work section: by Magda Ehlers from Pexels
- Contact section: by David Sun from Pexels

### Acknowledgements
- I refered to the JavaScript snippets of [Tooltips](https://www.w3schools.com/bootstrap/bootstrap_tooltip.asp), [Navbar](https://getbootstrap.com/docs/4.4/components/navbar/) and [Scrollspy](https://getbootstrap.com/docs/4.4/components/scrollspy/), explained in the links respectively.
- I refered to [this article by Madhav Bahl](https://hackernoon.com/use-custom-domain-with-github-pages-2-straightforward-steps-cf561eee244f) for how to use custom domain with Github pages
- For screen size optimizations, I refered to this article: [Optimizing for Large-Scale Displays](https://css-tricks.com/optimizing-large-scale-displays/)
