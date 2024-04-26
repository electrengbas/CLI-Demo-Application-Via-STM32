Hi everybody,

This is a demo application of command line interface via STM32

The board I've used is NUCLEO-H563ZI

The board is enables us to have Type-C power delivery and Type-C data transmit/receive from the same USB Virtual Com Port.

The board is employing VCP-to-UART convertor in it. VCP is directly connected to USART3 channel via the converter. This means, when we enable the USART3 channel,
we are able to transmit data to PC and receive data from PC through the VCP.

In this example, I've implemented very basic commands for CLI. I've used Hercules Terminal for PC.
