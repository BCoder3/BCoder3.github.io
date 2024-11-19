[Back to Portfolio](./)

HTML Parser
===============

-   **Class:** CSCI 315
-   **Grade:** B
-   **Language(s):** C++
-   **Source Code Repository:** [BCoder3/Brayden-K-csci-portfolio](https://github.com/BCoder3/source-code-repo-for-portfolio)  
    (Please [email me](mailto:BMKirkland@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project is designed to parse given HTML files, notify the user if the given file is balanced - meaning if it is fully semantically correct, or "balanced", or not, and also count and display how many other files the file can visit via url, and how many files that those found files can visit, and so on.

## How to compile and run the program

A makefile is included in the implementation of this project, which only requires the command "make" to compile the program. To run, use the command "make run", which also compiles the program again before running, if necessary.

```bash
make
make run
```

## UI Design

The program is not inherently designed to accept user input, but can be adjusted to do so. The program's main function is to iterate through given HTML files and parse each one to find if they are balanced, and to count how many other files can be visited through each, not including duplicate files.

![screenshot](images/project_2_fig_1.png)  
Fig 1. The UI Design

## 3. Additional Considerations

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
