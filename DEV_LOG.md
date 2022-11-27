# DEV LOG

* Day 1
  * [x] Upgrade Deno
  * [x] Generate Fresh Project
  * [x] Familiarize myself with Fresh
  * [x] Linter?
  * [x] Setup the database
    * [x] Docker Postgres
  * [x] Create a users table
  * [x] At least 1 route that returns data from DB
* Day 2
  * [x] Update the README
  * [x] use dotenv from std library
    * <https://deno.land/std@0.150.0/dotenv>
  * [x] Use source maps everywhere...
  * [x] Figure out DenoAuth
  * [x] Design the Database
* Day 3 - (September 5th 2022)
  * [x] Config schema validation
  * [x] Define our Models...
    * User
    * Social Profile
    * Spot List
    * Spot
  * [ ] Allow users to login and logout
    * [ ] Login
      * [x] If we have not seen a user before, insert
      * [x] If we have seen a user before, update
      * [ ] Issue a cookie
  * [ ] Show a map on the home page
    * [x] with hacks
* [x] Day 4 - September 12th
  * [x] Setup Kysely Connection
  * [x] Setup DB Models with Kysely
  * [x] Setup DB migrations... with Kysely
* [x] Day 5 - September 19th
  * [x] Replace DenoAuth with DenoGrant
  * [x] Get a Proper map on the page
  * [x] Login
    * [x] Upsert user into db
    * [x] Issue a Cookie
      * [x] Make sure cookie is signed
  * [x] Design Flows and Layout
    * [x] Color Pallette
      * <https://coolors.co/56bc58-202030-ff8811-9649cb-a52422>
    * [x] Landing Page
      * Description of the App
      * [x] Signup / Sign In
    * [x] Navbar
* [x] Day 6 - September 26th
  * [x] Work on TODOS
* [x] Day 7 - October 2nd
  * [x] Login
    * [x] Setup cookie session
  * [x] Navbar
    * [x] User State
* [x] Day 8 - October 9th
  * [x] Update fresh
  * [x] Fix login drop down on Chrome
  * [x] "Private / Logged In" Profile Page
    * [x] Show map on homepage
  * [x] Spot List Create Page
    * [x] Initial page
* [x] Day 9 - October 16th
  * [x] Review/Merge PRs
  * [x] Map Theme
  * [x] Auto Page Titles
  * [x] Map background style
  * [x] UI Library Setup
    * [x] Bootswatch
  * [x] Spot List Create Page
* [x] Day 10 - October 23rd
  * [x] Spot List Create Page
  * [x] Spot List Page
* [x] Day 11 - October 30th
  * [x] Spot List Edit Page
    * [x] Center Map on map pins
  * [x] Add spot to list
* [x] Day 12 - November 8th
  * [x] Edit / Update Spots on a List
* [x] Day 13 - November 26th
  * [x] Create Repository in Github

* Onboarding
  * Set default starting location
* IP geolocation - IN APP
* Comments on lists
* Favoriting / staring lists
* Posting pictures of food / events at the spots
* Lists can have a header / background image
* User profile that shows all the lists they've created
* Lists can be upvoted
* Dev Experience
  * Hot reload islands
