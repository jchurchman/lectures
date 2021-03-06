## **Week 1: The View**
# Class 2: jQuery and the DOM + some RWD

[Schedule](#schedule) | [Announcements](#announcements) </br>
[Objectives](#learning-objectives) | [Yesterday vs Today](#yesterday-vs-today) </br>
[Lecture Notes](#notes) | [Readings](#readings)


<hr></hr>

## Schedule
1. Objectives and Stand Up
1. Code Review
1. Agile & MVC
1. jQuery
1. Lab Prep

### Announcements
* 
* Questions? Resources to share?

<hr></hr>

## Learning Objectives
- Discuss the differences between mobile first design, responsive web design, and adaptive web design.
- Create a flexible layout using the following: percentage based media, media queries, and fluid layout.
- Scale a website to its viewport using the meta tag.
- ⭐ Streamline development using **live-server**.
- ⭐ Organize CSS using SMACSS.
- Display icons on a website using icon fonts, and specifically IcoMoon.
- Display icons on a website using the psuedo elements `:before` and `:after`.
- ⭐ Describe the different parts of the MVC design pattern.
- Include the jQuery library using a CDN or including it locally.
- Describe the pros and cons of using jQuery.
- ⭐ Perform DOM manipulations using `append`, `remove`, `clone`, `data`, `html`, `text`.
- ⭐Traverse the DOM tree, with `parents`, `children`, `find`.
- Differentiate between certain methods & the process of chaining.
- Include JavaScript files accounting for dependencies by loading `<script>` tags in order.


### Yesterday vs Today
| Yesterday we... | Today we will... |
| --------------- | ---------------- |
| <ul><li> Created websites from scratch, based off of a problem domain </li> <li> Opened our page from the terminal using `start` or `open`</li> <li> Organized our CSS all willy-nilly</li><li>Wrote our scripts with vanilla JavaScript</li><li>Retrieved elements from the DOM using the document object's methods</li><li>Manipulated the DOM using the document object's methods</li></ul> | <ul><li> Work on an existing code base!</li><li> "Serve" our page using live-server</li><li> Implement MFD and RWD techniques</li><li>Organize our CSS using SMACCS</li><li>Write JavaScript with the help of the jQuery library</li><li>Retrieve elements from the DOM using jQuery methods</li><li>Manipulate the DOM using jQuery methods</li></ul> |

<hr></hr>

## Notes
#### Topic 0 - KICKOFF (Round 1)
* Overview
  * Welcome to Code 301 (:
  * Campus and student introductions
  * Class structure info

#### Topic 1 - Agile and MVC (Round 1)
* Overview
  * Agile Web Development
    * [Infographic](https://toggl.com/developer-methods-infographic)
    * Compared with the ‘Waterfall’ process
    * Importance of stand-ups and pair programming (driver & navigator roles) in relation to this course
    * Some ways to implement agile:
      * Daily Sprints
      * ‘MVP’ & ‘Stretch’ Goals
      * User (or project stakeholder) stories & Developer stories
      * Iterative Development
      * Agile buzzwords (backlog, sprint demos, retrospective, etc)
  * MVC
    * Why do developers care about separating these concerns?
    * What are some other architectural design patterns?
    * What does each MVC layer do?
    * How does each MVC layer tie together in a modern web application?
    * Additional resources:
      * [MVC Architecture ](https://developer.chrome.com/apps/app_frameworks)
      * [Learning JavaScript Design Patterns: MVC](https://addyosmani.com/resources/essentialjsdesignpatterns/book/#detailmvcmvp)

#### Topic 2 - Responsive Web Design (Rounds 2-3)
* Overview
  * RWD
    * Responsive web design
    * Discuss flexible vs. adaptive layouts
    * Discuss importance of responsive development
      * Larger coverage area
      * Multiple device support
    * Discuss Chrome device emulation (and other emulation options - ie: x-code device simulator)
  * Viewports
    * Discuss the meta viewport tag and it’s width and scale options
  * Flexible Layouts
    * Discuss common responsive frameworks (Bootstrap, Foundation)
    * Discuss width based resizing and scalability of elements
  * Media Queries
    * Discuss min-width media query usage for mobile first design and development
    * High level overview of other media queries and options
  * Flexible Media
    * Discuss max-width based creation of scalable images
  * CSS Fundamentals
    * Discuss display types
      * Block vs Inline vs Inline-block
    * Discuss the box model
      * Overview (or whiteboard) the differences between margin, padding, content, border
    * Discuss positioning
      * Static, relative, absolute, fixed, inherit
* SMACSS
  * Discuss the importance of modular CSS
  * Discuss base, layout, module, state, and theme concepts
* Implementation and use of an icon font
  * [icomoon.io](https://icomoon.io/)
* Design basics and setting up a simple color palette
  * [Adobe Color CC](https://color.adobe.com/)
    * Other color combination tools are fine to show as well.

#### Topic 3 - DOM & jQuery / Assignment Prep (Rounds 4-6)
* Overview
  * Including jQuery from CDN/locally sourced
  * Vanilla DOM selection & manipulation review
  * Basic jQuery syntax
  * Waiting for DOM load using `$(document).ready()`;
  * Basic CSS selector review - how this works with jQuery selection
    * Each jQuery selection attempts to return a set of matched elements, and if it cannot, will return an empty array-like object.
  * Chaining methods
    * Why are we able to chain in jQuery?
      * Each method returns a jQuery object
  * Understanding the "getter" and “setter” differences between single and double parameter jQuery method calls
    * Ex:`$(‘.el’).data(‘some-data-attribute’)`- gets the data
    * Ex:`$(‘.el’).data(‘some-data-attribute’, ‘some val’)`- sets the data


## Readings
* Javascript & jQuery: pages 293-325
  * (Context: 293-301; Essential: 310-325; Reference: 302-309)

* [Shay Howe’s intro to RWD](http://learn.shayhowe.com/advanced-html-css/responsive-web-design/) (Essential)
* [Dale Sande's Intro to SMACSS](http://www.anotheruiguy.com/ux-design-dev/_book/smacss/README.html) (Essential)
* [SMACSS Official Documentation](https://smacss.com/) (Reference)
* In-Depth (optional) [Dale Sande’s intro](http://www.anotheruiguy.com/ux-design-dev/_book/rwd/README.html) to RWD (Reference)

## Lab
[Lab: jQuery & DOM](https://github.com/cfpdx-301d-spring-2017/lab-02-jquery-and-dom)
