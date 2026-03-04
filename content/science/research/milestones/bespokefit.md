---
title: "OpenFF BespokeFit"
color: red
status: released
date: "2022-02-24"
github: "https://github.com/openforcefield/openff-bespokefit"
doi: "https://doi.org/10.1021/acs.jcim.2c01153"
---

## Overview

OpenFF BespokeFit is an automated workflow for generating molecule-specific (bespoke) torsion parameters using on-the-fly QM calculations. Rather than relying solely on general torsion parameters, BespokeFit fits torsion profiles to each molecule's specific chemical environment, substantially improving conformational accuracy for complex molecules.

BespokeFit integrates with the OpenFF Toolkit, QCFractal, and OpenFF Fragmenter to provide a complete automated pipeline from molecule input to final bespoke force field.

**Note -- we will be deprecating support for BespokeFit past 2026.**

## Features

- Automated fragmentation to reduce QM cost
- On-the-fly QM torsion profile generation via QCFractal
- ForceBalance-based torsion fitting
- Compatible with Sage and other OpenFF force fields

## Links

{{< button href="https://github.com/openforcefield/openff-bespokefit" text="GitHub" >}}
{{< button href="https://docs.openforcefield.org/projects/bespokefit" text="Documentation" >}}

{{< button href="https://doi.org/10.1021/acs.jcim.2c01153" text="Publication" >}}