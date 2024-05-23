# E15
Repository containing code to reproduce figures in the Ervin et al. (2024) paper: Near subsonic solar wind outflow from an active region.

Figure One:
Overview of in situ plasma parameters at Parker from 03/15 to 03/20 showing identification of the streams of interest: the SA region (purple), HCS crossings (blue), and fast wind (pink). We identify the fast wind stream to use as a validation period. All observations are shown at a 30-minute cadence.
  \textit{Panel (a):} {\alf} (blue), sonic (green) and magnetosonic (red) Mach numbers calculated from Parker/FIELDS and SWEAP measurements. The dashed line at 1 shows the cutoff where the wind speed is equal to the Mach number. The y-axis is in a log scale.
  \textbf{
  \textit{Panel (b):} Proton radial (blue), tangential (green), and normal (red) velocity as measured by Parker/SWEAP. The dashed line shows the canonical 500 {\kms} cutoff between fast and slow wind at 1AU. 
  \textit{Panel (c):} The scaled radial magnetic field as measured by Parker/FIELDS. The dashed line at 0 shows the crossing of the neutral line by the spacecraft. 
  \textit{Panel (d):} The scaled proton, alpha particle, electron densities. Proton and alpha densities come from Parker/SWEAP, and the electron density is calculated from QTN following the methods of \citet{Romeo-2023}. The gap in electron density during the SA region is due to issues with the QTN analysis during this period.
  \textit{Panel (e):} Alpha-to-proton abundance ratio from Parker/SWEAP. The dashed lines at 0.015 and 0.045 show the cutoffs for low and high alpha abundance ratios \citep{Kasper-2007, Kasper-2012}.
  }
  \textit{Panel (f):} Alpha-to-proton differential velocity ({\vap} $\mathrm{= v_{\alpha} - v_p}$) normalized by the {\alf} speed ($\mathrm{v_A}$). The dashed line at 1 shows where the differential velocity is equal to the {\alf} speed.

Figure Two: 
\caption{A timeseries of the magnetic, kinetic, and total pressure along with plasma beta for E15. Streams of interest are identified following the convention of Figure~\ref{fig: identification}.
  % The left column shows 03/15 to 03/20 with data at a 30-minute cadence, while the right panel zooms into the SA period.
  \textbf{\textit{Panel (a):} Proton (blue), alpha particle (green), and electron (red) in situ temperatures from SPAN-I and SPAN-E.}
  \textit{Panel (b):} Plasma beta for protons (blue) and electrons (red).
  \textit{Panel (c):} Magnetic (red), ion (blue), and electron (green) pressure (nPa). The dashed green line in electron pressure during the SA region is the period where $N_p$ was substituted for $N_e$ in the pressure calculation due to issues with QTN. 
  \textit{Panel (d):} Comparison of the total pressure (black) and expected pressure red. The expected pressure is a function of radial distance and defined by $P_{expt} = 10^{6.61} \times R^{-3.71}$. We fit the total pressure for the SA region (purple dashed line) and find the following:  $P_{expt} = 10^{6.61} \times R^{-3.74}$.
  % \textit{Right hand panels:} Panels (d) through (f) show the same observables as in the left hand panels, but at full resolution for the SA period of interest from March 16 12:00 to March 17, 2023 06:00.
  }

Figure Three:
   \caption{The SA stream region is highlighted in purple in all panels. 
    \textit{Panel (a):} The trajectory of the spacecrafts in Carrington coordinates. The purple shaded region highlights the propagation of the SA stream and its intersection with the spacecraft trajectories.
    \textit{Panel (a.i):} Inset axes shows the scaled radial magnetic field for Parker, {\SO}, and Wind as a function of source surface longitude. The shaded region shows the neutral line crossing alignment.
    \textit{Panel (b):} {\alf} Mach number ($\mathrm{M_A = v_R/v_A}$) with a dashed line at 1 showing where $\mathrm{v_R = v_A}$. 
    \textit{Panel (c):} Magnetic field observations from Wind/MFI. 
    \textit{Panel (d):} The proton radial velocity from Wind/3DP. The dashed line at 500{\kms} shows the canonical 1AU cutoff between fast and slow wind.
    \textit{Panel (e):} The scaled proton number density ($\mathrm{cm^{-3}}$) from Wind/3DP. The dashed line at 5$\mathrm{cm^{-3}}$ shows the ambient 1AU solar wind density.
    \textit{Panel (f):} Plasma $\beta$ calculated from particle density, temperature, and magnetic field measurements. A dashed line at 1 shows where the magnetic pressure balances the plasma pressure. 
  }

Figure Four:
  \caption{Measurements of particle density and velocity from the HPCA instrument on MMS. The SA region of interest is shown in purple. Other regions where MMS is outside of Earth's magnetosphere and sampling the solar wind are highlighted in yellow.
  \textit{Panel (a):} {\MA} as determined by MMS observations. The dashed line at 1 shows the crossing into sub-{\alfic} plasma.
  \textit{Panel (b):} $\mathrm{H^+}$ velocity measurement.
  \textit{Panel (c):} $\mathrm{H^+}$ density measurement. Typical 1AU $\mathrm{H^+}$ density ($\sim$ 4 $\mathrm{cm}^{-3}$) is shown with a red dashed line.
  \textit{Panel (d):} $\mathrm{He^+/H^+}$ density measurement.
  \textit{Panel (e):} $\mathrm{He^{++}/H^+}$ density measurement.
\textit{Panel (f):} Plasma beta for $\mathrm{H^+}$. The dashed line at 1 shows where the magnetic and kinetic pressure components are balanced.
  }

Figure Five:
  \caption{
    Turbulence parameters for Parker E15 computed over 20 minute non-overlapping windows following the description in Section~\ref{sec: turb-spectra} from SWEAP/SPAN-I and FIELDS measurements. The SA region is identified in purple, FSW region in pink, and the HCS crossings are shown in light blue. The two intervals (during the SA period) used for the PSD calculation in Figure~\ref{fig: turbulence_psd} are labeled as \lq{}Interval One\rq{} and \lq{}Interval Two\rq{}.
  \textit{Panel (a):} Elasser variables ({\kms}) showing the forward ({\zp}) and backward ({\zm}) modes in blue and orange respectively.
  \textit{Panel (b):} Velocity ({\dv}) and magnetic field ({\db}) fluctuations calculated by subtracting the measured velocity and magnetic fields from the background field.
  \textit{Panel (c):} The angle between the magnetic field and velocity in the spacecraft frame ({\angvb}).
  \textit{Panel (d):} Cross helicity ({\sigmac}) versus residual energy ({\sigmar}) for this encounter. FSW is shown in pink squares, SA wind in purple diamonds, and near-HCS wind in blue triangles. All other wind periods are in grey circles. The dashed circle gives the outline for our expected result that {\sigmac} + {\sigmar} $\leq$ 1. 
  }

Figure Six:
  \caption{PSD of the turbulence parameters shown in Figure~\ref{fig: turbulence} for the SA period of interest. We split the period into three intervals (as seen in Figure~\ref{fig: turbulence}) and the PSD for each interval are shown in the left, middle, and right columns respectively.
  \textit{Top row:} Trace power spectra of the {\elas} variables ($\mathrm{\mathbf{z}^{\pm}}$) and fluctuations ({\dv} and {\db}) for interval one (panel (a)), interval two (panel (c)), and interval three (panel (e)). Fitted spectra for both {\zp} and {\zm} are shown in black \citep{Zank-2017, Zank-2022, Zhao-2022}. $f_t$ is the transition frequency from nonlinear to {\alfic} interaction dominated regions.
  \textit{Bottom row:} PSD of the inward ({\zm}) and outward ({\zp}) propagating {\elas} variables showing spectral fits. The dashed line separates the two regimes ($f^{-1}$ and $f^{-1.5}$) of the {\zp} spectra, \textbf{where the $f^{-1}$ portion at small frequencies corresponds to the energy containing range.}
  }

Figure Seven:
  \caption{Comparison of spacecraft trajectory and the SA stream with CME propagation based on a simplistic ice cream cone model \citep{Na-2017} in the inertial coordinate frame. \textbf{Each panel shown is a still from an animation showing the evolution of the SA stream and CME during the entire Encounter 15 period \citep{Ervin-2024-CME}. The animation spans from March 15 to April 3, 2024 lasting 3:02 and is annotated identically to the panels in this Figure with the addition of timestamps along each spacecraft trajectory.} The CME trajectory is shown in pink, the SA stream is in purple, and spacecraft trajectories are in black (Parker), blue (Solar Orbiter), and green (1AU). The stars in each panel indicate the location of the spacecraft at each time step.
  \textit{Panel (a):} AIA 193{\AA} image from March 15 06:48 showing the AR source of the CME eruption. 
  \textit{Panel (b):} March 15 07:00 showing the onset of the CME eruption.
  \textit{Panel (c):} March 15 10:30 showing the extent of the CME eruption.
  \textit{Panel (d):} March 16 18:00 showing Parker flying through the SA stream. 
  \textit{Panel (e):} March 24 12:00 showing {\SO} flying through the SA stream.
  \textit{Panel (f):} March 28 00:00 showing 1AU spacecraft flying through the SA stream.
  }

Figure Eight:
  \caption{Modeling results compared with in situ measurements and calculations with ballistic propagation to show data as a function of source surface longitude. The raw data is overlaid with data binned by 1{\degree} in source surface longitude (black).
    \textit{Panel (a):} PFSS model showing the modeled HCS (white) and estimated photospheric footpoints. We ballistically propagate the Parker trajectory, colored by measured polarity, to the source surface (2.5 {\Rsun}) using a varying solar wind speed (the SPAN-I $\mathrm{v_R}$). The modeled field lines, colored by modeled polarity, connect the spacecraft trajectory to the photospheric footpoints. We overlay this model on a Carrington map produced from SDO/AIA 193${\AA}$ images. 
    \textit{Panel (a.i):} FSW footpoints as pink squares overlaid on a SDO/AIA image from the estimated time when the plasma left the Sun based on the measured wind velocity and location of the spacecraft.
    \textit{Panel (a.ii):} GONG photospheric radial magnetic field with the SA footpoints overlaid as black diamonds.
    \textit{Panel (b):} {\alf} Mach number ({\MA}) as a function of source surface longitude in 1{\degree} bins. The dashed line at 1 shows where wind becomes sub-{\alfic}.
    \textit{Panel (c):} The scaled radial magnetic field as measured by Parker/FIELDS. The dashed line at 0 shows the crossing of the neutral line by the spacecraft.
    \textit{Panel (d):} The absolute photospheric radial magnetic field ($\mathrm{|B_{r, 0}|}$) based on estimated footpoints in panel (a). 
    \textit{Panel (e):} The relative intensity of the photospheric footpoints ($\mathrm{I_0}$) based on estimated footpoints in panel (a). This can be thought of as a proxy for the temperature of the plasma at the footpoint (darker/lower is colder).
    \textit{Panel (f):} Magnetic expansion factor ($\mathrm{f_{ss}}$) between the source surface ({\Rss} = 2.5 {\Rsun}) and photosphere (1.0 {\Rsun}) calculated following Equation~\ref{eqn: fss}. 
    \textit{Panel (g):} Photospheric footpoints in longitude (red) and latitude (blue) for Parker calculated using a PFSS model. Jumps in footpoints are indicative of a change in the structure Parker is magnetically connected to.
  }

Figure Nine:
  \caption{A comparison of model and in situ radial magnetic field polarities. \textit{Panel (a):} A comparison of the polarities measured by Parker and {\SO} with the predicted polarity from the PFSS and MHD solution. \textit{Panel (b):} A radial cut of the MHD solution at the source surface height (2.5{\Rsun}). The modeled HCS from the PFSS and MHD solutions are shown in solid black and dashed black respectively. The Parker trajectory is shown and colored blue (red) for negative (positive) polarity corresponding to the radial magnetic field measured by Parker/FIELDS.}

Figure Ten:
   \caption{A comparison of observables sampled from the MHD model along the trajectory of Parker (red) in comparison to Parker in situ measurements. We compare the proton radial velocity (panel (a)), scaled number density (panel (b)), and scaled radial magnetic field (panel (c)). In panel (c), we also show the radial position of the spacecraft (AU) in grey. The MHD results are in red. The Parker in situ observations are overlaid with binned data by 1{\degree} in longitude (black).}

Figure Eleven:
\caption{A comparison of how errors in the ballistic propagation and PFSS modeling can effect the resulting footpoints estimations for the wind streams of interest. The \lq{}best\rq{} PFSS model, the one used in this study, is shown in grey in all panels. The SA and FSW footpoints are shown by purple diamonds and pink squares as in Figure~\ref{fig: ar-detection}.
  \textit{Panel (a):} Estimated footpoints with $\pm 20$ {\kms} noise added to the input velocity used for ballistic propagation (pink) compared with the model used (grey).
  \textit{Panel (b):} Estimated footpoints with $\pm 5^{\circ}$ error added to output of the ballistic propagation ballistic propagation (pink) compared with the model used (grey).
  \textit{Panel (c):} Estimated footpoints produced by varying the source surface height of the PFSS model. This study uses the results from {\Rss} = 2.5{\Rsun} shown in grey.
  }

Figure Twelve:
\caption{An example of the finite velocity grid of SPAN-I and VDF for the SA stream (March 16, 2023 14:00). Left panel: Non-uniform 3D velocity grid showing the points over which a VDF is measured. Right panel: VDF contours summed and collapsed onto the $\theta$ plane.}

Figure Thirteen:
\caption{A comparison of the PSD for a velocity timeseries (200 {\kms}) with varying noise levels ({\dv}). Time series of 200 {\kms} speed with varying levels of random noise applied: 5 {\kms} (blue), 10 {\kms} (green), and 60 {\kms} (red). The offset between each timeseries for visualization purposes. \textit{Panel (b):} PSD of each of the velocity timeseries in panel (a) colored in the same manner.}

Figure Fourteen:
\caption{A comparison of the PSD for varying noise levels (5, 25, and 60 {\kms}) with the computed PSD for the {\zm} variable from Figure~\ref{fig: turbulence_psd} for each of the three intervals. Each panel shows the PSD of each of the velocity timeseries from Figure~\ref{fig: noise-psd} colored in the same manner.}
   
