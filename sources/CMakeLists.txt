cmake_minimum_required(VERSION 0.1)
project(veluwos-wallpapers)

set(BACKGROUNDS
	default.jpg
	wallpaper-1.jpg
	wallpaper-2.jpg
	wallpaper-3.jpg
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/veluwos)