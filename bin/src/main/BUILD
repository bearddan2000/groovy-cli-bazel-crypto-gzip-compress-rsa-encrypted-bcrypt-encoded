load("@io_bazel_rules_groovy//groovy:groovy.bzl", "groovy_binary")

groovy_binary (
    name = "BazelApp",
    srcs = glob(["groovy/**/*.groovy"]),
    main_class = "example.Main",
    deps = [
      "@maven//:org_mindrot_jbcrypt",
      "@maven//:javax_xml_bind_jaxb_api",
    ],
)
