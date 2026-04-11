# Christophe Pallier Programming projects

I am a cognitive neuroscientist at [Unicog](http://www.unicog.org). My actual homepage is at [pallier.org](http://www.pallier.org).

This is my github repository, featuring many of programming or documentation projects. I hightlight some of them below: 


* **Lexical Databases & Pseudoword generator**
  * **[OpenLexicon](https://chrplr.github.io/openlexicon)**: Platform providing access to lexical databases for psycholinguistic research, including Lexique
  * **[unipseudo-go](https://github.com/chrplr/unipseudo-go)**: Pseudoword generator using trigram Markov chains from real word dictionaries (port of UniPseudo)

* **Experiment Frameworks & Stimulus Delivery**
  
  Tools for building and running psychology/neuroscience experiments with precise timing.

  * **[goxpyriment](https://github.com/chrplr/goxpyriment)**: General-purpose framework for building behavioral experiments — stimuli, trials, blocks, logging
  * **[gostim2](https://chrplr.github.io/gostim2)**: Fixed-schedule multimedia stimulus delivery (image, audio, text, video) with millisecond timing and VSYNC sync
  * **[Audiovis](https://chrplr.github.io/audiovis)**: Audio-visual stimulus presentation based on expyriment

* **Stimulus List Preparation**
  
  Tools for generating stimuli and randomizing experimental lists.

  * **[shuffle-go](https://chrplr.github.io/shuffle-go)**: Randomize lists with sequential constraints (max repetitions, minimum gap)
  * **[match-go](https://github.com/chrplr/match-go)**: Implementation of van Casteren & Davis Mix & Match — match items across conditions on selected variables
  * **[dot-array-generator-go](https://github.com/chrplr/dot-array-generator-go)**: Generate non-symbolic number stimuli (dot arrays) with configurable spatial constraints (prot Lauren Aulet's code)
  * **[images2gv](https://github.com/chrplr/images2gv)**: Convert image sequences into GPU-accelerated video (.gv) with LZ4 compression and efficient frame seeking
  * **[llm_pseudoword_generator](https://github.com/chrplr/llm_pseudoword_generator)**: Neural pseudoword generator trained with a character-level language model
  * **[jabberwocky](https://github.com/chrplr/jabberwocky)**: Generates syntactically correct French nonsense text by replacing content words with pseudowords

* **Timing & Hardware Interfaces**
  * **[bbtkv3](https://chrplr.github.io/bbtkv3)**: Capture stimulus/response events using the Black Box ToolKit v3
  * **[bbtkv2_python](https://github.com/chrplr/bbtkv2_python)**: Python module for precise timing acquisition with the Black Box ToolKit v2
  * **[dlp-io8-g](https://github.com/chrplr/dlp-io8-g)**: Send/read TTL triggers via an FTDI chip
  * **[keyboard_scanner](https://github.com/chrplr/keyboard_scanner)**: HID event monitor — captures and timestamps keyboard/mouse input
  * **[neurospin_meg_response_keys_parallel_port](https://github.com/chrplr/neurospin_meg_response_keys_parallel_port)**: Record response button presses during MEG experiments via parallel port

* **Research Projects**

  * **The Little Prince (fMRI/MEG/EEG)**
    
    Multi-modal neuroimaging study in which participants listened to *The Little Prince* audiobook.

    * **[lpp-paradigms](https://github.com/chrplr/lpp-paradigms)**: Experimental stimuli and presentation code across EEG, fMRI, and MEG modalities
    * **[LePetitPrince](https://github.com/chrplr/LePetitPrince)**: Pipeline computing cross-validated R² maps of how well computational models predict brain activity
    * **[lpp-scripts3](https://github.com/chrplr/lpp-scripts3)**: Full fMRI analysis pipeline: regressor generation, first/second-level analyses, ROI studies

  * **Brain Lateralization & Language Models**
    
    Code for:
    * Bonnasse-Gahot, L., & Pallier, C. (2024). fMRI predictors based on language models of increasing complexity recover brain left lateralization. Advances in Neural Information Processing Systems, 37, 125231-125263.

    These codes were written by Laurent Bonnasse-Gahot:
    * **[llms_brain_lateralization](https://github.com/l-bg/llms_brain_lateralization)**: **NeurIPS 2024** — fMRI predictors from language models of increasing complexity recover left lateralization for language
    * **[llm_training_brain_asym](https://github.com/l-bg/llm_training_brain_asym)**: **arXiv:2602.12811** — Left-right brain asymmetry in LLM-based fMRI prediction across OLMo-2 training stages

* **Teaching Materials**
  * **[PCBS](https://pcbs.rtfd.io)**: Programming for Cognitive and Brain Sciences — full course
  * **[programming-psychology-experiments](https://github.com/chrplr/programming-psychology-experiments)**: Programming Psychology Experiments (subset of PCBS)
  * **[statistics_with_R](https://github.com/chrplr/statistics_with_R)**: Basic statistical analyses with R

* **Miscellaneous**
  * **[linux-tips](https://chrplr-linux-tips.readthedocs.io/en/latest/)**: Linux command-line tips and howtos

---

* [All my repositories](https://github.com/chrplr?tab=repositories).

