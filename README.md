# LaTeX-Blank-Template

A template made for creating LaTeX documents using Docker or GitHub Codespaces.

## What is?

This template creates a development environment for creating documents made in LaTeX. All it takes is that you have Visual Studio Code on your machine or use Github Codespaces.

If you just need the Docker image to build your environment, you can make use of it using this package: [MiKTeX-Image](https://github.com/andsfonseca/MiKTeX-Image/pkgs/container/miktex)

## Usage

* GitHub Workspaces

  You can use this Medium post which explains a step-by-step guide on how to set up GitHub Workspaces: [Use Github Codespaces as your default LaTex online editor](https://medium.com/@andsfonseca/use-github-codespaces-as-your-default-latex-online-editor-5519baf49224)

* Local Machine

  [Create a new repository from this template](https://github.com/andsfonseca/LaTeX-Blank-Template/generate) or use the commands below:

  ```shell
  git clone [https://github.com/andsfonseca/LaTeX-Blank-Template.git](https://github.com/andsfonseca/LaTeX-Blank-Template.git)

  ```

## Word Conversion (Pandoc)

This environment includes [Pandoc](https://pandoc.org/), the universal markup converter, allowing you to seamlessly convert your LaTeX source files into Microsoft Word (`.docx`) documents.

### How to use the conversion tasks

We have provided built-in VS Code tasks to automate the conversion. To use them:

1. Open the VS Code Command Palette (`Ctrl+Shift+P` on Windows/Linux, `Cmd+Shift+P` on macOS).
2. Type and select **Tasks: Run Task**.
3. Choose one of the following options:
* **📄 Generate Word (Standard):** Compiles your `main.tex` into a standard `main.docx` file, including a generated Table of Contents.
* **🏢 Generate Word (Company Template):** Compiles the document applying custom Word styles. **Note:** This requires a reference file named `company_template.docx` to be placed in the root directory of your project.



## Issues

Feel free to submit issues and enhancement requests.

## Contribution

1. Fork the project
2. Create a *branch* for your modification (`git checkout -b my-new-resource`)
3. Do the *commit* (`git commit -am 'Adding a new resource...'`)
4. *Push* (`git push origin my-new-resource`)
5. Create a new *Pull Request*
