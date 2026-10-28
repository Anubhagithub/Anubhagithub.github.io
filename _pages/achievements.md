---
layout: archive
title: "Achievements"
permalink: /achievements/
author_profile: true
---
<style>
.year-nav{display:flex;gap:.5rem;flex-wrap:wrap;margin-bottom:2rem}
.year-btn{padding:.4rem 1.1rem;border-radius:2rem;border:1.5px solid #ddd;background:#fff;color:#666;font-size:.85rem;font-weight:500;cursor:pointer}
.year-btn:hover,.year-btn.active{background:#2d6a9f;border-color:#2d6a9f;color:white}
.event{display:flex;gap:1rem;margin-bottom:1rem;background:#fff;border-radius:10px;padding:1rem 1.2rem;border:1px solid #eee}
.event.award{border-left:4px solid #c4922a;background:#fdf3e0}
.event.publication{border-left:4px solid #2d6a9f;background:#e8f1f9}
.event.talk{border-left:4px solid #2a7a5a;background:#e5f5ef}
.event-icon{font-size:1.3rem;flex-shrink:0}
.event-title{font-weight:500;font-size:.95rem;line-height:1.4}
.event-meta{margin-top:.3rem;font-size:.8rem;color:#888}
.tag{display:inline-block;font-size:.7rem;font-weight:500;padding:.2rem .6rem;border-radius:1rem;margin-top:.4rem;color:white}
.tag.award{background:#c4922a}
.tag.publication{background:#2d6a9f}
.tag.talk{background:#2a7a5a}
.year-label{font-size:1.6rem;font-weight:700;color:#2d6a9f;margin:1.5rem 0 1rem;padding-bottom:.5rem;border-bottom:2px solid #e8f1f9}
</style>

<div class="year-nav">
<button class="year-btn active" onclick="filterYear('all',this)">All</button>
<button class="year-btn" onclick="filterYear('2026',this)">2026</button>
<button class="year-btn" onclick="filterYear('2024',this)">2024</button>
<button class="year-btn" onclick="filterYear('2023',this)">2023</button>
<button class="year-btn" onclick="filterYear('2022',this)">2022</button>
</div>

<div class="year-section" data-year="2026">
<div class="year-label">2026</div>
<div class="event award"><div class="event-icon">🏆</div><div><div class="event-title">Young Scientist Award — Best Oral Presentation in Medical Biotechnology/Software in Medicine</div><div class="event-meta">ICoMB · Amity Noida · January 2026</div><span class="tag award">Award</span></div></div>
<div class="event talk"><div class="event-icon">🎤</div><div><div class="event-title">Invited Talk at International Conference on Medical Biotechnology (ICoMB)</div><div class="event-meta">Amity Noida · January 2026</div><span class="tag talk">Talk</span></div></div>
</div>

<div class="year-section" data-year="2024">
<div class="year-label">2024</div>
<div class="event publication"><div class="event-icon">📄</div><div><div class="event-title">MAGICAL: A multi-class classifier to predict synthetic lethal and viable interactions</div><div class="event-meta">PLOS Computational Biology · 2024</div><span class="tag publication">Publication</span></div></div>
<div class="event publication"><div class="event-icon">📄</div><div><div class="event-title">CaTCH: Calculating transcript complexity of human genes</div><div class="event-meta">MethodsX · 2024</div><span class="tag publication">Publication</span></div></div>
<div class="event publication"><div class="event-icon">📄</div><div><div class="event-title">Deubiquitinases as prognostic biomarkers and potential drug targets for gynecological cancers</div><div class="event-meta">International Journal of Clinical Oncology · 2024</div><span class="tag publication">Publication</span></div></div>
<div class="event publication"><div class="event-icon">📄</div><div><div class="event-title">CHOLAR: Characterization of LncRNA from raw reads</div><div class="event-meta">F1000Research · 2024</div><span class="tag publication">Publication</span></div></div>
<div class="event talk"><div class="event-icon">🎤</div><div><div class="event-title">Selected for Talk at HySci — IIT Hyderabad</div><div class="event-meta">IIT Hyderabad · April 2024</div><span class="tag talk">Talk</span></div></div>
<div class="event award"><div class="event-icon">🏆</div><div><div class="event-title">Best Oral Presentation Award at BioAnveshna — Felicitated by Nobel Laureate Sir Richard J. Roberts</div><div class="event-meta">University of Hyderabad · February 2024</div><span class="tag award">Award</span></div></div>
</div>

<div class="year-section" data-year="2023">
<div class="year-label">2023</div>
<div class="event publication"><div class="event-icon">📄</div><div><div class="event-title">Chromatin loop dynamics during cellular differentiation</div><div class="event-meta">Genome Research · 2023</div><span class="tag publication">Publication</span></div></div>
<div class="event publication"><div class="event-icon">📄</div><div><div class="event-title">Inefficient splicing of long non-coding RNAs is associated with higher transcript complexity</div><div class="event-meta">RNA Biology · 20(1), 563–572 · 2023</div><span class="tag publication">Publication</span></div></div>
<div class="event talk"><div class="event-icon">🎤</div><div><div class="event-title">Lightning Talk at 4th Indian Cancer Genome Atlas (ICGA) Conference</div><div class="event-meta">IISER Pune · 2023</div><span class="tag talk">Talk</span></div></div>
</div>

<div class="year-section" data-year="2022">
<div class="year-label">2022</div>
<div class="event award"><div class="event-icon">🏆</div><div><div class="event-title">Best Poster Presentation Award at 16th International Cancer Symposium</div><div class="event-meta">Jawaharlal Nehru University · November 2022</div><span class="tag award">Award</span></div></div>
</div>

<script>
function filterYear(year,btn){
document.querySelectorAll('.year-btn').forEach(b=>b.classList.remove('active'));
btn.classList.add('active');
document.querySelectorAll('.year-section').forEach(s=>{
s.style.display=(year==='all'||s.dataset.year===year)?'block':'none';
});
}
</script>
