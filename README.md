# Claude-

## Triple Feature

`triple-feature.html` — a movie-night party game for two to four players sharing one phone.
Open the file in any browser; there is no build step, no server and no dependencies.

Three games make up a night, best of three:

1. **Tape Race** — a shot-clock face-off decides who gives clues, then charades from that
   genre's shelf. Every card comes with scenes to play, words to say or ways to act it, so
   you can clue a film you have never seen. First to the tape target wins.
2. **Emoji Plots** — a movie as a row of emoji. Both players have a buzzer.
3. **Plot Twist** — same buzzers, but the movie is described in plain words.

There is also a "Just charades" mode for a single timed round.

Everything ships in the one file: 255 films with hints, 96 plot descriptions, emoji cards,
face-off prompts and wildcards. Sound effects are generated with the Web Audio API, so no
audio files are bundled. Settings and player names are remembered in `localStorage`.
