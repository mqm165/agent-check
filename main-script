mode con:cols=60 lines=55

@echo off

set /p router="Enter Router IP: "
set /p sector="Enter Sector IP: "
set /p station="Enter station IP: "
set /p accessPoint="Enter Access Point IP: "



echo .............................................
echo Router:
ping %router%		| findstr "Pinging Reply"

echo .............................................
echo Sector:
ping %sector%		| findstr "Pinging Reply"

echo .............................................
echo Station
ping %station%		| findstr "Pinging Reply"

echo .............................................
echo Access Point:
ping %accessPoint%	| findstr "Pinging Reply"

echo .............................................
echo Skyline-Main:
ping 10.0.0.1		| findstr "Pinging Reply"

echo .............................................
echo Google:
ping 8.8.8.8		| findstr "Pinging Reply"

echo .............................................
echo DNS:
nslookup www.mqm.com	| findstr "Address Name"
echo .............................................


pause


