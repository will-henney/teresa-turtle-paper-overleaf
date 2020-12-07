# Response to referee

We thank the referee for an insightful and useful report.  
Below we quote the referee's report in full, interspersed with our responses. 

> Reviewer's Comments:
> Reviewer: Prof. Albert Zijlstra 

> Comments to the Author

> The paper presents a thorough analysis of the kinematics of one of the more enigmatic planetary nebulae, NGC 6210. This PN is notable for its complex geometry, and unusual for a PN, lacks clear symmetry. The authors have obtained an extensive set of long-slit echelle spectra of several emissions lines, and used these to piece together the 3-d structure of the nebula. It is an impressive piece of work. Clearly, there are shortcomings. The slit spectra do not cover the full nebula but leave gaps, and become patchy in the outer regions. however, in the absence of integral field units at comparable resolution it will be difficult to do much better!

> I have very few comments on the paper.  The discussion makes some simplifying assumptions but they are justifiable and the assumptions are pointed out in the paper. I only request some minor additions or clarifications.

> Minor comments on presentation

> The spectra are shown in Fig. 3 as greyscale.  They have limited contrast and lack  information on the intensity scale, and so it is not possible to estimate line profiles from these.  The authors may want to show representative line profiles, or use a colour representation with a  colour-intensity scale.

We have added a new figure 4, which shows representative one-dimensional line profiles.

> The labeling of slits is comprehensive. But I found myself confused when some of the labels were also used for structural axes, e.g. in Fig. 12 'A' and 'B' refers to axes, but in Fig. 7 which it refers to, these designate slit positions. It is not a show stopper but  could perhaps be .

This is a good point.  We have changed the slit labels to be lower-case, which hopefully should avoid this potential confusion. 

> Axis directions in figures are indicated in E vs W, but none of the figures explicitly state the orientation. It may be helpful to add which direction is east in Fig. 1. (It can of course be deduced from any of the figures which shows coordinates).

We have added a compass to Fig 1, indicating N and E.

> Other comments

> In section 3, the  pattern of the proper motions, with edge curvature and a minimum above the centre  of the nebula has some similarity to the pattern of image distortion in WFPC2 (https://www.stsci.edu/hst/wfpc2/Wfpc2_hand_current/ch5_psf12.html, Fig. 5.17). The current paper does not describe the images, whether the pointing and image rotation was identical, nor how the image distortion was corrected. This should be clarified. I believe that the WFPC2 drizzle images downloaded from the STScI archive are not corrected for distortions but I may be wrong. Note the presence of non-radial vectors, while later in the paper velocities are assumed to be radial.

We have expanded the description of how the images were treated,
which will hopefully make things clearer. 
In particular, the geometric distortion that the referee mentions is automatically dealt with by the AstroDrizzle program. 
The residual uncertainties in these corrections are less than 0.1 pixels and these are included in our systematic error budget. 

With respect to the non-radial vectors, we suspect that these are mainly due to random noise. We have added a short mention of this.

> How are the velocities of the components calculated? Are they the velocity of peak intensity, mid-velocity, etc? An example spectrum with a derived velocity may be useful.

This is now addressed by the new figure 4, which shows results of multiple gaussian fits to the line profiles.  A short description is added to the first paragraph of section 4.

> In Fig. 12, the spatial extent of the emission along the major axis (A) and the minor axis (B) is very nearly the same (14 vs 12 arcsec), whereas in the image of Fig 11 they look more distinct. That raises the question whether all the velocities identified as such belong to the inner-most shell. 

Does the referee mean Fig 1 rather than Fig 11?  It is certainly true that the assignment of components to different structures is subjective to some extent.  Part of the issue here is that the thick blue line that traces the inner shell in the lower panel (axis B) of Fig 12 is not necessarily realistic.  In particular, it extends a few arcsec beyond the measured data in the WSW direction, which makes it look as though the minor axis is longer than it really is (should be only 10 arcsec).  We have redrawn this part of the line, which is only there to guide the eye, so as to more accurately reflect the evidence.
We use a thinner dashed line-style to indicate that it may or may not be a closed shell in that direction (also now referred to in the text). 

> This paper frequently mentions velocity gradients in the analysis, but the numbers are given as velocity amplitude (e.g. +-3 km/s) rather than as a gradient. Either the terminology or the units need updating. 

In most cases, we have kept "gradient" but modified the units. 
For example, "+/- 3 km/s over +/- 7 arcsec". 
In other cases, we have kept the unit as km/s but changed "gradient" to  "differential".

> Last sentence of section 4.2; I did not understand how diffuse versus compact emission can show a spatial velocity gradient. The statement does not seem to  link well with the previous sentence.

It is only at HST resolution that the [O III] appears more diffuse. 
Both are compact at the arcsecond scales of the ground-based spectra. 
We agree however that the statement was poorly phrased.
We have rewritten it as: "the [O III] emission ... seems to arise from the inner surface of the [N II] knots"
We have also added a reference to the new 1D line profile figure
(new Figure 4),
which clearly shows this difference.

> I find the knot complex the hardest to understand. It has a velocity that differs from the rest of structures, has a clear red-blue asymmetry, and is offset from the centre of the nebula in Fig. 1. It gives the impression of an asymmetric toroidal structure.  The abstract stresses the structure as tracing a 180 degree flip of ejection axis 2000 years ago.   I would be quite interested in further discussion.  

We agree that the knot complex is the most puzzling aspect of this nebula.
We have added some additional discussion and address particular points below.
However, we would take issue with the description "an asymmetric toroidal structure".
On the contrary, our analysis implies that the structure is broadly bipolar rather than toroidal.
Since the bipolar axis is close to the line of sight,
the appearance on the HST images is confused by projection effects.

> It can be difficult to measure acccurate kinematic ages for structures near the line of sight. Is there an alternative interpretation possible which does not require the 180 degree change at one point, something not seen in any other structure in the nebula, even those which overlap in age with the knot complex, nor is it known from other PNe? How about non-radial velocity components, as are apparent in Fig 5? 

We agree that the kinematical ages have considerable uncertainty because of this effect and it is worthwhile to interrogate our proposed interpretation and look for alternative explanations.  
We have therefore added a paragraph to the end of section 5.1 that describes a re-analysis of the proper motions under a worst-case scenario for the systematic error in image alignment between epochs.
We find that although this does reduce the contrast between the red and blue knot axes, there is still a significant difference in the average dynamic ages.  It is difficult to see how non-radial motions, if present, might change this result. 
We have added these new results to the figures and tables.


> The reconstruction of Fig. 22 puts the knot complex outside of the lobes while the numbers of Table 2 places them closer to the centre than the lobes (if I understand this correctly). It seems unexpected such dense structures are embedded in a very low density halo. 

In Table 2, we give both the observed and de-projected radii.
It is true that the observed radii of the knot complexes are closer to the center than the lobes,
but the knots tend to be close to the line of sight, so this is not always true for the deprojected radii.
The blue-shifted knots all have deprojected radii < 0.15 pc,
but the redshifted knots have deprojected radii around 0.2 pc,
with some of them seeming to lie outside of the lobes.
However, the uncertainty in the de-projection is high in these cases,
which was not reflected in the Figure (was 22, now 23). 
We have added some error bars to the Figure in order to address this
and have also taken advantage to correct some of the points in that figure,
which were based on an earlier provisional version of the analysis. 


> In Fig. 20, if I were to plot just the crosses, it would give the suggestion of an expanding shell. I have no opinion on this but would be interested in further discussion in the paper. 

Although that figure (now Fig 21) does plot velocity versus distance,
it is not really a "position-velocity" diagram in the observational sense
since both velocity and position have been de-projected 
and information on position angle has been suppressed. 
Hence, a circular arrangement of points on this diagram cannot be 
simply interpreted as an expanding shell.

> As the authors point out, the derived ages assume that velocities have remained constant. Photo-ionization and interacting winds both cause significant velocity changes, and in that case the lines of constant age in Fig 20 can also be the onset of acceleration of gas that may have been ejected earlier. This may complicate the derivation of a detailed mass loss history. It seems to me that the most important conclusion of Sect 5.3 would be whether a  very brief ejection event can be ruled out: such a near-instantaneous event is expected from a common envelope system.

This is a valid point. We have added an extra proviso to section 5.3 that the timescales of mass-loss history might be underestimated if acceleration to the currently observed velocity was delayed significantly after ejection from the star.  This would seem to be less likely to be an issue for the discrete components (lobes and knots), which tend to have higher velocities.  The range of dynamic times of these components spans an interval of at least 2000 years, so we believe that this does indeed rule out a single brief ejection event.  However, within the errors all the lobes and knots might feasible be explained by two ejection events: 3500 years ago and 1500 years ago.  We have added a discussion of this.

> And as a final point: PN lobes have quite a short visibility life. Gesicki et al. (2016) find a few thousand years, similar to the numbers in this paper. That raises the question whether there could be older lobes that have faded beyond visibility. Perhaps the authors wish to comment on this.

Although we cannot rule out this possibility, there is nothing in our data to suggest it.  We point out that we find several lobes to have ages > 3000 years, which is at least twice as old as those studied in the Gesicki paper.  We do find structure (knots) in the halo, but these are kinematically indistinguishable from the rest of the halo and are therefore unlikely to be relics of older lobes. 
