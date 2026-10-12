# under-the-hood

I read the source code of interesting projects, one at a time, and write down everything I understand about how they work. This repo is where all of it lives: raw notes, little experiments, diagrams, and the final write-ups.

The goal is simple: after reading one of my write-ups, you should be able to explain how the project works, even if you never open its code.

## Projects

| Project                  | What it is                                                              | Status      | Write-up      |
| ------------------------ | ----------------------------------------------------------------------- | ----------- | ------------- |
| [micrograd](./micrograd) | A tiny neural network library that learns by itself, built from scratch | In progress | _coming soon_ |
| [nanoGPT](./nanogpt)     | A small version of how ChatGPT-style language models work               | Planned     | _coming soon_ |

More to come (a browser engine and a game engine are on the wishlist).

## How this repo is organized

Every project gets its own folder with the same shape:

```
<project>/
  notes.md          # raw daily log: what I read, what I understood, what confused me
  experiments/      # small scripts I wrote to test my understanding
  diagrams/         # sketches and figures
  article.md        # the final, polished write-up
```

The `_template/` folder holds blank copies of `notes.md` and `article.md`. To start a new project, copy the template files into a new folder.

## How I work

1. **Read in small pieces.** One part of the code at a time, no rushing.
2. **Keep messy notes daily.** Especially the things that confused me, because those become the best parts of the article.
3. **Trace one example from start to finish.** Pick a single input and follow it through the code. That journey becomes the spine of the write-up.
4. **Write the article last,** mostly assembled from the notes.

## A note on accuracy

I'm learning as I write. If something here is wrong or unclear, please open an issue. Corrections are welcome and make the write-ups better.

## Where else to find these

Polished articles are also posted on Hashnode (link coming once the first one is published).
