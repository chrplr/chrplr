# Christophe Pallier

Cognitive neuroscientist at [Unicog](http://www.unicog.org). My homepage is at [pallier.org](http://www.pallier.org).

---

## Experiment Frameworks & Stimulus Delivery

Tools for building and running psychology/neuroscience experiments with precise timing.

| Repository | Description | Language |
|---|---|---|
| [goxpyriment](https://github.com/chrplr/goxpyriment) | General-purpose framework for building behavioral experiments — stimuli, trials, blocks, logging | Go |
| [gostim2](https://chrplr.github.io/gostim2) | Fixed-schedule multimedia stimulus delivery (image, audio, text, video) with millisecond timing and VSYNC sync | Go |
| [Pinel-localizer-go](https://github.com/chrplr/Pinel-localizer-go) | fMRI functional localizer (Pinel et al. 2007) identifying brain regions for perception, motor, reading, language, arithmetic | Go |
| [retinotopy-go](https://github.com/chrplr/retinotopy-go) | HCP retinotopic mapping — flickering checkerboard/wedge stimuli for visual cortex fMRI | Go |
| [Posner_attention_networks_task](https://github.com/chrplr/Posner_attention_networks_task) | Attention Network Test (ANT-R) measuring alerting, orienting, and executive control | Python |
| [Pinel_localizer](https://github.com/chrplr/Pinel_localizer) | Python/expyriment version of the Pinel functional localizer | Python |
| [Audiovis](https://chrplr.github.io/audiovis) | Audio-visual stimulus presentation based on expyriment | Python |
| [Expe3000](https://chrplr.github.io/expe3000) | Fixed-schedule audio/visual stimulus delivery | C |

---

## Stimulus List Preparation

Tools for generating and randomizing experimental stimulus lists.

| Repository | Description | Language |
|---|---|---|
| [shuffle-go](https://chrplr.github.io/shuffle-go) | Randomize lists with sequential constraints (max repetitions, minimum gap) | Go |
| [dot-array-generator-go](https://github.com/chrplr/dot-array-generator-go) | Generate non-symbolic number stimuli (dot arrays) with configurable spatial constraints | Go |
| [match-go](https://github.com/chrplr/match-go) | Implementation of van Casteren & Davis Mix & Match — match items across conditions on selected variables | Go |

---

## Lexical & Linguistic Tools

| Repository | Description | Language |
|---|---|---|
| [OpenLexicon](https://chrplr.github.io/openlexicon) | Platform providing access to lexical databases for psycholinguistic research, including Lexique | Python / R / JS |
| [unipseudo-go](https://github.com/chrplr/unipseudo-go) | Pseudoword generator using trigram Markov chains from real word dictionaries (port of UniPseudo) | Go |
| [llm_pseudoword_generator](https://github.com/chrplr/llm_pseudoword_generator) | Neural pseudoword generator trained with a character-level language model | Python |
| [jabberwocky](https://github.com/chrplr/jabberwocky) | Generates syntactically correct French nonsense text by replacing content words with pseudowords | Python |

---

## Timing & Hardware Interfaces

| Repository | Description | Language |
|---|---|---|
| [bbtkv3](https://chrplr.github.io/bbtkv3) | Capture stimulus/response events using the Black Box ToolKit v3 | Go |
| [bbtkv2_python](https://github.com/chrplr/bbtkv2_python) | Python module for precise timing acquisition with the Black Box ToolKit v2 | Python |
| [dlp-io8-g](https://github.com/chrplr/dlp-io8-g) | Send/read TTL triggers via an FTDI chip | Go |
| [keyboard_scanner](https://github.com/chrplr/keyboard_scanner) | HID event monitor — captures and timestamps keyboard/mouse input | Go / Python |
| [neurospin_meg_response_keys_parallel_port](https://github.com/chrplr/neurospin_meg_response_keys_parallel_port) | Record response button presses during MEG experiments via parallel port | Python |

---

## Research Projects

### The Little Prince (fMRI/MEG/EEG)

Multi-modal neuroimaging study in which participants listened to *The Little Prince* audiobook.

| Repository | Description |
|---|---|
| [lpp-paradigms](https://github.com/chrplr/lpp-paradigms) | Experimental stimuli and presentation code across EEG, fMRI, and MEG modalities |
| [LePetitPrince](https://github.com/chrplr/LePetitPrince) | Pipeline computing cross-validated R² maps of how well computational models predict brain activity |
| [lpp-scripts3](https://github.com/chrplr/lpp-scripts3) | Full fMRI analysis pipeline: regressor generation, first/second-level analyses, ROI studies |

### Brain Lateralization & Language Models

| Repository | Description |
|---|---|
| [llms_brain_lateralization](https://github.com/chrplr/llms_brain_lateralization) | **NeurIPS 2024** — fMRI predictors from language models of increasing complexity recover left lateralization for language |
| [llm_training_brain_asym](https://github.com/chrplr/llm_training_brain_asym) | **arXiv:2602.12811** — Left-right brain asymmetry in LLM-based fMRI prediction across OLMo-2 training stages |
| [td_llms_brain_lateralization](https://github.com/chrplr/td_llms_brain_lateralization) | Research code correlating LLMs (GPT-2, Qwen, Pythia) with fMRI brain activity patterns |

---

## fMRI / MRI Analysis Tools

| Repository | Description | Language |
|---|---|---|
| [mri-tools](https://github.com/chrplr/mri-tools) | Command-line utilities for processing fMRI data: image transformation, signal extraction, visualization | Python |

---

## Teaching Materials

| Repository | Description |
|---|---|
| [PCBS](https://pcbs.rtfd.io) | Programming for Cognitive and Brain Sciences — full course |
| [programming-psychology-experiments](https://github.com/chrplr/programming-psychology-experiments) | Programming Psychology Experiments (subset of PCBS) |
| [statistics_with_R](https://github.com/chrplr/statistics_with_R) | Basic statistical analyses with R |

---

## Miscellaneous

| Repository | Description |
|---|---|
| [linux-tips](https://chrplr-linux-tips.readthedocs.io/en/latest/) | Linux command-line tips and howtos |
| [images2gv](https://github.com/chrplr/images2gv) | Convert image sequences into GPU-accelerated video (.gv) with LZ4 compression and efficient frame seeking | Go |

