load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "backoff.go",
        "buffer.go",
        "doc.go",
        "go18.go",
        "header.go",
        "json.go",
        "jsonfloat.go",
        "media.go",
        "not_go18.go",
        "params.go",
        "resumable.go",
        "retry.go",
        "send.go",
    ],
    importmap = "io_k8s_cloud_provider_gcp/vendor/google.golang.org/api/gensupport",
    importpath = "google.golang.org/api/gensupport",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/net/context:go_default_library",
        "//vendor/golang.org/x/net/context/ctxhttp:go_default_library",
        "//vendor/google.golang.org/api/googleapi:go_default_library",
    ],
)
