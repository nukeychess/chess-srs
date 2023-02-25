# chess-srs

This is a yet-untitled project to make a free and open source standalone spaced repetition training app for chess positions.

## Why?

I love Anki for language flashcards, but I've never been satisfied with my attempts to hack interactive chessboards into Anki cards. It's possible, but the result isn't super pleasant to use. I am also a big fan of Chessable, but it's not as richly customizable as Anki and it is heavily geared towards studying paid pre-made courses offered in the store. I want an app that gives the user full control over the content like Anki does, but one that's built from the ground up with chess in mind.

## Features

### Current Features:
- None! Currently, it just displays a placeholder GUI with a position editor chessboard.
- This will not be a usable app until all the features in the short-term section are completed, at which point I'll make a 1.0 release.

### Planned Features (Short-term):

- Create collections to organize problems
- Add problems to collections with an FEN/PGN import system
- Solve problems that are due for review in a training view
- Puzzles are scheduled to be served on an SRS schedule
- User solve history and problem collections are stored as a sqlite database that can easily be transferred between devices.

### Planned Features (Long-term):
- Import positions from image
- UCI engine integration
- Import and export collections as PGN databases for sharing
- Web service to sync database between device in a user-friendly way

### Parts of the app that come from third party projects
- The chessboard GUI is [chessboard.js](https://github.com/oakmac/chessboardjs/)
- The app is made with [electronjs](https://www.electronjs.org/)
- The front-end framework is [bootstrap](https://getbootstrap.com/)
- The SRS scheduling algorithm is (will be) based on [SM-2](https://super-memory.com/english/ol/sm2.htm)
