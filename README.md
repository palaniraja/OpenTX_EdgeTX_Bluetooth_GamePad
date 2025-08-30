# WIP

## TX16S MK II - Bluetooth Joystick Mod


My attempt to use TX16S module bay micro RF with an ESP32/Pico2 to act as bluetooth joystick to connect to a computer to use it with simulator.

My attempt to use a TX16S module bay micro RF unit with an ESP32 or Pico2 to act as a Bluetooth joystick for connecting to a computer and using it with a simulator

### Pinout?

```
+-------+-----------------------------+
| Pin   | Description                 |
+-------+-----------------------------+
| SBUS  | Ext. module PPM/SBUS input  |
| HB    | Heartbeat signal            |
| +BAT  | External RF module power    |
| GND   | Ground                      |
| TELE  | S.Port telemetry output     |
+-------+-----------------------------+

```

+BAT - receiving 7.23? (3x18650 battery 3.7v)

### References:

- [Pinout](https://www.rcgroups.com/forums/showthread.php?3869543-Blog-17-RadioMaster-TX16S-schematic-diagram/page3)
- [moschotto/OpenTX_EdgeTX_Bluetooth_GamePad](https://github.com/moschotto/OpenTX_EdgeTX_Bluetooth_GamePad)
- [Radio Preparation](https://www.expresslrs.org/quick-start/transmitters/tx-prep/)