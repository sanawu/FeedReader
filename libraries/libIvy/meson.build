ivy_inc = include_directories('.')
ivy_lib = static_library(
  'ivy',
  [
    'Extractor.vala',
    'Frame.vala',
    'Printer.vala',
    'Stacktrace.vala'
  ],
  dependencies: [
    gee,
    linux,
    posix,
  ],
  vala_vapi: 'ivy.vapi'
)
