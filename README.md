# Template project folder

## Requirements
- [GCC compiler for ARM](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads)
- [STM32 Firmware File](https://www.st.com/en/embedded-software/stm32-standard-peripheral-library-expansion.html?querycriteria=productId=LN1734#overview)
- [st-link utility](https://github.com/stlink-org/stlink/releases)

## Flashing the STM board
```bash
make clean && make && make burn
```