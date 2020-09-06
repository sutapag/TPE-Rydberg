# TPE-rates

"TPE-rate" is a respository containing python codes to calculate two-photon spontaneous emission (TPE) rates in free space and inside an optical cavity. The results from this code is used in the manuscript "Creating heralded hyper-entangled photons using Rydberg atoms". This article is about a theoretical proposal to generate an entangle photon source where cloud of ultra-cold rubidium atoms, excited to Rydberg states, are trapped inside an optical cavity. The rubidium atom has been excited to Rydberg state, which due to larger size or higher dipole moment shown to have high two photon emission (TPE) rates. When such a system is placed in an optical cavity which is tuned such that it inhibits all the first order fast processes, then the only dominant decay process is through two photons. Later, the same system is shown also to generate polarization entanglement which together constitute hyper-entanglement (entanglement in two or more degrees of freedom).

This codes uses many python libraries which are developed by N. Šibalić, J. D. Pritchard, K. J. Weatherill, C. S. Adams, ARC: An open-source library for calculating properties of alkali Rydberg atoms, Computer Physics Communications 220, 319 (2017), which is also cited in the main manuscript. Notebook can also be downloaded in .ipython format here and used interactively in Jupyter.

In order to check the code, we compared the TPE rates for hydrogen atom from different energy levels and are compared with the literature, J. Chluba and R. A. Sunyaev, Two-photon transitions in hydrogen and cosmological recombination,Astronomy and Astrophysics 480, 629{645 (2008). We later extended it for rubidium atoms inside an optical cavity.

\begin{center}
\begin{table}
\begin{tabular}{ c| c| c |c}
\hline
 Transition & TPE wo continuum ($s^{-1}$) & with continuum ($s^{-1}$) & literature ($s^{-1}$) \\
 \hline
 $2S_{1/2} \rightarrow 1S_{1/2}$ & 10.014 & 8.218 & 8.2293\\ 
 $5S_{1/2} \rightarrow 1S_{1/2}$ & 25.137 & 13.7211 & 13.741\\ 
$5D_{5/2} \rightarrow 1S_{1/2}$ & 17.04 & 15.324 & 15.331\\ 
$10D_{5/2} \rightarrow 1S_{1/2}$ & 30.79 & 26.159 & 26.144\\
$10S_{1/2} \rightarrow 1S_{1/2}$ & 47.75 & 27.49 & 27.448\\
$20S_{1/2} \rightarrow 1S_{1/2}$ & 92.91 & 63.58 & 63.185\\
$20D_{5/2} \rightarrow 1S_{1/2}$ & 51.277 & 43.258 & 43.113\\
$50D_{5/2} \rightarrow 1S_{1/2}$ & 106.129 & 92.7 & 92.19\\
\end{tabular}
\caption{\label{tab:table-name} TPE rates for Hydrogen atom}
\end{table}
\end{center}

# Authors

Sutapa Ghosh, Nicholas Rivera, Gadi Eisenstein and Ido Kaminer

# Please cite as:

??

# License

All the files distributed with this program are provided subject to the BSD-3-Clause license. A copy of the license is provided.
