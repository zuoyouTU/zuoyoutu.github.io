# zuoyoutu.github.io

Resume site built from a single data source.

## Structure

- `index.html`: main resume page
- `resume/`: regular PDF wrapper page
- `ats/`: ATS HTML page and ATS PDF wrapper page
- `assets/`: shared static assets and generated PDFs
- `data/resume_data.json`: single resume content source
- `tools/build_resume.py`: generator for HTML and PDF outputs

## Build

```powershell
python tools/build_resume.py
```
