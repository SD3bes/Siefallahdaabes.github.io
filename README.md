# Sief Allah Daabes — Portfolio & CV

Personal portfolio and CV of Sief Allah Ahmed Daabes, cybersecurity and network engineer based in Giza, Egypt.

- **Live site:** https://sd3bes.github.io/
- **PDF CV:** [cv/Sief-Allah-Daabes-CV.pdf](cv/Sief-Allah-Daabes-CV.pdf)
- **LinkedIn:** https://www.linkedin.com/in/sief-allah-daabes/

## About the site

A single static `index.html` with no build step or dependencies beyond Google Fonts.
The same page carries a print stylesheet, so printing it (or `Ctrl+P → Save as PDF`,
headers and footers off) produces the light, single-column CV in `cv/`.

## Regenerating the PDF

From the repository root, with Microsoft Edge or Chrome installed:

```powershell
& "C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe" --headless=new --disable-gpu --no-pdf-header-footer --print-to-pdf="$PWD\cv\Sief-Allah-Daabes-CV.pdf" "file:///$PWD/index.html"
```
