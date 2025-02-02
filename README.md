# Software Engineer Resume Template with High ATS Score

## Overview
This repository contains a LaTeX template for creating a professional resume with a clean, modular, and structured design. The template is optimized for readability and ATS (Applicant Tracking System) compatibility.

## Features
- **Minimalist Design:** A clean, modern layout with well-structured sections.
- **Custom Commands:** Simplifies adding content with predefined LaTeX macros.
- **Hyperlinks Support:** Clickable links for email, LinkedIn, GitHub, and portfolio.
- **Typography Optimization:** Uses Roboto font for better readability.
- **Compact and ATS-friendly:** Simple layout with no excessive graphical elements.

## Installation
### Prerequisites
Ensure you have the following installed:
- LaTeX distribution (e.g., TeX Live, MikTeX, or Overleaf)
- A LaTeX editor (e.g., TeXworks, Overleaf, or VS Code with LaTeX Workshop extension)

### Compiling the Resume
1. Clone this repository:
   ```bash
   git clone https://github.com/manish-9245/ATS-Friendly-Resume-SDE.git
   cd ATS-Friendly-Resume-SDE
   ```
2. Open `resume.tex` in your LaTeX editor.
3. Compile using `pdflatex` or an equivalent tool.
4. The generated `ATS-Friendly-Resume-SDE.pdf` will be ready to use. You can see a sample [here](Software_Engineer_Resume_Template_High_ATS_Score.pdf).

## Usage
### Editing Personal Information
Modify the `\contacts` command in the **Profile** section to update:
- Name
- Email
- LinkedIn
- GitHub
- Portfolio
- Phone Number
- Location

### Adding Experience, Projects, and Education
Use the predefined commands:
- `\employer{Company}{Job Title}{Start Date}{End Date}{Bullet Points}`
- `\education{Institution}{Location}{Degree}{Start Date}{End Date}{GPA}`
- `\project{Project Name}{Project Link}{Tech Stack}{Bullet Points}`
- `\certification{Cert Link}{Cert Name}{Issuer}`

### Adjusting Technical Skills
Modify the `\techstack` command inside the **Technical Skills** section to update programming languages, tools, databases, and cloud technologies.

## Customization
- Modify spacing using the `geometry` package in `\usepackage[left=1cm, right=0.7cm, top=1cm, bottom=1cm]{geometry}`.
- Adjust font settings via the `\usepackage{roboto}` package.
- Change bullet styles using `\begin{itemize}[leftmargin=0.7cm, itemsep=-2pt, topsep=0pt]`.

## Contributing
Feel free to submit pull requests or issues for improvements, feature additions, or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
**Manish Tiwari**
- GitHub: [manish-9245](https://github.com/manish-9245)
- LinkedIn: [manishtiwari13](https://www.linkedin.com/in/manishtiwari13/)

