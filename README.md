
# Jordi Coscolla CV

### Resume

- To modify the resume, edit the `resume.json`

- enter the shell `nix develop`
- Preview while you editing => `npm run preview` 


### Launch latex to build the PDF (Old CV)

Inside the `OldLatex` folder...

```
docker run -v ${PWD}:/workfolder --workdir /workfolder tianon/latex xelatex cv_10.tex
```
