# What Humans Don't Know — Code Manuscript

This repository stores the manuscript in a code-inspired structure. Each chapter now lives in its own file, grouped by the book's parts.

## Directory layout

```
chapters/
  part01_the-hidden-self/
  part02_the-unseen-world/
  part03_the-machines-mirror/
  part04_the-forgotten-genius-of-ancients/
  part05_becoming-the-unknown/
```

Inside every part directory, chapter files follow the pattern:

```
chapterXX_<slugified-title>.txt
```

Each chapter file opens with a comment referencing its part and then captures the full chapter content using the code-like syntax established for the project.

## Updating content

1. Edit the relevant `chapterXX_*.txt` file in the appropriate part directory.
2. Keep the existing pseudo-code formatting intact (WordOfTheChapter, Story, Concept, etc.).
3. Run any custom tooling or scripts as needed to regenerate derived assets.
