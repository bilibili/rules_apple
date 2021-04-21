load("//tools:py2and3_test.bzl", "py2and3_test")

licenses(["notice"])

py_binary(
    name = "actoolrunner",
    srcs = ["actoolrunner.py"],
    srcs_version = "PY2AND3",
    # Used by the rule implementations, so it needs to be public; but
    # should be considered an implementation detail of the rules and
    # not used by other things.
    visibility = ["//visibility:public"],
    deps = [":actoolrunner_lib"],
)

py_library(
    name = "actoolrunner_lib",
    srcs = ["actoolrunner.py"],
    srcs_version = "PY2AND3",
    deps = ["//tools/wrapper_common:execute"],
)


