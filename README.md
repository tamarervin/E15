# E15
Repository containing code to reproduce figures in the Ervin et al. (2024) paper: Near subsonic solar wind outflow from an active region 
[![DOI](https://zenodo.org/badge/805028585.svg)](https://zenodo.org/doi/10.5281/zenodo.11266455)


# Figures

## Figure One:
Overview of in situ plasma parameters at Parker from 03/15 to 03/20 showing identification of the streams of interest: the SA region (purple), HCS crossings (blue), and fast wind (pink). We identify the fast wind stream to use as a validation period. All observations are shown at a 30-minute cadence.

- _Panel (a)_: Alfvén (blue), sonic (green), and magnetosonic (red) Mach numbers calculated from Parker/FIELDS and SWEAP measurements. The dashed line at 1 shows the cutoff where the wind speed is equal to the Mach number. The y-axis is in a log scale.
- _Panel (b)_: Proton radial (blue), tangential (green), and normal (red) velocity as measured by Parker/SWEAP. The dashed line shows the canonical 500 km/s cutoff between fast and slow wind at 1AU.
- _Panel (c)_: The scaled radial magnetic field as measured by Parker/FIELDS. The dashed line at 0 shows the crossing of the neutral line by the spacecraft.
- _Panel (d)_: The scaled proton, alpha particle, electron densities. Proton and alpha densities come from Parker/SWEAP, and the electron density is calculated from QTN following the methods of Romeo et al. (2023). The gap in electron density during the SA region is due to issues with the QTN analysis during this period.
- _Panel (e)_: Alpha-to-proton abundance ratio from Parker/SWEAP. The dashed lines at 0.015 and 0.045 show the cutoffs for low and high alpha abundance ratios (Kasper et al. 2007, 2012).
- _Panel (f)_: Alpha-to-proton differential velocity ($v_{ap} = v_{\alpha} - v_p$) normalized by the Alfvén speed ($v_A$). The dashed line at 1 shows where the differential velocity is equal to the Alfvén speed.

## Figure Two:
A timeseries of the magnetic, kinetic, and total pressure along with plasma beta for E15. Streams of interest are identified following the convention of Figure 1.

- _Panel (a)_: Proton (blue), alpha particle (green), and electron (red) in situ temperatures from SPAN-I and SPAN-E.
- _Panel (b)_: Plasma beta for protons (blue) and electrons (red).
- _Panel (c)_: Magnetic (red), ion (blue), and electron (green) pressure (nPa). The dashed green line in electron pressure during the SA region is the period where $N_p$ was substituted for N_e in the pressure calculation due to issues with QTN.
- _Panel (d)_: Comparison of the total pressure (black) and expected pressure (red). The expected pressure is a function of radial distance and defined by $P_{expt} = 10^{6.61} \times R^{-3.71}$. We fit the total pressure for the SA region (purple dashed line) and find the following: $P_expt = 10^{6.61} \times R^{-3.74}$.

## Figure Three:
The SA stream region is highlighted in purple in all panels.

- _Panel (a)_: The trajectory of the spacecrafts in Carrington coordinates. The purple shaded region highlights the propagation of the SA stream and its intersection with the spacecraft trajectories.
  - _Panel (a.i)_: Inset axes show the scaled radial magnetic field for Parker, Solar Orbiter, and Wind as a function of source surface longitude. The shaded region shows the neutral line crossing alignment.
- _Panel (b)_: Alfvén Mach number ($M_A = v_R/v_A$) with a dashed line at 1 showing where $v_R = v_A$.
- _Panel (c)_: Magnetic field observations from Wind/MFI.
- _Panel (d)_: The proton radial velocity from Wind/3DP. The dashed line at 500 km/s shows the canonical 1AU cutoff between fast and slow wind.
- _Panel (e)_: The scaled proton number density ($cm^{-3}$) from Wind/3DP. The dashed line at 5 $cm^{-3}$ shows the ambient 1AU solar wind density.
- _Panel (f)_: Plasma beta calculated from particle density, temperature, and magnetic field measurements. A dashed line at 1 shows where the magnetic pressure balances the plasma pressure.

## Figure Four:
Measurements of particle density and velocity from the HPCA instrument on MMS. The SA region of interest is shown in purple. Other regions where MMS is outside of Earth's magnetosphere and sampling the solar wind are highlighted in yellow.

- _Panel (a)_: $M_A$ as determined by MMS observations. The dashed line at 1 shows the crossing into sub-Alfvénic plasma.
- _Panel (b)_: $H^+$ velocity measurement.
- _Panel (c)_: $H^+$ density measurement. Typical 1AU $H^+$ density (~4 $cm^{-3}$) is shown with a red dashed line.
- _Panel (d)_: $He^+$ / $H^+$ density measurement.
- _Panel (e)_: $He^{++}$ / $H^+$ density measurement.
- _Panel (f)_: Plasma beta for $H^+$. The dashed line at 1 shows where the magnetic and kinetic pressure components are balanced.

## Figure Five:
Turbulence parameters for Parker E15 computed over 20-minute non-overlapping windows following the description in Section 2 from SWEAP/SPAN-I and FIELDS measurements. The SA region is identified in purple, FSW region in pink, and the HCS crossings are shown in light blue. The two intervals (during the SA period) used for the PSD calculation in Figure 6 are labeled as "Interval One" and "Interval Two".

- _Panel (a)_: Elasser variables (km/s) showing the forward ($z^+$) and backward ($z^-$) modes in blue and orange respectively.
- _Panel (b)_: Velocity ($\delta v$) and magnetic field ($\delta b$) fluctuations calculated by subtracting the measured velocity and magnetic fields from the background field.
- _Panel (c)_: The angle between the magnetic field and velocity in the spacecraft frame ($\theta_{vB}$).
- _Panel (d)_: Cross helicity ($\sigma_c$) versus residual energy ($\sigma_r$) for this encounter. FSW is shown in pink squares, SA wind in purple diamonds, and near-HCS wind in blue triangles. All other wind periods are in grey circles. The dashed circle gives the outline for our expected result that $\sigma_c + \sigma_r$ ≤ 1.

## Figure Six:
PSD of the turbulence parameters shown in Figure 5 for the SA period of interest. We split the period into three intervals (as seen in Figure 5) and the PSD for each interval is shown in the left, middle, and right columns respectively.

- _Top row_: Trace power spectra of the Elasser variables ($z^\pm$) and fluctuations ($\delta v$ and $\delta b$) for interval one (panel (a)), interval two (panel (c)), and interval three (panel (e)). Fitted spectra for both $z^+$ and $z^-$ are shown in black (Zank et al. 2017, 2022; Zhao et al. 2022). f_t is the transition frequency from nonlinear to Alfvénic interaction dominated regions.
- _Bottom row_: PSD of the inward ($z^-$) and outward ($z^+$) propagating Elasser variables showing spectral fits. The dashed line separates the two regimes ($f^{-1}$ and $f^{-1.5}$) of the $z^+$ spectra, where the $f^{-1}$ portion at small frequencies corresponds to the energy-containing range.

## Figure Seven:
Comparison of spacecraft trajectory and the SA stream with CME propagation based on a simplistic ice cream cone model (Na et al. 2017) in the inertial coordinate frame. Each panel shown is a still from an animation showing the evolution of the SA stream and CME during the entire Encounter 15 period (Ervin et al. 2024-CME). The animation spans from March 15 to April 3, 2024, lasting 3:02 and is annotated identically to the panels in this Figure with the addition of timestamps along each spacecraft trajectory. The CME trajectory is shown in pink, the SA stream is in purple, and spacecraft trajectories are in black (Parker), blue (Solar Orbiter), and green (1AU). The stars in each panel indicate the location of the spacecraft at each time step.

- _Panel (a)_: AIA 193Å image from March 15 06:48 showing the AR source of the CME eruption.
- _Panel (b)_: March 15 07:00 showing the onset of the CME eruption.
- _Panel (c)_: March 15 10:30 showing the extent of the CME eruption.
- _Panel (d)_: March 16 18:00 showing Parker flying through the SA stream.
- _Panel (e)_: March 24 12:00 showing Solar Orbiter flying through the SA stream.
- _Panel (f)_: March 28 00:00 showing 1AU spacecraft flying through the SA stream.

## Figure Eight:
Modeling results compared with in situ measurements and calculations with ballistic propagation to show data as a function of source surface longitude. The raw data is overlaid with data binned by 1° in source surface longitude (black).

- _Panel (a)_: PFSS model showing the modeled HCS (white) and estimated photospheric footpoints. We ballistically propagate the Parker trajectory, colored by measured polarity, to the source surface (2.5 $R_{\odot}$ ) using a varying $v_R$. We show the result from using a constant $v_R$ for reference in black. The PFSS model results are shown in the background.
- _Panel (b)_: Normalized proton number density ($cm^{-3}$) as a function of source surface longitude. The dashed horizontal line shows the ambient 1AU density.
- _Panel (c)_: Electron temperature (eV) calculated from SPAN-E measurements.
- _Panel (d)_: Alpha-to-proton abundance ratio. Dashed horizontal lines at 0.015 and 0.045 give the cutoffs for low and high alpha abundance (Kasper et al. 2007, 2012).

## Figure Nine:
A comparison of model and in situ radial magnetic field polarities.

- _Panel (a)_: A comparison of the polarities measured by Parker and Solar Orbiter with the predicted polarity from the PFSS and MHD solution.
- _Panel (b)_: A radial cut of the MHD solution at the source surface height (2.5 $R_{\odot}$ ). The modeled HCS from the PFSS and MHD solutions are shown in solid black and dashed black respectively. The Parker trajectory is shown and colored blue (red) for negative (positive) polarity corresponding to the radial magnetic field measured by Parker/FIELDS.

## Figure Ten:
A comparison of observables sampled from the MHD model along the trajectory of Parker (red) in comparison to Parker in situ measurements. We compare the proton radial velocity (panel (a)), scaled number density (panel (b)), and scaled radial magnetic field (panel (c)). In panel (c), we also show the radial position of the spacecraft (AU) in grey. The MHD results are in red. The Parker in situ observations are overlaid with binned data by $1^{\circ}$ in longitude (black).

## Figure Eleven:
A comparison of how errors in the ballistic propagation and PFSS modeling can effect the resulting footpoints estimations for the wind streams of interest. The "best" PFSS model, the one used in this study, is shown in grey in all panels. The SA and FSW footpoints are shown by purple diamonds and pink squares as in Figure 8.

- _Panel (a)_: Estimated footpoints with $\pm 20$ km/s noise added to the input velocity used for ballistic propagation (pink) compared with the model used (grey).
- _Panel (b)_: Estimated footpoints with $\pm 5^{\circ}$ error added to output of the ballistic propagation ballistic propagation (pink) compared with the model used (grey).
- _Panel (c)_: Estimated footpoints produced by varying the source surface height of the PFSS model. This study uses the results from $R_{ss}$ = 2.5 $R_{\odot}$ shown in grey.
  
## Figure Twelve:
An example of the finite velocity grid of SPAN-I and VDF for the SA stream (March 16, 2023 14:00). Left panel: Non-uniform 3D velocity grid showing the points over which a VDF is measured. Right panel: VDF contours summed and collapsed onto the $\theta$ plane.

## Figure Thirteen:
A comparison of the PSD for a velocity timeseries (200 km/s) with varying noise levels ({\dv}). 

- _Panel (a)_: Time series of 200 km/s speed with varying levels of random noise applied: 5 km/s (blue), 10 km/s (green), and 60 km/s (red). The offset between each timeseries for visualization purposes. 
- _Panel (b)_: PSD of each of the velocity timeseries in panel (a) colored in the same manner.

## Figure Fourteen:
A comparison of the PSD for varying noise levels (5, 25, and 60 km/s) with the computed PSD for the $z^-$ variable from Figure 6 for each of the three intervals. Each panel shows the PSD of each of the velocity timeseries from Figure 13 colored in the same manner.


