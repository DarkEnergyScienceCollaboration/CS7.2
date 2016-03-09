#  Produce shear maps

Summary -- Some working groups, e.g., the Cluster WG, need shear maps associated with the hydrodynamic
simulations. The tools exist to do the ray tracing for these shear maps, but once produced, they need to be
tested to make sure the resolution of the shear maps is sufficient for the various customers.

## Key Tasks
* Key Task CS7.2.1 ( 09/16 ): Generate shear maps for the available set of simulations.
* Key Task CS7.2.2 ( 09/16 ): Iterate with the interested working groups to ensure the shear
maps are sufficient for the analysis tasks.

### Suggested organization
Repositories are available per deliverable.  Each key task has a subdirectory.
We have a `source` directory in each key task area for any supporting
code that goes with an effort.  There will also be a `doc` directory to hold documents in markdown,
latex, or binary formats.  The idea is to version everything and give us a good way to diff things.

Each deliverable is slightly different, so these repositories should grow to support the different need.

Please feel free to use github issues on each repository to organize work.
