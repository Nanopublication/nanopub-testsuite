# ✅ Nanopublication Test Suite

A test suite for Trusty URIs and Nanopublication implementations

## Test suites

* The files in the **`valid`** and **`invalid`** folders of the test suite should only be used to validate nanopublications (not transform/sign). Note there are several valid ways to transform a pre-trusty nanopub into a trusty/signed one. This involves the decisions on how to introduce the trusty code, in particular when and how to add extra characters before and after, and more importantly how and in what order to Skolemize the blank nodes.

* The files in the **`transform`** folder show examples of how nanopubs can be transformed to trusty ones (and signing), but this is not fully deterministic (as it would open the notorious problem of graph normalization). 

## Existing implementations

* Java: https://github.com/Nanopublication/nanopub-java
* Python: https://github.com/fair-workflows/nanopub