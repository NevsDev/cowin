


https://github.com/treeform/glfm

#### build ios
nim c -c --os:ios --noMain:on main.nim 
#### build android
nim c -c --cpu:arm --os:android -d:androidNDK --noMain:on main.nim

