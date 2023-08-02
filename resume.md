---
title: Simmon Li's Resume
---

# Simmon Li
## Resume
* [hello@crespire.dev](mailto:hello@crespire.dev)
* Located in Markham, Ontario, Canada
* [![Github](https://img.shields.io/badge/-Simmon_Li-000?style=flat-square&logo=github&logoColor=azure&color=181717)](https://github.com/crespire)
* [![Linkedin](https://img.shields.io/badge/-Simmon_Li-000?style=flat-square&logo=linkedin&logoColor=azure&color=0A66C2)](https://www.linkedin.com/in/simmonli/)

Self-taught and tenacious, I'm an operations professional looking for an opportunity to jump into a career in software development. Fluent in HTML, CSS, Javascript, Ruby, Rails and React and open to learning new things! You can [check out my about me page](https://www.crespire.dev/) to see what I'm currently up to.  
&nbsp;  
I'd love to chat about what I can bring to the table, so [get in touch with me](https://github.com/crespire#get-in-touch).

---

## Selected Projects
### EZ Newswire
_Ruby on Rails, PostgreSQL, ViewComponents, Hotwire, Devise, Bootstrap_  
**Live:** [https://app.eznewswire.com/](https://app.eznewswire.com)  
* Delivered numerous new features from user stories and Figma design mocks, working across the stack as needed
* Implemented an organization/brand feature to manage multiple sets of press releases, benefiting agency users with multiple clients and/or brands
* Created an image upload feature using Turbo/Stimulus, enabling users to upload and (re)order accompanying images with their press release without full page loads, improving customer conversions
* Vendored an open source Javascript package to support image uploading with new required functionality, pending upstreaming
* Executed architectural changes with the tech lead, significantly reducing error rates (approximately 60%)
* Improved frontend reliability by switching from importmaps to esbuild-based Javascript packaging, further reducing failure rates due to data inconsistency and improving user experience
* Developed and implemented a user onboarding experience, helping user retention and improving data reliability
* Implemented, integrated, and tested a new checkout flow, supporting business goals to expand the publisher network and add additional payment processors, expanding reach
* Enhanced the backend with more data models to capture additional checkout and payment data for analytics purposes
* Crafted rake tasks and data migrations to ensure data integrity and consistency
* Built a comprehensive MiniTest test suite, later converted to RSpec, achieving ~87% code coverage

### CASA Volunteer Tracking
_Ruby on Rails, PostgreSQL, ViewComponents, jQuery, Devise, Pundit_  
**Live:** [https://casavolunteertracking.org/](https://casavolunteertracking.org/)  

* Implemented UI updates to leverage JQuery Datatables for management pages to make it easier to use
* Reviewed and improved multi-tenant permissions using Pundit to ensure security between tenants
* Encapsulated application jobs into unit-testable plain old Ruby objects and wrote tests, adding confidence in notifications

### Railsbook
_Ruby on Rails, devise, Turbo/Stimulus, Sass CSS, RSpec, dokku, docker, AWS S3_  
**Live:** [https://railsbook.crespire.dev](https://railsbook.crespire.dev/)  
**Repository:** [https://github.com/crespire/rails_railsbook](https://github.com/crespire/rails_railsbook/)
* Implements core Facebook friend and content experience
* Automated RSpec/Capybara test suite with ~83% coverage
* Styled via custom BEM system utilizing Sass
* Leverages dokku/docker on DigitalOcean for deployment. Hooks up to Sendgrid and AWS S3 for supporting services

### Buysell by crespire
_Ruby on Rails, React, Typescript, Tailwind, PostgreSQL, Rspec, cypress, git, docker, AWS S3, vercel_  
**Live:** [https://buysell.crespire.dev/](https://buysell.crespire.dev/)  
**Repository:** [https://github.com/crespire/buysell](https://github.com/crespire/buysell)  
* Implements a full stack buy & sell application with React Typescript/Rails API
* Custom hooks and providers on the React application centralize important application functions, including API access and data caching and user authentication
* Styled using daisyUI built on Tailwind, with some custom components created for re-usability.

### Where's Waldo?
_React, react router, Rails, Tailwind, webpack, npm, git, vercel, dokku, docker_  
**Live:** [https://waldo.crespire.dev/](https://waldo.crespire.dev/)  
**Repository:** [https://github.com/crespire/waldo](https://github.com/crespire/waldo)  
* Implements a fullstack clicker game with a React client and custom Rails API
* Uses react router for simple client routing
* Powered by a data-backed canvas for real time input feedback
* Styled with Tailwind, including custom animations
* Monorepo deployed via vercel and dokku/docker

### Rails Report Builder
_Ruby, Rails, Hotwire Stimulus, RESTful API, git, docker, docker compose_  
**Live:** Preview available upon request.
**Repository:** [https://github.com/crespire/report_generation](https://github.com/crespire/report_generation)
* An extension of the CLI Custom Report Automation Tool, this moves the application to a Rails app for ease of use with a GUI.
* Utilizes an external API to generate requested reports
* Relies on custom fork of WickedPDF gem to ensure temp file cleanup
* Containerized application for easy deployment and portability with docker compose

### Firebase Authorization Flow Sample
_React, Typescript, MaterialUI, React Router, Firebase Auth & Storage, webpack, npm, git, vercel_  
**Repository:** [https://github.com/crespire/ts-auth-sample](https://github.com/crespire/ts-auth-sample)  
* Implements a front end Typescript React application utilizing MaterialUI components
* Leverages Firebase for authentication and storage of user avatars
* Simple React router set up
* Relies on a custom authorization provider component as well as custom hook

### Portfolio v1
_React, Typescript, Tailwind, webpack, npm, git, vercel_  
**Live:** [https://crespire.dev/](https://crespire.dev/)  
**Repository:** [https://github.com/crespire/portfolio-v1](https://github.com/crespire/portfolio-v1)  
* Implements a front end portfolio application with Typescript React
* Utilizes advanced Tailwind techniques for interactive experience
* Live via vercel

### Cozy Creature Canteen
_React, react router, Tailwind, webpack, npm, git, vercel_  
**Live:** [https://pet-shop.crespire.dev/](https://pet-shop.crespire.dev/)  
**Repository:** [https://github.com/crespire/js-shopping-cart](https://github.com/crespire/js-shopping-cart)  
* Implements a frontend e-Commerce store front application in ReactJS
* Deploys react router for simple two page navigation
* Tracks a user's cart items and checkout information
* Employs a multi-step checkout flow with custom form hook for input validation
* Styled with Tailwind
* Deployed via vercel

### Chess
_Ruby, RSpec, git_  
**Live:** [https://replit.com/@crespire/rubychess](https://replit.com/@crespire/rubychess?lite=1&outputonly=1#README.md)  
**Repository:** [https://github.com/crespire/ruby_chess](https://github.com/crespire/ruby_chess)
* Implements Chess for 2 players via command line interface in Ruby
* Planned and implemented from broadly scoped requirements
* Automated RSpec test suite with ~96% coverage
* Program does not utilize any third party Chess libraries
* Wide compatibility with other Chess software via FEN (de)serialization

### Memory Card Game
_Javascript, ReactJS, Tailwind, webpack, npm, git, Github Pages_  
**Live:** [https://memory-cards.crespire.dev/](https://memory-cards.crespire.dev/)  
**Repository:** [https://github.com/crespire/js-memory-cards](https://github.com/crespire/js-memory-cards)  
* Implements a simple memory card game in ReactJS function components using hooks
* Leverages [https://www.deckofcardsapi.com/](https://www.deckofcardsapi.com/) to draw a set of 12 random cards
* Keeps track of current and best scores using React hooks
* Utilizes Tailwind styling

### Battleship
_Javascript, Jest, webpack, npm, git, Github Pages_  
**Live:** [https://crespire.github.io/js-battleship/](https://crespire.github.io/js-battleship/)  
**Repository:** [https://github.com/crespire/js-battleship](https://github.com/crespire/js-battleship)
* Implements a simple Battleship game on the front end in Javascript
* Designed to utilize factory functions to build domain objects
* Automated Jest test suite with ~95% coverage

### CV Builder
_Javascript, ReactJS, Tailwind, webpack, npm, git, Github Pages_  
**Live:** [https://crespire.github.io/js-cv-builder/](https://crespire.github.io/js-cv-builder/)  
**Repository:** [https://github.com/crespire/js-cv-builder](https://github.com/crespire/js-cv-builder)
* Implements a simple CV builder in ReactJS class components.
* Allows adding, editing and deleting of nested list items in their respective sections.
* Utilizes TailwindCSS for styling components

### CLI Custom Report Automation Tool
_Ruby, APIs, git_  
**Repository:** [https://github.com/crespire/report_automation](https://github.com/crespire/report_automation)
* Implements a command line application that ingests provided data and generates reporting
* Utilizes API and JSON data
* Relies on third party libraries for output generation
* Optional GUI powered by LibUI and Glimmer DSL for LibUI on Linux systems

---

## Education
### Honours Bachelor of Arts with High Distinction (3.73/4.0 GPA)
_University of Toronto_  
2011 - 2014
* Specialization in Peace, Conflict & Justice with a minor in Ethics, Society & Law

### Bachelor of Music in Performance (2.89/4.0 GPA)
_University of Toronto_  
2006 - 2010
* Specialization in Vocal Jazz

---

## Professional Experience
### Software Developer
_Sierra Rails_  
March 2023 - present | Toronto, Remote
* Build new features using Ruby on Rails, ViewComponents, Hotwire, Bootstrap, SCSS, and Devise
* Maintain development and production environments using VPS provders and container based systems
* Create and manage automated test suites for features using MiniTest and RSpec

### Office & Operations Manager
_Designstor_  
Feb 2017 - March 2023 | Toronto
* Accounts Payable/Receivable
  * Automated various financial reports to improve visibility for management
  * Improved A/R receivables timeline from ~60 days to ~30 days via follow-up automation
  * Centralized billing and project management information to reduce billing reconciliation times
  * Set up an automated time sheet parsing to reduce billing reconciliation times
* Taxes & Finance
  * Prepare and action periodic tax obligations including source deductions & sales tax remittances
* Payroll, Benefits & HR Administration for office of 10
  * Administer and process payroll for staff on a monthly basis
  * Track, manage and process overtime, vacation, sick days and other PTO/leave
  * Manage employee documents and information
  * Administer group benefits and manage changes to staff coverage
* Business Operations & Administrative Support
  * Manage and coordinate with property management and building operators on building systems and maintenance

### Trademark Sales Manager
_Witmart_  
Jul 2016 - Jan 2017 | Toronto
* With 4 direct reports, improved sales performance in a fast-paced start-up environment
* Responsible for on-boarding and performance
* Improved business processes in conjunction with senior managers
* Regular training and coaching responsibilities

---

## Volunteer Experience
### Ruby for Good
_Individual Contributor_  
* Contributed various fixes and improvements to the CASA Volunteer Tracking application

### The Odin Project
_Individual Contributor_  
* Contributed various curriculum updates, including new lessons on local development environment setup
* Contributed web application and community tool bug fixes

---

## Skills
* **Languages:** Ruby, Javascript, Typescript, HTML5, CSS3, SQL, MongoQL, Python
* **Frameworks:** Ruby on Rails, Hotwire Stimulus & Turbo, node.js, React, React Router, Sass, Tailwind
* **Automated Testing:** RSpec, Jest, React Testing Library
* **Cloud Services:** Github, Google Cloud Platform, Firebase, DigitalOcean, AWS, Heroku, Sendgrid, vercel
* **Tools:** git, VScode, Linux, Postman, postgreSQL, mongoDB, NoSQL, rbenv, ruby bundler, npm, webpack, docker, docker compose, dokku
