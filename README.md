# Recovering Convection Coefficients from Boundary Measurements

*Applied mathematics research at Beirut Arab University and University of Central Florida, 2012–2017*

I studied how to recover the two components of a convection field inside a two-dimensional domain using measurements taken along its boundary. Small errors in those measurements can be amplified during reconstruction. My research examined how to stabilize the reconstruction and estimate the error introduced by the approximations used to do so.

## Research approach

The reconstruction uses inverse scattering. I focused on a sensitive step in the method: recovering the boundary traces of exponentially growing solutions from the Dirichlet-to-Neumann map, which relates prescribed boundary values to the corresponding normal derivatives.

I analyzed two regularization steps. The first approximates the boundary traces by truncating a power series. The second replaces the Hilbert transform associated with the convection field with the classical Hilbert transform. I derived error estimates for the series truncation and for the two approximations applied together.

## My contributions

I wrote and proved all of the original theorems in the manuscript. The manuscript cites the sources for results from prior work.

I also worked on the numerical implementation using MATLAB and FreeFEM++. The manuscript focuses on the theoretical analysis because my supervisors disagreed on the numerical approach to include. The original code is currently unavailable.

## Collaboration

I conducted this research in collaboration with Toufic El Arwadi and Alexandru Tamasan. Our unpublished manuscript is titled *On the Stability of Recovering the Convection Coefficients from Boundary Data*.
