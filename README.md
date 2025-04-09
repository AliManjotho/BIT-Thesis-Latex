# BIT-Thesis-Latex (English Version)
The latex template for BIT-Thesis submission (Masters and PhD) (English Version)

## Setup the environment
1. Download TexLive
```
https://eu.mirrors.cicku.me/ctan/systems/texlive/Images/texlive2025.iso
```
3. Install TexLive by running install-tl-windows.exe
4. Confirm installation
5. Open PowerShell for Windows and run following commands one-by-one

```PowerShell
latexmk --version
xelatex --version
biber --version

tlmgr update --self
tlmgr install bithesis
tlmgr update bithesis
```
4. Download and Install TeXstudio
   https://www.texstudio.org/
5. Settings > Time & Language > Language & Region > Add a Language > Install Chinese (Simplified, China)
6. Download this repository Code > Download Zip
7. Extract the downloaded archieve
8. Open thesis.tex and Run


> [!NOTE]
> For Blind Review submission, set the flag blindPeerReview=true in the documentclass tag with in main.tex file. 
```latex
\documentclass[type=doctor,twoside=false, english=true, blindPeerReview=true]{bithesis}
```
