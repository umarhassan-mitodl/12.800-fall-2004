---
content_type: page
description: ''
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
title: Lecture Notes
uid: e9bc603b-ee9e-6391-f123-9ed7bb379805
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LEC #
{{< thclose >}}
{{< thopen >}}
CLASSROOM ACTIVITIES
{{< thclose >}}
{{< thopen >}}
NOTES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Introduced the Instructor.  
  
Gave handout on kinematics ({{% resource_link 7a879633-aea6-163d-0867-6a971446da9f "PDF" %}}).  
  
Went over the class description and the course syllabus.  
  
Defined a fluid with respect to its mode of resistance to applied forces and made an effort to demonstrate what makes the study of fluid dynamics hard/challenging/interesting.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 6f8470e7-1dfe-1057-ef5a-668cd6aac83c "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
_Maths primer_  
  
Briefly covered vector and tensor notation, vector and tensor algebra, wave kinematics, eigenvectors/values, dimensional analysis, and scale analysis.  
  
Handout on dimensional analysis from Jim Price ([PDF - 1.5 MB](/courses/res-12-001-topics-in-fluid-dynamics-dimensional-analysis-the-coriolis-force-and-lagrangian-and-eulerian-representations-fall-2004/resources/essay1)).
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link e03fe579-9e40-06d1-1b87-627d5264561b "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
New Kinematics of Fluid Flow from Jim Price ([PDF - 2.6 MB](/courses/res-12-001-topics-in-fluid-dynamics-dimensional-analysis-the-coriolis-force-and-lagrangian-and-eulerian-representations-fall-2004/resources/essay3)).  
  
Introduced Lagrangian and Eulerian frameworks giving pros and cons for each.  
  
Derived the material derivative (time rate of change following the flow in an Eulerian context). Introduced trajectories, streaklines, and streamlines.  
  
Technology conspired to foil two demos (one mpeg movie and one video).
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link f5d398ec-f0c2-ef2f-33bb-e61fa633f4d7 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
Introduced the Cauchy-Stokes decomposition theorem.  
  
Quantified how fluid motion may be broken down into translation, dialation, and rigid rotation.  
  
Defined the linear strain rate, the shear strain rate, and the rigid rotation rate.  
  
Showed that by a special choice of initial axes, the mathematical impact of shear strain rate is removed, and only dialation and rigid rotation remain.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 7bb9e945-4055-34b3-6776-cbe404a8f839 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
Briefly reviewed Lagrangian vs. Eulerian, the material derivative, rates of strain (in the context of viscosity), and the Cauchy-Stokes decomposition theorem.  
  
Defined the velocity gradient tensor and showed how it can be broken down into the sum of the strain rate tensor and the rotation rate tensor.  
  
Gave some kinematic examples of how each component of the velocity gradient tensor deforms fluid blobs (G=\[4 4;2 8\] ({{% resource_link c67ade14-adf4-8743-a846-37f8b18d0d3e "ZIP" %}}), G=\[-1 6;1 -1\] ({{% resource_link 6e62e1db-2d9c-ff5f-8224-bdbb2f3f9ed4 "ZIP" %}}), G=\[-1 6;6 -1\] ({{% resource_link f3f6f35f-c645-a026-a78d-e221c4ccda2e "ZIP" %}}), G=\[-3 6;-6 -1\] ({{% resource_link abd2c2a1-1416-7cc9-a0b8-98fa3f8d3256 "ZIP" %}}), these are zipped pdf files).  
  
Gave a real-world example of shear in a rock.  
  
Introduced the linear uncertainty propagator and derived how one finds the directions at initial time that evolve into the directions of the principal axes of the final time ellipse, and proved that the initial time directions form an orthonormal basis. Followed up the maths with some pictures of circles evolving into ellipses.  
  
Introduced singular value decomposition as a shortcut to finding the eigenvectors and values of MM' and M'M.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 0761927d-52c9-d196-c9a8-a11bbd62f45a "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Spent a little more time on singular vectors, drawing the analogy between circular blobs of fluid evolving into elliptical blobs of fluid, and circular blobs of state space evolving into elliptical blobs of state space.  
  
Discussed extensive and intensive properties, derived various forms of the Reynolds Transport Theorem to express Lagrangian rates of change of extensive properties in an Eulerian framework.  
  
Pseudo-derived the divergence theorem. Trivially derived the continuity equation using the Reynolds Transport Theorem.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 6142530d-9f01-4a62-0edd-acc06da975b6 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
Distributed notes deriving the linear uncertainty propagator for a generic flow.  
  
Briefly reviewed the motivation for spending all that time on circles evolving into ellipses (essentially to help us better understand the derivation and interpretation of frictional terms in various equations we will derive).  
  
Introduced the Boussinesq and anelastic approximations for the continuity equation, Showed that Boussinesq results in changing the expression of conservation of mass to one of conservation of volume. The anelastic approximation is a bit more difficult to interpret, and seems to boil down to conserving some mass and some volume.  
  
Started the derivation of the momentum equations by applying the Reynolds Transport Theorem to the Lagrangian expression for conservation of mass. The sum of the forces on the right hand side become the body force (gravity) and the surface force (stress).  
  
Using the divergence theorem, converted the area integral of the flux of stress for the surface force to a volume integral of the divergence of stress.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link db2c647b-8092-6c8b-2c6e-dc3577b65f88 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
Pseudo-derived the simple, linear constitutive equation of Stokes and provided interpretations and implications for each term.  
  
Plugged the resulting stress tensor into the momentum equations and its divergence resulted in the production of the Navier-Stokes equations.  
  
Attempted to interpret each of the terms in the equation.  
  
Obtained the Euler equations by ignoring viscosity and the Boussinesq approximation by assuming the mean density is much greater than perturbations to the mean.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link af868588-b669-fd2d-852a-b812b23df83d "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
Recap of the previous week, focusing on the Boussinesq approximation and the derivation of the Navier-Stokes equations.  
  
Derived the energy conservation equations starting from the Lagrangian form.  
  
Used the RTT on the LHS and expanded the work rate and heating rate terms of the RHS into volume and area integrals. Then used the divergence theorem to turn the area integrals into volume integrals. Obtained an expression for internal energy by subtracting off the mechanical energy terms, and expressed the internal energy in terms of temperature. Applied the Boussinesq approximation to the resulting heat equation.  
  
Notes (with some typos) are available for download ({{% resource_link b2f2a20e-fc8f-36b4-b5b8-2ee4a6f039e1 "PDF" %}}).
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link d510167b-c5cc-ee17-5ad6-d6345039892a "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
Returned to Boussinesq arguments about the energy equation. Demonstrated that the pressure correction term need not be negligible under Boussinesq, and derived potential temperature as a means to circumvent the problem. Produced the potential temperature form of the heat equation. Followed the KC04 derivation of the second law of thermodynamics. Summarized our derivations of continuity, momentum, energy, and entropy for

1.  no approximation,
2.  Boussinesq approximation, and
3.  Euler fluid


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link d9d0ff4b-4084-467d-756b-69f612327c3d "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
Guest lecture by Jon Moskaitis.  
  
Derived the Bernoulli form by noting that the gravity body force can be written in terms of a potential and that if we assume that density is constant or only a function of pressure, then the pressure gradient force can also be written as a potential. Showed results for steady flow, steady irrotational flow, and irrotational flow. Defined the velocity potential and gave situations in which the velocity potential and/or the stream function obey Laplace's equation.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link dbdc2bbc-8825-b710-d919-9f1e7f435a1d "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
Another guest lecture by Jon Moskaitis.  
  
Introduced vorticity by analyzing a rotational vortex and an irrotational vortex.  
  
Defined circulation, introduced Stokes theorem, and gave an arm waving proof for Stokes theorem. Showed that for a rotational vortex, vorticity is constant and therefore circulation scales with radius (for an area that bounds the vortex). For an irrotational vortex, vorticity is zero everywhere except at the center of the vortex (where vorticity is infinite). The circulation associated with the vortex is constant for an area that bounds the center of the vortex, but zero for any area that does not bound the center of the vortex.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 6411e619-b5fb-45f1-32cc-9ac1b83d4d14 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
Long discussion on how to model interacting point vortices. Derived Kelvin's Circulation Theorem. Discussed how the theorem breaks down if the assumptions of

1.  inviscid,
2.  barotropic, and
3.  conservative body forces break down


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 742b3656-764a-3d3a-60d9-1f7d7ddd539c "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
Introduced the Helmholtz vortex theorems and provided arm waving proofs.  
  
Derived the incompressible, barotropic (and baroclinic) vorticity equations by taking the curl of the associated momentum equation.  
  
Explained the stretching and tilting terms.  
  
Showed that vorticity is constant for the additional constraints of 2d and inviscid.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 39ab5419-814f-2e2e-3eff-bf2a84967f95 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
Showed how to transform vectors between rotating and inertial frames. Used the transformation to alter the momentum equations to account for the earth's rotation.  
  
Described that the centrifugal force acts to deform the shape of the earth so that the tangential component of the centrifugal force balances the tangential component of gravity. Gravity is redefined as the sum of gravity and the centrifugal force. The coriolis force is introduced and the impact of the coriolis force is demonstrated in a series of movies and demonstrations.  
  
A nice writeup on the Coriolis force from Jim Price ([PDF - 2.2 MB](/courses/res-12-001-topics-in-fluid-dynamics-dimensional-analysis-the-coriolis-force-and-lagrangian-and-eulerian-representations-fall-2004/resources/essay2)).
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 31fabd09-9b71-0f22-3c9a-10806e955db9 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Began by deriving the period of inertial circles and comparing it with the period of the rotating frame.  
  
Introduced the locally Cartesian coordinate system and discussed the inclusion of the curvature terms.  
  
Wrote down the momentum equations on a rotating sphere is the locally Cartesian coordinate system.  
  
Modified the vorticity equation obtained in the first half of the class to include the earth's rotation. Ended up with a stretching/tilting term for planetary vorticity.  
  
Modified Kelvin's circulation theorem to include the earth's rotation. An expression for conservation of absolute vorticity is obtained.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 0013f63d-f053-0942-a410-d7466f551ea7 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
Recapped the momentum and vorticity equations in the rotating frame.  
  
Did some scaling on the momentum equations to put them in a more friendly form.  
  
Started talking about modeling constraints and the necessity of parameterizing the impact of eddy-scale mixing, and promptly reinserted horizontal "viscosity" back into our simplified momentum equations. After all that worrying about viscosity, we ignored it in order to start looking at some balances in the simplified momentum equations.  
  
Started by revisiting the inertial oscillation, and then moved on to geostrophy.  
  
Showed that one needed a small Rossby number in order for the geostrophic balance to be justified.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 63da77dc-b61a-8b0e-ce8f-3d028f81bc53 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
Produced the height-gradient form of the geostrophic velocity equations and provided many examples of geostrophy by looking at 500mb height maps.  
  
Produced the gradient wind equation and showed examples of gradient wind (and its difference from the geostrophic wind) in 500mb height maps.  
  
Solved the gradient wind equation (a quadratic equation), and plotted solutions as a function of "Rossby number" and a non-dimensional pressure gradient term.  
  
Demonstrated in maths and force diagrams the various solutions (and non-solutions) to the equation. Ended with cyclostrophic flow.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 89d0372f-d8c6-d020-79ee-402c0ba994d6 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
Recapped inertial circles, geostrophy, gradient wind, and cyclostrophic wind.  
  
Next introduced the isallobaric wind (ageostrophic wind found at the entrance and exit regions of jets) and gave some observation examples.  
  
Brought back friction, introduced the Ekman number, and discussed the Ekman balance (a balance between the pressure gradient force, the Coriolis force, and the frictional force). Showed examples in observations.  
  
Moved to the vorticity equations, and derived the Taylor-Proudman theorem by assuming inviscid, barotropic, small Rossby number flow.  
  
Examples of the vertical rigidity of rotating fluids were given in two movies.  
  
The Taylor column result was discussed, and a movie was provided.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link a23d92d6-e97a-2f27-65c2-064939a30b2c "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
Recapped inertial circles, geostrophy, gradient wind, cyclostrophic wind, isallobaric wind, Ekman balance, Taylor-Proudman, and Taylor columns.  
  
Derived the thermal wind relationship from the vorticity equation assuming small Rossby number and no viscosity (but allowing for baroclinicity).  
  
Explained how tilting of planetary vorticity balances the vorticity generated by sloping density surfaces trying to flatten out. Recast in terms of temperature gradient, and showed examples in atmospheric observations and in the lab (see hadley.mpeg).  
  
Introduced boundary layers and showed that under the influence of rotation, the thickness of planetary boundary layers does not grow with time. The diffusion of vorticity in the boundary is balanced by the tilting of planetary vorticity.  
  
Derived an expression for mass transport in the ocean's surface boundary layer in terms of the applied atmospheric wind stress.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 7a1125db-ddc6-2446-6eec-36973022e0c5 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
Started with a quick recap of the mass transport in the Ekman layer, and provided an arm-waving description of the velocity structure with depth within the Ekman layer. An Ekman balance-like argument produced an Ekman spiral.  
  
The wind stress patterns in the northern hemisphere outside of the tropics result in convergence of mass in the mid-latitudes, and divergence of mass in the high latitudes. Continuity results in Ekman pumping and suction out of and into the Ekman layer.  
  
Used Kelvin's circulation theorem and a desire for a steady state solution, it was argued that the only way the ocean interior can respond is by moving fluid to an area of lower planetary vorticity (equatorward). The magnitude of this Sverdrup transport was quantified in terms of the curl of the surface wind stress.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 827e1203-7f63-fbf7-14ba-ebb84bf9b0f5 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
_Waves Primer_  
  
Various forms of wave equations, definitions of wave number and frequency, derivations of phase speed and group velocity, and a quick discussion on dispersion relationships. See contents of waves.zip for movies showing how different wave numbers and frequencies impact phase and group speed. Primer notes and associated figures are available (Waves.pdf, wavefigs.pdf).
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 6aae0ce5-8d9d-0548-af48-2b517ffe591c "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
Derived the fixed depth, barotropic, inviscid vorticity equation starting from Kelvin's circulation theorem. Linearized the equation using Reynold's averaging, put linearized equation in terms of streamfunction, assumed a wavy (normal mode) solution, and solved for the dispersion relation.  
  
Found that the phase speed of the resulting Rossby waves is westward relative to the mean zonal flow, and that the group velocity could be westward or eastward depending upon the wave number.  
  
Returned to the linearization of the governing equation and added a y-dependence to the mean zonal velocity, which resulted in a y-dependence in the wave amplitude of the assumed normal mode solution.  
  
Began to discuss the stability implications.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link bd93c290-3904-0c13-dfc0-b42ab1a84ccb "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
Began by recapping the "recipe" for producing dispersion relations and performing stability analysis (identify equations, linearize, assume a wavy solution, grind through the algebra, analyze results).  
  
Discussed stability analysis in the context of the fixed depth, barotropic vorticity equations with a time mean zonal flow that varies in the meridional direction.  
  
Sketched profiles of the coriolis parameter and observed mean relative vorticity as a function of latitude, and showed that the necessary condition for barotropic instability exists in the tropics.  
  
Sketched an idealized shear flow to show the mechanisms by which the perturbations grow, and related to both generic shear instability and to baroclinic instability.  
  
Ended class by deriving the shallow water equations.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 7d3888b5-0457-c872-8fb4-751569f20770 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}
Derived the shallow water potential vorticity equation from the shallow water momentum and continuity equations.  
  
Provided some examples of how the trade-offs between relative vorticity, coriolis parameter, and fluid depth can be described in terms of potential vorticity conservation or absolution circulation conservation.  
  
Made the point that the "depth" term in the potential vorticity equation can be interpreted in many ways.  
  
Demonstrated that westerly flow is stable to small perturbations, and then demonstrated that such perturbations can be generated by topography.  
  
A laboratory example was given in topo\_beta.mpg. Derived the shallow water Rossby wave dispersion relation by making a quasi-geostrophic assumption, and showed that it is qualitatively identical to the fixed depth dispersion relation. The primary difference is that the Rossby radius of deformation that finds its way into the shallow water dispersion relation sets a spatial scale for the system and does not allow infinitely fast waves.
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
24
{{< tdclose >}}
{{< tdopen >}}
A day of gravity waves. Started from the shallow water equations sans rotation to produce the gravity wave dispersion relation, then added rotation back to the shallow water equations to produce the Poincare (or inertia-gravity) wave dispersion relation.  
  
Discussed how the Poincare waves behave like inertial oscillations and like gravity waves without rotation in the limits of small and large wavenumbers, respectively.  
  
Introduced the Kelvin wave, derived the dispersion relation, then plugged it back into the assumed solution and, along with boundary conditions, derived the form of the Kelvin wave.  
  
Ended with a discussion of the delayed action oscillator model of ENSO.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 12338788-8816-ae13-5204-9141db64a789 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}