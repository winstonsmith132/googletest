workspace(name = "com_google_googletest")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_google_absl",  # 2020-10-13T16:49:13Z
    urls = [
        "https://github.com/abseil/abseil-cpp/archive/f3f785ab59478dd0312bf1b5df65d380650bf0dc.zip"
    ],
    strip_prefix = "abseil-cpp-f3f785ab59478dd0312bf1b5df65d380650bf0dc",
    sha256 = "00c3707bf9cd5eabd1ec6932cc65b97378c043f22573be3adf7d11bb7af17d06",
)

null
http_archive(
    name = "rules_python",  # 2020-09-30T13:50:21Z
    urls = [
        "https://github.com/bazelbuild/rules_python/archive/c064f7008a30f307ea7516cf52358a653011f82b.zip",
    ],
    strip_prefix = "rules_python-c064f7008a30f307ea7516cf52358a653011f82b",
    sha256 = "6e49996ad3cf45b2232b8f94ca1e3ead369c28394c51632be8d85fe826383012",
)
