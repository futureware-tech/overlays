# overlays

These are the "templates" for repositories. Each subdirectory contains a set of
files which will replace files in repositories which use an overlay.

A list of overlays is configured in the OVERLAYS file in the root of each
repository. Overlay name is equal to directory name.

A workflow defined in the template repository is responsible of pulling in any
changes to overlay files which happen in this repository.
