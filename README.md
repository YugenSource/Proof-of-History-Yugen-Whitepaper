# Proof-of-History-Yugen-Whitepaper

## Abstract

With the introduction of Solana's timestamping/consensus mechanism called Proof-of-History (PoH), there became a novel way of measuring time and keeping order of blocks using hash functions iterated recursively that could not be parallelized but parallelized during verification. This new system used ticks to measure time, an interval of recursively hashed outputs of the previous hash function digest to inputs in the next hash function digest.

This paper presents an extension on proof-of-history guaranteeing higher security, more powerful extensions, and more useful mechanisms. This is known as **proof-of-history-yugen (PoHyug)** and offers several extensions to the base mechanism that can become useful.

## 1. Introduction

