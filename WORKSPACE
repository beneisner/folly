load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_github_google_double_conversion",
    urls = ["https://github.com/google/double-conversion/archive/v3.1.5.tar.gz"],
    strip_prefix = "double-conversion-3.1.5",
)
http_archive(
    name = "com_github_gflags_gflags",
    urls = [ "https://github.com/gflags/gflags/archive/master.zip"],
    strip_prefix = "gflags-master",
)

http_archive(
    name = "com_github_google_glog",
    urls = [ "https://github.com/google/glog/archive/master.zip" ],
    strip_prefix = "glog-master",
    workspace_file_content = "",
)

http_archive(
  name = "com_github_google_googletest",
  strip_prefix = "googletest-90a443f9c2437ca8a682a1ac625eba64e1d74a8a",
  urls = ["https://github.com/google/googletest/archive/90a443f9c2437ca8a682a1ac625eba64e1d74a8a.zip"],
  sha256 = "6fb9a49ad77656c860cfdafbb3148a91f076a3a8bda9c6d8809075c832549dd4",
)