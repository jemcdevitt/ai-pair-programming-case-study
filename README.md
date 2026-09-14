# AI Pair Programming After 40 Years of Software Development

A practical case study in AI-assisted software development based on four months of building three Minecraft/Paper plugins with ChatGPT as an engineering partner.

## Read the Article

The published version is available here:

**[Read the full case study](https://jemcdevitt.github.io/ai-pair-programming-case-study/)**

If this repository is being viewed through GitHub Pages, the article is the site homepage.

## About the Case Study

I have been developing software for more than forty years, through everything from embedded C and early Java to distributed systems, cloud platforms, architecture, and engineering leadership.

When generative AI began attracting increasingly polarized opinions — from claims that it would replace developers to dismissals of AI-generated software as "AI slop" — I decided to evaluate it the same way I have evaluated many new technologies over the years:

Build something with it.

That experiment became three Minecraft plugins:

- **SimpleShips** — smoothly moving and rotating ships assembled from ordinary Minecraft blocks
- **Dead Man's Chest** — a pirate treasure system with custom maps, markers, encounters, and composite display objects
- **Ramps and Wedges** — new building geometry created with custom resource-pack models, carrier blocks, and display entities

What began with ChatGPT acting primarily as an API research assistant gradually became something much closer to pair programming: architecture discussions, code reviews, design tradeoffs, debugging, rapid prototyping, visual iteration, and implementation work.

The article documents that journey, including the approaches that worked, the ones that did not, and the places where engineering judgment mattered more than generated code.

## What I Took Away From It

AI can replace a surprising amount of work.

What I did not find it could replace was engineering judgment and accountability.

The most useful collaboration was not "AI writes the code." It was a fast feedback loop:

**idea → options → prototype → test → review → refine**

In many ways, it felt less like automation and more like the architecture whiteboarding sessions I have spent much of my career participating in.

The tools changed again.

The engineering process did not.

## Repository Contents

- `index.html` — published HTML version of the article
- `TheArticle.org` — original Emacs Org Mode source
- `images/` — screenshots and illustrations used in the article

## The Projects

The case study is based on the development of:

- [**SimpleShips**](https://github.com/jemcdevitt/SimpleShips)
- [**Dead Man's Chest**](https://github.com/jemcdevitt/DeadMansChest)
- [**RampsNWedges**](https://github.com/jemcdevitt/rampsnwedges)

## About the Source

The article was written in **Emacs Org Mode** and exported to HTML for publication through GitHub Pages.

The source is included intentionally. This repository is not only the published article, but also the original document used to produce it.
