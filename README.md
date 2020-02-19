# travelog app

This repo includes the wireframes and User stories for the travelog project.

## Screens & Wireframes

-   [Landing Page](https://repl.it/@gssingh/travelog-landing-page)

-   [Signup page](https://repl.it/@gssingh/Travelog-signup-page)

-   [Login page](https://repl.it/@gssingh/Travelog-login-page)

-   [Add a Place](https://repl.it/@gssingh/Travelog-AddSpot)

-   [My Place](https://repl.it/@gssingh/travelog-myspots)

-   [Edit Place](https://repl.it/@gssingh/travelog-Edit-Place)

## User Flows:

### Landing Page

-   Signup (nav button) -> Taken to Sign Up page (shown only if not logged in)
-   Login (nav button) -> Taken to Login Page (shown only if not logged in)
-   Logout (nav button) -> Upon clicking, user is logged out (shown only if user is logged in)
-   My Places (nav button) -> Takes user to the My Places page (shown only if user is logged in)
-   Add a Place (nav button) -> Takes user to the Add a Place form (shown only if user is logged in)
-   Signup or Login (buttons at the bottom section of page) -> user taken to the signup/login page

### Signup page

-   User enters valid info and clicks Signup (button) -> Taken to login page
-   User enters incomplete or invalid info and clicks Signup (button) -> warning (tooltip) pops on the page

### Login page

-   User enters valid info and clicks Login (button) -> Taken to My Place (page)
-   User enters incomplete or invalid info and clicks Login (button) -> warning (tooltip) pops on the page

### Add a Place page

-   User enters valid info and clicks Add Place (button) -> Taken back to My Places page
-   User enters incomplete or invalid info and clicks Add Place (button) -> warning (tooltip) pops on the page

### My Places page

-   If no places added -> User sees a popup with suggestion to add a place
-   If places added previously -> User sees all their added places, each contained within a card.
-   If places added previously -> View On Map (button) -> Popup shows the place on a map
-   If places added previously -> Edit (button) -> Takes user to Edit Place page
-   If places added previously -> Delete (button) -> Popup where user can Confirm (button) or Cancel (button) deletion

## Edit Place

-   User enters valid info and clicks Update (button) -> Taken back to My Places page
-   User enters incomplete or invalid info and clicks Update (button) -> warning (tooltip) pops on the page
