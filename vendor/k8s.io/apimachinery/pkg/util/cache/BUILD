load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "cache.go",
        "lruexpirecache.go",
    ],
    importmap = "io_k8s_cloud_provider_gcp/vendor/k8s.io/apimachinery/pkg/util/cache",
    importpath = "k8s.io/apimachinery/pkg/util/cache",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/hashicorp/golang-lru:go_default_library"],
)
