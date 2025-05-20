# Function: <code>regmap_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81566980)
Location: drivers/base/regmap/regmap.c:1512
Inline: False
Direct callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/misc/bmp085.c:bmp085_update_raw_temperature
  - drivers/misc/bmp085.c:show_pressure
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/axp20x.c:axp20x_power_off
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff81566980-ffffffff815669d6: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815bb310)
Location: drivers/base/regmap/regmap.c:1620
Inline: False
Direct callers:
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff815bb310-ffffffff815bb363: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ea720)
Location: drivers/base/regmap/regmap.c:1666
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff815ea720-ffffffff815ea773: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ff080)
Location: drivers/base/regmap/regmap.c:1669
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff815ff080-ffffffff815ff0d5: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81667340)
Location: drivers/base/regmap/regmap.c:1748
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff81667340-ffffffff816673a1: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a2c00)
Location: drivers/base/regmap/regmap.c:1764
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff816a2c00-ffffffff816a2c61: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3620)
Location: drivers/base/regmap/regmap.c:1800
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff816c3620-ffffffff816c3681: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fe4d0)
Location: drivers/base/regmap/regmap.c:1797
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff816fe4d0-ffffffff816fe531: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817228f0)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff817228f0-ffffffff81722951: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817dec10)
Location: drivers/base/regmap/regmap.c:1799
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init_hw
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init_hw
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_disable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_disable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff817dec10-ffffffff817dec71: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f3c90)
Location: drivers/base/regmap/regmap.c:1948
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init_hw
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init_hw
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_disable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_disable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff817f3c90-ffffffff817f3cf1: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d8500)
Location: drivers/base/regmap/regmap.c:1948
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_disable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_disable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff817d8500-ffffffff817d8561: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81863c40)
Location: drivers/base/regmap/regmap.c:1989
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/clk/versatile/clk-icst.c:icst_set_rate
  - drivers/clk/versatile/clk-icst.c:icst_set_rate
  - drivers/clk/versatile/clk-icst.c:vco_set
  - drivers/clk/versatile/clk-icst.c:vco_set
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_notify
```
**Symbols:**

```
ffffffff81863c40-ffffffff81863ca1: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819abde0)
Location: drivers/base/regmap/regmap.c:2008
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_notify
```
**Symbols:**

```
ffffffff819abde0-ffffffff819abe4b: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1f390)
Location: drivers/base/regmap/regmap.c:2012
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/tty/serial/max310x.c:max310x_spi_extended_reg_enable
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff81b1f390-ffffffff81b1f3fb: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6e590)
Location: drivers/base/regmap/regmap.c:2030
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/tty/serial/max310x.c:max310x_spi_extended_reg_enable
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff81b6e590-ffffffff81b6e5fb: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bc2190)
Location: drivers/base/regmap/regmap.c:1938
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/pwm/pwm-crc.c:crc_pwm_apply
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/tty/serial/max310x.c:max310x_spi_extended_reg_enable
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff81bc2190-ffffffff81bc21fb: regmap_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010917240)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_resume
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_set_pull
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_set_mux
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_set_pull_select
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_set_pull_select
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_spec_set_ies_smt_range
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_set_ies_smt
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_set_direction
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_level_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/clk/actions/owl-gate.c:owl_gate_set
  - drivers/clk/actions/owl-mux.c:owl_mux_helper_set_parent
  - drivers/clk/actions/owl-divider.c:owl_divider_helper_set_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_helper_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_disable
  - drivers/clk/actions/owl-pll.c:owl_pll_enable
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_set_rate
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_disable_inv
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_enable_inv
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_disable
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_enable
  - drivers/clk/mediatek/reset.c:mtk_reset_set_clr
  - drivers/clk/mediatek/reset.c:mtk_reset_set_clr
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_disable_setclr
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_enable_setclr
  - drivers/clk/meson/meson-aoclk.c:meson_aoclk_do_reset
  - drivers/clk/rockchip/clk-muxgrf.c:rockchip_muxgrf_set_parent
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_set_rate
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/rockchip/grf.c:rockchip_grf_init
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/reset/reset-berlin.c:berlin_reset_reset
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_enable_ldo_in_suspend
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_enable_ldo_in_suspend
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/power/reset/vexpress-poweroff.c:vexpress_reset_do
  - drivers/power/reset/sc27xx-poweroff.c:sc27xx_poweroff_do_poweroff
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_select_channel
  - drivers/thermal/armada_thermal.c:armada_select_channel
  - drivers/thermal/armada_thermal.c:armada_select_channel
  - drivers/thermal/armada_thermal.c:armada_cp110_init
  - drivers/thermal/armada_thermal.c:armada_cp110_init
  - drivers/thermal/armada_thermal.c:armada_ap806_init
  - drivers/thermal/armada_thermal.c:armada380_init
  - drivers/thermal/armada_thermal.c:armada380_init
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada370_init
  - drivers/thermal/armada_thermal.c:armadaxp_init
  - drivers/thermal/armada_thermal.c:armadaxp_init
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:s10_edac_dberr_handler
  - drivers/edac/altera_edac.c:s10_edac_dberr_handler
  - drivers/edac/altera_edac.c:a10_eccmgr_irq_unmask
  - drivers/edac/altera_edac.c:a10_eccmgr_irq_mask
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_mc_err_handler
```
**Symbols:**

```
ffff800010917240-ffff8000109172b8: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fd0c8)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - arch/arm/mach-alpine/alpine_cpu_pm.c:alpine_cpu_wakeup
  - arch/arm/mach-imx/anatop.c:imx_anatop_init
  - arch/arm/mach-imx/anatop.c:imx_anatop_init
  - arch/arm/mach-imx/anatop.c:imx_anatop_post_resume
  - arch/arm/mach-imx/anatop.c:imx_anatop_post_resume
  - arch/arm/mach-imx/anatop.c:imx_anatop_post_resume
  - arch/arm/mach-imx/anatop.c:imx_anatop_pre_suspend
  - arch/arm/mach-imx/anatop.c:imx_anatop_pre_suspend
  - arch/arm/mach-imx/anatop.c:imx_anatop_pre_suspend
  - arch/arm/mach-imx/anatop.c:imx_anatop_enable_weak2p5
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_resume
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_set_pull
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_set_mux
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_disable
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_suspend
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_resume
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pmx_set_one_mux
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_set_pull_select
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_set_pull_select
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_spec_pull_set_samereg
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_spec_set_ies_smt_range
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_set_ies_smt
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_set_direction
  - drivers/pinctrl/mediatek/pinctrl-mt8135.c:spec_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mt8135.c:spec_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mt8135.c:spec_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mt8135.c:spec_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mt8135.c:spec_pull_set
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_level_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_irq
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_reset_assert
  - drivers/clk/clk-ast2600.c:aspeed_g6_reset_deassert
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_disable
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_disable
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_enable
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_enable
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_enable
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_enable
  - drivers/clk/actions/owl-gate.c:owl_gate_set
  - drivers/clk/actions/owl-mux.c:owl_mux_helper_set_parent
  - drivers/clk/actions/owl-divider.c:owl_divider_helper_set_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_helper_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_disable
  - drivers/clk/actions/owl-pll.c:owl_pll_enable
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_set_rate
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_disable_inv
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_enable_inv
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_disable
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_enable
  - drivers/clk/mediatek/reset.c:mtk_reset_set_clr
  - drivers/clk/mediatek/reset.c:mtk_reset_set_clr
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_disable_setclr
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_enable_setclr
  - drivers/clk/rockchip/clk-muxgrf.c:rockchip_muxgrf_set_parent
  - drivers/clk/ti/clk.c:clk_memmap_writel
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_set_rate
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/rockchip/grf.c:rockchip_grf_init
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/reset/reset-berlin.c:berlin_reset_reset
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_disable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_disable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_enable_ldo_in_suspend
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_enable_ldo_in_suspend
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_resume_noirq
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/vexpress-poweroff.c:vexpress_reset_do
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_select_channel
  - drivers/thermal/armada_thermal.c:armada_select_channel
  - drivers/thermal/armada_thermal.c:armada_select_channel
  - drivers/thermal/armada_thermal.c:armada_cp110_init
  - drivers/thermal/armada_thermal.c:armada_cp110_init
  - drivers/thermal/armada_thermal.c:armada_ap806_init
  - drivers/thermal/armada_thermal.c:armada380_init
  - drivers/thermal/armada_thermal.c:armada380_init
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada370_init
  - drivers/thermal/armada_thermal.c:armadaxp_init
  - drivers/thermal/armada_thermal.c:armadaxp_init
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_disable
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_resume
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_remove
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_remove
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_dai_tdm_slot
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_dai_tdm_slot
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_isr
```
**Symbols:**

```
c09fd0c8-c09fd134: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b9ff0)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
c0000000009b9ff0-c0000000009ba0a8: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000597c0a)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffe000597c0a-ffffffe000597c68: regmap_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e8c20)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
**Symbols:**

```
ffffffff816e8c20-ffffffff816e8c81: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3260)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
**Symbols:**

```
ffffffff816c3260-ffffffff816c32c1: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81715db0)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff81715db0-ffffffff81715e11: regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81731050)
Location: drivers/base/regmap/regmap.c:1804
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/pwm/pwm-crc.c:crc_pwm_config
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_shutdown
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:wm5102_apply_hardware_patch
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_reg_write
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_power_off
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_write_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_sync_unlock
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_sync_unlock
```
**Symbols:**

```
ffffffff81731050-ffffffff817310b1: regmap_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
