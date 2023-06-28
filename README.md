# hello-yocto

This is a simple example app for build with Yocto SDK.

Please refer below link for setup Yocto eSDK.
* https://docs.yoctoproject.org/sdk-manual/extensible.html


You can build this application using devtool commands below:
```
devtool add hello-yocto <source path>
devtool build hello-yocto
devtool build-image core-image-sato
```

Launch qemu and check hello_yocto command on terminal
```
runqemu kvm
```
