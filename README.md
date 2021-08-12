# raspberryPi

### Raspberry Something

**Bluetooth**

_first step: open the Bluetooth manager   enter the  "bluetoothctl" and "agent on" in terminal_

_second step: find MAC address of your bluetooth devices enter the "scan on", then you will see something like the code_
`bluetoothctl`
`agent on`
`scan on` 
`[CHG] Device C0:9F:05:49:99:2C Modalias: bluetooth:v0046p0802d0903`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 00001105-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 0000110a-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 0000110c-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 0000110e-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 00001112-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 00001115-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 00001116-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 0000111f-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 0000112f-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 00001132-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 00001200-0000-1000-8000-00805f9b34fb`
`[CHG] Device C0:9F:05:49:99:2C UUIDs: 00001800-0000-1000-8000-00805f9b34fb`

_last step: connect the bluetooth enter the "pair xx:xx:xx:xx:xx:xx" like the code and last you can trust the device enter the "trust  xx:xx:xx:xx:xx:xx" to auto connect the bluetooth_
`pair C0:9F:05:49:99:2C`
`Pairing successful`
`trust C0:9F:05:49:99:2C`
