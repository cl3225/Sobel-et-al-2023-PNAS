# Sobel-et-al.-2023-PNAS
Codes & data for conducting analysis in Sobel et al. 2023. We use SST from Hadley SST (HadISST_sobel_etal_2023PNAS.nc) as an example, but one can swap the data with SST or track density from CMIP6 or HighResMIP. Analysis codes were originally written by Naomi Henderson for Seager et al. (2019, 2022). 

### Underlying data
- The Jupyter notebook shows example codes for calcuating trend and the North-South; East-West gradient.
- All the underlying data are provided in the respective folder.
- plot_TP works for all the SST trend files as the example below and one can modify plot_TP for track trend files
- ENSO SST and TC composite data are provided in Figure2 folder and can be ploted using plt.pcolormesh.

References:
- Sobel et al. (TBD)
- Seager, R., N. Henderson, and M. Cane, 2022: Persistent Discrepancies between Observed and Modeled Trends in the Tropical Pacific Ocean. J. Climate, 35, 4571–4584, https://doi.org/10.1175/JCLI-D-21-0648.1.
- Seager, R., Cane, M., Henderson, N. et al. Strengthening tropical Pacific zonal sea surface temperature gradient consistent with rising greenhouse gases. Nat. Clim. Chang. 9, 517–522 (2019). https://doi.org/10.1038/s41558-019-0505-x



