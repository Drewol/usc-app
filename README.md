# Build Guide

Clone this repo by

```
git clone --recurse-submodules https://github.com/SieR-VR/usc-app.git
```

Install vcpkg with custom patches
```sh
git clone https://github.com/Drewol/vcpkg.git
./vcpkg/bootstrap-vcpkg.sh
# Set VCPKG_ROOT environment variable to the full path to the vcpkg clone location.
```

finally, run

```
./gradlew assembleDebug
```

at project folder
