# `noEmitOnError` and composite projects

It appears that `noEmitOnError` is simply ignored. This is eminently reasonable, as downstream consumers of a package cannot reliably depend on the output from a non-type-checking module.