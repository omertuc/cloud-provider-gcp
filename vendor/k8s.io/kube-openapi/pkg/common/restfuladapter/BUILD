load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "adapter.go",
        "param_adapter.go",
        "response_error_adapter.go",
        "route_adapter.go",
        "webservice_adapter.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kube-openapi/pkg/common/restfuladapter",
    importpath = "k8s.io/kube-openapi/pkg/common/restfuladapter",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/emicklei/go-restful:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/common:go_default_library",
    ],
)
