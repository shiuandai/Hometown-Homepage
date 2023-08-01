<h2 align="center">Hometown-Homepage</h2>

<p align="center">
  <em> The hometown homepage is my first project of Scrimba Front-End course, in this course I build web designs from scratch and structure the code to finish the layout design.</em>
</p>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com) [![Join the chat at https://gitter.im/Front-End-Checklist/Front-End-Design-Checklist](https://badges.gitter.im/Front-End-Checklist/Front-End-Design-Checklist.svg)](https://gitter.im/Front-End-Checklist/Front-End-Design-Checklist) [![CC0](https://img.shields.io/badge/license-CC0-green.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

## Table of Contents
* **[1. Design requirements](#1---design-requirements)**
	* [1.1 Structure Design](#11---grid-system)
	* [1.2 Colors](#12---colors)
	* [1.3 Fonts and texts](#13---fonts-and-texts)
	* [1.4 Links and navigation](#14---links-and-navigation)
	* [1.5 Images / Icons](#15---images--icons)
	* [1.6 Forms and buttons](#16---forms-and-buttons)
	* [1.7 Responsive Web Design](#17---responsive-web-design)
	* [1.8 Style Guide and component approach](#18---style-guide-and-component-approach)
	* [1.9 Delivery files](#19---delivery-files)
* **[2. Analysis and pre-work phases](#2---analysis-and-pre-work-phases)**
	* [2.1 Paper analysis](#21---paper-analysis)
	* [2.2 Pre-development phase](#22---pre-development-phase)
* **[3. Validation](#3---validation)**
* **[4. Development phase](#4---development-phase)**
* **[5. Before production](#5---before-production)**

---

> The **Hometown Homepage** is my first static website which I introduce my hometown spots and the brief information to visitors who can review from and knowing more Taiwan culture. Welcome to contact me if you need a local tour guide.

I start the Scrimba Module 2 course- Web dev basics and learn how to use basic HTML & CSS knowledge. At the end of the course, I follow the Figma template to finish my hometown page where you can know more about me, take a look on the → [My Hometown Homepage](https://shiuandai.github.io/Hometown-Homepage/).

## How I start the project?

* Ensure all points are taken into consideration from Figma Template. → [Figma Template from Scrimba](https://www.figma.com/file/2QuGfAOcHaZJ6aHXfuamnK/Hometown-Homepage?type=design&node-id=0%3A1&mode=design&t=JhG1UWTiUmIeW14l-1)
* Having a materials preparation document where I collect pictures/text information/text font/color to match a better visual communication and coherence in one page.
* It's important to brainstorm the HTML structure before starting coding, this step helps me save the time.
* Use the "DRY" concept (Don't Repeat Yourself), so that I learn from tailoring the developer's code and learn from it and Scrimba course.
* To show the completed work between a Web and a template, I prefer refining the CSS code to make sure the project can align the design.

---

## 1. - Design requirements

Designing a homwtown homepage website requires following some rules and taking into consideration that the project is not only a graphic project but a web project too. The next sections are crucial for any web project.

### 1.1 - Structure design

* [ ] **HTML** is "HyperText Markup Language" It defines the meaning and structure of web content. The Web Designer should keep the structure simple and the similar content chould be grouped together to make sure it can be read clearly.
	> ℹ️ [HTML] GET to know more about the definition. → [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML)

* [ ] **Be familiar with the HTML** I’ll be familar with the HTML by learning more its <tag>. 
* [ ] Before working on each website project, I can **build every templates** with my own strcutre concept. Building the structure before everything else, will facilitate my work afterwards.

```html
<div class="container">
  <div class="row">
    <div class="col-sm">
    </div>
  </div>
</div>
```

⚠️ *Use the container to define which tags should be contained inside, they can be active when using the **flex-box**, it is a crucial method to foster the strcture building.* 

**[⬆ back to top](#table-of-contents)**

### 1.2 - Colors

You can "SAVE" your color preference in your account. → [Color Palette](https://scrimba.com/links/hometown-palette)

* [ ] **All colors used in the creatives are named** (RED: #E63946, LIGHT: #F1FAEE, AQUA: #A8DADC, LIGHT BLUE: #457B9D, DARK BLUE: #1D3557) which are provided by Scrimba course so that they become the basic color guideline to use in my project.

* [ ] All or the most important/used **colors contrast** in the design to allow text with the background can be easily read.

**[⬆ back to top](#table-of-contents)**

### 1.3 - Fonts and texts

Fonts are an essential part of every design.

It is recommended to organise the font size and style in the design process. There are several website where the designer can download the font.([Google font](https://fonts.google.com/)).

* [ ] Using the technique **@font-face** in CSS, the link is embedded to the CSS. 

  __Resources:__
	* 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/)

* [ ] The **Web Safe Fonts** is an important concept. Web safe fonts are fonts that are pre-installed by many operating systems. While not all systems have the same fonts installed, you can use a web safe font stack to choose several fonts that look similar, and are installed on the various systems that you want to support.

**[⬆ back to top](#table-of-contents)**


### 1.4 - Publish files

* [ ] For all websites, the web designer needs to provide at least **2 PSD** (mobile, desktop and eventually tablet) or at least **1 Sketch file** which needs to be delivered with the dimension below (if you have Photoshop CC 2015 and above, I recommend using artboards).

	> ℹ️ Some web designers could eventually create multiple PSD corresponding to each components used and import them in a single PSD as “smart layer”. In that case, you’ll have multiple PSD linked to one or two files. In the case of Sketch, since the **libraries** exist since version 47, it is possible to link multiples files with symbols ……..

* [ ] The **creative files are cleaned** before delivering to developers (empty and unnecessary layer needs to be removed to avoid large files).

* [ ] The **404 error** (and eventually the page 500 error) page were designed.
* [ ] All **popins, popups and alert boxes** were designed and can be enable throw layers of compositions.

__Additional Resources:__

* 📖 [Photoshop Etiquette: A Guide to Discernible Web Design](http://photoshopetiquette.com/)

#### Specific rules for PSD file:

* [ ] **Layer compositions** are used to show each different pages, if multiple views are provided within the same PSD. It’s an easy way to avoid confusions and check that all elements are correctly organized.

**[⬆ back to top](#table-of-contents)**

## 2. - Analysis and pre-work phases

![Analysis and phases](/images/phases.png)

Before starting the analysis and the pre-work phases and after receiving the creative files, you need to check some important elements:

* __*Which version of Photoshop, Sketch is used?*__
  Some features are specific to some versions of Photoshop or Sketch. It is important to flag any issue regarding this as soon as possible.
* __*Is the width of each PSD or artboard correct?*__
  In case some space is added on each side of the design, check the exact width of the website.
* __*Are the creatives using too much “box-shadow”, “linear or radial gradient”…?*__
  Don’t forget the .... Effect which can have impacts on the browser painting performance.
* __*Is a sitemap / breadcrumb provided to understand the architecture of all pages and their dependencies?*__
* __*Does the website needs to have retina images?*__

**[⬆ back to top](#table-of-contents)**

### 2.1 - Paper analysis

![Paper Analysis](/images/analysis.png)

It is recommended **printing** some (or all) of the pages you have on an A3 format (or A4 if you don’t have this format). Because of the height of the page. you’ll probably need to print some designs on multiple pages.

I can’t imagine a better way to start than analysing creatives on a paper with a pencil (or different colourful pencils chosen to highlight different type of information).

1. Define the **structure of the pages**, the headers, the sections, the articles, main, footer outlining these on at least one printed page.

2. Find all the **headings** that structured a page, ensure the `H1` is not on the logo and that the logical order is followed. Most of the time, the H1 for the homepage will be hidden with CSS but needs to keep its legitimate meaning. That analysis should be done with the help of a SEO specialist in case you have one in your team.

3. Try to find and regroup **similar components** giving them an individual name regarding their functionality and not just their context. For example, naming a tab system “

4. Most of the creative elements can be **done using CSS**. Today, it is not recommended to create any layout element using images. Any simple graphical element like buttons or borders should be done in CSS to avoid performance or scalability issues.

5. Find some **possible lack of coherence**, in case a Styleguide was not provided by the creative team, it’s your responsibility to ensure that every graphic element belong to a possible category (Buttons, Typography, Sliders…). It’ll help you to create your own CSS / Sass architecture or to identify which component you’ll need from an identified CSS Framework.

⚠️ *After the paper analysis phase, you can invite the creative team to use a tool like [InVision](https://www.invisionapp.com/), to facilitate the communication and exchange between the creative team and the developers. The possibility to comment directly on pages can be a time-saver and allow to keep a history of modifications and decisions.*

### 2.2 - Pre-development phase

* [ ] According to the specifications, **plugins needed were defined** in an early stage. Having a pre-list of possible plugins before starting the development can help the developer to stay focus and not spend too much time in doing research during the development phase. Obviously, some plugins may not perfectly fit and will be changed accordingly.

__Additional Resources:__

* 🛠 [Awesome JS][22]
* 🛠 [BestOfJS][23]


**[⬆ back to top](#table-of-contents)**

## 3. - Validation

The validation phase is when everything seems to be ready to be integrated. The client, in general, validate the creatives without waiting for any approval from the technical team. As exposed in the Design Checklist, it is essential that developers ensure the quality of the delivery before starting to code.

## 4. - Development phase

* [ ] All **medias can be cut and saved** before starting the development phase. That can help you to avoid back and forth between your creative software and your code editor.

* [ ] **The image folder has a clear architecture** where you  arranged the layout's images. It is important to stay consistent between projects in general. Defining a structure for that folder and a naming convention can be helpful.


  You can find an example of a possible structure with prefixes used to recognise each image appurtenance.

```bash
.
└── images
    ├── background
    ├── banners
    ├── icons
    └── layout
```

* [ ] **A naming convention is used** like adding prefixes to differentiate types of images, all images used for background can be prefixed by `bg-`, icons by `icon-`, hero banners by `hero-` or `banner-` and so on.

## 5. - Before production

Before launching your website, be sure to review all your code and make sure the text layout and comment it's easy to read.

**[⬆ back to top](#table-of-contents)**

---

## Support

If you have any question or suggestion, don't hesitate to use Gitter or Twitter:

* [Give an UP on Product Hunt](https://www.producthunt.com/posts/front-end-design-checklist)
* [Chat on Gitter](https://gitter.im/Front-End-Checklist][28]/Front-End-Design-Checklist?utm_source=share-link&utm_medium=link&utm_campaign=share-link)
* [Facebook](https://www.facebook.com/frontenddesignchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Author

**[Shiuan Dai](https://www.linkedin.com/in/shiuandai/)**

All icons are provided by [Icons8](https://icons8.com/)

**[⬆ back to top](#table-of-contents)**


[6]:	https://guideguide.me/
[7]:	https://www.sketchapp.com/docs/canvas/rulers-guides-grids/
[8]:	https://getbootstrap.com/docs/4.0/layout/grid/
[9]:	http://flexboxgrid.com/
[10]: https://css-tricks.com/dont-overthink-it-grids/
[11]:	https://www.lifewire.com/aco-file-2619477
[16]:	http://bradfrost.com/blog/post/atomic-web-design/
[22]:	https://js.libhunt.com/
[23]:	https://bestof.js.org/
[28]:	https://gitter.im/Front-End-Checklist/Front-End-Design-Checklist
