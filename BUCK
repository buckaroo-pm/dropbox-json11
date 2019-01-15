cxx_library(
  name = 'json11',
  header_namespace = '',
  exported_headers = [
    'json11.hpp',
  ],
  srcs = [
    'json11.cpp',
  ],
  licenses = [
    'LICENSE.txt',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'test',
  srcs = [
    'test.cpp',
  ],
  deps = [
    ':json11',
  ],
)
