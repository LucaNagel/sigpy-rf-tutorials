# sigpy-rf-tutorials
A collection of tutorial information and application examples for the sigpy-rf software package, an extension of the SigPy software package. 

# insteresting links:
* Educational (slides from John Pauly) https://web.stanford.edu/class/ee469b/Notes/Spin_Echo.pdf
* Paper preprint Frank Ong https://arxiv.org/pdf/2103.07629.pdf
* shaped pulses Robin de Graaf Video: https://www.youtube.com/watch?v=bdA1HTPN6nk (14:40 starting the topic of ripples)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jonbmartin/sigpy-rf-tutorials/HEAD)


# SLR introduction
* Forward SLR Transform: The pulse is converted into two polynominals (alpha, beta, so called Cayley-Klein *CK* parameters). For this the pulse is discretized into a sequence of impulses/hard pulses. Then an off resonance precession follows which is then again followed by a hard pulse rotation and so on.
** Off-resonance rotates the magnetization around the z-axis, hard pulses rotate the magnetization around an axis in the transverse plane.