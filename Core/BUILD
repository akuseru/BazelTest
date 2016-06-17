
objc_library(
    name="ClientLibOBJc",
    srcs = glob(["Client/**/*.cpp", "Client/**/*.mm", "Client/**/*.h"], exclude=["Client/sf.h"]),
    hdrs = ["Client/sf.h"],
    copts = ["-std=c++14"],
    visibility =["//Clients:__pkg__"],
    sdk_frameworks=["QuartzCore","ApplicationServices","OpenGL","IOKit"],
    )
