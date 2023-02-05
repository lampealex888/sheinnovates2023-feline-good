# Feline Good - She Innovates Hackathon 2023 Submission

## Architecture

Feline Good relies on a reactive architecture in order to coordinate the state and flow of the application. The index.js contains our State class, which is a data structure to hold the current values needed by the application, and propagate changes based on those values. The APIcalls.js class contains the UI and DOM logic. It subscribes to changes in the global State object, and hooks the interactive elements of the DOM to their State values.

## Technical Details

Feline Good relies on one external library, namely hammer.mins.js for the multi-touch functionality animations, but no frameworks for the front-end application. As noted in the Architecture section, Feline Good bootstraps its own application flow. We chose a reactive model in order to concisely handle the asynchronous aspect of the buttons and API calls.

## Links 

Live Demo --> https://lampealex888.github.io/feline-good/

DevPost Submission --> https://devpost.com/software/feline-good

## Many Thanks To

* [Named Link]((https://some-random-api.ml/) "Some Random API") for their many beautiful APIs
* [Named Link](https://github.com/D3vd/Meme_Api) "Meme API") for their meme API
* [Named Link](https://hammerjs.github.io/) "Hammer.js") for their JavaScript Library that added multi-touch functionality


