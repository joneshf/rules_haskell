load("@io_tweag_rules_haskell//haskell:haskell.bzl",
  "haskell_toolchain",
)

exports_files([
    "hazel.bzl",
    "BUILD.ghc",
    "paths-template.hs",
])

haskell_toolchain(
    name = "ghc",
    c2hs = "@c2hs//:bin",
    version = "8.2.2",
    tools = "@ghc//:bin",
)