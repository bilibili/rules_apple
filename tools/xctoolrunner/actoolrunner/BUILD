
licenses(["notice"])

py_binary(
    name = "actoolrunner",
    srcs = ["actoolrunner.py"],
    srcs_version = "PY3",
    python_version = "PY3",
    visibility = ["//apple/internal:__pkg__"],
    deps = [":actoolrunner_lib"],
)

py_library(
    name = "actoolrunner_lib",
    srcs = ["actoolrunner.py"],
    srcs_version = "PY3",
    deps = ["//tools/wrapper_common:execute"],
)





