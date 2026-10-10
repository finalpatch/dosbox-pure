build commands

release build: ndk-build -j12 APP_ABI=arm64-v8a NDK_DEBUG=0
debug build: ndk-build -j12 APP_ABI=arm64-v8a
