# Configuring the board

## Klipper

The Klipper configuration for this board is ultimately very simple. The only difference compared to any other fan port, is the specifying of the external MCU and a PWM frequency.

Please reference the Klipper Configuration Reference documentation pages for more in-depth information on setting up the relevant configuration file sections:

- [Micro-controller configuration](https://www.klipper3d.org/Config_Reference.html#micro-controller-configuration)
  - [\[mcu my_extra_mcu\]](https://www.klipper3d.org/Config_Reference.html#mcu-my_extra_mcu)
- [Fans](https://www.klipper3d.org/Config_Reference.html#fans)
  - [\[fan\]](https://www.klipper3d.org/Config_Reference.html#fan)
  - [\[fan_generic\]](https://www.klipper3d.org/Config_Reference.html#fan_generic)

1. Configure the WhisperDrive as an extra MCU

```python
[mcu whisperdrive]
serial: <your-serial-port-here>
restart_method: command # May need to be switched to "rpi_usb" if restarts are ignored
```

2. Configure a fan section to your choosing

```python
[fan]
pin: whisperdrive:<fan-pin>
cycle_time: 0.00004 # 25 kHz, to calculate: cycle_time = 1 / frequency in Hz
# tachometer_pin: # Planned in future revisions
```
