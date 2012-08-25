## What is it?

It is an effort to create an ivilink server/client for Android devices.

## How to download?

Clone repository:

    git clone git://github.com/ivilink/ividroid.git

Fetch submodules:

    git submodule update --init

## How to build?

### Satisfy prerequisites

* Download and install Android SDK
* Download and install Android NDK

### Build it

```bash
cd <project>
<ndk>/ndk-build LIB
```

## How to use?

Unfortunately, it is not usable yet.

Intended way to use:

1. Setup IP network between your android device and a host machine
* Download, build and install ivilink on your host machine
* Install ividroid on your android device
* Run client/server on the host machine
* Run server/client on the android device
* Pair devices
* ??? (do something awesome)
