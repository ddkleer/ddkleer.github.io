---
layout: page
title: "Student Resources"
---

<!-- ========= Scoped styles (won't mess with rest of site) ========= -->
<style>
  .res-wrap { --gap: 1rem; --radius: 14px; --pad: 1rem; }
  .res-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: var(--gap);
    margin: 1rem 0 2rem;
  }
  .res-card {
    border: 1px solid rgba(0,0,0,.08);
    border-radius: var(--radius);
    padding: var(--pad);
    box-shadow: 0 4px 14px rgba(0,0,0,.04);
    background: var(--card-bg, #fff);
    transition: transform .08s ease, box-shadow .2s ease;
  }
  .res-card:hover { transform: translateY(-2px); box-shadow: 0 10px 24px rgba(0,0,0,.08); }
  .res-card h3 { margin-top: .2rem; font-size: 1.05rem; }
  .res-card p { margin: .4rem 0 .6rem; font-size: .95rem; }
  .res-actions a {
    display: inline-block; margin-right: .5rem; margin-top: .25rem;
    padding: .45rem .7rem; border-radius: 999px; font-size: .9rem;
    text-decoration: none; border: 1px solid rgba(0,0,0,.12);
  }
  .btn { background: #111; color: #fff; border-color: #111; }
  .btn:hover { filter: brightness(1.05); }
  .chip { background: #f6f6f6; }
  .section-title { margin: 2.2rem 0 0.6rem; font-size: 1.25rem; }
  .muted { color: #666; font-size: .95rem; }
  .two-col {
    display: grid; gap: var(--gap);
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    margin: .5rem 0 1.5rem;
  }
  .list-clean { margin: .3rem 0 0; padding-left: 1.2rem; }
  .list-clean li { margin: .25rem 0; }
  .note {
    border-left: 4px solid #111; padding: .8rem 1rem; background: #fafafa;
    border-radius: 10px; margin: 1rem 0 1.4rem;
  }
</style>

<div class="res-wrap">

## 📚 Quick Links

<div class="res-grid">
  <div class="res-card">
    <h3>📄 Syllabus</h3>
    <p class="muted">Current course outline, policies, deadlines.</p>
    <div class="res-actions">
      <a class="btn" href="https://example.com/syllabus.pdf">Open PDF</a>
      <a class="chip" href="https://example.com/syllabus.docx">Download .docx</a>
    </div>
  </div>

  <div class="res-card">
    <h3>🗓️ Office Hours</h3>
    <p class="muted">Times, room/Zoom link, and booking.</p>
    <div class="res-actions">
      <a class="btn" href="https://example.com/booking">Book a slot</a>
      <a class="chip" href="mailto:you@example.com?subject=Office%20hours">Email me</a>
    </div>
  </div>

  <div class="res-card">
    <h3>🧰 Methods Toolkit</h3>
    <p class="muted">R starter, reproducible projects, templates.</p>
    <div class="res-actions">
      <a class="btn" href="https://example.com/r-starter">R Starter</a>
      <a class="chip" href="https://example.com/project-template.zip">Project template</a>
    </div>
  </div>

  <div class="res-card">
    <h3>🔎 Research & Writing</h3>
    <p class="muted">Citation, lit reviews, argument structure.</p>
    <div class="res-actions">
      <a class="btn" href="https://example.com/citation-guide">Citation guide</a>
      <a class="chip" href="https://example.com/lit-review-checklist.pdf">Checklist</a>
    </div>
  </div>
</div>

---

### 🧭 Course Resources (by week/topic)

<div class="two-col">
  <div class="res-card">
    <h3>Week 1 — Foundations</h3>
    <ul class="list-clean">
      <li><a href="https://example.com/slides-w1.pdf">Slides</a></li>
      <li><a href="https://example.com/readings-w1.pdf">Readings</a></li>
      <li><a href="https://example.com/lab-w1.html">Lab notebook</a></li>
    </ul>
  </div>

  <div class="res-card">
    <h3>Week 2 — Measurement</h3>
    <ul class="list-clean">
      <li><a href="https://example.com/slides-w2.pdf">Slides</a></li>
      <li><a href="https://example.com/readings-w2.pdf">Readings</a></li>
      <li><a href="https://example.com/lab-w2.html">Lab notebook</a></li>
    </ul>
  </div>

  <div class="res-card">
    <h3>Week 3 — Causality</h3>
    <ul class="list-clean">
      <li><a href="https://example.com/slides-w3.pdf">Slides</a></li>
      <li><a href="https://example.com/readings-w3.pdf">Readings</a></li>
      <li><a href="https://example.com/lab-w3.html">Lab notebook</a></li>
    </ul>
  </div>

  <div class="res-card">
    <h3>Week 4 — Measurement Error</h3>
    <ul class="list-clean">
      <li><a href="https://example.com/slides-w4.pdf">Slides</a></li>
      <li><a href="https://example.com/readings-w4.pdf">Readings</a></li>
      <li><a href="https://example.com/lab-w4.html">Lab notebook</a></li>
    </ul>
  </div>
</div>

> Want a single PDF bundle? <a href="https://example.com/course-pack.pdf"><strong>Download the Course Pack</strong></a>.

---

### 🧪 Data & Code

<div class="res-grid">
  <div class="res-card">
    <h3>📦 Datasets</h3>
    <p class="muted">Clean copies used in assignments.</p>
    <div class="res-actions">
      <a class="btn" href="https://example.com/data.zip">Download .zip</a>
      <a class="chip" href="https://example.com/data-readme.html">Data README</a>
    </div>
  </div>

  <div class="res-card">
    <h3>🧾 R Templates</h3>
    <p class="muted">RMarkdown + project structure.</p>
    <div class="res-actions">
      <a class="btn" href="https://example.com/rmarkdown-template.Rmd">Rmd template</a>
      <a class="chip" href="https://example.com/renv-lock.json">renv lock</a>
    </div>
  </div>

  <div class="res-card">
    <h3>🧪 Repro Tips</h3>
    <p class="muted">How to keep your analysis tidy & reproducible.</p>
    <div class="res-actions">
      <a class="btn" href="https://example.com/repro-notes.html">Guide</a>
      <a class="chip" href="https://example.com/git-cheatsheet.pdf">Git cheat-sheet</a>
    </div>
  </div>
</div>

<div class="note">
  <strong>Pro tip:</strong> if you can’t find a file, check the file names used in your scripts and keep everything in a single project folder. Relative paths > copy-pasting files everywhere.
</div>

---

### 📝 Assignments & Submission

<div class="two-col">
  <div class="res-card">
    <h3>Deadlines & Rubrics</h3>
    <ul class="list-clean">
      <li><a href="https://example.com/assignment-1.pdf">Assignment 1</a> — due Sep 23</li>
      <li><a href="https://example.com/assignment-2.pdf">Assignment 2</a> — due Oct 7</li>
      <li><a href="https://example.com/assignment-3.pdf">Assignment 3</a> — due Oct 28</li>
      <li><a href="https://example.com/rubric.pdf">Grading rubric</a></li>
    </ul>
  </div>
  <div class="res-card">
    <h3>Submit Work</h3>
    <p class="muted">Follow file naming rules; PDF unless told otherwise.</p>
    <div class="res-actions">
      <a class="btn" href="https://example.com/submission-portal">Submission portal</a>
      <a class="chip" href="mailto:you@example.com?subject=Submission%20question">Questions?</a>
    </div>
  </div>
</div>

---

### 💡 Study Aids

- 📚 <a href="https://example.com/reading-list.pdf">Reading list</a>  
- 🧠 <a href="https://example.com/concepts-cheatsheet.pdf">Key concepts cheat-sheet</a>  
- 🎯 <a href="https://example.com/exam-practice.pdf">Practice questions</a>  
- 🗂️ <a href="https://example.com/bibliography.bib">Sample BibTeX</a>  

<hr/>

<p class="muted">Last updated: {{ site.time | date: "%B %d, %Y" }} • Found a broken link? <a href="mailto:you@example.com?subject=Broken%20link%20on%20resources">Tell me</a>.</p>

</div>
