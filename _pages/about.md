---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* Keep the topic colors; use spacing and typography for hierarchy. */
.profile-home {
  --fairness: #00695C;
  --transportation: #1565C0;
  --energy: #2E7D32;
  --pricing: #6A1B9A;
  --optimization: #EF6C00;
  --ml: #C62828;
  line-height: 1.65;
}
.profile-home .text-fairness { color: var(--fairness); }
.profile-home .text-transportation { color: var(--transportation); }
.profile-home .text-energy { color: var(--energy); }
.profile-home .text-pricing { color: var(--pricing); }
.profile-home .text-optimization { color: var(--optimization); }
.profile-home .text-ml { color: var(--ml); }
.profile-home .research-intro { margin: 1.6em 0; }
.profile-home .research-lead {
  margin: 0 0 .45em;
  font-size: 1.12em;
  font-weight: 650;
  line-height: 1.5;
}
.profile-home .research-description { margin: 0; }
.profile-home .research-description span { font-weight: 500; }
.profile-home .job-market { margin: 1.4em 0 0; font-style: italic; }
.profile-home .section-title {
  margin: 2em 0 .85em;
  padding-bottom: .3em;
  border-bottom: 1px solid #d9dfe3;
  font-size: 1.5em;
  font-weight: 650;
  line-height: 1.3;
}
.profile-home .subsection-title {
  margin: 1.6em 0 1.1em;
  font-size: 1.05em;
  font-weight: 650;
}
.profile-home .author-note {
  margin: -.65em 0 1.5em;
  color: #687078;
  font-size: .78em;
  font-style: italic;
}
.profile-home .paper { margin-bottom: 1.8em; }
.profile-home .paper-title {
  margin: 0 0 .22em;
  padding: 0;
  border: 0;
  font-size: 1em;
  font-weight: 650;
  line-height: 1.45;
}
.profile-home .paper-title .code-link {
  margin-left: .45em;
  font-size: .8em;
  font-weight: 400;
  white-space: nowrap;
}
.profile-home .paper-authors,
.profile-home .paper-venue,
.profile-home .paper-status {
  margin: .12em 0;
  font-size: .9em;
  line-height: 1.5;
}
.profile-home .paper-venue { font-style: italic; }
.profile-home .paper-status { color: #687078; font-style: italic; }
.profile-home .paper-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 4px;
  margin-top: .55em;
}
.profile-home .tag {
  display: inline-block;
  padding: 2px 6px;
  border-radius: 3px;
  font-size: .68em;
  font-weight: 600;
  line-height: 1.35;
}
.profile-home .tag-fairness { background: #E0F2F1; color: var(--fairness); }
.profile-home .tag-transportation { background: #E3F2FD; color: var(--transportation); }
.profile-home .tag-energy { background: #E8F5E9; color: var(--energy); }
.profile-home .tag-pricing { background: #F3E5F5; color: var(--pricing); }
.profile-home .tag-optimization { background: #FFF3E0; color: var(--optimization); }
.profile-home .tag-ml { background: #FFEBEE; color: var(--ml); }
.profile-home .paper-awards {
  list-style: none;
  padding: 0;
  margin: .65em 0 0;
  color: var(--transportation);
  font-size: .8em;
  line-height: 1.5;
}
.profile-home .paper-awards li {
  display: flex;
  align-items: flex-start;
  gap: .45em;
  margin: .3em 0;
}
.profile-home .paper-awards .trophy { flex-shrink: 0; }
.profile-home .detail-list { padding-left: 1.15em; }
.profile-home .detail-list li { margin-bottom: .65em; }
.profile-home .detail-list .detail { color: #687078; font-size: .9em; }
.profile-home .detail-list span[class^="text-"] { font-weight: inherit; }
@media (max-width: 600px) {
  .profile-home .paper { margin-bottom: 1.6em; }
  .profile-home .paper-title { line-height: 1.55; }
  .profile-home .section-title { margin-top: 1.7em; }
}
</style>

<div class="profile-home">

<p>Hi! I am a final-year Ph.D. student in the Department of <a href="https://ieor.columbia.edu/">Industrial Engineering and Operations Research</a> at Columbia University, and I am fortunate to be advised by Prof. <a href="https://www.columbia.edu/~ae2516/">Adam Elmachtoub</a>.</p>

<div class="research-intro">
  <p class="research-lead">My research centers around <span class="text-fairness">socially responsible</span> operations.</p>
  <p class="research-description">More specifically, my work focuses on designing <span class="text-fairness">fairness-aware</span> systems via <span class="text-pricing">pricing</span>, with applications in <span class="text-transportation">transportation</span> and <span class="text-energy">energy</span>, using <span class="text-optimization">optimization</span> and <span class="text-ml">machine learning</span>.</p>
</div>

<p>I received my MS degree in Industrial and Systems Engineering from Korea Advanced Institute of Science and Technology (KAIST), where I was advised by Prof. <a href="https://aai.kaist.ac.kr/bbs/board.php?bo_table=sub2_1&amp;wr_id=3">Il-Chul Moon</a>. Prior to that, I received my BS degree in Industrial and Systems Engineering and Electrical Engineering from KAIST.</p>

<p class="job-market">I am excited to be on the 2026–2027 academic job market!</p>

<h2 class="section-title">Research</h2>
<p class="author-note">(*) Equal contribution. (α-β) Alphabetical order.</p>

<h3 class="subsection-title">Conference &amp; Journal Papers</h3>

<article class="paper">
  <h4 class="paper-title"><a href="https://arxiv.org/abs/2604.03559">Fair Aggregation in Virtual Power Plants</a> <a class="code-link" href="https://github.com/HyemiK1m/Fair_Aggregation_in_VPPs">[code]</a></h4>
  <p class="paper-authors">Liudong Chen*, <strong>Hyemi Kim</strong>*, Adam N. Elmachtoub, and Bolun Xu</p>
  <p class="paper-venue">The 9th ACM Conference on Fairness, Accountability, and Transparency (FAccT), 2026</p>
  <div class="paper-tags"><span class="tag tag-fairness">Fairness</span><span class="tag tag-energy">Energy</span><span class="tag tag-pricing">Pricing</span><span class="tag tag-optimization">Optimization</span></div>
</article>

<article class="paper">
  <h4 class="paper-title"><a href="https://arxiv.org/abs/2606.06830">Learning Fair Demand Models</a> <a class="code-link" href="https://github.com/HyemiK1m/Learning_Fair_Demand_Models">[code]</a></h4>
  <p class="paper-authors">Adam N. Elmachtoub, <strong>Hyemi Kim</strong>, and Jonathan Y. Tan (α-β)</p>
  <p class="paper-venue">The 9th ACM Conference on Fairness, Accountability, and Transparency (FAccT), 2026</p>
  <p class="paper-status">Major Revision at Operations Research</p>
  <div class="paper-tags"><span class="tag tag-fairness">Fairness</span><span class="tag tag-pricing">Pricing</span><span class="tag tag-ml">Machine Learning</span><span class="tag tag-optimization">Optimization</span></div>
</article>

<article class="paper">
  <h4 class="paper-title"><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4699813">Fair Fares for Vehicle Sharing Systems</a> <a class="code-link" href="https://github.com/HyemiK1m/Fair_Fares">[code]</a></h4>
  <p class="paper-authors">Adam N. Elmachtoub and <strong>Hyemi Kim</strong> (α-β)</p>
  <p class="paper-venue">Operations Research, 2026</p>
  <p class="paper-venue">The 8th ACM Conference on Fairness, Accountability, and Transparency (FAccT), 2025</p>
  <div class="paper-tags"><span class="tag tag-fairness">Fairness</span><span class="tag tag-transportation">Transportation</span><span class="tag tag-pricing">Pricing</span><span class="tag tag-optimization">Optimization</span></div>
  <ul class="paper-awards">
    <li><span class="trophy" aria-hidden="true">🏆</span><span>Finalist, INFORMS DEI Best Student Paper Award, 2024</span></li>
    <li><span class="trophy" aria-hidden="true">🏆</span><span>Finalist, INFORMS Transportation Science and Logistics Society Best Student Paper Award, 2024</span></li>
  </ul>
</article>

<article class="paper">
  <h4 class="paper-title"><a href="https://cdn.aaai.org/ojs/16990/16990-13-20484-1-2-20210518.pdf">Counterfactual Fairness with Disentangled Causal Effect Variational Autoencoder</a> <a class="code-link" href="https://github.com/HyemiK1m/DCEVAE">[code]</a></h4>
  <p class="paper-authors"><strong>Hyemi Kim</strong>, Seungjae Shin, JoonHo Jang, Kyungwoo Song, Weonyoung Joo, Wanmo Kang, Il-Chul Moon</p>
  <p class="paper-venue">Association for the Advancement of Artificial Intelligence (AAAI), 2021</p>
  <div class="paper-tags"><span class="tag tag-fairness">Fairness</span><span class="tag tag-ml">Machine Learning</span></div>
</article>

<article class="paper">
  <h4 class="paper-title"><a href="https://arc.aiaa.org/doi/10.2514/1.I010831">Black-Box EM Algorithm for Estimating Latent States of High-Speed Vehicles</a></h4>
  <p class="paper-authors">Yoon-Yeong Kim, <strong>Hyemi Kim</strong>, WonSung Lee, Han-Lim Choi, Il-Chul Moon</p>
  <p class="paper-venue">American Institute of Aeronautics and Astronautics, 2021</p>
  <div class="paper-tags"><span class="tag tag-ml">Machine Learning</span></div>
</article>

<article class="paper">
  <h4 class="paper-title"><a href="https://aclanthology.org/2020.findings-emnlp.280.pdf">Neutralizing Gender Bias in Word Embedding with Latent Disentanglement and Counterfactual Generation</a></h4>
  <p class="paper-authors">Seungjae Shin, Kyungwoo Song, Joonho Jang, <strong>Hyemi Kim</strong>, Weonyoung Joo, Il-Chul Moon</p>
  <p class="paper-venue">Findings of Empirical Methods in Natural Language Processing (EMNLP), 2020</p>
  <div class="paper-tags"><span class="tag tag-fairness">Fairness</span><span class="tag tag-ml">Machine Learning</span></div>
</article>

<article class="paper">
  <h4 class="paper-title"><a href="https://dl.acm.org/doi/10.1145/3340531.3411971">Deep Generative Positive-Unlabeled Learning under Selection Bias</a></h4>
  <p class="paper-authors">ByeongHu Na, <strong>Hyemi Kim</strong>, Kyungwoo Song, Weonyoung Joo, Yoonyeong Kim, Il-Chul Moon</p>
  <p class="paper-venue">Conference on Information and Knowledge Management (CIKM), 2020</p>
  <div class="paper-tags"><span class="tag tag-ml">Machine Learning</span></div>
</article>

<h3 class="subsection-title">Workshop Paper</h3>

<article class="paper">
  <h4 class="paper-title"><a href="https://openreview.net/pdf?id=okCTFCRavwh">Improving Group-based Robustness and Calibration via Ordered Risk and Confidence Regularization</a></h4>
  <p class="paper-authors">Seungjae Shin, Byeonghu Na, HeeSun Bae, JoonHo Jang, <strong>Hyemi Kim</strong>, Kyungwoo Song, Youngjae Cho, Il-chul Moon</p>
  <p class="paper-venue">ICML 2022: Workshop on Spurious Correlations, Invariance and Stability</p>
  <div class="paper-tags"><span class="tag tag-ml">Machine Learning</span></div>
</article>

<h2 class="section-title">Teaching</h2>
<ul class="detail-list">
  <li><strong>Introduction to Probability and Statistics</strong><br><span class="detail">Columbia IEOR · Fall 2024</span></li>
  <li><strong>Stochastic Models</strong><br><span class="detail">Columbia IEOR · Spring 2024</span></li>
  <li><strong>Analytics in Action</strong><br><span class="detail">Columbia Business School · Fall 2023</span></li>
  <li><strong><span class="text-transportation">Transportation</span> Analytics &amp; Logistics</strong><br><span class="detail">Columbia IEOR · Spring 2023</span></li>
  <li><strong>Data Structure</strong><br><span class="detail">KAIST ISysE · Fall 2018, Fall 2019</span></li>
</ul>

<h2 class="section-title">Fellowships &amp; Awards</h2>
<ul class="detail-list">
  <li><strong>Columbia-Dream Sports <span class="text-ml">AI</span> Innovation Fellowship</strong><br><span class="detail">Columbia University · 2025</span></li>
  <li><strong>Finalist, INFORMS <span class="text-fairness">DEI</span> Best Student Paper Award</strong><br><span class="detail">2024</span></li>
  <li><strong>Finalist, INFORMS <span class="text-transportation">Transportation</span> Science and Logistics Best Student Paper Award</strong><br><span class="detail">2024</span></li>
  <li><strong>Finalist, INFORMS 2023 BSS Data Challenge Competition</strong><br><span class="detail">2023 · Decoupling <span class="text-pricing">Price</span> and Demand Estimation for Profit Optimization</span></li>
  <li><strong>Deming Doctoral Fellowship</strong><br><span class="detail">Columbia Business School · 2023</span></li>
  <li><strong>Songhyun Award</strong><br><span class="detail">KAIST · 2019</span></li>
  <li><strong>Presidential Science Scholarship</strong><br><span class="detail">KFAS · 2012</span></li>
</ul>

</div>
