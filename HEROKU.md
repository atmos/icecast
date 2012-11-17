Building icecast on vulcan
==========================


Get the libogg build

http://atmos-vulcan.herokuapp.com/output/128cbd68-ddc3-4888-8bdf-f93c1dcb8ea1

Build libvorbis referencing the libogg build.

```
libvorbis-1.3.3(master*)$ vulcan build -v -d http://atmos-vulcan.herokuapp.com/output/128cbd68-ddc3-4888-8bdf-f93c1dcb8ea1
```

Build icecast referencing both projects

```
iceast$ vulcan build -v -d http://atmos-vulcan.herokuapp.com/output/69621463-23c7-4062-9f59-19086677fc5a http://atmos-vulcan.herokuapp.com/output/128cbd68-ddc3-4888-8bdf-f93c1dcb8ea1
```
