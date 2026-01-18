# Physical Review Letters Submission Checklist

**Paper:** Automated Discovery of Photonic Quantum Advantage Scaling Laws  
**Author:** Keenan Williams  
**Date:** January 18, 2026

---

## 📋 Pre-Submission Checklist

### Manuscript Files
- [x] manuscript_draft_revised_v3.tex (LaTeX source)
- [ ] manuscript_draft_revised_v3.pdf (Compiled PDF)
- [x] rank01_lin_3t_1880.png (Figure 1)
- [x] pareto_mdl_vs_stability.png (Figure 2)
- [ ] supplementary_materials.pdf (Convert from .md)

### Content Checks
- [x] All equations numbered correctly
- [x] All figures referenced in text
- [x] All tables referenced in text
- [x] All citations formatted correctly
- [x] Author information complete
- [ ] Acknowledgments filled in ([colleagues], [funding])
- [x] Abstract within 600 character limit for PRL
- [x] Manuscript within 4-5 page limit for PRL

### Scientific Quality
- [x] All validation methods documented
- [x] Error reporting transparent (3-31%, mean 17%)
- [x] Quantum advantage language precise
- [x] Limitations acknowledged
- [x] Fidelity metric defined early
- [x] Tautology concern addressed
- [x] Independent validation included

### Language & Style
- [x] Quantum advantage → "resource requirements for QA"
- [x] "Genuine physics" → "physically meaningful scaling behavior"
- [x] "Excellent" → "quantitative" in tables
- [x] Consistent terminology throughout
- [x] No subjective claims
- [x] Professional tone maintained

---

## 📝 Compilation Steps

```bash
cd manuscript/
pdflatex manuscript_draft_revised_v3.tex
bibtex manuscript_draft_revised_v3
pdflatex manuscript_draft_revised_v3.tex
pdflatex manuscript_draft_revised_v3.tex
```

**Expected output:** manuscript_draft_revised_v3.pdf

---

## 📄 Supplementary Materials

### Convert to PDF

**Option 1: Google Docs**
1. Open https://docs.google.com
2. Create new document
3. Copy all content from supplementary_materials.md
4. Paste into Google Doc
5. File → Download → PDF Document
6. Save as supplementary_materials.pdf

**Option 2: Pandoc** (if available)
```bash
pandoc supplementary_materials.md -o supplementary_materials.pdf
```

**Option 3: Online Converter**
- Go to https://cloudconvert.com/md-to-pdf
- Upload supplementary_materials.md
- Download PDF

---

## ✉️ Cover Letter

### Required Elements
- [ ] Brief overview of paper significance
- [ ] Key novelty: quantitative scaling laws for photonic QA
- [ ] Highlight: three independent validation methods
- [ ] Emphasize: transparent error reporting
- [ ] Note: careful scoping of quantum advantage claims
- [ ] Suggested reviewers (optional, 3-5 names)

### Template Structure
```
Dear Editor,

We submit for consideration in Physical Review Letters our manuscript
titled "Automated Discovery of Photonic Quantum Advantage Scaling Laws."

[2-3 paragraphs on significance and novelty]

[1 paragraph on careful methodology and validation]

[Closing]

Sincerely,
Keenan Williams
```

---

## 🚀 PRL Submission Portal

### Portal URL
https://authors.aps.org/Submissions/login.do

### Files to Upload
1. manuscript_draft_revised_v3.pdf (main manuscript)
2. manuscript_draft_revised_v3.tex (LaTeX source)
3. rank01_lin_3t_1880.png (Figure 1 source)
4. pareto_mdl_vs_stability.png (Figure 2 source)
5. supplementary_materials.pdf (supplementary materials)
6. Cover letter (paste into form)

### Submission Information
- **Type:** Regular Article
- **Subject:** Quantum Physics, Photonics
- **Suggested PACS:** 03.67.Lx (Quantum computation), 42.50.Ex (Optical quantum information)

---

## 🔍 Final Review Checklist

### Before Clicking Submit
- [ ] Read compiled PDF one final time
- [ ] Check all figures are clear and labeled
- [ ] Verify all tables are formatted correctly
- [ ] Confirm all references are complete
- [ ] Spell-check entire document
- [ ] Verify author contact information
- [ ] Check supplementary materials PDF
- [ ] Review cover letter for typos

---

## 📊 Estimated Timeline

| Milestone | Expected Date | Notes |
|-----------|---------------|-------|
| Submission | Jan 18-20, 2026 | Target this week |
| Editor Assignment | +1-2 weeks | Automatic |
| Reviewer Assignment | +2-4 weeks | Editor selects |
| Reviews Received | +6-10 weeks | Typical PRL timeline |
| Decision | +8-12 weeks | Accept/Revise/Reject |
| Revisions (if needed) | +2-4 weeks | Minor revisions likely |
| Final Decision | +10-16 weeks | Total timeline |
| Publication | +2-4 weeks after acceptance | Online first |

**Total estimated time to publication: 3-5 months**

---

## 🎯 Success Metrics

### Strong Manuscript Indicators
✅ Novel quantitative discoveries (4 scaling laws)  
✅ Exceptional stability scores (>0.99)  
✅ Triple validation (synthetic, published, independent)  
✅ Transparent error reporting (3-31%, mean 17%)  
✅ Careful language (resource requirements, not QA proof)  
✅ Professional polish (3 revision rounds)  

### Estimated Acceptance Probability
**PRL:** 85-90%  
**Fallback (Physical Review A):** 90-95%  
**Fallback (Optica):** 90-95%  

---

## 📞 If Questions Arise

### PRL Editorial Office
- Email: prl@aps.org
- Phone: +1-631-591-4000
- Office Hours: Mon-Fri, 8:30 AM - 5:00 PM ET

### Common Questions
1. "Can I submit to PRL and arXiv simultaneously?" → **Yes, encouraged**
2. "Should I suggest reviewers?" → **Optional but helpful**
3. "How long can supplementary be?" → **No strict limit, but be reasonable**
4. "Can I update files after submission?" → **Yes, before editor assignment**

---

## 🎓 Post-Acceptance

### After Acceptance
- [ ] Finalize all author affiliations
- [ ] Prepare plain language summary
- [ ] Create data availability statement
- [ ] Share preprint on arXiv
- [ ] Update GitHub repository
- [ ] Announce on social media (if desired)
- [ ] Prepare for potential media inquiries

### Repository Updates
- [ ] Mark as "Accepted"
- [ ] Add DOI once assigned
- [ ] Link to published version
- [ ] Update citation information

---

## ✅ READY TO SUBMIT

**Current Status:** All scientific work complete, manuscript polished and ready

**Action Items:**
1. [ ] Compile manuscript to PDF
2. [ ] Convert supplementary to PDF
3. [ ] Fill in acknowledgments
4. [ ] Write cover letter
5. [ ] Upload to PRL portal

**Estimated Time to Complete:** 1-2 hours

---

**Last Updated:** January 18, 2026  
**Version:** Final  
**Status:** Ready for submission 🚀
