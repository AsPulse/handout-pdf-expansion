# handout-pdf-expansion
Specify the number of copies for each distribution destination and copy and merge the specified PDF files.

**Warning:** This software is under development.
Some of the information below has not yet been implemented.

## Usage

1. Create directories named `targets`, `output` in your current directory.
1. Put your pdf file which you want to print directly under your current directory, and change its name to `original.pdf`.
1. Put your pdf file which is to be the front cover of each targets under your `targets` directory, and change its name to `<target-name>_<number-of-copies>.pdf`

    At this point, the directory structure should look like the one below:
    ```
    <your current dir>
     |
     +-- original.pdf
     |
     +-- targets
     |    +-- sales-team_5.pdf
     |    +-- development-team_3.pdf
     |
     +-- output (empty)
    ```
1. Run handout-pdf-expansion. It create the files under output directory. Each of them has front cover, and specified number of copies.

    ```
    <your current dir>
     |
     +-- original.pdf
     |
     +-- targets
     |    +-- sales-team_5.pdf
     |    +-- development-team_3.pdf
     |
     +-- output
          +-- sales-team.pdf
          +-- development-team.pdf
    ```

1. Let's print the generated pdf files and finish your work!
