# curl with Visual Studio 2015 build notes
 
### Build
 
  - sln: curl-7.51.0\projects\Windows\VC14
 
  - modify the proj config of libcurl: openssl include path (C/C++>General>Additional Include Directories)

  - choose LIB Release - LIB OpenSSL
  
  - build libcurl
  
  - modify the proj config of curl: openssl lib path(Linker>Additional Library Directories)
  
  - Output: at "curl-7.51.0\build\Win32\VC14\LIB Release - LIB OpenSSL"

### Notes

  - #define CURL_STATICLIB when using static lib

### References

  - https://curl.haxx.se/
