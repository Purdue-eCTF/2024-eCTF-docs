# 2023-eCTF-design-docs-private
!!! Internal !!! design docs for the PARED protocol and documentation

## Instructions

To write and build the document, you'll need an appropriate LaTeX 2e distribution and compiler. You can run LaTeX locally on your own computer (better integrates with GitHub, slightly slower to setup) or use Overleaf (easier to setup and also has basic GitHub integration, but disallows branching and [has other issues with synchronization](https://www.overleaf.com/learn/how-to/Using_Git_and_GitHub#Known_Limitations)). For convenience, see below for instructions on how to install and use both:

### Local CLI (recommended)

1. Install your favorite LaTeX distribution / package manager + compiler (e.g. [TeXLive](https://www.tug.org/texlive/) + pdfTeX)
2. Add your LaTeX distribution and compiler to your `PATH` or environment variables 
3. [recommended] Install your favorite text editor's LaTeX extension (e.g. [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) for VSCode) to automatically build PDF on save.
4. [optional] If using commandline tools to compile LaTeX, follow the appropriate compiler documentation to build your PDF.

To make changes:
1. Pull, commit, merge, push, etc. to the `main` branch, OR
2. Create a new branch then submit a pull request, if you'd prefer.

### Overleaf

To properly sync this repository with Overleaf, you should clone and merge from Overleaf Premium's GitHub interface:
1. [sidebar] Click "New Project" then [dropdown] click "Import from GitHub"
2. Scroll down until you see `Purdue-eCTF-2023/2023-eCTF-design-docs-private`, then click "Import to Overleaf". This might take a few moments.
3. Open the project that it created.

To make changes:
1. Open the sidebar menu, click "GitHub" then click "**Pull** changes into Overleaf" **before AND after** making changes.
2. Once you're done, click "**Push** changes into Overleaf" to update the `main` branch.

## Contributing

Since we're mostly working on the `main` branch, please keep in touch with others on the design documentation team to avoid merge or other logistical conflicts.

Any comments or contributions on the documentation is appreciated!

### Authors
- Jacob White (@enigcryptist)
- Jayashree Srinivasan
### Contributors
- Many other b01lers & PurS3cure team members
