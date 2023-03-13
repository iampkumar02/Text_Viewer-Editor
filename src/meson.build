text_viewer_app_sources = [
  'main.c',
  'text_viewer_app-application.c',
  'text_viewer_app-window.c',
]

text_viewer_app_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1'),
]

text_viewer_app_sources += gnome.compile_resources('text_viewer_app-resources',
  'text_viewer_app.gresource.xml',
  c_name: 'text_viewer_app'
)

executable('text_viewer_app', text_viewer_app_sources,
  dependencies: text_viewer_app_deps,
       install: true,
)
