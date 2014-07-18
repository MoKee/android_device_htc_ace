apply patches

Just run script 

./applypatch.sh

After patches applied, don't run this script again.

generate patches

run 

repo diff -u project > output.patch

:
repo diff -u build/core > device/htc/ace/patches/core.patch

repo diff -u frameworks/base > device/htc/ace/patches/base.patch

command. -u is required to inclued the project path
