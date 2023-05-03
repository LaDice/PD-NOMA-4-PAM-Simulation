# PD-NOMA-4-PAM-Simulation
Considering two uniform 4-PAM constellations, M-PAM1, with average
constellation energy ES1 = α, with α ∈ [0,1] and 4-PAM2 with average constellation
energy ES2 = 1 − α.
Supposed that the transmitter has to transmit symbol S1 E 4-PAM1 to user 1 (UE1)
and symbol S2 ∈ 4-PAM2 to user 2 (UE2). In order to serve the two users simultaneously,
the transmitter submits a complex symbol x with Re part S1 and Im part S2. It should
be noted that the transmitted signal x is a symbol of an 16-QAM with average constellation
energy Et = E[x^2]

At the receiver’s side, UE1 receives the signal r1 = x + n1 and UE2 receives the signal
r2 = x + n2, where n1 and n2 follow the normal distribution CN(0,NO/2) and CN(0,cN0/2)
respectively, and c=0.5.
Finally, n1'and n2'are random variables following the normal distribution N(0.NO/4) AND N(0,cNO/4) respectively.

For System 1, by considering a = 0.25, I devoloped a simulation in MATLAB to
plot the SEP vs. SNR for both UE1 and UE2, where SNR = Et/N0. I verified the simulation
results through the SEP expressions for 4-PAM. Also, I found at every SNR
the value of α such that the maximum SEP between UE1 and UE2 is minimized.

