# icecast-split

I once had my computer listen to internet radio, to play back later.

I didn't yet realize icecast means it intersperses metadata (mostly title) in the otherwise plain media stream, so I then had to parse it out.


And because it parses ot out the title anyway, I added a mode that splits on songs.
Which is imperfect, both because radios fade songs, and also because right now it doesn't even cut on the nearest media frame.


# TODO:
- add code
- add test case (using copyright free music)
