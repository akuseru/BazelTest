workspace(name = "sf")

git_repository(
  name = "protobuf",
  remote = "https://github.com/google/protobuf",
  tag = "v3.0.0-beta-3.1"
)

bind(
    name = "protobuf_compiler",
    actual = "@protobuf//:protoc_lib",
)

new_http_archive(
  name = "zlib",
  url = "http://zlib.net/zlib-1.2.8.tar.gz",
  sha256 = "36658cb768a54c1d4dec43c3116c27ed893e88b02ecfcb44f2166f9c0b7f2a0d",
  build_file = "zlib.BUILD",
)
