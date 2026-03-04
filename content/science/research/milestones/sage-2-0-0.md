---
title: "Sage 2.0.0"
color: red
status: released
date: "2021-08-18"
github: "https://github.com/openforcefield/openff-forcefields/releases/tag/2.0.0"
doi: "https://zenodo.org/record/5214478"
---

## Overview

Sage (OpenFF 2.0.0) is the second-generation OpenFF small molecule force field. The key advance over Parsley is the first retraining of Lennard-Jones parameters, using condensed-phase physical property data alongside QM geometry targets.

Sage was produced via a multi-stage optimisation: first, selected vdW parameters were trained against experimental mass densities and enthalpies of mixing from the NIST ThermoML archive; then bond, angle, and torsion parameters were trained against QM optimised geometries and torsion profiles.

## Links

{{< button href="https://github.com/openforcefield/openff-forcefields/releases/tag/2.0.0" text="GitHub release" >}}
{{< button href="https://zenodo.org/record/5214478" text="DOI" >}}
{{< button href="https://doi.org/10.1021/acs.jctc.3c00039" text="Publication" >}}

Training data and re-run instructions are in the [openff-sage](https://github.com/openforcefield/openff-sage) repository.

