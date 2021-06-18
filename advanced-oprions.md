Advanced options doc - https://oreans.com/help/advopt/

------------------------------------------------------------------------------------------------------------------------

Manual VM macro (address - RVA)
Example:
```
OPTION_ADVANCED_MANUAL_VM_MACRO_1=0x11570 - 0x1158e
OPTION_ADVANCED_MANUAL_VM_MACRO_ID_1=0x3AFA5205
```
You can grab the VM ID from the specific ".vm" file. The above example is for the "DOLPHIN32(RED)" virtual machine.

------------------------------------------------------------------------------------------------------------------------

"OPTION_ADVANCED_MANUAL_MUTATE_MACRO_xx = hex_RVA_start - hex_RVA_end" to be used as:
```
OPTION_ADVANCED_MANUAL_MUTATE_MACRO_1 = 0x1000 - 0x2000
OPTION_ADVANCED_MANUAL_MUTATE_MACRO_2 = 0x3100 - 0x3600
.....
```

------------------------------------------------------------------------------------------------------------------------

Fix encrypt strings:
```
OPTION_ADVANCED_SKIP_STR_ENCRYPT_HEADER=YES
```

------------------------------------------------------------------------------------------------------------------------

Other options:

`OPTION_ADVANCED_CHECK_DEBUGGER_EXT` - YES / NO

`OPTION_ADVANCED_DETECT_VIRTUAL_ENVIRONMENT_MK1` - YES / NO

`OPTION_ADVANCED_XBUNDLER_FAKE_DLL`

`OPTION_ADVANCED_PROTECT_OVERLAY` - for overlay protection

`OPTION_ADVANCED_DONT_PROCESS_SECTIONS` - to skip sections from being compressed/encrypted

`OPTION_ADVANCED_XBUNDLER_CLOSE_FILE_DONT_ENCRYPT` - to avoid re-encrypting the file in memory after being

`OPTION_MACROS_ENCRYPT_STRINGS_DECRYPT_ON_HEAP` - for STR_ENCRYPT macros

`OPTION_MACROS_ENCRYPT_STRINGS_REENCRYPT` - for STR_ENCRYPT macros

`OPTION_VIRTUAL_MACHINE_ISOLATE_REGS`

`OPTION_MACROS_SWITCH_CASE_SUPPORT`

`OPTION_ADVANCED_MAP_FUNCTION_AS_MUTATE_MACRO`

`OPTION_COMPRESSION_COMPRESS_ONLY_CODE_SECTIONS`

`OPTION_ADVANCED_DISABLE_REPORT_STRINGS_TO_ENCRYPT`

`OPTION_ADVANCED_XBUNDLER_MATCH_PATHS`

`OPTION_ADVANCED_XBUNDLER_SKIP_ARCHITECTURE_CHECK`

`OPTION_ADVANCED_SKIP_MEMORY_EXCEPTION_CHECKS` - for better support with manual mapped protected DLLs

