### Astropy as a platform of stability in the astronomy software landscape

### Project Team
This proposal is to support Clément Robert's continued software engineering work
on the astropy core library.

### Project Description / Scope of Work

- improving backward and forward compatibility of astropy with its own dependencies at large
- coordinating with upstream and downstream stake holders to improve testing on a range
  of compatibile environments
- improve portability and re-usability of binary artifacts
- simplify the development process for most contributors to the core library (reduced build times)
- improve long-term maintainability of new APIs through developer documentation
  and code reviews
- tackle long standing bugs
- fix incompatibilities with development versions of core and secondary dependencies as needed
- extend support to future features of the Python interpreter (like JIT compilation and free-threading)
- handle long-term API evolutions through deprecation cycles

#### Roadmap Items

The proposed work aligns with the following roadmap items:

- Improve and/or maintain interoperability with performant I/O file formats and libraries such as HDF5 and Dask.
- Improve support for using Astropy tools in heterogeneous computing environments such as cloud environments or GPU systems.
- Support JIT compilation (e.g., numba, JAX, etc.) throughout Astropy core and coordinated packages.
- Increase the learning and mentoring opportunities for people interested in becoming contributors and helping to develop existing contributors into maintainers.


#### Project / Work / Deliverables

Listed hereafter are the concrete deliverables to be expected

- reproducible builds in "oldestdeps" testing environments (issue) 
- split out extension modules to a `astropy-core` package (pre-APE)
- developer guidelines for maintainable new APIs (email)
- detailed, quarterly reports of bug reports closed and PRs reviewed

> Note: 3 of these 4 items are, at the time of writing, being actively discussed
> in the open with other maintainers and other stake holders.
> I intend to provide links to where the most recent discussions are happening
> but these may change over the course of the Cycle 5 review process.

### Approximate Budget
Currency: US
Budget: $80,000

I'm requesting funding for 800 hours of contractual work, over a performance period of one year,
at a rate of 100$/hr.


### Period of Performance

2026 (Jan 1 to Dec 31)
