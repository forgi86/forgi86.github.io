---
layout: track
title: "Learning Across Dynamical Systems | SYSID 2027"
permalink: /sysid2027/
track_title: "Learning Across Dynamical Systems: Meta-Learning, Transfer Learning, and In-Context Identification"
band_title: "SYSID 2027 Open Invited Track"
band_venue: "7–9 July 2027 · Lyon, France"
conference_url: "https://conferences.ifac-control.org/sysid2027/"
conference_name: "21st IFAC Symposium on System Identification (SYSID 2027)"
conference_dates: "7–9 July 2027"
conference_place: "Lyon, France · ECAM Lyon"
contact_email: "marco.forgione@supsi.ch"
description: "Open invited track on meta-learning, transfer learning, in-context learning and foundation models for dynamical systems at the 21st IFAC Symposium on System Identification (SYSID 2027), Lyon, France."
---

## Organizers

<div class="organizers" markdown="1">

<div class="organizer" markdown="1">
<p><span class="org-name">Matteo Rufolo</span></p>
<p class="org-aff">IDSIA Dalle Molle Institute for Artificial Intelligence,
USI-SUPSI, Lugano, Switzerland</p>
<p><a href="mailto:matteo.rufolo@supsi.ch">matteo.rufolo@supsi.ch</a></p>
</div>

<div class="organizer" markdown="1">
<p><span class="org-name">Marco Forgione</span><span class="org-role">contact person</span></p>
<p class="org-aff">IDSIA Dalle Molle Institute for Artificial Intelligence,
USI-SUPSI, Lugano, Switzerland</p>
<p><a href="mailto:marco.forgione@supsi.ch">marco.forgione@supsi.ch</a></p>
</div>

<div class="organizer" markdown="1">
<p><span class="org-name">Ankush Chakrabarty</span></p>
<p class="org-aff">Mitsubishi Electric Research Laboratories (MERL),
Cambridge, MA, USA</p>
<p><a href="mailto:achakrabarty@merl.com">achakrabarty@merl.com</a></p>
</div>

</div>


## Scope

System identification is usually carried out one system at a time: data are
collected from a single plant and a model is fitted. Many applications instead
involve families of similar systems, such as motors from the same production
line, cells in a battery pack or vehicles in a fleet. Identifying each of them
from scratch is inefficient, as it ignores what has been learned on the others.
This track is about methods that learn across such classes of systems, so that
a new member can be identified from little data and limited computational
resources.

In transfer learning, a model pretrained on a class of systems is fine-tuned on
limited data from a new one. Meta-learning includes this adaptation step in the
training objective. Gradient-based methods learn initialisations from which a
few updates suffice, and hypernetworks map a dataset directly to model weights.
In-context methods skip the model update altogether: a sequence model reads a
short input–output record of a system and directly predicts its response.
Foundation models extend pretraining to heterogeneous time series from many
domains.

## Topics of interest

Theoretical, methodological and applied contributions are welcome. Topics
include, but are not limited to:

- Meta-learning algorithms for identification: gradient-based methods,
  hypernetworks, in-context learning, amortised inference.
- Pretraining on synthetic data: design of simulated system classes and
  sim-to-real transfer.
- Foundation models for dynamical systems and time series.
- Physics-informed and grey-box meta-learning.
- Probabilistic and hierarchical Bayesian meta-learning, uncertainty
  quantification.
- Transfer learning and domain adaptation across plants and operating
  conditions.
- Meta-generalisation beyond the training distribution: distributionally robust
  optimisation, contrastive and invariance-based objectives.
- Sample complexity, identifiability and the relation to classical estimators.
- Self-tuning and predictive control with meta-learned models.
- State estimation, fault detection and diagnosis across system classes.
- Industrial applications, benchmarks and open datasets.

## Submitting a contribution

Contributions are submitted through the [IFAC PaperCept](https://ifac.papercept.net/) platform. Select **Open Invited Track Paper** and use the invited session code <span class="tba">to be announced</span>.

- **Submission deadline:** 2 November 2026
- **Paper length:** 4&ndash;8 pages at submission; final manuscripts are limited
  to 6 pages in the proceedings.
- **Format:** standard IFAC two-column format, as specified in the
  [SYSID 2027 author guidelines](https://conferences.ifac-control.org/sysid2027/).

Submissions must be original and not under review elsewhere.

### Other types of contribution

The procedure above is for regular track papers. To contribute a joint
journal/conference paper, a dissemination paper or a discussion paper, please
contact [Marco Forgione](mailto:marco.forgione@supsi.ch).
