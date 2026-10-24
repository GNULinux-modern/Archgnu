qdbus org.kde.plasmashell /PlasmaShell org.kde.PlasmaShell.evaluateScript 'var allDesktops = desktops(); for (i=0;i<allDesktops.length;i++) { d = allDesktops[i]; d.wallpaperPlugin = "org.kde.image"; d.currentConfigGroup = Array("Wallpaper", "org.kde.image", "General"); d.writeConfig("Image", "file:///usr/share/wallpapers/custom_wallpaper.jpg"); }'
------------------------------------------------------------------------------------
curl -s -L "https://res.cloudinary.com/dtz0urit6/image/upload/q_auto:best,f_jpg/cloudinary-tools-uploads/zfkoxq369nd0upsyfhmm" -o /tmp/custom_wallpaper.jpg
-----------------------------------------------------------------------------------
qdbus org.kde.plasmashell /PlasmaShell org.kde.PlasmaShell.evaluateScript 'var allDesktops = desktops(); for (i=0;i<allDesktops.length;i++) { d = allDesktops[i]; d.wallpaperPlugin = "org.kde.image"; d.currentConfigGroup = Array("Wallpaper", "org.kde.image", "General"); d.writeConfig("Image", "file:///tmp/custom_wallpaper.jpg"); }'
---------------------------------------------------------------------------------------
sudo ln -s /usr/lib/libboost_python314.so.1.92.0 /usr/lib/libboost_python314.so.1.91.0
-----------------------------------------------------------------------------------------------------------------
sudo mkdir -p /home/hamedmustafa/Desktop/archgnu/airootfs/usr/lib/
sudo ln -sf /usr/lib/libboost_python314.so.1.92.0 /home/hamedmustafa/Desktop/archgnu/airootfs/usr/lib/libboost_python314.so.1.91.0
