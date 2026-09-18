# Claude-

## Triple Feature

`triple-feature.html` — a movie-night party game for two to four players sharing one phone.
Open the file in any browser; there is no build step, no server and no dependencies.

A night is three games, best of three, picked from:

1. **Tape Race** — a shot-clock face-off decides who gives clues, then charades from that
   genre's shelf. Every card comes with scenes to play, words to say or ways to act it, so
   you can clue a film you have never seen. First to the tape target wins.
2. **Emoji Plots** — a movie as a row of emoji. Both players have a buzzer.
3. **Plot Twist** — same buzzers, but the movie is described in plain words.
4. **Which Came First?** — two films side by side; buzz in and pick the older one. The app
   knows the answer, so nobody argues.

There is also a "Just charades" mode for a single timed round.

### Aimed at the rental-shop generation

- **Era switch** — set the shelf to 1980–1999 and the whole night comes out of the video shop.
  170 of the 341 films are from those twenty years.
- **Rewind Mode** — four extra clue types on top of charades: narrate the trailer, sell it
  like a video-store clerk, read the back of the box, or post it as a 2003 away message.
- **Late fees** — the drinking mode. Losing a game costs a shot, and anyone can be charged
  another at any point between rounds. The night ends on a rental receipt that totals them up.
- VHS tracking glitch between screens, tape-deck sound effects and a dial-up handshake when
  a game starts.

Everything ships in the one file: 341 films with hints and emoji cards, 116 plot
descriptions, face-off prompts and wildcards. Sound effects are synthesised with the Web
Audio API, so no audio files are bundled. Settings and player names are remembered in
`localStorage`.
