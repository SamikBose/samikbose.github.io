---
description: "Samik Bose — computational biophysicist at Michigan State University working on molecular dynamics, enhanced sampling, Markov state models, and machine learning for drug binding kinetics and protein conformational dynamics."
---

<header class="hero">
  <svg class="hero__net" viewBox="0 0 1200 420" preserveAspectRatio="xMidYMid slice" aria-hidden="true">
    <g stroke="#1c5b3a" stroke-opacity="0.18" stroke-width="1.2">
      <line x1="120" y1="80"  x2="280" y2="160"/>
      <line x1="280" y1="160" x2="180" y2="300"/>
      <line x1="280" y1="160" x2="430" y2="120"/>
      <line x1="430" y1="120" x2="560" y2="230"/>
      <line x1="560" y1="230" x2="700" y2="150"/>
      <line x1="560" y1="230" x2="480" y2="350"/>
      <line x1="700" y1="150" x2="850" y2="240"/>
      <line x1="850" y1="240" x2="980" y2="130"/>
      <line x1="980" y1="130" x2="1100" y2="250"/>
      <line x1="850" y1="240" x2="900" y2="360"/>
      <line x1="430" y1="120" x2="700" y2="150"/>
    </g>
    <g fill="#1c5b3a" fill-opacity="0.28">
      <circle cx="120"  cy="80"  r="5"/>
      <circle cx="280"  cy="160" r="7"/>
      <circle cx="180"  cy="300" r="5"/>
      <circle cx="430"  cy="120" r="6"/>
      <circle cx="560"  cy="230" r="8"/>
      <circle cx="700"  cy="150" r="6"/>
      <circle cx="480"  cy="350" r="5"/>
      <circle cx="850"  cy="240" r="7"/>
      <circle cx="980"  cy="130" r="6"/>
      <circle cx="1100" cy="250" r="5"/>
      <circle cx="900"  cy="360" r="5"/>
    </g>
  </svg>

  <div class="hero__inner">
    <div class="hero__photo">
      <img src="/SB.jpg" alt="Portrait of Samik Bose">
    </div>
    <div class="hero__intro">
      <p class="eyebrow">Computational Biophysics &amp; Molecular Modeling</p>
      <h1 class="hero__name">Samik Bose</h1>
      <p class="hero__role">Fixed-Term Assistant Professor</p>
      <p class="hero__affil">
        Department of Computational Mathematics, Science &amp; Engineering<br>
        Michigan State University · East Lansing, Michigan, USA
      </p>
      <p class="hero__contact">
        <a href="mailto:bosesami@msu.edu">bosesami@msu.edu</a>
        <span class="dot">·</span>
        <a href="mailto:samikbose20121990@gmail.com">samikbose20121990@gmail.com</a>
      </p>
      <div class="hero__actions">
        <a class="btn btn--solid" href="/CV_SamikBose.pdf" target="_blank" rel="noopener">Download CV</a>
        <a class="btn btn--ghost" href="/research-accomplishments.html">Research accomplishments</a>
        <a class="btn btn--ghost" href="/news.html">News</a>
      </div>
    </div>
  </div>
</header>

<section id="about" class="section">
  <div class="wrap">
    <p class="eyebrow">About</p>
    <h2 class="section__title">Molecular modeling for human health and biology</h2>
    <p>
      I am a Fixed-Term Assistant Professor in the Department of Computational Mathematics, Science and
      Engineering at Michigan State University. Since joining the department in Fall 2024, I have taught
      several undergraduate and graduate courses, including Computational Medicine, Linear Algebra and
      Matrix Applications, Machine Learning in Molecular Dynamics, and Independent Research Study. I also
      continue my postdoctoral research in Computational Biophysics and Pharmacology under the mentorship
      of Prof. Alex Dickson (Biochemistry and Molecular Biology, MSU).
    </p>
    <p>
      As a faculty member, my goal is to combine the complementary strengths of machine
      learning and theoretical physical chemistry to develop computational methods for pharmacologically
      relevant, long-timescale processes — augmenting biomedical and health research through molecular
      modeling. With my expertise in theoretical chemistry and my interest in drug discovery, I aim to
      provide a molecular basis for solving critical problems in human health and biology.
    </p>
    <p>
      To that end, I work to strengthen the synergy between experiment and computation, drawing on
      facilities such as cryo-EM, NMR, and mass spectrometry. I currently collaborate with experimental
      scientists across medicinal chemistry (Prof. V. T. Karamyan, Oakland University), cryo-EM and
      structural biology (Dr. B. J. Orlando, MSU), pharmacology (Dr. K. S. S. Lee, MSU), and
      biochemistry and structural biology (Prof. A. A. Pioszak, University of Oklahoma Health Sciences
      Center). These collaborations, at the interface of chemistry, biology, and medicine, continually
      sharpen my view of the molecular-modeling tools the community needs.
    </p>
  </div>
</section>

<section id="research" class="section section--alt">
  <div class="wrap">
    <p class="eyebrow">Research</p>
    <h2 class="section__title">Selected projects</h2>

    <div class="project">
      <span class="project__tag">Project 1 · Reactive kinetics</span>
      <h3 class="project__title">
        Modeling slow reactive processes — including covalent inhibition — by integrating weighted-ensemble
        sampling with QM/MM and ML/MM molecular dynamics
      </h3>
      <p class="project__sub">
        A weighted-ensemble framework (wepy + OpenMM) coupled to first-principles and machine-learning
        potentials: QM/MM in electrostatic embedding via PySCF, and ML/MM via TorchANI and MLForce with a
        Flexible Topology treatment of the environment.
      </p>
      <figure>
        <img src="/figs/WE_QM_QMMM.png" alt="Weighted-ensemble QM/MM and ML/MM simulation framework for reactive processes">
        <figcaption>
          (A) Weighted-ensemble QM/MM: the QM/MM runner (wepy + OpenMM) passes QM-region coordinates and
          MM-region electrostatics to PySCF, which performs the QM/MM calculation in electrostatic embedding;
          forces, energies, charges, and dipoles are parsed back to OpenMM. (B) Weighted-ensemble ML/MM: ANI
          atomic-environment-vector inputs are evaluated by TorchANI and returned through MLForce, with
          environmental effects captured via a Flexible Topology custom non-bonded force and ANI-MBIS charges.
          (C) The covalent-inhibition kinetic scheme (k<sub>on</sub>, k<sub>off</sub>, k<sub>inact</sub>,
          k<sub>rev</sub>) that motivates direct simulation of the slow reactive step.
          (Panel C adapted from <a href="https://doi.org/10.1021/acs.chemrev.4c00745">Chem. Rev. 2024</a>.)
        </figcaption>
      </figure>
    </div>

    <div class="project">
      <span class="project__tag">Project 2 · Kinetics</span>
      <h3 class="project__title">
        Predicting the kinetics and mechanism of long-timescale biomolecular processes by integrating
        weighted-ensemble molecular dynamics with Markov state modeling
      </h3>
      <p class="project__sub">
        Inhibitor unbinding from soluble epoxide hydrolase (sEH): REVO-enhanced MD projected onto
        conformational-space networks.
      </p>
      <figure>
        <img src="/figs/JACS_2.jpeg" alt="Conformational-space networks of ligand unbinding from soluble epoxide hydrolase">
        <figcaption>
          Conformational-space networks (CSNs) of ligand unbinding from sEH on the scale of the ligand
          RMSD. The networks are arranged and oriented by pathway specificity. Three frames from the most
          probable unbinding pathways are highlighted for ligand 4 (cavity specificity: left) and ligand 5
          (cavity specificity: right), with the corresponding states highlighted in the CSNs. In each
          panel, the ligands are shown in licorice and the amino-acid residues within 2.5 Å are shown in
          CPK representation, with binding-site Asp335 and Tyr383 in vdW representation.
        </figcaption>
      </figure>
    </div>

    <div class="project">
      <span class="project__tag">Project 3 · Allostery</span>
      <h3 class="project__title">
        Decoding the structure and mechanism of allosteric modulators in the Zn-metallopeptidase
        neurolysin by molecular dynamics and Markov state modeling
      </h3>
      <p class="project__sub">Effect of activator binding across different allosteric sites.</p>
      <figure>
        <img src="/figs/NLN_work.png" alt="Allosteric modulation of neurolysin across binding sites">
        <figcaption>
          (A) The reference starting conformation, where all three binding regions are simultaneously
          occupied. (B) Probability distribution of Open, Semi-open, and Closed states (red, green, and
          blue) for apo (crystal), apo (open), System I, System II, System III, and NLN-10Py-Pip; the most
          probable poses in the closed System II and open System III are shown in the adjacent circles.
          (C) Free-energy distributions along TIC-1 and TIC-2 for all six systems, with representative NLN
          conformations in the relevant basins shown below.
        </figcaption>
      </figure>
    </div>

    <div class="project">
      <span class="project__tag">Project 4 · ML-driven design</span>
      <h3 class="project__title">
        Understanding the chemical attributes of suitable binders in target proteins through
        machine-learning-driven Flexible Topology simulations
      </h3>
      <figure>
        <img src="/figs/Flextop_intro.png" alt="Machine-learning-driven Flexible Topology simulation schematic">
      </figure>
    </div>

    <div class="project">
      <span class="project__tag">Project 5 · Transport</span>
      <h3 class="project__title">
        A biophysical basis for molecular transport in transmembrane proteins and GPCRs through molecular
        modeling and time-lagged dimensionality-reduction approaches
      </h3>
    </div>

    <div class="project">
      <span class="project__tag">Project 6 · Virtual screening</span>
      <h3 class="project__title">
        Virtual screening of inhibitor candidates for soluble epoxide hydrolase by molecular docking
      </h3>
    </div>

    <div class="future">
      <strong>Future aim 1.</strong> Improving the efficacy of reversible covalent inhibitors by modeling
      the slow reactive process through enhanced-sampling QM/MM and ML/MM molecular dynamics.
    </div>
    <div class="future">
      <strong>Future aim 2.</strong> Identifying druggable cryptic pockets through directed
      enhanced-sampling search and ML-guided Flexible Topology scans for allosteric pharmacophore
      features that bind those pockets.
    </div>

    <p class="keywords">
      <strong>Keywords:</strong> computational chemistry · molecular dynamics · machine learning ·
      enhanced sampling · weighted ensemble · Markov state modeling · QM/MM.
    </p>
  </div>
</section>

<section id="publications" class="section">
  <div class="wrap">
    <p class="eyebrow">Publications</p>
    <h2 class="section__title">Selected publications</h2>
    <ol class="pubs">
      <li>
        <strong>K. Babin, C. Kilinc, S. Bose</strong>, S. E. Gostynska, A. Dickson, A. Pioszak
        “An allosteric CLR N-terminal swing-out mechanism for RAMP-mediated adrenomedullin receptor selectivity.”
        <span class="venue"> Under revision in JACS </span>
      </li>
      <li>
        <strong>M. A. Orlando, T. Shah, M. W. Faber,  S. Bose</strong>, B. J. Orlando.
        “Structure and conformational dynamics of the transceptor CbrXA and the mechanism of histidine transport.”
        <span class="venue">Protein Science</span> <span class="badge">Under review · co-corresponding</span>
        <a href="https://www.biorxiv.org/content/10.64898/2026.03.10.710862v1">bioRxiv preprint</a>
      </li>
      <li>
        <strong>S. Bose</strong>, A. Aly, V. T. Karamyan, B. J. Orlando, A. Dickson.
        “Conformation-driven enhancement of neurolysin activity in the presence of a small-molecule activator.”
        <a href="https://www.biorxiv.org/content/10.64898/2026.01.05.697776v1">bioRxiv preprint</a> <span class="badge">Preprint</span>
      </li>
      <li>
        H. E. L. ElZorkany, H. Kandil, S. Jayaraman, S. H. Esfahani, D. Patel, D. Dannecker, M. Maciag,
        A. Paul, K. Lowran, <strong>S. Bose</strong>, D. A. Ostrov, C. G. Wu, A. Dickson, T. J.
        Abbruscato, P. C. Trippier, B. J. Orlando, V. T. Karamyan.
        “Discovery of a pyridine-piperazine small molecule that enhances the activity of peptidase neurolysin.”
        <span class="venue">The Journal of Pharmacology and Experimental Therapeutics</span> <span class="badge">Submitted</span>
      </li>
      <li>
        <strong>S. Bose</strong>, C. Kilinc, A. Dickson.
        “Markov state models with weighted-ensemble simulation: how to eliminate the trajectory-merging bias.”
        <span class="venue">J. Chem. Theory Comput.</span> 2025, 21 (4), 1805–1816.
      </li>
      <li>
        <strong>S. Bose</strong>, S. D. Lotz, I. Deb, M. Schuck, K. S. S. Lee, A. Dickson.
        “How robust is the ligand-binding transition state?”
        <span class="venue">J. Am. Chem. Soc.</span> 2023, 145, 25318–25331.
      </li>
      <li>
        N. Donyapour, F. F. Niazi, N. Roussey, <strong>S. Bose</strong>, A. Dickson.
        “Flexible Topology: a new method for dynamic drug design.”
        <span class="venue">J. Chem. Theory Comput.</span> 2023, 19, 5088–5098.
      </li>
      <li>
        <strong>S. Bose</strong>, S. Chakrabarty, D. Ghosh.
        “Support-vector-regression-based Monte Carlo simulation of flexible water clusters.”
        <span class="venue">ACS Omega</span> 2020, 5, 7065–7073.
      </li>
      <li>
        <strong>S. Bose</strong>, D. Dhawan, S. Nandi, R. R. Sarkar, D. Ghosh.
        “Machine-learning prediction of interaction energies in rigid water clusters.”
        <span class="venue">Phys. Chem. Chem. Phys.</span> 2018, 20, 22987–22996.
      </li>
      <li>
        R. Chakraborty, <strong>S. Bose</strong>, D. Ghosh.
        “Effect of solvation on the ionization of guanine nucleotide: a hybrid QM/EFP study.”
        <span class="venue">J. Comput. Chem.</span> 2017, 38, 2528–2537. <span class="badge">Equal first authorship</span>
      </li>
      <li>
        <strong>S. Bose</strong>, D. Ghosh.
        “An interaction-energy-driven biased sampling technique: a faster route to ionization spectra in the condensed phase.”
        <span class="venue">J. Comput. Chem.</span> 2017, 38, 2248–2257.
      </li>
      <li>
        <strong>S. Bose</strong>, S. Chakrabarty, D. Ghosh.
        “Electrostatic origin of the red solvatochromic shift of DFHBDI in RNA Spinach.”
        <span class="venue">J. Phys. Chem. B</span> 2017, 121, 4790–4798.
      </li>
      <li>
        <strong>S. Bose</strong>, S. Chakrabarty, D. Ghosh.
        “Effect of solvation on electron detachment and excitation energies of a green-fluorescent-protein chromophore variant.”
        <span class="venue">J. Phys. Chem. B</span> 2016, 120, 4410–4420.
      </li>
    </ol>
    <p class="pubs-more">
      <a href="https://www.ncbi.nlm.nih.gov/myncbi/samik.bose.1/bibliography/public/">Full publication list&nbsp;→</a>
    </p>
  </div>
</section>

<section id="teaching" class="section section--alt">
  <div class="wrap">
    <p class="eyebrow">Teaching</p>
    <h2 class="section__title">Courses at Michigan State University</h2>
    <div class="teach">
      <div class="teach__item">
        <h4>Computational Medicine</h4>
        <p class="teach__meta">400-level (graduate &amp; undergraduate) · Fall 2024 · Lead instructor — curriculum development.</p>
      </div>
      <div class="teach__item">
        <h4>Linear Algebra and Matrix Applications</h4>
        <p class="teach__meta">300-level undergraduate (3 sections) · Spring &amp; Fall 2025 · Section instructor — team curriculum development.</p>
      </div>
      <div class="teach__item">
        <h4>Machine Learning in Molecular Dynamics</h4>
        <p class="teach__meta">900-level graduate · Spring 2023 · One module (2 lectures, 2 labs).</p>
      </div>
      <div class="teach__item">
        <h4>Independent Research Study</h4>
        <p class="teach__meta">400-level undergraduate · Summer &amp; Fall 2025.</p>
      </div>
    </div>
  </div>
</section>

<section id="contact" class="section">
  <div class="wrap">
    <p class="eyebrow">Contact</p>
    <h2 class="section__title">Get in touch</h2>
    <p>
      The best way to reach me is by email at
      <a href="mailto:bosesami@msu.edu">bosesami@msu.edu</a> or
      <a href="mailto:samikbose20121990@gmail.com">samikbose20121990@gmail.com</a>.
    </p>
    <div class="socials">
      <a href="https://github.com/SamikBose">GitHub</a>
      <a href="https://www.linkedin.com/in/samik-bose-b781b031/">LinkedIn</a>
      <a href="https://orcid.org/0000-0002-0273-9162">ORCID</a>
      <a href="https://www.researchgate.net/profile/Samik-Bose">ResearchGate</a>
      <a href="https://scholar.google.co.in/citations?user=VzCHxDQAAAAJ&hl=en">Google Scholar</a>
    </div>
  </div>
</section>
