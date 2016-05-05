# opensource

# openssl Android
use openssl-android to build 

armeabi armeabi-v7a mips need build with anroid-19
arm64-v8a mips64 x86_64 need build with android-21

x86_64 rc4_hmac_md5_cipher: error: undefined reference to 'rc4_md5_enc'

build command: ./openssl-android /Users/patyang/workspace/SDK/Android/android-ndk-r10e . 19 x86_64 4.8 ./output/x86_64