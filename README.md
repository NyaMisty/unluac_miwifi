# unluac for MiWifi

![unluac Nightly Build](https://github.com/NyaMisty/unluac_miwifi/workflows/unluac%20Nightly%20Build/badge.svg)

Xiaomi Router encrypts its lua files in models AC2100, AX3600, R4. 

They modified the Lua interpreter, which introduces string encryption, shifted opcode order, and customized opcodes.

This unluac is imported from upstream unluac at 2020.6.14 

Credits:
- @lvqier for the initial port from https://github.com/lvqier/unluac
- unluac team for a brilliant luac decompiler
