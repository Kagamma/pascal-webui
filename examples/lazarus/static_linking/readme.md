# Example with static linking

! FPC 3.3.1 is required (FPC 3.2.2 causes an error caused by a bug of the compiler itself)

! x64 only

webui static library is taken from https://github.com/webui-dev/webui/suites/15744248695/artifacts/898948037

other static libraries is taken from https://www.mingw-w64.org/downloads/

FileSize	: 286739 bytes ( 280.019 KB,  0.273 MB )  - without optimization

FileSize	: 265747 bytes ( 259.519 KB,  0.253 MB )  - max optimization (-20992 bytes, 7,3%)

FileSize	: 103443 bytes ( 101.019 KB,  0.099 MB )  - upx packed (--ultra-brute) (-183 296 bytes, 63,9%)
