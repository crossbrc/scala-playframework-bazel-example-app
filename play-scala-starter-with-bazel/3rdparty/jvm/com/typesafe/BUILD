load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
java_library(
    name = "config",
    exports = [
        "//external:jar/com/typesafe/config"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "ssl_config_core_2_12",
    exports = [
        "//3rdparty/jvm/org/scala_lang/modules:scala_parser_combinators_2_12",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//external:jar/com/typesafe/ssl_config_core_2_12",
        ":config"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


