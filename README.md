# OpenWebRTC fork of cerbero (libnice 0.1.13 package)

We made this fork and added a package definition in order to be able to compile *libnice 0.1.13 and all their dependencies for iOS*. It includes one patch to solve a segfault in it.

In order to build it, you should follow the instructions at Ericsson fork:
[Using this cerbero fork to build OpenWebRTC](https://github.com/EricssonResearch/openwebrtc/wiki/Building-OpenWebRTC)

After the whole openwebrtc package is compiled you can run the following command to get a tar.gz with libnice and all the dependencies in it:
```
   ./cerbero-uninstalled -c config/cross-ios-universal.cbc package -f libnice -t
```

