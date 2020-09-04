load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_binary(
    name = "hello-world",
    srcs = ["hello-world.cc"],
    deps = [
        "@stage3//lib:hello-time",
    ],
)