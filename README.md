# frontend-roadmap-notes
As I go through the frontend roamap at my own pace, this repo will contain my notes on the topic. 

# Table of contents
 1. [Project goals](#project-goals-1)
 2. [DNS and how it works?](#dns-and-how-it-works)


# Project goals [^1]

## 1. What exactly do I want to accomplish?
1. understand frontend development
2. manage frontend devs and roadmap
3. gain experience in the non-sap domain

## 2. How will the frontend roadmap help me reach my goals?
1. Learn at least one frontend language, the basics of internet, and web development.
2. Learn and revise the modern tools used for web development such as git and package managers.
3. Learn to use *Clean Code* and *Test Driven Development*.
4. Learn to use tools to test my apps.
5. Gain enough experience to understand and drive the frontend roadmap in my org.
6. Ensure I can devliver a better performance in managing sap and non-sap teams.

## 3. What needs to be done, and in what order, to reach my goals?
> As a side note, your goals are not necessarily set in stone. They evolve over time even in the course of the project, especially if you run across unexpected obstacles or just change your mind. [^1]

1. Understand frontend development
    1. Follow the roadmap at [roadmap.sh](https://roadmap.sh/frontend)
    2. Define scope of learning for each topic learnt. 
        > Note to self: When is it enough?
    3. Complete at least 10-11 projects on the tech learnt. 
    4. Practice tech learnt by publishing the knowledge learnt.
    5. Take notes and diagrams for reference.
    6. Understand the pros and cons of the tech being learnt. 
2. Manage frontend devs and roadmap
    1. Collaborate to define frontend best practices we will adapt as a team.
    2. Perform code review and technical discussions with frontend devs.
    3. Understand where frontend devs need help and provide them the support required.
    4. Support in defining the product roadmap
3. Gain experience in the non-sap domain
    1. As a result of achieving goal 1, round of my career profile in the non-sap tech domain.
    2. Check how this experience can be leveraged in the sap domain such as SAP BTP and SAP Cloud development. 

## 4. Conclusion:
The above is a rough plan to go through the journey of understanding frontend development. 

*Note:* The above plan was started in Trello (by Attlassian) and was moved to GitHub to practice markdown and get acquainted with GitHub features. 

[^1]: [How do I start to design my website?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)


# DNS and how it works
[Diagram: How DNS works?](/DNS%20-%20Frontend%20Roadmap.pdf) [^2]

[^2]: Example of markdown for relative URLs in GitHub.

# History of the web
* 1960s - ARPANET by US military - first implementation of TCP/IP protocol(s).
* 1980s - Tim Berners-Lee - wrote notebook program ENQUIRE - contained concept of links between different nodes.
* 1989 - TimBL wrote down *Information Management - A Proposal* and *HyperText* at CERN.
* 1990 - TimBL had created HTTP, HTML, Web browser called WorldWideWeb, HTTP server and few web pages.
* 1994 - World Wide Web COnsortium was created by TimBL

# Web Standards
Agreed to be kept free to **contribute and use**. Try to *not break the web*, i.e. standards should be backwards compatible and forwards compatible (future tech should be compatible with current tech).

* [HTML Living Standard](https://html.spec.whatwg.org/multipage/) - describes how HTML should be ideally implemented.

# Standard bodies
* [W3C](https://www.w3.org/Consortium/facts) - World Wide Web Consortium: creates web tech specs.
* [WHATWG](https://whatwg.org/faq) - Web Hypertext Application Technology Working Group: maintains the HTML Living Standard.
* [ECMA](https://en.wikipedia.org/wiki/Ecma_International) - European Computer Manufacturers Association: publishes standard for ECMAScript (javascrpipt is based on it).
* [Khronos](https://www.khronos.org/about) - creates royalty free graphics standards such as OpenGL, WebGL, OpenXR, etc.

> Markdown does not support opening links on a new page or tab. To open links on a new page, use: 
`<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>`

# Modern web tech - overview
## Browsers
Software programs used by humans to consume the content on the web (besides other ways like using assistive tech like screenreaders).
## HTTP
Messaging protocol used by browsers to communicate with the web servers.
## HTML, CSS, Javascript
* HTML - wrap your content to provide meaning and structure to it.
* CSS - Style the HTML content based on rules such as adding borders or font colors, etc.
* Javascript - add interactivity to the web page (HTML and CSS).

## Tooling
* dev tools - common in most modern web browsers to debug code.
* test tools - to test the web code that it behaves as intended.
* Linters - code styler such as pretty print in ABAP (from SAP) - linters highlight where the code has not followed some coding guidelines.
* Minifiers - remove the whitespace in the code and reduce the download size of the web pages. Results in web browsers downloading content faster and web servers able to serve content faster than non-Minified code. 
## Server-side languages and frameworks 
While HTML, CSS and Javascript run on the front-end or the werb broweser, other languages such as PHP, Python, ASP.net, NodeJS etc run on the web servers to produce the content sent to the front-end. Typical use case is to query data from a database and modify it before sending to front-end. Front-end languages are also called client-side languages. 

# Web best practices
## Uncertainties
* User 1 might be looking at it on an iPhone, with a small, narrow screen.
* User 2 might be looking at it on a Windows laptop with a widescreen monitor attached to it.
* User 3 might be blind, and using a screenreader to read the web page out to them.
* User 4 might be using a really old desktop machine that can't run modern browsers.

## Best practices
1. Cross-browser compatibility
2. Responsive web design
3. Performance
4. Accessibility
5. Internationalization
6. Privacy and Security