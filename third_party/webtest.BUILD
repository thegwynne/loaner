# Description:
#   BUILD file for @webtest_archive//:webtest.

licenses(["notice"])  # MIT

py_library(
    name = "webtest",
    srcs = glob(["webtest/*.py"]),
    srcs_version = "PY2AND3",
    visibility = ["//visibility:public"],
    deps = [
        "@six_archive//:six",
        "@waitress_archive//:waitress",
        "@beautifulsoup4_archive//:beautifulsoup4",
    ],
)
