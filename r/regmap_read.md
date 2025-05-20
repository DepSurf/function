# Function: <code>regmap_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815650d0)
Location: drivers/base/regmap/regmap.c:2259
Inline: False
Direct callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/misc/bmp085.c:bmp085_detect
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm8400-core.c:wm8400_reg_read
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65217.c:tps65217_update_bits
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff815650d0-ffffffff81565127: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815b9b40)
Location: drivers/base/regmap/regmap.c:2359
Inline: False
Direct callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff815b9b40-ffffffff815b9b93: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e8f30)
Location: drivers/base/regmap/regmap.c:2397
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff815e8f30-ffffffff815e8f83: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fd910)
Location: drivers/base/regmap/regmap.c:2402
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff815fd910-ffffffff815fd965: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81665ae0)
Location: drivers/base/regmap/regmap.c:2481
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_vr_val
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_power
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff81665ae0-ffffffff81665b41: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a14b0)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_vr_val
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_power
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff816a14b0-ffffffff816a1511: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1d30)
Location: drivers/base/regmap/regmap.c:2560
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_vr_val
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_power
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff816c1d30-ffffffff816c1d91: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fccb0)
Location: drivers/base/regmap/regmap.c:2557
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_clk_freq
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_clk
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_vr_val
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_power
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff816fccb0-ffffffff816fcd11: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81721060)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_clk_freq
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_clk
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_vr_val
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_power
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff81721060-ffffffff817210c1: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817dcf90)
Location: drivers/base/regmap/regmap.c:2559
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_test_bits
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_init
  - drivers/mfd/wm8400-core.c:wm8400_init
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff817dcf90-ffffffff817dcff1: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f2030)
Location: drivers/base/regmap/regmap.c:2716
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_test_bits
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_init
  - drivers/mfd/wm8400-core.c:wm8400_init
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff817f2030-ffffffff817f2091: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d68e0)
Location: drivers/base/regmap/regmap.c:2716
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_test_bits
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff817d68e0-ffffffff817d6941: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81861ef0)
Location: drivers/base/regmap/regmap.c:2757
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/clk/versatile/clk-icst.c:icst_recalc_rate
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_test_bits
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff81861ef0-ffffffff81861f51: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819a9dc0)
Location: drivers/base/regmap/regmap.c:2777
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_test_bits
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_fix
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff819a9dc0-ffffffff819a9e2b: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1cf90)
Location: drivers/base/regmap/regmap.c:2910
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_test_bits
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_test_bits
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_fix
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff81b1cf90-ffffffff81b1cffb: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6c000)
Location: drivers/base/regmap/regmap.c:2934
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_test_bits
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_test_bits
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_fix
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff81b6c000-ffffffff81b6c06b: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bbfc30)
Location: drivers/base/regmap/regmap.c:2822
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/pwm/pwm-crc.c:crc_pwm_get_state
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_regs_handler
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_get_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_test_bits
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_test_bits
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_fix
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_clear_fault_log
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read_clear_intrbits
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_msg
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
**Symbols:**

```
ffffffff81bbfc30-ffffffff81bbfc9b: regmap_read (STB_GLOBAL)
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
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010915580)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get_gpio_bit
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_suspend
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_get_pull
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_regmap_mpp_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_get
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_get_direction
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_get_direction
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get_direction
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_level_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_cause
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-layerscape.c:ls1021_pcie_link_up
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_link_up_hip05
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_vr_val
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_power
  - drivers/clk/actions/owl-gate.c:owl_gate_clk_is_enabled
  - drivers/clk/actions/owl-gate.c:owl_gate_set
  - drivers/clk/actions/owl-mux.c:owl_mux_helper_set_parent
  - drivers/clk/actions/owl-mux.c:owl_mux_get_parent
  - drivers/clk/actions/owl-divider.c:owl_divider_helper_set_rate
  - drivers/clk/actions/owl-divider.c:owl_divider_helper_recalc_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_helper_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_disable
  - drivers/clk/actions/owl-pll.c:owl_pll_enable
  - drivers/clk/actions/owl-pll.c:owl_pll_is_enabled
  - drivers/clk/actions/owl-reset.c:owl_reset_status
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_round_rate
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_round_rate
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_round_rate
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_recalc_rate
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_bit_is_set
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_bit_is_cleared
  - drivers/clk/mediatek/clk-cpumux.c:clk_cpumux_get_parent
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_get_parent
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_is_enabled
  - drivers/clk/meson/clk-cpu-dyndiv.c:meson_clk_cpu_dyndiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-mpll.c:mpll_recalc_rate
  - drivers/clk/meson/clk-mpll.c:mpll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pcie_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_mux_get_parent
  - drivers/clk/meson/clk-regmap.c:clk_regmap_div_round_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_div_recalc_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_gate_is_enabled
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_round_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_round_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_round_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_recalc_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_recalc_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_recalc_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_parent
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_get_parent
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_get_parent
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_get_parent
  - drivers/clk/mvebu/ap806-system-controller.c:ap806_syscon_common_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_gate_is_enabled
  - drivers/clk/rockchip/clk-muxgrf.c:rockchip_muxgrf_get_parent
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_recalc_rate
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_shutdown
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-ee-pwrc.c:pwrc_ee_get_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
  - drivers/thermal/armada_thermal.c:armada_get_temp_legacy
  - drivers/thermal/armada_thermal.c:armada_select_channel
  - drivers/thermal/armada_thermal.c:armada_cp110_init
  - drivers/thermal/armada_thermal.c:armada_cp110_init
  - drivers/thermal/armada_thermal.c:armada_ap806_init
  - drivers/thermal/armada_thermal.c:armada380_init
  - drivers/thermal/armada_thermal.c:armada380_init
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada370_init
  - drivers/thermal/armada_thermal.c:armadaxp_init
  - drivers/thermal/armada_thermal.c:armadaxp_init
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:s10_edac_dberr_handler
  - drivers/edac/altera_edac.c:altr_edac_a10_irq_handler
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_mc_err_handler
  - drivers/edac/altera_edac.c:altr_sdram_mc_err_handler
  - drivers/edac/altera_edac.c:altr_sdram_mc_err_handler
  - drivers/edac/altera_edac.c:altr_sdram_mc_err_handler
  - drivers/edac/altera_edac.c:altr_sdram_mc_err_handler
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
ffff800010915580-ffff8000109155f8: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fb560)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-imx/anatop.c:imx_anatop_enable_weak2p5
  - arch/arm/mach-imx/mach-imx7ulp.c:imx7ulp_init_machine
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get_gpio_bit
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_suspend
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_get_pull
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pin_config_get
  - drivers/pinctrl/aspeed/pinmux-aspeed.c:aspeed_sig_desc_eval
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_regmap_mpp_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_twsi_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_twsi_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_nand_ctrl_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_dbg_show
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pin_dbg_show
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pin_dbg_show
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pin_dbg_show
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_get_direction
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get_direction
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_level_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_cause
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
  - drivers/clk/clk-aspeed.c:aspeed_reset_status
  - drivers/clk/clk-aspeed.c:aspeed_clk_is_enabled
  - drivers/clk/clk-aspeed.c:aspeed_clk_is_enabled
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_reset_status
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_is_enabled
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_is_enabled
  - drivers/clk/actions/owl-gate.c:owl_gate_clk_is_enabled
  - drivers/clk/actions/owl-gate.c:owl_gate_set
  - drivers/clk/actions/owl-mux.c:owl_mux_helper_set_parent
  - drivers/clk/actions/owl-mux.c:owl_mux_get_parent
  - drivers/clk/actions/owl-divider.c:owl_divider_helper_set_rate
  - drivers/clk/actions/owl-divider.c:owl_divider_helper_recalc_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_helper_set_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_helper_recalc_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_disable
  - drivers/clk/actions/owl-pll.c:owl_pll_enable
  - drivers/clk/actions/owl-pll.c:owl_pll_is_enabled
  - drivers/clk/actions/owl-reset.c:owl_reset_status
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_round_rate
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_round_rate
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_round_rate
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_recalc_rate
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_bit_is_set
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_bit_is_cleared
  - drivers/clk/mediatek/clk-cpumux.c:clk_cpumux_get_parent
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_get_parent
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_is_enabled
  - drivers/clk/meson/clk-mpll.c:mpll_recalc_rate
  - drivers/clk/meson/clk-mpll.c:mpll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pcie_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_mux_get_parent
  - drivers/clk/meson/clk-regmap.c:clk_regmap_div_round_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_div_recalc_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_gate_is_enabled
  - drivers/clk/rockchip/clk-muxgrf.c:rockchip_muxgrf_get_parent
  - drivers/clk/ti/clk.c:clk_memmap_readl
  - drivers/clk/uniphier/clk-uniphier-cpugear.c:uniphier_clk_cpugear_get_parent
  - drivers/clk/uniphier/clk-uniphier-gate.c:uniphier_clk_gate_is_enabled
  - drivers/clk/uniphier/clk-uniphier-mux.c:uniphier_clk_mux_get_parent
  - drivers/clk/versatile/clk-icst.c:icst_recalc_rate
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_recalc_rate
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_on
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_off
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_shutdown
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-ee-pwrc.c:pwrc_ee_get_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_domain_is_idle
  - drivers/soc/samsung/exynos-chipid.c:exynos_chipid_early_init
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_is_jack_det_active
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65217.c:tps65217_update_bits
  - drivers/mfd/tps65217.c:tps65217_irq_thread
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/net/ethernet/ti/cpsw-common.c:cpsw_am33xx_cm_get_macid
  - drivers/net/ethernet/ti/cpsw-common.c:cpsw_am33xx_cm_get_macid
  - drivers/net/ethernet/ti/cpsw-common.c:davinci_emac_3517_get_macid
  - drivers/net/ethernet/ti/cpsw-common.c:davinci_emac_3517_get_macid
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_get_vbus_status
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_get_vbus_status
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_suspend_noirq
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
  - drivers/thermal/armada_thermal.c:armada_get_temp_legacy
  - drivers/thermal/armada_thermal.c:armada_read_sensor
  - drivers/thermal/armada_thermal.c:armada_select_channel
  - drivers/thermal/armada_thermal.c:armada_cp110_init
  - drivers/thermal/armada_thermal.c:armada_cp110_init
  - drivers/thermal/armada_thermal.c:armada_ap806_init
  - drivers/thermal/armada_thermal.c:armada380_init
  - drivers/thermal/armada_thermal.c:armada380_init
  - drivers/thermal/armada_thermal.c:armada_wait_sensor_validity
  - drivers/thermal/armada_thermal.c:armada_wait_sensor_validity
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada370_init
  - drivers/thermal/armada_thermal.c:armadaxp_init
  - drivers/thermal/armada_thermal.c:armadaxp_init
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_get_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_get_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_get_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_v2_disable
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_get_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_set_event
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_disable
  - sound/soc/soc-ops.c:snd_soc_bytes_put
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_suspend
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_suspend
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_dai_tdm_slot
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_isr
```
**Symbols:**

```
c09fb560-c09fb5cc: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b7a90)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_is_jack_det_active
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
c0000000009b7a90-c0000000009b7b48: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000596780)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_is_jack_det_active
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
ffffffe000596780-ffffffe0005967de: regmap_read (STB_GLOBAL)
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
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e7390)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
**Symbols:**

```
ffffffff816e7390-ffffffff816e73f1: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c19d0)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
```
**Symbols:**

```
ffffffff816c19d0-ffffffff816c1a31: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81714520)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_clk_freq
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_clk
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_vr_val
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_power
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff81714520-ffffffff81714581: regmap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_read(struct regmap *map, unsigned int reg, unsigned int *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8172f720)
Location: drivers/base/regmap/regmap.c:2564
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_clk_freq
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_clk
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_vr_val
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_get_power
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_bypass_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_is_enabled_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_tx_empty
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max14830_detect
  - drivers/tty/serial/max310x.c:max3109_detect
  - drivers/tty/serial/max310x.c:max3108_detect
  - drivers/tty/serial/max310x.c:max3107_detect
  - drivers/base/regmap/regmap.c:regmap_fields_read
  - drivers/base/regmap/regmap.c:regmap_field_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/88pm860x-i2c.c:pm860x_reg_read
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_enable_freerun_sysclk
  - drivers/mfd/arizona-core.c:arizona_underclocked
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_reg_read
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_get_vibralr_status
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-core.c:da9052_clear_fault_log
  - drivers/mfd/da9052-core.c:da9052_adc_read_temp
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_read_byte
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_read
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff8172f720-ffffffff8172f781: regmap_read (STB_GLOBAL)
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
