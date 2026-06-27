---
title: "Research Accomplishments"
description: "Research accomplishments of Samik Bose — personal statement, appointments, honors, and contributions to science."
---

<header class="page-head">
  <div class="wrap">
    <p class="eyebrow">Portfolio</p>
    <h1>Research Accomplishments</h1>
    <p>Personal statement, appointments and honors, and contributions to science.</p>
  </div>
</header>

<div class="doc">
  <div class="wrap">

    <h2>A. Personal Statement</h2>
    <p>
      I am a computational biophysicist with 10+ years of experience developing and applying molecular
      modeling tools to investigate fundamental biomolecular processes relevant to medicinal chemistry and
      biochemistry. During my PhD at the Indian Association for the Cultivation of Science, I developed
      quantum-mechanics/molecular-mechanics (QM/MM) methods<sup>1</sup> and machine-learning-based force
      fields for molecular dynamics (MD) simulations aimed at understanding photophysical processes in
      biology<sup>2</sup>. In my postdoctoral training in Dr. Alex Dickson's laboratory at Michigan State
      University, I gained expertise in enhanced-sampling MD methods — essential tools for understanding
      long-timescale, rare events in biology (e.g., drug binding, protein folding, large-scale
      conformational switches, and molecular transport through transmembrane proteins). I developed a
      robust enhanced-sampling technique<sup>3</sup> by integrating the weighted-ensemble (WE) MD method
      with Markov state models (MSMs) to decipher the pathways of slow, pharmacologically relevant
      inhibitor (un)binding in soluble epoxide hydrolase, and provided key insights for increasing ligand
      residence time<sup>4</sup> — a crucial determinant of pharmacokinetic efficacy. I have also applied
      WE simulations to explore the long-timescale membrane-association dynamics of the PIKfyve kinase,
      otherwise inaccessible to conventional MD.
    </p>
    <p>
      My long-term objective is to establish an independent research lab that leverages state-of-the-art
      computational techniques to advance our understanding of pharmacological and biochemical mechanisms.
      To this end, I have recently begun an independent position as a Fixed-Term Assistant Professor, where
      I am committed to fostering interdisciplinary collaborations that integrate molecular simulation with
      experimental approaches in structural and molecular biology. I have collaborated with several
      experimentalists and applied methods such as WE, MSM, and unbiased MD to study molecular mechanisms,
      thermodynamics, and kinetics across a wide range of biomolecular systems. Most recently, I have been
      working with Dr. Benjamin Orlando to investigate substrate-transport pathways in the transmembrane
      protein CbrA from <em>Pseudomonas</em> species using long, unbiased MD simulations. I plan to extend
      this work by applying enhanced-sampling techniques to probe the energetics and mechanisms of
      molecular transport and signaling in CbrA. By integrating structural and biochemical results with
      molecular simulation, our ultimate goal is to provide a comprehensive understanding of the principles
      that allow CbrA to act as a transceptor central to <em>Pseudomonas</em> virulence and pathogenesis.
    </p>
    <ol class="refs">
      <li>Bose S, Chakrabarty S, Ghosh D. Electrostatic Origin of the Red Solvatochromic Shift of DFHBDI in RNA Spinach. <em>J Phys Chem B.</em> 2017 May 11;121(18):4790-4798. PMID: 28437617.</li>
      <li>Bose S, Dhawan D, Nandi S, Sarkar RR, Ghosh D. Machine learning prediction of interaction energies in rigid water clusters. <em>Phys Chem Chem Phys.</em> 2018 Sep 12;20(35):22987-22996. PMID: 30156235.</li>
      <li>Bose S, Kilinc C, Dickson A. Markov State Models with Weighted Ensemble Simulation: How to Eliminate the Trajectory Merging Bias. <em>J Chem Theory Comput.</em> 2025 Feb 25;21(4):1805-1816. PMCID: PMC11866749.</li>
      <li>Bose S, Lotz SD, Deb I, Shuck M, Lee KSS, Dickson A. How Robust Is the Ligand Binding Transition State? <em>J Am Chem Soc.</em> 2023 Nov 22;145(46):25318-25331. PMCID: PMC11059145.</li>
    </ol>

    <h2>B. Positions, Scientific Appointments, and Honors</h2>

    <h3>Positions and Scientific Appointments</h3>
    <div class="appointments">
      <p><strong>2024 – present</strong> &nbsp; Fixed-Term Assistant Professor, Michigan State University, East Lansing, MI</p>
      <p><strong>2021 – 2024</strong> &nbsp; Postdoctoral Research Associate, Michigan State University, East Lansing, MI</p>
      <p><strong>2017 – 2020</strong> &nbsp; CSIR Senior Research Fellow &amp; PhD fellow, Indian Association for the Cultivation of Science, Kolkata, India</p>
      <p><strong>2014 – 2017</strong> &nbsp; CSIR Junior Research Fellow, National Chemical Laboratory, Pune, India</p>
    </div>

    <h3>Honors</h3>
    <div class="appointments">
      <p><strong>2017</strong> &nbsp; Physical and Materials Chemistry Division Day poster award, National Chemical Laboratory, India</p>
      <p><strong>2014</strong> &nbsp; National Eligibility Test (NET) PhD fellowship in Chemistry, Council of Scientific and Industrial Research, India</p>
      <p><strong>2014</strong> &nbsp; Graduate Aptitude Test in Engineering (GATE) PhD fellowship, National Coordination Board — GATE, India</p>
    </div>

    <h2>C. Contributions to Science</h2>

    <h3>1. Methods to study rare events &amp; applications in pharmacologically relevant biomolecules</h3>
    <p>
      Modeling rare but biologically significant events — such as ligand unbinding or long-timescale
      protein conformational changes — is essential for understanding the fundamentals of biochemistry.
      Traditional MD simulations cannot capture these long-timescale processes because of their
      computational cost. My research has contributed to the development and application of enhanced-sampling
      techniques that overcome this limitation, enabling detailed study of rare events with pharmacological
      relevance. I have used WE-based methods to investigate the unbinding mechanisms of several inhibitors
      targeting soluble epoxide hydrolase (sEH)<sup>a</sup>. These inhibitors span a wide range of
      experimentally measured residence times, a pharmacokinetic property directly related to drug efficacy.
      By capturing statistically meaningful ensembles of unbinding pathways, we characterized the transition
      state ensembles (TSEs) for each ligand, revealing that structurally similar bound states can give rise
      to surprisingly diverse TSEs. These results underscore the complexity of computational drug design and
      highlight the importance of simulating transition states directly, rather than relying solely on static
      structures or thermodynamic endpoints. We also show that, although standalone WE methods provide
      reasonable mechanistic insight, they are not quantitatively accurate in describing the underlying slow
      kinetics that are crucial in kinetics-driven drug discovery. In a subsequent study, we propose that
      combining MSMs with WE methods increases the statistical significance of kinetic predictions. This is
      not straightforward, however; we identify the methodological challenges of integrating MSMs with WE
      data and build an analytical framework for constructing WE-MSMs. Applied to the long-timescale
      unbinding of inhibitors from sEH, our method achieves a significant improvement (more than an order of
      magnitude) in accuracy and robustness compared with standalone WE or MSM methods<sup>b</sup>.
      Collectively, these contributions advance computational methods for studying rare, long-timescale
      events in biologically and pharmacologically important systems — enhancing both mechanistic
      understanding and predictive power for the rational design of more effective therapeutics.
    </p>
    <ol class="refs">
      <li>Bose S, Lotz SD, Deb I, Shuck M, Lee KSS, Dickson A. How Robust Is the Ligand Binding Transition State? <em>J Am Chem Soc.</em> 2023 Nov 22;145(46):25318-25331. PMCID: PMC11059145.</li>
      <li>Bose S, Kilinc C, Dickson A. Markov State Models with Weighted Ensemble Simulation: How to Eliminate the Trajectory Merging Bias. <em>J Chem Theory Comput.</em> 2025 Feb 25;21(4):1805-1816. PMCID: PMC11866749.</li>
    </ol>

    <h3>2. Polarizable QM/MM methods to explain spectral shifts in green-fluorescent-protein variants</h3>
    <p>
      Fluorescent proteins and their synthetic analogs are indispensable tools in biomedical imaging and
      molecular diagnostics. A quantitative understanding of how the local environment modulates the spectral
      properties of these chromophores is essential for rational probe design. My research has used polarizable
      hybrid QM/MM methods to dissect and predict environment-induced spectral shifts in chromophores,
      particularly those derived from green fluorescent protein (GFP). Using a polarizable QM/MM framework
      based on the effective-fragment-potential (EFP) method, I investigated the solvatochromic behavior of a
      GFP chromophore variant in water<sup>a</sup>. While vertical excitation energies (VEEs) showed minimal
      solvent-induced shifts (~0.1 eV), the vertical detachment energies (VDEs) showed a pronounced red shift,
      validating a long-standing hypothesis about significant charge reorganization during ionization. In a
      subsequent study, I integrated QM/MM with MD to simulate and characterize the absorption spectra of the
      GFP chromophore variant in the RNA Spinach aptamer<sup>b</sup>. Our hybrid method reproduced the red
      shift observed in the complex RNA Spinach environment. Contrary to prior assumptions that π-stacking
      interactions between chromophore and nucleobases drove the shift, our simulations showed that long-range
      electrostatics between the chromophore and the negatively charged RNA scaffold played the dominant role.
      We further uncovered an interplay between opposing electrostatic influences: the RNA backbone and
      surrounding polarized water molecules exerted partially cancelling effects that together shaped the
      observed shift. These findings emphasize the complex heterogeneity of biomolecular environments and
      their nontrivial influence on chromophore photophysics, and establish the utility of polarizable QM/MM
      models for interpreting and predicting environment-induced spectral changes — a pathway toward more
      sensitive, tunable optical probes in complex biological settings.
    </p>
    <ol class="refs">
      <li>Bose S, Chakrabarty S, Ghosh D. Effect of Solvation on Electron Detachment and Excitation Energies of a Green Fluorescent Protein Chromophore Variant. <em>J Phys Chem B.</em> 2016 May 19;120(19):4410-20. PMID: 27116477.</li>
      <li>Bose S, Chakrabarty S, Ghosh D. Electrostatic Origin of the Red Solvatochromic Shift of DFHBDI in RNA Spinach. <em>J Phys Chem B.</em> 2017 May 11;121(18):4790-4798. PMID: 28437617.</li>
    </ol>

    <h3>3. Biased-sampling algorithms to accelerate spectral-property prediction by QM/MM</h3>
    <p>
      Accurate prediction of spectral properties such as ionization energies (IEs) and electron affinities
      (EAs) in complex biological environments requires extensive sampling, because solvation dynamically
      affects the chromophore structural ensemble. Traditional QM/MM approaches are often prohibitively
      expensive in this context, requiring thousands of calculations to predict properties such as spectral
      peak maxima and full widths at half maximum. My research addresses this bottleneck through a
      solute–solvent interaction-energy-driven descriptor that can serve as a reaction coordinate for the
      rapid sampling of critical snapshots in a spectral shape<sup>a</sup>. This biased sampling significantly
      accelerates the convergence of spectral properties while maintaining high accuracy, without explicit
      QM/MM calculation at every configuration. The approach has been validated across multiple systems —
      phenol, thymine, and the GFP chromophore in the condensed phase — with consistent acceleration in
      predicting ionization energies and spectral widths. In a subsequent collaborative study on a much larger
      guanine nucleotide in water, a high-level QM/MM framework combined the EFP method (MM) with the
      equation-of-motion coupled-cluster technique for ionization potentials (EOM-IP-CCSD; QM). The expense of
      these methods required minimal sampling of critical snapshots; even so, the biased-sampling technique
      recovered the vertical ionization energies and spectral properties accurately with only a handful of
      expensive QM/MM calculations<sup>b</sup>. Overall, these contributions advance the computational toolkit
      for simulating the spectral properties of photophysically relevant biomolecules — facilitating broader,
      more detailed studies of light–matter interactions, an essential component for understanding
      radiation-induced DNA damage and photochemical reactivity in biology.
    </p>
    <ol class="refs">
      <li>Bose S, Ghosh D. An interaction energy driven biased sampling technique: A faster route to ionization spectra in condensed phase. <em>J Comput Chem.</em> 2017 Oct 5;38(26):2248-2257. PMID: 28762244.</li>
      <li>Chakraborty R†, Bose S†, Ghosh D. Effect of solvation on the ionization of guanine nucleotide: A hybrid QM/EFP study. <em>J Comput Chem.</em> 2017 Nov 5;38(29):2528-2537. PMID: 28856705. († equal contribution)</li>
    </ol>

    <h3>4. Machine-learning force fields for water and their use in Monte Carlo simulation</h3>
    <p>
      Accurate and efficient estimation of interatomic interaction energies is foundational to molecular
      simulation. Classical force fields offer speed but often sacrifice accuracy through simplified empirical
      forms, whereas quantum-mechanical (QM) methods provide high precision but are prohibitively expensive for
      large systems. My research addresses this trade-off by developing machine-learning (ML) force fields that
      combine QM accuracy with classical efficiency, particularly for water — a fundamental yet notoriously
      challenging system because of its strong polarization effects. I explored support-vector regression (SVR)
      as an alternative to neural-network methods; by integrating SVR with the many-body-expansion (MBE)
      framework, we achieved highly accurate interaction-energy predictions for water clusters. For the water
      decamer, the method achieved less than 2% ML error relative to the parent QM calculations in absolute
      interatomic interaction energy and showed transferability across temperatures<sup>a</sup>. To validate
      the model in real-world simulations, we implemented it in Monte Carlo (MC) simulations and compared the
      resulting ensemble properties with those from ab initio MD (AIMD) and the classical TIP3P model. The
      ML-based MC (MLMC) simulations reproduced key structural metrics — radial distribution functions,
      tetrahedral order parameters, and hydrogen-bonding patterns — with remarkable fidelity to AIMD, whereas
      the classical model showed noticeable deviations<sup>b</sup>. Collectively, these studies represent a
      significant advance toward next-generation force fields: by leveraging ML within a physically grounded
      framework such as MBE, and deploying it successfully in simulation protocols such as MC, my work
      demonstrates a pathway to highly accurate, scalable, and computationally tractable modeling of complex
      molecular systems.
    </p>
    <ol class="refs">
      <li>Bose S, Dhawan D, Nandi S, Sarkar RR, Ghosh D. Machine learning prediction of interaction energies in rigid water clusters. <em>Phys Chem Chem Phys.</em> 2018 Sep 12;20(35):22987-22996. PMID: 30156235.</li>
      <li>Bose S, Chakrabarty S, Ghosh D. Support Vector Regression-Based Monte Carlo Simulation of Flexible Water Clusters. <em>ACS Omega.</em> 2020 Apr 7;5(13):7065-7073. PMCID: PMC7143414.</li>
    </ol>

    <h3>Complete list of published work</h3>
    <p>
      <a href="https://www.ncbi.nlm.nih.gov/myncbi/samik.bose.1/bibliography/public/">My Bibliography (NCBI)&nbsp;→</a>
    </p>

  </div>
</div>
