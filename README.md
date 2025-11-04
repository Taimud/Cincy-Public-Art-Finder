Cincy Public Art Finder

Introduction

Cincy Public Art Finder is a web application designed to help residents and tourists discover and explore the rich collection of public art, murals, and statues across Cincinnati. Users can find art locations, view details, and get curated walking tours based on their location and current weather conditions. The application also allows users to "check in," leave comments, and submit their own photos, creating a community-driven guide to the city's art scene.

Icon/Logo

(Placeholder: Create a simple icon/logo for the project and insert it here. The instructions mention you can use PowerPoint or other tools to create a simple logo.)

![Image Description](/path/to/image)

Storyboard

(Placeholder: The assignment requires a simple storyboard showing screens and widgets. You can create this in a tool like Figma or PowerPoint and link to it or embed screenshots here.)

Projects (User Stories)

User requirements will be tracked as "Tasks" in our GitHub Project board.

User Stories

    As a tourist, I want to see a map of art installations near me, so that I can easily find and navigate to them.

        Given I have allowed location services,

        When I load the homepage,

        Then the map centers on my location and displays pins for nearby art.

    As a user, I want to tap on an art installation's map pin, so that I can see its name, a picture, and a short description.

        Given I am viewing the art map,

        When I click a pin,

        Then a pop-up or sidebar appears with the art's details.

    As a user, I want to know if it's a good time for a walking tour, so that I can plan my day.

        Given the application has fetched weather data,

        When I look at the "Tours" page,

        Then I see a message like "It's a great day for a walk!" or "It's raining, you may want to visit an indoor gallery."

    As a user, I want to leave a comment or post a photo on an art's detail page, so that I can share my experience with other users.

        Given I am on an art installation's detail page,

        When I fill out the "Add Comment" form and click submit,

        Then my comment appears on the page for others to see.

    As a user, I want to view user-submitted photos, so that I can see what the art looks like in different seasons or times of day.

        Given I am on an art installation's detail page,

        When I click the "User Photos" tab,

        Then I see a gallery of photos submitted by the community.

Data Sources

This project will integrate data from multiple sources:

    Public JSON Source (1): Cincinnati Open Data Portal. We will use a JSON-based dataset for public art locations, murals, or historical markers.

    Public JSON Source (2): A public weather API (e.g., OpenWeatherMap). This will be used to provide context for walking tours.

    Student Group JSON Source: We will consume the RESTful JSON API from another group (e.g., CincyCompass or CincyCrimeWatch) to add relevant data layers to our map, such as nearby events or safety information.

    Produced JSON (Our API): Our application will produce its own RESTful JSON service. This API will serve the user-generated content (comments, ratings, and submitted photos) associated with each art location. This will be documented with an OpenAPI file.

Team Composition

List group members:

    Cheikh Abdoul 

    Oladele Awonusi

    Taiwo Mudah


Weekly Meeting Time and Format
TBD