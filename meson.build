project(
  'reproducer',
  ['c', 'cpp'],
  meson_version : '>=1.1'
)

cpp = meson.get_compiler('cpp')
sources = [
  'src/main.cpp'
]
cpp_args = ['-std=c++17', '-Wall', '-Wextra', '-Wshadow', '-Wconversion', '-Wpedantic', '-Werror']
link_args = []

executable(
  'reproducer',
  sources,
  include_directories: [],
  dependencies: [],
  cpp_args : cpp_args,
  link_args : link_args
)
