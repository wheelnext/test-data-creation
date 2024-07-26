# test-data-creation

The purpose of this repo is to prototype what the inputs of a variant package look like, and what the outputs should come out as.

## Key points for input
* How do dimensions of variability get specified?
* How do values (or matrices of values) for those dimensions get specified?

## Key points for output

These are implementation details for projects that consume this repo and produce distributions (files) that consider these key points.

* Distinguish filenames for variants with different values
  * store in filename
  * build number
  * suffix on platform tag
* Outputs must have uniform metadata. They can't have different dependencies.
  * likely achievable with markers, but these have to be custom