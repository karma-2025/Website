



# Briefly comment on which portions you used or revised and why.

For the sake of clarity and relevance as well as personal impact, I made some major revisions to my updated portfolio. I changed the title to best represent my MBA journey with “MBA Portfolio: “Karma Galley” as a professional and descriptive heading. The “About Me” section was revised to reflect my double professional experience and to illustrate how keen I am to contribute to positive social and economic change especially in under served areas. I moved from general job roles to specific organisations I worked for to support my profile and added concise bullet points that identify my huge contributions and achievements. I streamlined the skills section to emphasize the practical skills in line with my MBA course work and the skills I want to develop in the future. I ended the portfolio with a contact section that would make it easy for potential contacts to be in touch with me during my career. Such changes make the portfolio informative and really reflect my personal experiences and hopes.

# References

1. Quarto Documentation. (n.d.). *Visual Studio Code integration*. Retrieved from https://quarto.org/docs/tools/vscode.html
2. Quarto Documentation. (n.d.). *Creating a Website with Quarto*. Retrieved from https://quarto.org/docs/websites/
3. Quarto Documentation. (n.d.). *Publishing with GitHub Pages*. Retrieved from https://quarto.org/docs/publishing/github-pages.html
4. APA Style. (2020). *Publication manual of the American Psychological Association* (7th ed.). American Psychological Association.



# Appendix A: MBA Portfolio Source Code (LLM Output)

Create an outline and sample text for a one-page MBA student portfolio.  
I have shared my background and details below:

**Name:** Karma Galley  
**MBA:** 2024–2025  
**B.Com:** 2007  

**Experience:**  
- Accountant (2010–2015)  
- Construction Supervisor (2016–2022)  

I am using VS Code for Quarto which has 3 files:  
- `styles.css`  
- `index.qmd`  
- `_quarto.yml`

---

# Appendix B: `index.qmd` (Portfolio Source)

````qmd
---
title: "Karma Galley"
format: html
css: styles.css
---

# MBA Student Portfolio

**Name:** Karma Galley  
**Program:** MBA, 2024–2025  
**Undergraduate Degree:** B.Com, 2007  

---

## 🎓 Professional Summary

Motivated and disciplined MBA candidate with over a decade of diverse experience in accounting and construction management. I bring a unique blend of financial acumen and operational expertise, with a strong interest in strategic planning, process optimization, and leadership development. My journey reflects a commitment to continuous growth and the ability to adapt across industries.

---

## 💼 Experience

### Accountant  
**2010 – 2015**  
Handled full-cycle accounting duties including bookkeeping, payroll processing, and financial reporting. Developed solid foundations in financial compliance, budget monitoring, and data accuracy.

### Construction Supervisor  
**2016 – 2022**  
Led site operations for multiple residential and commercial projects. Coordinated teams, managed procurement, ensured safety compliance, and met critical deadlines—contributing to successful on-time project delivery.

---

## 🎯 Key Skills

- Financial Reporting & Budgeting  
- Project Coordination & Site Management  
- Cross-functional Team Leadership  
- Problem Solving & Decision Making  
- Strategic Thinking & Communication  

---

## 📈 Career Goals

As I pursue my MBA, I aim to bridge the gap between finance and operations, targeting leadership roles where I can drive efficiency and innovation. My long-term goal is to contribute to sustainable growth strategies within infrastructure or real estate sectors.
````

---

# Appendix C: Configuration Files

## `_quarto.yml`
```yaml
project:
  type: website

format:
  html:
    theme: default
    css: styles.css
```

## `styles.css`
```css
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 2em;
  color: #333;
  background-color: #fff;
}

h1, h2 {
  color: #2a4d69;
  margin-bottom: 0.4em;
}
```
