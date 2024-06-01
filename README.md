# LaTeX Template

This template is one that I created for my university proyects.

I cause I'm new in latex I designed this template to be as simple as possible with a minimal amount of effort to be reusable for all my proyects.

## Repository Contents

- `main.tex`: The main file that compiles the complete document.
- `core/`: Folder containing the core files of the document. (Vars, Configurations, imports, colors...)
- `sections/`: Folder containing the files for different sections of the document.
  - `intro.tex`: Introduction.
  - `methods.tex`: Methods.
  - `results.tex`: Results.
  - `conclusion.tex`: Conclusion.
- `images/`: Folder to store images used in the document.

## How to Use

1. **Clone the repository**:

```bash
git clone https://github.com/HugoAlvarezAjenjoDocs/SimpleLatexTemplate.git
```

2. Navigate to the project directory:

```bash
cd your_repository
```

3. Delete `.git` folder.

```bash
rm -r .git
```

4. Compile the document:

Use your favorite LaTeX editor (e.g., TeXShop, Overleaf, VS Code with the LaTeX Workshop extension, etc.) to open and compile main.tex.
Customization
You can customize the template to suit your needs:

Add or remove sections: Simply create new .tex files in the sections/ folder and include them in main.tex.

```tex
\input{sections/intro}
\input{sections/methods}
\input{sections/results}
\input{sections/conclusion}
```

## License

This template is released under the Creative Commons Zero v1.0 Universal license.
Fell free to use it in your projects.

---

Thank you for using this LaTeX template! We hope it will be helpful for your projects.

