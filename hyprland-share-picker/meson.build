subdir('src')

exe_src = ['main.go']

custom_target('hyprland-share-picker-gtk',
    output: 'hyprland-share-picker',
    input: exe_src,
    command: ['go', 'build', '-o', '@OUTPUT@', '@INPUT@'],
    build_by_default: true
)

install_data(
    sources: ['README.md'],
    install_dir: join_paths(get_option('datadir'), meson.project_name())
)
