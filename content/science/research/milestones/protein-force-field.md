---
title: "Protein force field"
color: red
status: current
target: "2026"
github: ""
doi: ""
---

## Overview

Development of a comprehensive SMIRNOFF-compatible protein force field that can be applied consistently with OpenFF small molecule parameters. The goal is to enable all-atom simulations of protein–ligand systems using a unified, self-consistent OpenFF parameter set.

The project builds directly on the biopolymer infrastructure added to the OpenFF Toolkit (0.9+) and draws on structural benchmark datasets to validate backbone and side-chain geometries.

## Scientific goals

- Consistent treatment of standard, non-standard and unnatural amino acids using the direct chemical perception framework
- Validated against QM data, peptide NMR observables, protein NMR observables, and protein–ligand relative binding free energies
- Co-optimized with small molecule parameters for seamless protein–ligand simulations

## Related work

- [Structure-Based Experimental Datasets for Benchmarking of Protein Simulation Force Fields](/science/publications/) — Cavender et al., 2023

## Meeting minutes

This project is discussed at the [fortnightly protein biopolymers meeting](https://openforcefield.atlassian.net/wiki/spaces/MEET/pages/2017329178/Protein+FF+meeting+notes).