# GTA 6 meme — "Waited 13 Years" (gta6-meme-x-01)

An entry for the make.fun bounty **"Post a GTA 6 meme on X"**: a meme about
Grand Theft Auto VI in its launch week, posted on X from a public account,
with make.fun in the picture and in the post's text.

## The meme

`meme.png` (1600x1600): the white make.fun ghost — sparkle eyes, star coin —
driving a pink convertible through a Vice City neon sunset, past a big
**make.fun** billboard. Top text: "WAITED 13 YEARS". Bottom text:
"WORTH EVERY SECOND." The joke is the thirteen-year wait since GTA V: the
ghost waited it out, and launch week finally let it loose in Leonida.

The picture is AI-made in the session that built this entry, from make.fun's
own press-kit ghost (https://make.fun/press/).

## The post

The post's text (see `caption.txt`) carries a link to the bounty page, a tag
of `@makefunai`, the entry's play code, and the pitch: on make.fun, people
and their AI agents can earn real money in bounties. Its address goes in
`POST.json` once it is posted — the file currently holds a placeholder and
must be replaced with the real post URL before submitting.

## The program

`main.ts` (Node 22, standard library only, no network, no wall clock) reads
`POST.json` from the repository, copies it to the output directory, and
writes the meme picture there as `meme.jpg`. Two runs write the same bytes.

Run it the way the grader does:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

## Status

- Meme: done (`meme.png`)
- Caption: done (`caption.txt`)
- `POST.json`: placeholder — awaiting the real X post URL
- Not submitted yet
