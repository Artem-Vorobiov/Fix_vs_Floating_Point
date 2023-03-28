[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/8h-cwzJG)


## DCA Assignment 2 - "Fixed Point and Floating Point"
### Students SSE - Artem Vorobiov and Mohadeseh Kolbadi Nejad

### Introduction
In the following assignment the FIR filter and the process of applying fixed and floating point are introduced.

**GAOLS**: 

- Implement low-pass filter with different numerical systems in order to observe what is the defference in output of the FIR filter. 
- Analyse filtered signals graphically
- Analyse execution time
- Analyse errors.

For the experiment low-pass filter is chosen and pseudo code is taken from wikipedia. 
First, the original signal is created and converted to fixed and/or floating points. 
Then the signal iterates inside the loop where main formula is applied with coefficients. The filtered signal is stored and returned.

**Low-pass filter:**

<img src="pseudocode.png" alt="Alt text" width="600" height="200" align="center">

Source:
- https://stackoverflow.com/questions/62448904/how-to-implement-continuous-time-high-low-pass-filter-in-python
- https://en.wikipedia.org/wiki/Low-pass_filter
- https://helpful.knobs-dials.com/index.php/Low-pass_filter
