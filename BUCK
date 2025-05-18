cxx_library(
    name = "gtest",
    srcs = glob([
      "googletest/src/*.cc",
    ], exclude = ["googletest/src/gtest-all.cc"]),
    include_directories        = ["googletest"],
    public_include_directories = ["googletest/include"],
    visibility                 = ["PUBLIC"],
    compiler_flags             = ["-std=c++17"],
)
