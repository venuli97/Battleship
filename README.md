
# Battleship

## Known Errors (csharp)

`DllNotFoundException: Unable to load DLL 'sgsdk.dll': The specified module could not be found.` when building on Windows

**FIX:** Copy contents from `lib\win\` to `bin\Debug\`.