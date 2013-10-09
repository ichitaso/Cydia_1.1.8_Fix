Cydia 1.1.8+ for iPhone 4 iOS 7 fixed

Use Xcode 5.0 and iPhoneOS6.1.sdk

1. git clone git://git.saurik.com/cydia.git

-----------------------------------------------------------

1. git clone https://github.com/ichitaso/Cydia_1.1.8_Fix.git
2. Replace to cydia ( SDURLCache, /Library/move.sh, makefile, MobileCydia.mm )
3. (SDURLCache orignal: https://github.com/SaurikIT/SDURLCache ) 
4. install Fink (the only sane choice)
5. activate Fink (. /sw/bin/init.sh)
6. sudo fink install bash ldid tar wget xz
7. ./sysroot.sh
8. make package
