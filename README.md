# Assignment 0
#### Due: 11:59pm Friday, Jan 24

This is the repository for assignment 0. It contains the following files:

* `.gitignore` - tells git to ignore certain kinds of files. This prevents you from submitting the auxiliary files created when producing LaTeX documents.
* `A0.jmd` - the source code used to generate the assignment document, including examples of starter Julia code you may use for your own solutions. Feel free to fill in your answers directly into this file to produce your pdf writeup. Also feel free to try a more traditional workflow by writing your final writeup in a LaTeX `.tex` document, and completing your code in a standard Julia `.jl` file, or translate the starter code into a python `.py`.
* `A0.pdf` - the text of the assignment.
* `Project.toml` - the Julia environment, specifying packages and versions you can use to complete the programming questions. You can activate this environment by opening this project folder, and inside the Julia REPL typing: `] activate .`
* `README.md` - the text you are currently reading.
* `make_pdf.jl` - a short Julia script that contains the code used to produce A0.pdf from A0.jmd.

## Submitting with Github Classroom
If you are a registered student in the course, you will receive a link to accept this assignment which will `git clone` this repository through GitHub Classroom.

**If you are registered in the course and did not receive a Github Classroom assignment invitation, contact the instructors!**

You will submit your solutions for assessment by using the following `git` commands in commandline, with git integrated into your editor environment like [Atom](https://github.atom.io/), or with a dedicated [Github application](https://desktop.github.com/):

* `git status` - See what files have been changed, which have been `staged` (added and ready for a commit), or `unstaged` and will need to be added.
* `git add` - Add all the files you want assessed. Including your `.pdf` writeup and your source code (`.jl`, `.jmd`, or `.py`)
* `git commit` - Saves all the changes that were `staged` (by `git add`). 
* `git push` - Sends your changes off your machine. 

**Everything you want assessed must be committed and pushed before the assignment due date**

Please practice using git and pushing your solutions prior to the deadline. If you have any difficulties, ask on the course forum.

Keep your solutions to this assignment private and in accordance with our collaboration and academic integrity policy.

