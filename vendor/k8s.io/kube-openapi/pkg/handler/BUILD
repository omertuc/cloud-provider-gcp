load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "default_pruning.go",
        "handler.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kube-openapi/pkg/handler",
    importpath = "k8s.io/kube-openapi/pkg/handler",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/NYTimes/gziphandler:go_default_library",
        "//vendor/github.com/emicklei/go-restful:go_default_library",
        "//vendor/github.com/golang/protobuf/proto:go_default_library",
        "//vendor/github.com/google/gnostic/openapiv2:go_default_library",
        "//vendor/github.com/munnerz/goautoneg:go_default_library",
        "//vendor/gopkg.in/yaml.v2:go_default_library",
        "//vendor/k8s.io/klog/v2:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/builder:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/common:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/common/restfuladapter:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/internal/handler:go_default_library",
        "//vendor/k8s.io/kube-openapi/pkg/validation/spec:go_default_library",
    ],
)
