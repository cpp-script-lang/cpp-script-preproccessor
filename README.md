# cpp-script-preproccessor
Preproccessor (set of macros) for C++Script
# Building (tests; this is header-only lib)
On Unix-like OS run **in the root of this repo**
```bash
build/build.bash
```
On Windows (in cmd) run **in the root of this repo**
```bat
build\build.bat
```
In PowerShell run **in the root of this repo**
```PowerShell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
build\build.ps1 # On Windows
build/build.ps1 # On Unix-like
```
# Using
When you built tests, you can see that this macros work. Unfortunately, macros aren't as powerful as normal code, so you have to type semicolons after statements and you can't unleash all powers of C++Script.
