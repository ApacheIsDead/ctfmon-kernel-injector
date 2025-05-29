# ctfmon-kernel-injector
Kernel-mode shellcode injector targeting ctfmon.exe — allocates executable memory, injects shellcode, and hooks function thunk for admin trusted process code execution and EDR evasion.

Hooks IAT - Import Address table, for the main function in ctfmon, DosCtfMon at 021D0. Replaces with our shellcodes address!
