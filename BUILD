load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_prefix")

go_prefix("github.com/wlynch/bazeltest")

go_library(
    name = "foo",
    srcs = ["foo.go"],
    visibility = ["//visibility:public"],
)

go_library(
    name = "bar",
    srcs = ["foo.go"],
    visibility = ["//visibility:public"],
)
