# libapr with Visual Studio 2015 build notes

### Build

  - use aprutil\aprutil.sln

### Notes

  - APR 1.5.2 Win32 Source
  - APR-util 1.5.4 Win32 Source
  - APR iconv 1.2.1 Win32 Source
  - remove build configuration other than Release/Debug
  - fix build/modules.mk.win(adobe-stdenc.obj error)
  - remove duplicate import of user.props in project files

### References

  - https://apr.apache.org/