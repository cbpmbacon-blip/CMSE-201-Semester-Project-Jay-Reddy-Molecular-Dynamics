# CMSE-201-Semester-Project-Jay-Reddy-Molecular-Dynamics
### NEW! V1.1.0!!
Here is a list of all of the new changes since the last project proposal file:

Whats New:
- Units!! This is an Argon model
- New Force Field Calculation
- Temperature and Pressure Readouts (Not confirmed accurate)
- Working velocity distribution
- Improved feature selection menu
- Working on simulation logs
- Working on tensor logs for alternate data-analysis methods
- Improved visualization loop

Going Forward: 
- verifying boltzmann distribution
- verifying temperature and pressure readouts
- auto calculation of ideal gas law for deviation analysis
- front end?? (if i have time)
- HDF5 files for logs and tensor printouts
- timestep auto calculation + optimization?

Assumptions: 
- Elastic and Smooth Walls
- Spherical particles with spherical force fields
- No rotational motion
- 2 Femtosecond timesteps
- Rounding/cutoff error due to GPU architecture (float 32 precision)
- Verlet integration
- 12-6 Lennard Jones Potential (mathematical approximation)
- No loss of KE 
- No gravity
- My code works correctly 
- isotropic, homogenous fluid (not inviscid)
