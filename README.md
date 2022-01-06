# DTMFDecoder

A DTMF Decoder development kit designed with KiCad

This is an implementation of SM8223 Application Circuit and integrated with ESP32 Devkit. Makes it handy to retrieve CID(Caller Identification) and handle through both serial port and HTTP requests.

![](https://i.imgur.com/cUNcotL.png)
![](https://i.imgur.com/e5L5kCF.png)
![](https://i.imgur.com/krUBF5t.jpg)

## Components

- ESP32-WROOM-32D DevKit
- [SM8223](https://pdf.dzsc.com/88889/22272.pdf) IC

## IO

### ESP32

IO25 : Read DTMF Signals at the baud rate of 1200
IO33 : indicates the signal type (FSK/DTMF)

## PCB / SMT

GBR is included so that it can go through PCB / SMT process directly

## LICENSE

MIT
