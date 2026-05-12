# quarto-tutorial

Welcome to this Quarto tutorial, where the goal is to create a first Quarto project, add some content, and render it as a PDF. In the end, we want to apply the IEEE-template which can be used for the Expose part of this course.

We will use GitHub Codespaces for this tutorial.

# Task 1
1. Create a Quarto project using the command from below.

```bash
quarto create project
```

2. Choose type: default
3. Give your project a name
4. Enter a directory name for your Quarto project (e.g. MyQuartoPrj)
5. Open the generated `.qmd` file inside the generated project directory

You have now successfully created your first Quarto project!

# Task 2

Paste the tutorial.qmd file into the generated Quarto directory. The file contains gaps that you have to fill out. The gaps are visualized like this: `[___]`.

What you have to do:
1. Fix the header
    - Use your name as author
    - Move the `references.bib` file inside the Quarto project directory
2. Fix the plot
    - Give a label
    - Give a caption
    - Use echo to show the code in the rendered document
3. Reference the plot using the label
4. Cite the paper from the `references.bib`
5. Run `quarto render` in the terminal
6. Replace `echo: true` with `echo: false` and rerun the render command
7. Inspect the pdf. The code from the plot is no longer visible.

# Task 3
Now we want to use the IEEE-template for the Quarto project.

1. 


# Sources
How to setup a Quarto GitHub Codespace: https://quarto.org/docs/blog/posts/2025-05-19-quarto-codespaces/index.html

