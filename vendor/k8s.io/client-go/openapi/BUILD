load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "client.go",
        "groupversion.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/openapi",
    importpath = "k8s.io/client-go/openapi",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/gnostic/openapiv3:go_default_library",
        "//vendor/google.golang.org/protobuf/proto:go_default_library",
        "//vendor/k8s.io/client-go/rest:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/handler3:go_default_library",
    ],
)
