
# Jordi Coscolla CV

### Resume

- To modify the resume, edit the `resume.json`

- Preview while you editing => `npm run preview` 
- Create a PDF => `npm run export-pdf`
- Create a HTML => `npm run export-html`


### Launch latex to build the PDF (Old CV)

Inside the `OldLatex` folder...

```
docker run -v ${PWD}:/workfolder --workdir /workfolder tianon/latex xelatex cv_10.tex
```
