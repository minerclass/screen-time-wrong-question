# Screen Time Is the Wrong Question

An interactive companion to the CoSN blog post *Screen Time Is the Wrong Question: What Is the Screen Asking Students to Practice?* by Micah J. Miner, CETL, Ed.S.

The piece reframes the K–12 screen time conversation around cognitive work and pedagogical friction in the age of generative AI. This site renders the full essay with interactive elements designed for district technology leaders, instructional coaches, and school board members.

The repository also contains a Fall 2026 public-scholarship companion:

- [`pouch-and-bypass/`](https://minerclass.github.io/screen-time-wrong-question/pouch-and-bypass/) maps the distinct arguments made by Jared Cooney Horvath, Jonathan Haidt, Candice Odgers, and Stefan Bauschard; examines phone restrictions alongside school-device access models; applies the pedagogical-friction framework; and offers a six-question district policy audit.
- [`pouch-and-bypass/research-notes.md`](pouch-and-bypass/research-notes.md) records the claim boundaries, APA-style citations, and policy-source distinctions behind the companion.

## View the site

Open `index.html` in any modern browser, or enable GitHub Pages on this repository to publish it at:

`https://<username>.github.io/screen-time-wrong-question/`

## What's interactive

- Scroll progress indicator and scroll-reveal section animations
- Four expandable leadership-question cards covering the cognitive, dialogic, authorship, and infrastructure dimensions of pedagogical friction
- A subject-switching diagram showing when AI should enter the learning sequence in writing, science, and social studies
- A productive-friction vs. exclusionary-friction comparison panel
- A district leadership priority checklist with progress state

## Structure

```
.
├── index.html      Single-file site with inline CSS and JS
├── pouch-and-bypass/
│   ├── index.html         Fall 2026 debate companion and district audit
│   └── research-notes.md  Evidence notes, citations, and policy sources
├── README.md       This file
├── LICENSE         Creative Commons BY-NC-SA 4.0
└── .nojekyll       Disables Jekyll processing on GitHub Pages
```

No build step. No dependencies. No tracking scripts.

## Publishing to GitHub Pages

1. Push this repository to GitHub.
2. In repository settings, open **Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, **Branch** to `main`, and **Folder** to `/ (root)`.
4. Save. The site will be live within a minute or two.

## License

The code is released under the MIT License (see `LICENSE-CODE` if added separately). The written content is released under [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Attribution: Micah J. Miner.

## Author

Micah J. Miner, CETL, Ed.S. — Director of Innovation and Technology, Beach Park CCSD 3. Author of *AI Goes to School* (Times 10 Publications). Doctoral candidate at National Louis University. CoSN AI and EdTech Innovation Committees.

[micahminer.com](https://micahminer.com)
