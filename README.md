Cydia 1.1.8+ for iPhone 4 iOS 7 fixed

Use Xcode 5.0 and iPhoneOS6.1.sdk

1. git clone git://git.saurik.com/cydia.git
2. cd cydia
3. git clone https://github.com/SaurikIT/SDURLCache.git

-----------------------------------------------------------
1. cd ../
2. git clone https://github.com/ichitaso/Cydia_1.1.8_Fix.git
3. Replace to cydia (/Library/move.sh makefile MobileCydia.mm)
4. install Fink (the only sane choice)
5. activate Fink (. /sw/bin/init.sh)
6. sudo fink install bash ldid tar wget xz
7. ./sysroot.sh
8. make package
