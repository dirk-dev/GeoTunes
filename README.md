# GeoTunes
_____________________________________________________________________________________________

### Problems:
GeoTunes was created with the idea of using APIs to create a playlist based on geographic location. The user selects the country and the number of songs desired. Additionally, GeoTunes was to display lyrics for the songs of the playlist, as well as a video of the chosen song. User input validation was needed for the number of songs selected.  


### Solutions:
* The LastFM API provides a way to get the current playlist of top songs based on country. Links to the video for the playlist songs are also provided by the LastFM API. 
* The Lyrics.ovh API provides the user requested lyrics.
* user input validation was implemented using an if/else conditional to check for correct user input.

### Technical Details:
* LastFM & Lyrics.ovh APIs were used for the song data (playlist, lyrics, and videos).
* AJAX calls were used to access for the APIs.
* The country flags are SVG graphics. SVGs are vector format, so the file size is small, and the images are infinitely scalable with no loss of image quality.
* jQuery was used for accessing & changing elements in the DOM.


Deployed Site: https://dirk-kiesewetter.github.io/GeoTunes/

_____________________________________________________________________________________________


GeoTunes was a group project. Below is the ReadMe from the group repository:

### Team

    Pauline (team lead)
    Dirk
    Joel
    Evan

### Project Details:

    GeoTunes allows users to choose a country and the number of songs to generate a list of the top tracks in that location. GeoTunes also displays the flag of the nation selected.
    Users can click on a link that directs them to listen to the song or to display the lyrics on the page.

APIs used:
* [last-fm] (https://www.last.fm/api/)
* [lyrics.ovh] (https://lyricsovh.docs.apiary.io/)

### Requirements:

    * Must use at least two APIs
    * Must use AJAX to pull data
    * Must utilize at least one new library or technology that we haven't discussed
    * Must have a polished frontend / UI
    * Must meet good quality coding standards (indentation, scoping, naming)
    * Must NOT use alerts, confirms, or prompts (look into modals!)
    * Must have some sort of repeating element (table, columns, etc.)
    * Must use Bootstrap or Alternative CSS Framework
    * Must be Deployed (GitHub Pages or Firebase)
    * Must have User Input Validation

### Presentation Requirement

    10 minute formal presentation
    Explain in detail:
        Our overall application's concept
        Our Design process
        The motivation for its development
        The technologies we used (and briefly how they work)
        A demonstration of its functionality
        Directions for future development

### Grading Metrics

    * Concept
    * Design
    * Functionality
    * Collaboration
    * Presentation

### API Suggestions

    Stick to APIs that do all of the following:
        * Allows CORS
        * Simple or no authentication
        * JSON response returned
        * Well documented