# EGFET_PDK

Motivation:
EGFET is an inkjet printed electrolyte-gated transistor technology for developing pritable devices and circuits. The EGFET technology is a low-voltage technology
with a typical supply voltage of 1V. The detailed information about the technology is given in R1. We developed the standard cell libraries for the EGFET technology
by characterizing the combinational and sequential logic gates. The characteristics of the libraries are reported in our paper Printed Microprocessors, published in ISCA 2020. 


Library Details:
The EGFET standard libraries are developed using the compact models of the EGFET. Only n-type transistor is available in EGFET technology and all logic gates are realized with
tranistor-resisitor logc. The pull-up logic is realized using a resistor and pull-down logic is relaized using an EGFET. 
The ./lib folder contains the standard libraries for the supply voltage ranging from 0.6V to 1.0V.

[R1] G.C. Marques, D.Weller, A. T. Erozan, X. Feng, M. Tahoori, and J. Aghassi-Hagmann, “Progress Report on ‘From printed electrolyte-gated metal-oxide devices to circuits'”, Advanced Materials, 2019.

