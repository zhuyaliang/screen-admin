actions_icons = [
  ['16x16', 'gnome-recorder-admin.png'],
  ['22x22', 'screen-start.png'],
  ['22x22', 'gnome-recorder-admin.png'],
  ['24x24', 'gnome-recorder-admin.png'],
  ['32x32', 'gnome-recorder-admin.png'],
  ['48x48', 'gnome-recorder-admin.png']
]

foreach icon: actions_icons
  install_data(
    join_paths(icon[0], 'apps', icon[1]),
    install_dir: join_paths(get_option('prefix'), 'share/icons', 'hicolor', icon[0], 'apps')
  )
endforeach
