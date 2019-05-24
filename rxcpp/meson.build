project(
    'rxcpp',
    'cpp',
    version : '4.1.0',
    license : 'Apache-2.0'
)

includes = include_directories('Rx/v2/src')

thread_dep = dependency('threads')

rxcpp_dep = declare_dependency(
    include_directories : includes,
    dependencies: [thread_dep]
)

subdir('Rx/v2/test')
