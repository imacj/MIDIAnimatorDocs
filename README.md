# MIDIAnimator documentation

Read the docs here: https://midianimatordocs.readthedocs.io/

To build:

1. If you don't have sphinx installed, run `pip install sphinx && pip install sphinx_rtd_theme && pip install myst-parser`
2. Clone the repository `git clone https://github.com/imacj/MIDIAnimatorDocs.git`
3. Run `cd docs && make clean && make html` in the repository directory.
4. Open `index.html` or run `cd build/html/ && open index.html` (for Mac users)

Note: Instead of reStructuredText markdown files, we are using MyST markdown files. For some basic information on MyST markdown, visit https://myst-parser.readthedocs.io/en/v0.15.1/sphinx/intro.html.

**Please open a PR if you want to make changes to the docs.**

<!--

Useful commands:

for building (in docs dir)
make clean && make html

(for opening built html and going back to docs dir)
cd build/html/ && open index.html && cd ../../

-->
