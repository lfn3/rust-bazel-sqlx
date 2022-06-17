load("@rules_rust//rust:defs.bzl", "rust_binary")
load("@crates//:defs.bzl", "all_crate_deps")

rust_binary(
    name = "rust-bazel-sqlx",
    srcs = glob([
        "src/**/*.rs",
    ]),
    proc_macro_deps = all_crate_deps(
        proc_macro = True,
    ),
    deps = all_crate_deps(
        normal = True,
    ),
)
