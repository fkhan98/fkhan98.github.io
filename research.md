---
layout: page
title: "Research"
permalink: /research/
lede: "My research uses database systems to make machine learning over massive relational data more efficient and scalable."
---

<div class="project">
  <div class="project-head">
    <h3>ContextDB: Database-Native Prediction Maintenance for Relational AI</h3>
    <span class="tag">Ongoing</span>
  </div>
  <ul>
    <li>Defining a new class of relational queries that repeatedly predict a fixed future outcome as we move forward in time.</li>
    <li>Formulating incremental maintenance of relational foundation model (RFM) predictions for these queries as the database evolves.</li>
    <li>Developing database-native algorithms that recompute only the predictions affected by changes to the database, keeping or even improving results compared to full recomputation at a fraction of the cost.</li>
  </ul>
</div>

<div class="project">
  <div class="project-head">
    <h3>MetaSieve: SQL-Based Metapath Selection for Relational Deep Learning</h3>
    <span class="tag tag-accent">VLDB 2027</span>
  </div>
  <ul>
    <li>A model-independent metapath selection layer for relational deep learning (RDL) that uses efficient SQL joins and aggregations to identify and prune uninformative relational paths before Graph Neural Network (GNN) training.</li>
    <li>A lightweight, cost-aware scoring method based on database statistics and mutual information that reduces subgraph sampling overhead without sacrificing predictive accuracy.</li>
    <li>Up to <strong>10&times; faster per-epoch training</strong> on <a href="https://star-project.stanford.edu/relbench/">RelBench</a> while maintaining or improving accuracy, evaluated across 15 prediction tasks, 5 relational databases and 3 GNN architectures on HPC infrastructure.</li>
  </ul>
  <p class="links"><a href="https://arxiv.org/abs/2608.25903">arXiv</a><a href="https://github.com/lids-lab/metasieve">Code</a></p>
</div>

<div class="project">
  <div class="project-head">
    <h3>A Vision for SQL-Based Relational Deep Learning</h3>
    <span class="tag">VLDB TaDA 2025</span>
  </div>
  <ul>
    <li>Proposes using the expressive power and execution efficiency of SQL to push relational deep learning operations into the DBMS, establishing a database-centric direction for scalable relational AI.</li>
  </ul>
  <p class="links"><a href="https://vldb.org/2025/Workshops/VLDB-Workshops-2025/TaDA/TaDA25_3.pdf">PDF</a></p>
</div>

<h2>Talks</h2>
<ul class="news">
  <li><time>Sep 2025</time><span>&ldquo;A Vision for SQL-Based Relational Deep Learning,&rdquo; VLDB 2025 <a href="https://tabular-data-analysis.github.io/tada2025/">TaDA Workshop</a>, London, United Kingdom.</span></li>
</ul>
