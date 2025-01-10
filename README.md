# Wordle POP

## Version 1

last updated : January 2025

Live version at https://wordle-pop.netlify.app/

## Description

A word game to explore and learn Javascript. I based this game on a tutorial from https://www.freecodecamp.org/news/build-a-wordle-clone-in-javascript/ and Wordle game from New York Times https://www.nytimes.com/games/wordle/index.html .

I built up this game to include statistics which are stored on users local storage in browser and a light/dark mode. I have refined the style to make a more retro theme and made it mobile friendly.

If you find a bug or want to add a word to the dictionary please contact me via github https://github.com/darren-uk or Twitter @darren*colson https://twitter.com/darren_colson*

### New features

- new color scheme

- Code stream lined and dependencies replaced with native code

### Bug fixes

- New games do not refresh the web page. Only one call to web server on first load

- Fixed color flashing on first page load when in dark mode

- removed dependency for animate.css external library

- removed dependency for toastr.js / toastr.css / jquery.js

- reseting stats / clear stats now show instantly in stats panel.

- clear stats and streak seperatly.

- Game can be restarted mid way through another game without letters repeating from previous game.

- dark mode added to stat screen

### Future improvments to come

- Add 2 step to reseting stats incase button is accidentaly clicked on.

- timed mode

- more animated themes

  Based on a tutorial from https://www.freecodecamp.org/news/build-a-wordle-clone-in-javascript/
  Repo sited at https://github.com/Morgenstern2573/wordle_clone.git

### Roadmap

- set proper notification animations

In manu panel add

- clear settings without streak
- clear streak
- view contact and licence details
- set up aria's in HTML tag for color-theme & data-theme

## Dependencies

- mo.js for burst animations
