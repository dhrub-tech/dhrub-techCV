# dhrub-tech/CV

A one-page CV created using **Markdown → HTML → PDF**.

The purpose of this repository is to keep the CV content, layout and final PDF version together and maintain them through Git/GitHub.

---

## CV Creation Process

### 1. Resume Content — `resume.md`

The resume content is maintained in `resume.md`.

Markdown is used as the main resume template because it keeps the content simple, readable and easy to update.

The file contains:

- Personal information
- Professional summary
- Work experience
- Personal projects
- Technical skills
- Certifications
- Professional links

Whenever the resume content needs to be updated, `resume.md` is the primary file to edit.

---

### 2. Resume Layout — `resume.html`

The Markdown content is structured into an HTML resume layout using `resume.html`.

HTML is used to control the visual presentation of the CV, including:

- A4 page layout
- Typography
- Section headings
- Spacing
- Alignment
- Margins
- Borders
- Links
- Print formatting

The layout was designed to keep the CV clean, professional and suitable for a **single A4 page**.

---

### 3. PDF — `resume.pdf`

The final HTML resume is opened in a browser and exported/printed as a PDF.

`resume.pdf` is the final version used for applications and sharing.

---

## Repository Structure

```text
dhrub-techCV/
│
├── README.md
├── resume.md
├── resume.html
├── resume.pdf
└── LICENSE
