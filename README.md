# Awesome Nonlinear Loudspeakers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](contributing.md)

[![GitHub Discussions](https://img.shields.io/badge/discussions-join-ff69b4)](https://github.com/yourusername/awesome-nonlinear-loudspeakers/discussions)

> A curated list of papers, models, experiments, datasets, methods, and open resources for understanding and researching **non‑linear loudspeakers and microspeakers**. 🔊📚

Our mission is to lower the barrier of entry so that students, hobbyists, and professionals can **learn, experiment, and contribute** to the science of loudspeaker non‑linearity. 🚀

---

## 📜 Contents
- [Survey Papers](#survey-papers)
- [Open Source Projects](#open-source-projects)

- [Tutorials and Experiments](#tutorials-and-experiments)
- [Methods](#methods)
  - [Modeling](#modeling)
  - [Measurement](#measurement)
  - [Compensation and Control](#compensation-and-control)


- [Datasets](#datasets)
  - [Public & Open](#public-open)

  - [Supplemental](#supplemental)
  - [Dataset tools](#dataset-tools)
- [State of the Art (SOTA)](#state-of-the-art-sota)

  - [Measurement Systems](#measurement-systems)
  - [Real Time Compensation](#real-time-compensation)
  - [High Accuracy Modeling](#high-accuracy-modeling)
- [Notable Research Groups](#notable-research-groups)
- [Other Resources](#other-resources)
- [Contributing](#contributing)
- [License](#license)

---

## Survey Papers


| Year | Citation & Link | Notes |
|------|-----------------|-------|
| 2006 | Klippel W. - **Wolfgang Klippel (2006)** – [“Loudspeaker Nonlinearities: Causes, Parameters, Symptoms”](https://www.klippel.de/fileadmin/klippel/Files/Know_How/Literature/Papers/Loudspeaker%20Nonlinearities_Causes%2CParameters%2CSymptoms_06.pdf) | Physics, measurement, perception overview. |

| 2007 | Agerkvist F.T. [*Modeling Loudspeaker Non‑linearities*](https://aes2.org/publications/elibrary-page/?id=14203) | Compares modeling strategies. |
| 2016 | Klippel W. [*Measurement & Perception of Regular Loudspeaker Distortion*](https://www.klippel.de/fileadmin/klippel/Files/Know_How/Literature/Papers/Loudspeaker%20regular%20signal%20distortion%20caused%20by%20design_part%201_Klippel_Werner.pdf) | Updates metrics & audibility thresholds. |

---

## Open Source Projects

Its a bit empty for now...

---

## Tutorials and Experiments

- **[`quant‑comp‑ls‑mod‑ica22`](https://github.com/fhchl/quant-comp-ls-mod-ica22)** – Full measurement chain & raw data used for ICA 2022 loudspeaker model comparison.
- **Klippel Application Notes** – Practical guides on large‑signal testing ([PDF list](https://www.klippel.de/know-how/literature/application-notes.html)).
- **Klippel Training Videos** – Free webinar recordings ([YouTube playlist](https://youtube.com/playlist?list=PLl94n_3SYVnGdrCFZ8BVtTzRsc5tkD0TI&si=2uEYDruuZC2YG-XI)).
- **ARTA** – [ARTA Software](http://www.artalabs.hr/) guides for multi‑tone distortion.
- **Chalmers MSc (2010)** – *Modeling and Compensation of Nonlinear Loudspeakers* ([PDF](https://publications.lib.chalmers.se/records/fulltext/126003.pdf)).
- **COMSOL Example** – *How to Perform a Nonlinear Distortion Analysis of a Loudspeaker Driver* ([Model gallery](https://www.comsol.com/blogs/how-to-perform-a-nonlinear-distortion-analysis-of-a-loudspeaker-driver)).

---

## Methods

### Modeling of nonlinearities

- **general overview of Nonlinaer systen identification** - For a general introduction to nonlinear systems identification - see [Wikipedia](https://en.wikipedia.org/wiki/Nonlinear_system_identification)

  - **Volterra / Polynomial Models** – a linear combination of convolutions approach - see[Wikipedia](https://en.wikipedia.org/wiki/Nonlinear_system_identification#Volterra_series_methods).
  
  - **NARMAX methods** - generalization of volterra series using kernels - see [Wikipedia](https://en.wikipedia.org/wiki/Nonlinear_system_identification#NARMAX_methods)

  - **Neural Nets** – Neural networks used as function approximators - see ([Wikipedia](https://en.wikipedia.org/wiki/Nonlinear_system_identification#Neural_networks)).

  - **SINDY** - SINDY (System identification of nonlinear dynamics) is a datadriven sparse regression based approach to identifying the underlying system. It uses regression upon a "library" of candidate multivariate functions (polynomials, geometric functions,...) to determine the underlying system using lasso regression - see [SINDY paper](https://www.pnas.org/doi/10.1073/pnas.1517384113)


## Notable Research Groups

Klippel GmbH – Dresden, Germany

Acoustic Technology Group – DTU, Denmark

IRCAM / Sorbonne U. – Paris, France

Key Lab of Modern Acoustics – Nanjing University, China

## Other Resources

AES E‑Library – Thousands of peer‑reviewed audio papers.

Klippel Webinars – Free video lectures on large‑signal topics.

## Contributing

Contributions welcome! 🌟 Please read contributing.md and follow the Awesome Guidelines. Keep entries short, link directly to the source, and sort alphabetically.

## License

CC0 1.0 Universal — public domain dedication.

