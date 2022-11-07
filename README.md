# Latest tpm2-tools from https://github.com/tpm2-software/tpm2-tools/ build inside Docker container.

## How to build

| docker build -t tpm2-tools  |
| --- |

## How to run
### Get TPM chip information:
| docker run --privileged -it tpm2-tools tpm2_getcap properties-fixed |
| --- |

### Example output on my machine:

| TPM2_PT_FAMILY_INDICATOR:
  raw: 0x322E3000
  value: "2.0"
TPM2_PT_LEVEL:
  raw: 0
TPM2_PT_REVISION:
  raw: 0x8A
  value: 1.38
TPM2_PT_DAY_OF_YEAR:
  raw: 0x12F
TPM2_PT_YEAR:
  raw: 0x7E3
TPM2_PT_MANUFACTURER:
  raw: 0x494E5443
  value: "INTC"
TPM2_PT_VENDOR_STRING_1:
  raw: 0x496E7465
  value: "Inte"
TPM2_PT_VENDOR_STRING_2:
  raw: 0x6C000000
  value: "l"
TPM2_PT_VENDOR_STRING_3:
  raw: 0x0
  value: ""
TPM2_PT_VENDOR_STRING_4:
  raw: 0x0
  value: ""
TPM2_PT_VENDOR_TPM_TYPE:
  raw: 0x0
TPM2_PT_FIRMWARE_VERSION_1:
  raw: 0x1F4000A
TPM2_PT_FIRMWARE_VERSION_2:
  raw: 0x0
TPM2_PT_INPUT_BUFFER:
  raw: 0x400
TPM2_PT_HR_TRANSIENT_MIN:
  raw: 0x3
TPM2_PT_HR_PERSISTENT_MIN:
  raw: 0x7
TPM2_PT_HR_LOADED_MIN:
  raw: 0x3
TPM2_PT_ACTIVE_SESSIONS_MAX:
  raw: 0x40
TPM2_PT_PCR_COUNT:
  raw: 0x18
TPM2_PT_PCR_SELECT_MIN:
  raw: 0x3
TPM2_PT_CONTEXT_GAP_MAX:
  raw: 0xFFFF
TPM2_PT_NV_COUNTERS_MAX:
  raw: 0x80
TPM2_PT_NV_INDEX_MAX:
  raw: 0x800
TPM2_PT_MEMORY:
  raw: 0x6
TPM2_PT_CLOCK_UPDATE:
  raw: 0x400000
TPM2_PT_CONTEXT_HASH:
  raw: 0xB
TPM2_PT_CONTEXT_SYM:
  raw: 0x6
TPM2_PT_CONTEXT_SYM_SIZE:
  raw: 0x100
TPM2_PT_ORDERLY_COUNT:
  raw: 0xFF
TPM2_PT_MAX_COMMAND_SIZE:
  raw: 0xF80
TPM2_PT_MAX_RESPONSE_SIZE:
  raw: 0xF80
TPM2_PT_MAX_DIGEST:
  raw: 0x20
TPM2_PT_MAX_OBJECT_CONTEXT:
  raw: 0x3A0
TPM2_PT_MAX_SESSION_CONTEXT:
  raw: 0xF8
TPM2_PT_PS_FAMILY_INDICATOR:
  raw: 0x1
TPM2_PT_PS_LEVEL:
  raw: 0x0
TPM2_PT_PS_REVISION:
  raw: 0x103
TPM2_PT_PS_DAY_OF_YEAR:
  raw: 0x0
TPM2_PT_PS_YEAR:
  raw: 0x0
TPM2_PT_SPLIT_MAX:
  raw: 0x80
TPM2_PT_TOTAL_COMMANDS:
  raw: 0x65
TPM2_PT_LIBRARY_COMMANDS:
  raw: 0x65
TPM2_PT_VENDOR_COMMANDS:
  raw: 0x0
TPM2_PT_NV_BUFFER_MAX:
  raw: 0x800
TPM2_PT_MODES:
  raw: 0x0
|
| --- |
