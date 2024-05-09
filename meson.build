
helper_files = [
    'src/galliumhelper.cpp'
]

helper_lib = library(
  'galliumhelper',
  helper_files,
  implicit_include_directories: false,

  version: meson.project_version(),
  override_options: ['b_lundef=false'],
  cpp_args: cpp_args,
  install: true,
)