# svd

This repository contains CMSIS System View Description (CMSIS-SVD) files for Espressif products.

Please note that these SVDs are still in-progress and may be missing peripherals, interrupts, and/or registers. If you discover any errors within any of the SVD files please consider opening an issue to report it.

## What is CMSIS-SVD?

From the [CMSIS System View Description documentation]:

> The CMSIS System View Description format(CMSIS-SVD) formalizes the description of the system contained in Arm Cortex-M processor-based microcontrollers, in particular, the memory mapped registers of peripherals. The detail contained in system view descriptions is comparable to the data in device reference manuals. The information ranges from high level functional descriptions of a peripheral all the way down to the definition and purpose of an individual bit field in a memory mapped register.

This format was intended for use with ARM microcontrollers, however it is still applicable to other architectures. SVD files can be used by some tools (such as [svd2rust]) to generate libraries for low-level hardware access.

[cmsis system view description documentation]: https://www.keil.com/pack/doc/CMSIS/SVD/html/
[svd2rust]: https://github.com/rust-embedded/svd2rust

## License

The files in this repository are distributed under the Apache License, Version 2.0 ([LICENSE](LICENSE) or http://www.apache.org/licenses/LICENSE-2.0)
