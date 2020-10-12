
cc_library(
    name = "angle",
    srcs = [
        "binaries/x64/libEGL.dll.lib",
        "binaries/x64/libGLESv2.dll.lib",
        "binaries/x64/libEGL.dll",
        "binaries/x64/libGLESv2.dll",
    ],
    hdrs = glob(["include/**/*.h*"]),
    includes = ["include/"],
    linkstatic = 1,
    visibility = ["//visibility:public"],
)
