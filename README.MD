# Uncertainty-Aware Inference in Noisy Regression

This repository contains a minimal exploratory study demonstrating how uncertainty
is concealed by point-estimate regression methods and revealed through Bayesian inference.

## Motivation
In many scientific settings, data are limited and noisy. While point estimates may
appear confident, they often fail to communicate uncertainty arising from noise and
data sparsity.

## Method
We compare ordinary least squares regression with Bayesian Ridge Regression on synthetic
datasets generated under controlled noise and sampling regimes.

## Key Insight
Agreement in mean predictions does not imply agreement in confidence.

## Contents
- `notebook/uncertainty_vs_point_estimates.ipynb`: Full experimental analysis

## Note
This study is intended as a conceptual probe rather than a complete solution.
