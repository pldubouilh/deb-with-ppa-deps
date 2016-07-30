Framework for scripted debian packages. Package with `sudo dpkg-deb --build helloworld_1.0-1`

Pre/post installation scripts in `DEBIAN/preinst`. Note that post install spwans a sub process that waits till dpkg exit to execute itself, allowing full use of `dpkg` again :+1:
