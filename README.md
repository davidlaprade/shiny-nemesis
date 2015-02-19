This is my attempt at versioning a philosophy paper.

### How this will work:
1. The paper will be written in micro-sections, called modules.
  * modules will be discrete: they will not make reference to one another, nor to things written in each other. They should be "free-standing".
  * modules will argue for at most one claim
  * modules will contain meta-data
    * module metadata will contain the names of dependencies, i.e. other modules that argue for the assumptions of the current module
  * modules may have specific issues associated with them to facilitate tagging in commits
  * modules will be stored in a `modules` directory
2. The paper will be outlined in `outline.md` in the root
  * the outline will outline each of the modules and their arrangement in the paper
