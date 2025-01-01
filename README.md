# ATS Friendly Resume for SDE
Probably the best single page ATS Friendly resume for Software Engineers
A clean and professional LaTeX resume template with modern features including FontAwesome icons, hyperlinks, and custom spacing.

## Features

- Clean and professional layout
- Custom spacing and formatting commands
- Integration with FontAwesome 5 icons
- Hyperlinked contact information
- Support for custom images (e.g., LeetCode logo)
- Sections for Education, Experience, Projects, Honors & Awards, and Technical Skills
- Customizable bullet points with reduced spacing
- Mobile-friendly A4 paper size

## Prerequisites

The template requires the following LaTeX packages:
- fullpage
- amsmath
- amssymb
- textcomp
- inputenc
- fontenc
- hyperref
- geometry
- longtable
- enumitem
- fontawesome5
- graphicx

## File Structure

```
resume/
├── resume.tex
├── images/
│   └── leetcode.png
└── README.md
```

## Usage

1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX)
2. Place your custom images in the `images/` directory
3. Modify the resume.tex file with your information
4. Compile using your preferred LaTeX compiler:
   ```bash
   pdflatex resume.tex
   ```

## Customization

### Profile Section
```latex
\begin{center}
{\Huge \scshape \textbf {Your Name}}
% Add your contact links here
\end{center}
```

### Custom Commands

- `\area{title}{content}`: Creates a new section with custom spacing
- `\lineunder`: Adds an underline separator
- `\header{title}`: Creates a section header
- `\employer{company}{date}{position}`: Formats employer information
- `\contact{name}{info1}{info2}`: Formats contact information
- `\schoolwithcourses{school}{date}{location}{courses}`: Formats education information with courses
- `\school{school}{date}{location}{details}`: Formats education information

## Icon Support

The template includes FontAwesome 5 icons for:
- Email (`\faEnvelope`)
- LinkedIn (`\faLinkedin`)
- GitHub (`\faGithub`)
- Website (`\faGlobe`)
- Custom icons (via images)

## Page Layout

- Paper size: A4
- Margins: 1.5cm on all sides
- Font size: 10.85pt
- Single column layout

## Tips for Best Results

1. Keep bullet points concise and achievement-focused
2. Use consistent spacing between sections
3. Highlight key achievements and metrics in bold
4. Ensure all hyperlinks are working properly
5. Maintain consistent date formatting throughout

## License

This template is available under the MIT License. Feel free to modify and distribute as needed.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.