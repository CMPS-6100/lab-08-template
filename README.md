# CMPS 6100  Lab 08

In this lab, you will build your own tiny shell.

To complete this lab, follow the instructions in [lab-08.md](lab-08.md) ([PDF version](lab-08.pdf)). Below you'll find important and useful information about submitting your work, using git, and testing your code. 

## Turning in your work
- At the top of `src/tsh.c` file, **include your name**.
- Once you have pushed your final submission to GitHub, go to Canvas and submit a link to your repository to the Canvas assignment for this lab.
- We will use gradescope to grade this assigment. Submit only your `tsh.c` 
source file to gradescope. Gradescope will take care of the rest.

## Using Git 
- [Clone] your lab repository.
- As you complete this lab, `add`, `commit`, and `push` your work up to GitHub. 
  - You will need to issue `git add` for all files that you have modified. For this lab, namely `tsh.c`, `answers.md`.
  - For example, on the command line, in the same directory as your cloned lab:
    ```
    $ git add tsh.c
    $ git commit -m "Implement builtin_cmd"
    $ git push origin main
    ```
  - It is recommended that you `add`, `commit`, and `push` your work often in order to regularly save your work to GitHub. The latest version of your work will be what is graded.

## About Markdown

We use Markdown extensively in these labs. Markdown is a great way to easily add formatting to simple text documents.

Here is a [cheatsheet] for markdown syntax.

You will notice in the lab documents that you can format mathematical expressions in markdown. To do so, wrap them in dollar signs. You can use [latex syntax] within the dollar signs. 

For example, the run time of our first example, linear search, this semester is $c_1n + c_2n + c_4 \in O(n)$. 

More generally, the runtime of any program can be expressed as:

$$\sum_i c_i * n_i$$

for every instruction $n_i$ and its cost $c_i$.

It's easy to do powers too. Euler's identity states: $e^{ix} + 1 = 0$

Pretty cool, huh?

You can also convert from markdown to pdf. `convert.sh` is provided for you to convert your `answers.md` to `answers.pdf`. As the comment in the script says, you will need to install pandoc and latex, but its pretty convenient to be able to do so. You do not need to submit you answers in PDF format, but you may if you like.

[Clone]: https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository
[cheatsheet]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[latex syntax]: https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions
