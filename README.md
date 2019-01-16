# MusicPlayerDaemon 0.21 armhf deb package
# It's not working now.. :(
/usr/bin/mpd binary is compiled by romanceassassin.  
deb package maintained by djjproject.  

## depends
Debian8 (jessie) armhf mpd package need to be preinstalled.  
You need u5pvr / u5mini android tv box (Android over Linux installed).  
ref link : http://www.badasystem.co.kr  

## features
DSD ISO Playback supported.  
DVD ISO Palyback supported.  
tidal token supported.  

## make deb package
git clone https://github.com/djjproject/mpd_0.21_armhf  
cd mpd_0.21_armhf  
rm -rf .git  
rm -rf README.md  
cd ..  
dpkg -b mpd_0.21_armhf  
