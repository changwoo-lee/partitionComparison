partitionComparison
===================

An R package which implements many measures for (graph) partition comparison.
For more details, see the package details on CRAN (https://cran.r-project.org/package=partitionComparison)

Changes
-------

TODO list

1) Distance between one partition versus many partitions, vectorized computation (no for loop). Useful when there is 'true partition' and have posterior samples of partition.
2) Bug in the classificaton error metric, when k = length(unique(p)) > k' = length(unique(q)).
3) Binder loss and related loss functions missing

0.2.5
  - Changed maintainer information and updated URL/BugReports links

0.2.4
  - Fixed some encoding issues

0.2.3
  - Replaced ``==`` comparisons by tolerance permissive ``isTRUE(all.equal(x, y))``

0.2.2
  - First version published on CRAN
  - Finalized description, documentation, references
  - Added a ``compareAll`` method to run comparison with all measures

0.2.1
  - Dropped igraph dependency in favor of lpSolve
  - Added some tests for method signature registration
  - normalizedMutualInformation now with default "min"
  - Rewritten registration of measure methods for plain partition vectors

0.2.0
  - First finished version
