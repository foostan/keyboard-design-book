# How to Design a Keyboard

This repository contains the source files for the book "How to Design a Keyboard." The book is written in Markdown format and can be built into PDF and EPUB formats using Pandoc.

## Building the Book

### Prerequisites

- [Pandoc](https://pandoc.org/) installed on your system

### Build Instructions

1. Open a command prompt or terminal in the folder containing the Markdown files.
2. Run the following commands to build the book:

   - To convert the Markdown file to PDF:
     ```
     pandoc keyboard_design_book.md -s -o keyboard_design_book.pdf
     ```
   - To convert the Markdown file to EPUB:
     ```
     pandoc keyboard_design_book.md -s -o keyboard_design_book.epub
     ```

## How to Contribute

We welcome contributions to improve and expand the content of this book. Here's how you can contribute:

1. **Fork this repository**: Click the "Fork" button at the top-right corner of this page to create your own copy of the repository.

2. **Clone your fork**: Clone your forked repository to your local machine using the following command (replace `your-username` with your GitHub username):

```
git clone https://github.com/your-username/keyboard-design-book.git
```

3. **Create a new branch**: Navigate to the cloned repository on your local machine and create a new branch for your changes:

```
cd keyboard-design-book
git checkout -b your-feature-branch
```


4. **Make your changes**: Edit the `keyboard_design_book.md` file or any other relevant files to make your changes or additions to the book content.

5. **Commit your changes**: Add and commit your changes to your local repository:

```
git add .
git commit -m "Description of your changes"
```

6. **Push your changes**: Push your changes to your forked repository on GitHub:

```
git push origin your-feature-branch
```


7. **Create a pull request**: Go to the original repository on GitHub and click the "New Pull Request" button. Select your forked repository and the branch containing your changes, and submit the pull request.

After you submit your pull request, the project maintainers will review your changes and, if everything is in order, merge your changes into the main repository. Thank you for your contributions!


