---
layout: post
title: "Local and Sparse Kernel Operator Learning for Incompressible Flows: An Operator Lagrange Formulation"
date: 2026-10-21 00:20:47 +00:00
image: /images/local_sparse_operator_lagrange.png
categories: research
author: "Ramansh Sharma"
authors: "<strong>Ramansh Sharma</strong>, Matthew Lowery, Houman Owhadi, Varun Shankar"
venue: "<font color='red'>Preprint</font>"
paper: /docs/local_sparse_operator_lagrange.pdf
arxiv: https://arxiv.org/abs/2610.29009
---

We present a local and sparse kernel method for learning the solution operators of incompressible flows. It builds on our earlier property-preserving kernel method, whose global output reconstruction and dense operator regression scale poorly. Our method replaces the global output reconstruction by local divergence-free interpolants with divergence-free polynomials of any degree, solved in parallel on the GPU. These interpolants are divergence free, periodic on periodic domains, and, with a multiscale kernel, approach Kolmogorov statistics under refinement. A compactly supported kernel, positive semidefinite in any input dimension, makes the operator regression sparse.
