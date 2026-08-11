<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0f1b2d,100:1a2744&height=200&section=header&text=Raja%20Rathour&fontSize=52&fontColor=58a6ff&fontAlignY=55&desc=ML%20Systems%20%C2%B7%20GPU%20Inference%20%C2%B7%20Open%20Source&descSize=18&descAlignY=75&descColor=8b949e&animation=fadeIn" width="100%"/>

<a href="https://www.linkedin.com/in/raja-rathour/">
  <img src="https://img.shields.io/badge/LinkedIn-Raja_Rathour-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:imraja729@gmail.com">
  <img src="https://img.shields.io/badge/Email-imraja729@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://raja-portfolio-ebon.vercel.app">
  <img src="https://img.shields.io/badge/Portfolio-Visit_Site-111827?style=flat-square&logo=vercel&logoColor=white"/>
</a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=Raja-89&style=flat-square&color=58a6ff&label=Profile+Views"/>

<br/><br/>

<img src="https://img.shields.io/badge/GSoC_2026-FFmpeg-4285F4?style=flat-square&logo=google&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/7_PRs-Merged_to_FFmpeg_master-2ea44f?style=flat-square&logo=git&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Commits-GPG_Signed-8957e5?style=flat-square&logo=gnuprivacyguard&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/DCO-Compliant-0078D4?style=flat-square&logo=git&logoColor=white"/>

</div>

<br/>

---

## Who I am

I'm a **Google Summer of Code 2026 contributor** working inside FFmpeg's C++ codebase and a 3rd-year B.Tech student at DTU (Mathematics & Computing). I build ML systems where latency, memory efficiency, and production correctness matter as much as model accuracy.

Right now I'm modernizing FFmpeg's neural network inference pipeline — replacing slow host-to-device memory transfers with a zero-copy CUDA pipeline, and building a dynamic batching engine for the LibTorch backend. I've merged **7 pull requests** into FFmpeg's master branch across the project.

Every commit I push is **GPG-signed** and **DCO-compliant**. This isn't optional hygiene — it's how I've worked since day one, because FFmpeg enforces it.

**Hackathon record:** Won Brainwave 2.0 MLH (200+ competitors) · Top 1% Smart India Hackathon 2025 (1,000+ participants)

> Open to **ML infrastructure**, **computer vision**, and **applied AI** internships for 2026–27.

---

## Currently Shipping

<table>
  <tr>
    <td valign="top" width="100%">
      <h3>🚀 Google Summer of Code 2026 — FFmpeg DNN Backend</h3>
      <p>
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
        <img src="https://img.shields.io/badge/LibTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white"/>
      </p>
      <p>
        Modernizing FFmpeg's ML inference pipeline inside the <code>libavfilter</code> C++ layer.
        Replacing slow host-to-device memory copies with a <strong>zero-copy CUDA pipeline</strong>
        using pinned-memory pools — targeting <strong>30% reduction</strong> in data transfer
        overhead on NVIDIA T4 benchmarks.
      </p>
      <p>
        Also shipping a <strong>dynamic batch processing engine</strong> with asynchronous queuing,
        resolving multi-threading race conditions in the LibTorch inference path. Authored the
        <strong>first automated regression test suite</strong> for FFmpeg's neural network backends.
      </p>
      <p>
        <strong>7 pull requests merged to FFmpeg/FFmpeg master</strong> — surviving multi-round
        review in a 500K+ LOC production codebase.
      </p>
      <a href="https://github.com/Raja-89">View patches on GitHub →</a>
    </td>
  </tr>
</table>

---

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ Interceptor — Agentic Deepfake Detection</h3>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/LangGraph-111827?style=flat-square&logo=langchain&logoColor=white"/>
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
      <p>
        Won <strong>Brainwave 2.0 MLH Hackathon</strong> (Jan. 2026, 200+ competitors).
      </p>
      <p>
        A <strong>deterministic agentic router</strong> that dispatches video across 5 specialist
        detectors (compression, lighting, audio-visual, resolution, temporal) based on file
        characteristics — guaranteeing forensic-grade reproducibility with verdicts under
        <strong>3 seconds</strong>.
      </p>
      <p>
        Distilled ResNet-50 → <strong>EfficientNet-B0</strong> via knowledge distillation.
        <strong>95.2% AUC-ROC</strong> on DFDC · <strong>3× lower</strong> inference cost.
        Grad-CAM explainability layer with audit-trail logging for law enforcement use.
      </p>
      <a href="https://github.com/Raja-89/interceptor-4x4">View on GitHub →</a>
      &nbsp;|&nbsp;
      <a href="https://interceptor-4x4.vercel.app/">Live Demo →</a>
    </td>
    <td width="50%" valign="top">
      <h3>🧬 Taxaformer — Marine eDNA Taxonomy</h3>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/Nucleotide_Transformer-FFB300?style=flat-square&logo=huggingface&logoColor=black"/>
        <img src="https://img.shields.io/badge/FAISS-009688?style=flat-square&logoColor=white"/>
      </p>
      <p>
        <strong>Top 1% at Smart India Hackathon 2025</strong> (1,000+ participants, Grand Finals).
      </p>
      <p>
        Fine-tuned the <strong>Nucleotide Transformer</strong> genomic foundation model on marine
        eDNA sequences. <strong>87% cluster alignment</strong> with NCBI taxonomy ground truth.
        Automated novelty detection flags potentially undiscovered species.
      </p>
      <p>
        Processes <strong>1.2M+ DNA sequences</strong> from 47 global sampling locations against
        PR2 + SILVA reference databases. FAISS HNSW indexing cut retrieval latency
        <strong>30%</strong> and GPU memory <strong>25%</strong> within a 16 GB VRAM budget.
      </p>
      <a href="https://github.com/Raja-89/OceanEYE-s-TaxaFormer">View on GitHub →</a>
      &nbsp;|&nbsp;
      <a href="https://oceaneye-taxaformer.vercel.app/">Live Demo →</a>
    </td>
  </tr>
</table>

---

## What I Work With

<table>
  <tr>
    <td valign="top" width="50%">

**Systems & Inference**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LibTorch](https://img.shields.io/badge/LibTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-009688?style=flat-square&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFB300?style=flat-square&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat-square&logo=langchain&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

  </td>
  <td valign="top" width="50%">

**Languages**

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Tools & Infrastructure**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GPG Signed](https://img.shields.io/badge/Commits-GPG_Signed-2ea44f?style=flat-square&logo=gnuprivacyguard&logoColor=white)
![DCO](https://img.shields.io/badge/DCO-Compliant-0078D4?style=flat-square&logo=git&logoColor=white)

  </td>
  </tr>
</table>

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Raja-89&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&include_all_commits=true&count_private=true" height="180"/>
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Raja-89&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=8" height="180"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Raja-89&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=f0883e&currStreakLabel=58a6ff" height="180"/>
</div>

---

## Commit Hygiene

Every repository follows strict provenance standards inherited from FFmpeg contribution requirements:

- ✅ **GPG-signed commits** — cryptographic proof of authorship, verifiable by any maintainer
- ✅ **DCO sign-off on every commit** — certifying origin under the [Developer Certificate of Origin](https://developercertificate.org/)

If you're a maintainer reviewing a contribution from me, you will never chase me for these.

---

## Education

**B.Tech — Mathematics and Computing**
Delhi Technological University (DTU) · 2024–2028

*A dual-focus program grounding ML work in rigorous linear algebra, probability theory, OOP, operating systems, and statistical modelling — not just framework calls.*

---

<div align="center">
  <sub>Open to ML infrastructure · computer vision · applied AI internships for 2026–27 · <a href="mailto:imraja729@gmail.com">Get in touch</a></sub>
  <br/><br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a2744,60:0f1b2d,100:0d1117&height=100&section=footer" width="100%"/>
</div>
