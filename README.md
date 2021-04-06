# Build dlib in Android Studio

1. Source code of dlib 12.22.99 is copied into `app/src/main/cpp/dlib`
2. `app/src/main/cpp/CMakeLists.txt` is set as an input of the external native build system
3. `libdlib.so` is built under `app\.cxx\cmake\debug\[ABI]\dlib`
