# FreeRTOS RTOS Repository for CrossCore Embeddded Studio FreeRTOS Add-In

This repository contains a subset of the FreeRTOS Real-Time OS source code.
The repository is intended to be used by the CrossCore Embedded Studio FreeRTOS Add-In which will generate the remainder of the sources.

The repository is not intended to be used directly by software developers intending to run FreeRTOS on Analog Devices processors.

For more information regarding FreeRTOS for Analog Devices DSP processors please visit [analog.com/freertos](http://www.analog.com/freertos)

## Getting Started
For instructions on using this repository and the FreeRTOS Add-In for CrossCore Embedded Studio please refer to the documentation located at [wiki.analog.com](https://wiki.analog.com/resources/tools-software/freertos/freertos-addin).

## Supported Processors
The following processors are supported by this repository:
* ADSP-SC5xx (SHARC+ and ARM cores)
* ADSP-215xx (SHARC+ core)
* ADSP-BF57x (Blackfin core)

Other Analog Devices processors may support FreeRTOS, but are not part of the CrossCore Embedded Studio Add-In product. Please refer to the documentation for these specific processors for more details.

## Branch Information
The source code for each processor and each release of the software is stored on individual branches.
The add-in will check out the latest version of the sources for a given processor when you create a project within CrossCore Embedded Studio or add the FreeRTOS Add-in to your CrossCore Embedded Studio to your project.\
For a list of all branches available issue the git command: git branch -a\
The **main** branch shall contain no code.

## Licensing Information
The licensing information for the contents of this repository are located within the specific software branches within the repository. This ensures that the licensing information is correct for the given version of FreeRTOS and the port for a specific processor.

## Support and Help
Support for FreeRTOS on Analog Devices processors is provided by the Engineer Zone community forum.\
For support related to FreeRTOS please visit [FreeRTOS Engineer Zone](https://ez.analog.com/dsp/software-and-development-tools/freertos/).\
For support related to CrossCore Embedded Studio please visit [CCES Engineer Zone](https://ez.analog.com/dsp/software-and-development-tools/cces/)
