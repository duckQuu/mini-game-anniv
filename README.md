# The Dungeon of Us

A little anniversary dungeon adventure that runs in the browser. Explore torch-lit rooms, dodge slimes, beat each guardian's mini challenge, answer their question to unlock the door, collect memory hearts, and open the treasure chest at the end.

- **WASD / arrow keys**: walk
- **Space**: dash (smashes pots and dummies, pops slimes)
- **E / Enter**: talk, answer, open
- **C**: wardrobe (outfits, bags, shoes, hair, hats)
- **M**: sound on/off
- Phone: drag on the left half to walk, tap the right half to dash or talk

## Making it yours

Everything personal lives in the `CONFIG` block near the top of `index.html`: names, the guardians' questions and answers, the memories, and the final letter. Photos are optional. Put them in a `photos/` folder and reference them as `photo: 'photos/1.jpg'`.

To use your own song as the soundtrack, save it as `music/yue-ding.mp3` (or change `soundtrack.file`). Set `playFrom` to `'start'` to hear it through the whole game or `'finale'` to save it for the ending, and `finaleStartAt` to jump to a favorite part (in seconds) when the boom happens. If the file is missing, the built-in tune plays.

After the bouquet there's a little movie of your photos, each with a line of text underneath, before the letter. Put the pictures in `photos/` and list them in `movie.photos` (see `photos/README.md`). With no photos listed, the movie is skipped.

Only `music/yue-ding.mp3` from the `music/` folder is uploaded; any other files there stay on your computer.
