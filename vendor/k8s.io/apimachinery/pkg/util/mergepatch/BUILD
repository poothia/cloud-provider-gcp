load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "errors.go",
        "util.go",
    ],
    importmap = "io_k8s_cloud_provider_gcp/vendor/k8s.io/apimachinery/pkg/util/mergepatch",
    importpath = "k8s.io/apimachinery/pkg/util/mergepatch",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/davecgh/go-spew/spew:go_default_library",
        "//vendor/github.com/ghodss/yaml:go_default_library",
    ],
)
