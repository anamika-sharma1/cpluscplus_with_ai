# cpluscplus_with_ai
steps 
1) download microsoft visual studio c++ build tools
2) download c++ vcpkg package from git (git clone https://github.com/microsoft/vcpkg.git C:\vcpkg)
3) instal open ssl via vcpkg () -> .\vcpkg install openssl:x64-windows
4) install jetbrains clion (non-commercial version) and set compiler in toolchain settings as visual studio by default. (it uses ninja.exe as build tool and builtin c and c++ compiler).
5) add exclusion for (folder in whichc c++ code lies, vcpkg lies and where visual studio build tools are installed in virua and threat exclusion folders) so that antiirus doesn't slow down build or interfere with cmake or executables getting vanished.
bool passed{}; // value initialization, by default the value is false
and bool passed; // if global or static the value is 0 otherwise the value is indeterminate
