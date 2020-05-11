
1) Remove Trial Data from files:
```
rm -rf ~/Library/Preferences/$'.\xe2\x80\xa6\x45\xcc\x80\x7c\x56\x49\xcc\x80\x67\x53\xc2\xa0'
defaults write ~/Library/Preferences/de.appsolute.mamppro.plist regData -data 00
```

2) Remove other Folders and Files (not required)...
```
rm -rf ~/Library/Application\ Support/de.appsolute.mamppro
rm -rf ~/Library/Caches/de.appsolute.mamppro
```

3) Restart Services...
```
sudo killall de.appsolute.mampprohelper
sudo killall cfprefsd
```
** Debe estar cerrado
