### Description

Azan is an Islamic prayer times extension for Gnome Shell.

![alt text](/.img/azan.png) 

### Features

- List 5 prayer times
- Optionally display Imsak, Sunrise, Sunset, Midnight
- Show remaining time for the upcoming prayer
- Show current date in Hijri calendar
- Display a notification when it's time for prayer
- Automatic location detection
- Display times in either 24 hour or 12 hour format
- Adjustement of Hijri date

### Installation

```
wget https://github.com/raihan2000/azan-gnome-shell-extension/archive/refs/heads/master.zip
unzip master.zip -x
cd azan-gnome-shell-extension-master
make install
```
- Installation for old Gnome version

```
wget https://github.com/raihan2000/azan-gnome-shell-extension/archive/refs/heads/old-gnome.zip
unzip old-gnome.zip -x
cd azan-gnome-shell-extension-old-gnome
make install
```

### Changelog

- 01 : initial upload
- 02 : Add automatic location detection & bugfixes
- 03 : 12 hour times and optional hiding of non-prayer times
- 04 : Add support for Hijri adhustement
- 05 : Add support for Gnome 40+
- 06 : Bump version Gnome 42
- 07 : Added support for Gnome 3.36+
- 08 : Add support for Gnome 43
- 09 : Add support for Gnome 44
- 10 : Add support for Gnome 45

### License

Licensed under the GNU General Public License, version 3

### Third-Party Assets & Components

- [PrayTimes.js](http://praytimes.org/manual/)
- [HijriCalendar-Kuwaiti.js](http://www.al-habib.info/islamic-calendar/hijricalendar-kuwaiti.js)
