<div align="center">
    <img alt="JetKVM logo" src="https://jetkvm.com/logo-blue.png" height="28">

### ATX Power Control Firmware

[Discord](https://jetkvm.com/discord) | [Website](https://jetkvm.com) | [Issues](https://github.com/jetkvm/cloud-api/issues) | [Docs](https://jetkvm.com/docs)

[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/jetkvm.svg?style=social&label=Follow%20%40JetKVM)](https://twitter.com/jetkvm)

</div>

This is an ATX power control module for the JetKVM platform, built on the Raspberry Pi RP2040, the same chip as the Raspberry Pi Pico. It provides remote control of PC power and reset functions, along with status monitoring of power and drive activity LEDs.

## Features
- Remote control of PC power and reset buttons via UART interface
- Power and HDD activity LED status monitoring

If you've found an issue and want to report it, please check our [Issues](https://github.com/jetkvm/atx-extension-firmware/issues) page. Make sure the description contains information about the firmware version you're using, your hardware setup, and a clear explanation of the steps to reproduce the issue.

# Development

The firmware is written in C using the Raspberry Pi Pico SDK. Knowledge of C programming and embedded systems is recommended. To get started, see [Getting Started with the Raspberry Pi Pico-Series](https://rptl.io/pico-get-started) for information on how to install the SDK and build the project.
