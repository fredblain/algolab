# AlgoLab: from exercise text to Python function

Practice tool for **822207 – Programming & Algorithmic Thinking**.

**Use it online: https://fredblain.github.io/edu/algolab/**
or open **`index.html`** in any web browser (double-click it). Nothing to install.

An exam exercise is a few sentences of English. Writing the Python goes wrong when you jump
straight to code. AlgoLab trains the method from the course, one step at a time, on 67 exercises.

## The three steps

For every exercise, in this order:

1. **Recognise**: click a phrase of the exercise, then the component it is (the function, an input,
   the output, a check, …). A wrong match gives a hint; after two hints you can ask to be shown.
2. **Loop?**: first decide whether something has to be repeated (sometimes it does not). If so, answer
   the loop questions in words: over what, where it starts, when it stops, what to remember, what to
   return. A loop inside a loop gets the same questions. Every wrong answer explains why.
3. **Assemble**: build the function from shuffled lines: drag them into order and left or right to
   indent them (or use the buttons). Three lines are distractors that go against your answers.

Once solved, AlgoLab shows the finished function, explains each distractor, and opens the loop in
[LoopLab](https://fredblain.github.io/edu/looplab/) to watch it run or to trace it yourself.

## Good to know

- It opens on a **Start** page: the exercises are grouped by topic (Numbers, Time and schedules, Text,
  Lists, Dictionaries), easier first, and turn green when solved.
- **Nothing is graded and no code is run**: it is practice. The solution shown is one good way to write
  each function, not the only one.
- **Progress is saved in your browser only**, on this device. Another computer or a private window
  starts fresh. Nothing is sent anywhere.
- The page works offline, except the fonts and the LoopLab buttons.
- **Feedback**: use **Send feedback** at the bottom of the page or under a solved exercise. It opens
  an email with the version and the exercise already filled in.

Current version: **1.1.0** (shown at the bottom of the page).

## Folder contents

```
index.html      AlgoLab (a single self-contained file)
README.md       this file
LICENSE         licence for the content (CC BY 4.0) and notice on third-party material
LICENSE-CODE    licence for the code (MIT)
```

## Credits and licence

Designed and edited by Frédéric Blain, with drafting assistance from Claude (Anthropic).

50 of the 67 exercises are based on the *Python Exercise Bank v1.8* (November 2025) by Paris
Mavromoustakos-Blom, with acknowledgements to Pieter Spronck (Python book, notebooks and exercises)
and Lisa Rombout (exercises). They are marked "Exercise Bank" in the page and remain their authors'
work; they are not covered by the licences below.

AlgoLab's own content is licensed under CC BY 4.0 (see `LICENSE`), the code under the MIT License
(see `LICENSE-CODE`). AlgoLab loads the fonts Inter, Space Grotesk and JetBrains Mono from Google
Fonts. They are under the SIL Open Font License and are not included in this repository.
