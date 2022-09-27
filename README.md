# ahdg-simulations

Each .ipynb contains the source code used to generate the plots generated in the work.
The first cell contains all functions used in the experiements.
In both cases, both ipynbs implement (simCTI,simSISGCG) which are functions that run a single (random) trial of the respective experiement, using utility and learning functions generated from other source code in the block.
The following block in each ipynbs produce the experiements in the work by initilizing initial conditions and functions and then passing it to simCTI/simSISGCG function which run a trial.
Once the desired number of runs are recorded, the data is aggregated in formatted in the plot.
Note that in each case we set the seed using np.random.seed(0), which ensures running the code replicated the plots in the work even though the simulations are random.






This material is based upon work supported by the National Science Foundation under Grant Numbers DEB-2032465 and ECCS-2013779. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
