<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

16 Ring oscillators in parallel. Each ring oscillator have 1 input enable to start (Active high). Each enable input enables 2 ring oscillators. The output of each ring oscillator is sampled by a D-type Flip-Flop triggered by the input sampling clock.  

## How to test

Enable one of the eight input enables setting it to a logic high. Next turn on the sampling clock signal. Capture the respective output signal for the available 16. The output of each should be random. 

## External hardware

Requires a signal generator for the sample clock and a logic analyzer or equivalent acquisition equipment to record the output random bitstream.
