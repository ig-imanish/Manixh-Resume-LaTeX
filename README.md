# ATS-Friendly Resume Template 📄

A clean, professional, and **ATS (Applicant Tracking System) friendly** LaTeX resume template optimized for software developers and engineers.

![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![Overleaf](https://img.shields.io/badge/Overleaf-47A141?style=for-the-badge&logo=overleaf&logoColor=white)

## ✨ Features

- **ATS Optimized** - Machine-readable format that passes through applicant tracking systems
- **Clean Design** - Professional layout with proper spacing and typography
- **FontAwesome Icons** - Modern icons for contact information
- **Easy to Customize** - Well-organized sections with clear comments
- **Single Page** - Concise format preferred by recruiters
- **Hyperlinks** - Clickable links for portfolio, GitHub, and LinkedIn

## 📋 Sections Included

- Header (Name, Phone, Email, LinkedIn, GitHub, Portfolio)
- Work Experience
- Projects
- Achievements
- Technical Skills
- Education

## 🚀 Quick Start

### Option 1: Using Overleaf (Recommended)

1. Go to [Overleaf.com](https://www.overleaf.com/)
2. Create a free account or log in
3. Click **"New Project"** → **"Blank Project"**
4. Name your project (e.g., "My Resume")
5. Delete the default content in `main.tex`
6. Copy the entire content from [`manish.tex`](./manish.tex)
7. Paste it into the Overleaf editor
8. Click **"Recompile"** to see your resume
9. Edit with your own information
10. Download as PDF when done!

### Option 2: Local Compilation

```bash
# Clone the repository
git clone https://github.com/ig-imanish/ats-resume-template.git
cd ats-resume-template

# Compile with pdflatex
pdflatex manish.tex
```

**Requirements for local compilation:**
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- `fontawesome5` package

## 📝 How to Customize

### 1. Update Header Information
```latex
{\Large \scshape Your Name} \\[3mm]
\faPhone\ \underline{+91-XXXXXXXXXX} ~
\faEnvelope\ \underline{your.email@gmail.com} ~
\faLinkedin\ \underline{\href{https://linkedin.com/in/yourprofile}{linkedin.com/in/yourprofile}} ~
\faGithub\ \underline{\href{https://github.com/yourusername}{github.com/yourusername}} ~
```

### 2. Add Work Experience
```latex
\resumeSubheading{Company Name}{Start Date -- End Date}{Job Title}{Location}
\resumeItemListStart
    \resumeItem{Your achievement with \textbf{metrics} and \textbf{impact}}
    \resumeItem{Another achievement showing \textbf{quantifiable results}}
\resumeItemListEnd
```

### 3. Add Projects
```latex
\resumeProjectHeading
    {\textbf{Project Name} $|$ \emph{\href{https://link.com}{Website}}}{Tech Stack}
    \\[5mm]
  \resumeItemListStart
    \resumeItem{Description with \textbf{impact metrics}}
  \resumeItemListEnd
```

### 4. Update Skills
```latex
\textbf{Languages}{: Java, Python, JavaScript, ...} \\[1mm]
\textbf{Backend}{: Spring Boot, Node.js, ...} \\[1mm]
\textbf{Frontend}{: React, Next.js, ...} \\[1mm]
```

## 💡 Tips for ATS-Friendly Resumes

1. **Use metrics** - "Improved performance by **40%**" instead of "Improved performance"
2. **Use keywords** - Match keywords from job descriptions
3. **Professional terms** - "OAuth 2.0 SSO authentication" instead of "login with Google"
4. **Bold important terms** - Use `\textbf{keyword}` for emphasis
5. **Keep it one page** - Recruiters spend ~6 seconds on initial scan
6. **No images/graphics** - ATS can't read them (icons are fine)

## 📁 File Structure

```
├── manish.tex          # Main resume template
├── README.md           # This file
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Submit issues for bugs or suggestions
- Create pull requests with improvements
- Share your customized versions

## 📄 License

This template is open source and available under the [MIT License](LICENSE).

## 🙏 Credits

- Template inspired by [Jake's Resume](https://github.com/jakegut/resume)
- Icons by [FontAwesome](https://fontawesome.com/)

---

**Made with ❤️ by [Manish Kumar](https://manixh.dev)**

If this template helped you land an interview, consider giving it a ⭐!
