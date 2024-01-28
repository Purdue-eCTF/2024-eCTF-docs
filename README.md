# eCTF-2024-docs-private
!!!NOTE: Internal design docs for the MISC protocol and documentation

If you simply want to view the current state of the design documentation, ask one of the authors for a copy (including PDF makes version control a mess...). 

## Contributing

Since we're mostly working on the `main` branch, please keep in touch with others on the design documentation team to avoid merge or other logistical conflicts. See `#threats-and-protocols` channel on the Discord for relevant design and/or documentation updates.

Any comments on or contributions to the documentation is appreciated!
### PDF Build Instructions

To write and build the document, you'll need an appropriate LaTeX 2e distribution and compiler. You have two options here:
1. You can run LaTeX locally on your own computer (+: better integrates with GitHub, -: slightly more annoying to setup) or;
2. Use Overleaf (+: easier to setup and has basic GitHub integration, -: disallows branching and you must [MANUALLY push from/pull to repository](https://www.overleaf.com/learn/how-to/Using_Git_and_GitHub#Known_Limitations) to synchronize changes).

For convenience, see below for instructions on how to install and use both:

#### Option 1: Local LaTeX Build

1. Install your favorite LaTeX distribution / package manager + compiler (e.g. [TeXLive](https://www.tug.org/texlive/) distribution with pdfTeX compiler).
2. Add your LaTeX distribution and compiler to your `PATH` / environment variables.
3. [recommended] Install your favorite text editor's LaTeX extension (e.g. VSCode's [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)) to automatically build and view PDF on save.
4. [advanced] If using command line tools to compile LaTeX, follow the appropriate compiler documentation to build your PDF.

To make changes:
1. Pull, commit, merge, push, etc. to the `main` branch, OR;
2. Create a new branch then submit a pull request, if you'd prefer.

#### Option 2: Overleaf

To properly sync this repository with Overleaf, you must clone and merge from Overleaf Premium's GitHub interface (available with Purdue student account):
1. [sidebar] Click "New Project" then [dropdown] click "Import from GitHub"
2. Scroll down until you see `Purdue-eCTF-2024/eCTF-2024-docs-private`, then click "Import to Overleaf". This might take a few moments.
3. Open the project that it created.

To make changes, you **MUST** follow these directions:
1. Open the Overleaf Menu, click "GitHub", then check for any new commits **before AND after** making changes. If there are any, "**Pull** changes into Overleaf".
2. Once you're done, click "**Push** changes into Overleaf" to update the `main` branch.

### Authors
- Jacob White (@enigcryptist)
- Jimmy
- Vinh
- Susan
### Other Contributors
- Many other b01lers & PurS3cure team members
