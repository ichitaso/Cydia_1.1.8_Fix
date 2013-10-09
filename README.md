Cydia 1.1.8+ for iPhone 4 iOS 7 fixed
====
Use Xcode 5.0 and iPhoneOS6.1.sdk

git clone git://git.saurik.com/cydia.git

-----------------------------------------------------------

1. git clone https://github.com/ichitaso/Cydia_1.1.8_Fix.git
2. Replace to cydia ( SDURLCache, /Library/move.sh, makefile, MobileCydia.mm )

  (SDURLCache orignal: https://github.com/SaurikIT/SDURLCache )

3. install Fink (the only sane choice)
4. activate Fink (. /sw/bin/init.sh)
5. sudo fink install bash ldid tar wget xz
6. ./sysroot.sh
7. make package
