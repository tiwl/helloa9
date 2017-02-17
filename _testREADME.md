## Example Summary

Example that uses the ADCBuf driver to make a number of samples
and echo them via UART. This example shows how to initialize the
ADCBuf driver in continuous mode.

## Peripherals Exercised

* `Board_ADCBUF0` - Used to take samples on an analogue input.
* `Board_UART0` - Used to echo samples to host serial session

## Resources & Jumper Settings

> Please refer to the development board's specific __Settings and Resources__
section in the Getting Started Guide. For convenience, a short summary is also
shown below.

| Development Board | Notes  |
| ----------------- | ------ |
| CC1310_LAUNCHXL   |        |
| CC1350_LAUNCHXL   |        |
| CC2650_LAUNCHXL   |        |
| MSP-EXP432P401R   |        |

> To view UART output, the RX and TX jumpers must be in place.
> Fields left blank have no specific settings for this example.

## Example Usage

* Open a serial session (e.g. [`PuTTY`](http://www.putty.org/ "PuTTY's Homepage"), etc.) to the appropriate COM port.
    * The COM port can be determined via Device Manager in Windows or via `ls /dev/tty*` in Linux.

The connection will have the following settings:
```
    Baud-rate:     115200
    Data bits:          8
    Stop bits:          1
    Parity:          None
    Flow Control:    None
```

* Run the example.

* The target will send packages of 100 samples and a header to the serial session
twice per second. The values displayed on the console are in micro-volts.

## Application Design Details

* A single task sets up the UART connection to the serial console and starts
a continuous conversion with the ADCBuf driver. After this is completed, the task sleeps forever.

* The ADCBuf driver performs 100 samples at 200 Hz each.
    * The driver supports higher sampling rates; however, 200 Hz was chosen for
easily interpretable output. The maximum sampling rates are device specific.

* The callback function `adcBufCallback` is called whenever an ADC buffer is full. The contents
of the buffer are converted into human-readable format and sent via UART.

TI-RTOS:

* When building in Code Composer Studio, the configuration project needs to be built first. These projects can be found under <SDK_INSTALL_DIR>/os/tirtos/builds/<BOARD_NAME>/(release|debug|custom)/(ccs|gcc).

FreeRTOS:

* Please view the `FreeRTOSConfig.h` header file for example configuration
information.

## References

* For GNU and IAR users, please read the following website for details
  about enabling [semi-hosting](http://processors.wiki.ti.com/index.php/TI-RTOS_Examples_SemiHosting)
  in order to view console output.
