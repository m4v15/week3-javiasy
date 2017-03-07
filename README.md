# week3-javiasy

## User stories:
- Want to be able to visit the site and quickly get information on the actors that play the book characters in the TV show.
- A user wants to read on mobile, tablet or desktop.
- A user wants to immediately see what the site is about - headline
- A user wants to navigate the site using a screen reader that reads out the content of the site
- Wants to be able to use the site without waiting for page loading times
    - async


## Site design

## Architecture

##### File structure:
- index.html
- main.js
- style.css
- tests/
    - tests.js
    - spec.html
    - fixtures/
        - MockData.js

##### Module structure:
<!-- - MainModule
    - var extractData - pure functions
        - .getBooks... -->
- ListenerModule
    - event listeners
- APIRequestModule
    - make API requests here
- ExtractDataModule
    - pseudo-code: var extractData {gameOfThrones: functions, movieDatabase: functions}
- RenderDOMModule
    - Functions

##### HTML structure:
