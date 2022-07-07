Data and Replication Codes for 'Labor Market Effects of Technology Shocks Biased Toward the Traded Sector' by
Luis Bertinelli,  Olivier Cardi and Romain Restout, June 2022.

Data: database2022.xlsx (all data are scaled by the working age population and are expressed in rate of change).

The software for Figures 2a, 3, 4, 5, 6 is RATS Pro 10.0.

Figure 2a: run Panel_VAR.RPF
Figure 3: run Panel_VAR.RPF
Figure 4: run Panel_VAR.RPF
Figure 5: run Country_VAR.RPF
Figure 6: run Country_VAR.RPF

The files bqdodraws.src, mcvardodraws.src and mcprocessirf.src are RATS procedure files:
- bqdodraws.src: does Monte Carlo draws for a Blanchard and Quah (AER 1989) factorization.
- mcvardodraws.src: computes impulse response functions for a VAR using Monte Carlo imulation.
- mcprocessirf.src: extracts information for error bands for impulse response functions. 
The three files are downloadable from the RATS website (https://www.estima.com/cgi-bin/procbrowser.cgi).