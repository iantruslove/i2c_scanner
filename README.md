# I2C Scanner

Scans the I2C bus, printing out any addresses that correctly start an I2C protocol transmission.

Install platformio.

`platformio run --target upload`

Fire up a serial monitor.

You should see stuff like this:

```
I2C Scanner
Scanning...
I2C device found at address 0x4A  !
I2C device found at address 0x76  !
done
```
