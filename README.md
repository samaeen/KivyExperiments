These repo is my tests on building the kivy apps in windows 10 with the help of bash feature on windows.
I followed mostly this video to build the app. ( https://www.youtube.com/watch?v=KQ68bJE8g7c )

But I ran into some problems.So the steps are listed below.

 -create setup dir> create install.sh and put contents of https://raw.githubusercontent.com/HeaTTheatR/KivyMD-data/master/install-kivy-buildozer-dependencies.sh >change permission with chmod 777 install.sh >then use the install command and its installed.. 
  ..* if the ndk link doesnot work then download it manually
  ..* if other packages(for example unzip) is not installed then install it manually.
  ..* you may need to install libffi-dev and create the autoconf.
  ..* create python 3 as your default python or problem will arise while building.
 - once ready create the app.And the required process for that is.
  ..* so buildozer.init > buildozer android debug
  ..* same process goes here.if anything missing install them..And carefull edit the buildozer.spec file.Specially the requirements may be missing, So put other requirements in buildozer.spec file


  ## Still running problems building opencv apps.
  --- **need to update code from bash** ---
