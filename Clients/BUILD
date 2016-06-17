package(default_visibility = ["//visibility:public"])

apple_binary(
    name="sfios",
    srcs=["OSX/main.cpp"],
    pch="OSX/Prefix.pch",
    resources= ["src/Info.plist", "src/Icon.icns"],
    deps=["//Core:ClientLibOBJc"],
    copts=["-std=c++14"],
    platform_type="ios",

)
