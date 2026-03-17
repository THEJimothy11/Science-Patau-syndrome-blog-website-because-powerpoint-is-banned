# 🧬 Patau Syndrome Research Blog
**Genetic Disorder Research Project — Biology Class**

A blog-style website about Patau Syndrome (Trisomy 13), built in HTML and ready to host on GitHub Pages.

---

## 📁 File Structure

```
your-repo/
├── index.html                  ← Home page (links to all 4 posts)
├── doctors-report.html         ← Part 1: Doctor's Report
├── genetic-counselor.html      ← Part 2: Genetic Counselor's Report
├── parents-journal.html        ← Part 3: Parent's Journal
├── community-resources.html    ← Part 4: Community Resources
├── references.html             ← Works Cited page
├── README.md                   ← This file
└── images/                     ← Create this folder, add your 6+ images here
    ├── karyotype.jpg            (Image 1 — used in doctors-report.html)
    ├── ultrasound.jpg           (Image 2 — used in doctors-report.html)
    ├── nondisjunction.jpg       (Image 3 — used in genetic-counselor.html)
    ├── family.jpg               (Image 4 — used in parents-journal.html)
    ├── hospital.jpg             (Image 5 — used in parents-journal.html)
    └── support.jpg              (Image 6 — used in community-resources.html)
```

---

## ✅ How to Host on GitHub Pages

1. Create a free account at [github.com](https://github.com)
2. Click **New Repository** — name it anything (e.g., `patau-syndrome-blog`)
3. Upload `index.html`, `README.md`, and your `images/` folder
4. Go to **Settings → Pages → Source → main branch → Save**
5. Your site will be live at: `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## ✏️ What You Need to Fill In

Every yellow `TO FILL IN` box in the HTML is something you need to complete. Here's a summary:

### 🔖 Title Page (top of the page)
- [ ] Replace `[YOUR NAME]` with your actual name
- [ ] Replace `[CLASS PERIOD]` with your class period
- [ ] Replace `[DATE]` with the due date or submission date
- [ ] Replace the hero image placeholder with a real image (see Images section below)

---

### 🩺 Part 1 — Doctor's Report
- [ ] **What Is Patau Syndrome** — Rewrite completely in your own words. Explain the extra chromosome and what it does.
- [ ] **Symptoms** — Expand the bullet list in your own words. Explain what each symptom means medically.
- [ ] **Statistics** — Verify the stat boxes with your sources. Add info about maternal age as a risk factor.
- [ ] **Treatment Options** — Describe each treatment in your own words. How would it apply to YOUR child?
- [ ] **Research / Cure** — Look up recent studies on PubMed or Google Scholar. Describe current research directions.
- [ ] **Assistive Technologies** — Name specific brands/products. Explain how each one helps.

---

### 🧬 Part 2 — Genetic Counselor's Report
- [ ] **Types of Patau Syndrome** — Explain full, mosaic, and translocation trisomy in your own words.
- [ ] **Dominant/Recessive explanation** — Write a paragraph on why this classification doesn't apply here.
- [ ] **Parent Genotypes** — Explain recurrence risk and maternal age in your own words.
- [ ] **Punnett Square** — Edit the table to match YOUR scenario. Write an explanation below it. If you focus on nondisjunction, explain why a Punnett square doesn't fully apply.
- [ ] **Pedigree** — Modify or recreate the SVG pedigree to match your family. Write a paragraph explaining it. The pedigree must show 3 generations.

---

### 💛 Part 3 — Parent's Journal (write in FIRST PERSON throughout)
- [ ] **Daily Routine** — Describe specifically what a day in YOUR life would look like with this child.
- [ ] **Accommodations** — Research real accommodations and describe them personally.
- [ ] **Medical Costs** — Verify cost estimates with cited sources. Add how you'd handle them financially.
- [ ] **Emotional Impact** — Write a genuine, heartfelt reflection on how you, your spouse, family feel.
- [ ] **Move?** — Research local facilities. Would you need to relocate? Name specific hospitals.
- [ ] **Social considerations** — How would your child be treated? How would you advocate for them?
- [ ] **Heredity** — Personalize the recurrence risk section based on your counselor section.

---

### 🤝 Part 4 — Community Resources
- [ ] **Local Treatment Centers** — Name and describe 2+ real facilities near you. Add addresses and phone numbers.
- [ ] **Local Support Groups** — Research local or regional groups. If none, explain and use online options.
- [ ] **National Organizations** — The 4 national orgs are pre-filled — verify contact info is current.
- [ ] **Special Schools/Programs** — Fill in your state's Early Intervention contact. Add a specific local school.
- [ ] **Local Businesses** — Research local businesses, Ronald McDonald House, Rotary Clubs, etc. Add contact info.
- [ ] **Online Support** — Add a second online community with real contact details.

---

### 📚 References (Works Cited)
- [ ] Replace all 5 citation placeholders with your real sources in **APA or MLA format**
- [ ] **At least 1 source must be non-website** (medical journal, textbook, book). Search PubMed.gov for journal articles.
- [ ] Recommended sites: `medlineplus.gov`, `trisomy.org`, `rarediseases.org`, `marchofdimes.org`, `pubmed.ncbi.nlm.nih.gov`
- [ ] Use [EasyBib.com](https://www.easybib.com) or [CitationMachine.net](https://www.citationmachine.net) to format citations

---

## 🖼️ Adding Your 6 Images

The project requires **at least 6 images**. The HTML has 6 placeholder spots already:

| Image # | Location | Suggested Content |
|---------|----------|-------------------|
| 1 | Part 1 (Doctor's Report) | Trisomy 13 karyotype diagram |
| 2 | Part 1 (Doctor's Report) | Prenatal ultrasound or medical illustration |
| 3 | Part 2 (Genetic Counselor) | Nondisjunction diagram or chromosome image |
| 4 | Part 3 (Parent's Journal) | Family-themed or hopeful image |
| 5 | Part 3 (Parent's Journal) | Children's hospital or therapy image |
| 6 | Part 4 (Community Resources) | Support group or community event |

### To replace a placeholder:
1. Create an `images/` folder in your project
2. Save your image there (e.g., `karyotype.jpg`)
3. In `index.html`, find the placeholder `<div>` and replace it with:
   ```html
   <img src="images/karyotype.jpg" alt="Trisomy 13 karyotype showing extra chromosome 13" class="blog-img">
   ```

**Image sources:** Use images from reputable medical sources, government health websites (NIH, CDC), or images licensed for educational reuse (Google Images → Tools → Usage Rights → Creative Commons).

---

## 🎨 Customizing the Design

The blog is styled with CSS variables at the top of `index.html`. You can change colors easily:

```css
:root {
  --rose: #c97b63;        /* Accent color — change this to any color */
  --cream: #fdf6ee;       /* Background color */
  --ink: #2c2416;         /* Main text color */
}
```

To change the blog name: find `Our Journey 🌿` in the `<header>` and replace it.

---

## 📋 Checklist Before Submitting

- [ ] All 4 sections are complete (Doctor, Counselor, Parent, Resources)
- [ ] Everything is written in your own words (no copy-pasting)
- [ ] At least 6 images added and displaying correctly
- [ ] Punnett square is filled in and explained
- [ ] Pedigree shows 3 generations and is explained
- [ ] All `[YOUR NAME]`, `[DATE]`, etc. placeholders replaced
- [ ] All yellow `TO FILL IN` boxes removed (delete the `<div class="todo">` lines when done)
- [ ] 5+ references on the Works Cited page, at least 1 non-website
- [ ] Site loads on GitHub Pages without errors

---

## 💡 Tips

- **Write in first person** throughout the Parent's Journal (Part 3) — this section is your personal voice.
- **Parts 1 and 2** should sound more formal/clinical (doctor and genetic counselor voices).
- **Don't copy-paste** — even paraphrasing too closely is plagiarism. Put it in your own words.
- **The pedigree and Punnett square** are worth points — make sure they're explained in writing, not just shown.
- Run your site through [validator.w3.org](https://validator.w3.org) to check for HTML errors before submitting.

---

*Good luck! — This blog template was built for the Heredity Unit Genetic Disorder Research Project.*
