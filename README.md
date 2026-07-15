# Python Coder

A browser-based Python sandbox for learners. Write Python in an in-page editor and run it against an interactive terminal — no installs, no server, no accounts.

Python Coder is a static web app powered by [PyScript](https://pyscript.net/). It runs entirely in the browser and is designed to be hosted on GitHub Pages or any static host.

To get started, open [https://microsoftlearning.github.io/python-coder/](https://microsoftlearning.github.io/python-coder/) in a any browser (Chrome, Edge, or Firefox). You can also clone this repository and host it yourself.

## Features

- **In-browser Python** — code is executed by PyScript directly in the browser.
- **Interactive terminal** — supports `print()` output and `input()` prompts.
- **Quick-start templates** — one-click samples for **Hello World, User Input, Math & Types, and Loops & Decisions**.
- **Preloaded packages** — `numpy`, `pandas`, `matplotlib`, and `scikit-learn` are available out of the box.
- **Resizable layout** — drag (or use arrow keys on) the splitter to resize the editor and terminal panes.
- **Static-host friendly** — ships with a COOP/COEP service worker (`coi-serviceworker.js`) so terminal input works on GitHub Pages via cross-origin isolation.
