<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The attention mechanism is the core innovation behind transformers - the architecture powering GPT, BERT, and modern AI. 

## How to test

Design must implement the following steps:

Compute Q=XWQ, K=XWK, and V=XWV
Compute attention scores using S=QKT
Apply scaling with S=S/dk−−√
Apply softmax (approximation allowed)
Compute final output by O=softmax(S)V

## External hardware

A logic Analyzer for verifying the ouputs with respect to the inputs.
