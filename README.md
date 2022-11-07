# Latest tpm2-tools from https://github.com/tpm2-software/tpm2-tools/ build inside Docker container.

## How to build

| docker build -t tpm2-tools  |
| --- |

## How to run
### Get TPM chip information:
| docker run --privileged -it tpm2-tools tpm2_getcap properties-fixed |
| --- |

### Example output on my machine:

