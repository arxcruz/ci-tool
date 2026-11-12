# ci-tool

A stand-in for a CI tool, used by the demo in
[zuul-kafka-driver](https://github.com/arxcruz/zuul-kafka-driver).

The demo's bundle tests read `tool.yaml`. On `master` it has a bug that makes
two of the tests fail. The open pull request fixes it, so the demo can test a
bundle with that fix applied (`Depends-On`) before it's merged.

Please keep the pull request open: it's part of the demo.
