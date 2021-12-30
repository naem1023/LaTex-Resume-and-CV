# LaTex-Resume-and-CV
LaTex Resume and CV

# Requirements on VSCode
- LaTex Workshop Extension
- TexLive from [Link](https://www.tug.org/texlive/)
- Restart system

# How To Use
## pdfTex
Just save tex file. LaTex Workshop will generate pdf file.
## XeLaTex
1. File -> Preference -> Search LaTex Workshop -> Press "Edit in settings.json"  
2. Append the code below.
3. From Command Palette, Search "LaTex Workshop: Build with recipe".
4. Select "xelatex". 
```json
{
    "latex-workshop.latex.recipes":[
        {
            "name": "xelatex",
            "tools": [
                "xelatex"
            ]
        }
    ],
    "latex-workshop.latex.tools": [
        {
            "name": "xelatex",
            "command": "xelatex",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOC%"
            ]
        }
    ]
}
```

# My Resume & CV
## Div2
[CV PDF file](Div2/main.pdf)
- Update
  - 2021.12.31: Fix all syntax error.
- Reference: [Link](https://www.overleaf.com/latex/templates/resume-template/gxymbfbhdjwk)

## PlushCV
[CV PDF file](PlushCV/PlushCV.pdf)
- Reference: [Link]()
