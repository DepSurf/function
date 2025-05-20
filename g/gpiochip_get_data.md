# Function: <code>gpiochip_get_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146d620)
Location: drivers/gpio/gpiolib.c:1217
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_debounce
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_lock
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_set_type
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_unmask
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_mask
  - drivers/gpio/gpio-sx150x.c:sx150x_gpio_direction_output
  - drivers/gpio/gpio-sx150x.c:sx150x_gpio_direction_input
  - drivers/gpio/gpio-sx150x.c:sx150x_gpio_set_single_ended
  - drivers/gpio/gpio-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-sx150x.c:sx150x_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_set_value
  - drivers/gpio/gpio-zx.c:zx_get_value
  - drivers/gpio/gpio-zx.c:zx_direction_output
  - drivers/gpio/gpio-zx.c:zx_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff8146d620-ffffffff8146d636: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148f4f0)
Location: drivers/gpio/gpiolib.c:1298
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_debounce
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_single_ended
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff8148f4f0-ffffffff8148f506: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81498f40)
Location: drivers/gpio/gpiolib.c:1291
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff81498f40-ffffffff81498f56: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d7230)
Location: drivers/gpio/gpiolib.c:1319
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff814d7230-ffffffff814d7246: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815063f0)
Location: drivers/gpio/gpiolib.c:1426
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff815063f0-ffffffff81506406: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151a8a0)
Location: drivers/gpio/gpiolib.c:1456
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff8151a8a0-ffffffff8151a8b6: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81548a40)
Location: drivers/gpio/gpiolib.c:1475
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff81548a40-ffffffff81548a56: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81569a90)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff81569a90-ffffffff81569aa6: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160c3c0)
Location: drivers/gpio/gpiolib.c:1862
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_lock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_type
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-msic.c:msic_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff8160c3c0-ffffffff8160c3d6: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81633200)
Location: drivers/gpio/gpiolib.c:809
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_lock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_type
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-msic.c:msic_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff81633200-ffffffff81633216: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81616ee0)
Location: drivers/gpio/gpiolib.c:798
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_lock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_type
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff81616ee0-ffffffff81616ef6: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81686160)
Location: drivers/gpio/gpiolib.c:820
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_lock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_type
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff81686160-ffffffff81686176: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a2ae0)
Location: drivers/gpio/gpiolib.c:850
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_lock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_type
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff817a2ae0-ffffffff817a2afc: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818b9d30)
Location: drivers/gpio/gpiolib.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_lock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_type
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
```
**Symbols:**

```
ffffffff818b9d30-ffffffff818b9d4c: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fce20)
Location: drivers/gpio/gpiolib.c:697
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_print_chip
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_lock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_type
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
```
**Symbols:**

```
ffffffff818fce20-ffffffff818fce3c: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81944510)
Location: drivers/gpio/gpiolib.c:771
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_print_chip
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dbg_show
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_lock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_type
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_get
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_out
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_dir_in
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
```
**Symbols:**

```
ffffffff81944510-ffffffff8194452c: gpiochip_get_data (STB_GLOBAL)
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
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bd718)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_to_irq
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_set
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_direction_output
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_direction_input
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_to_irq
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_ack
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_unmask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_mask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_ack
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handler
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_get_direction
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_get
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_direction
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_free
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_request
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_ack
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_ack
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_set
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_get
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_direction_output
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_get_direction
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_reqres
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get_direction
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_to_irq
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_to_irq
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_get_direction
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_to_irq
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_to_irq
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_get_direction
  - drivers/gpio/gpio-davinci.c:gpio_to_irq_unbanked
  - drivers/gpio/gpio-davinci.c:gpio_to_irq_banked
  - drivers/gpio/gpio-davinci.c:davinci_gpio_set
  - drivers/gpio/gpio-davinci.c:davinci_gpio_get
  - drivers/gpio/gpio-davinci.c:davinci_direction_out
  - drivers/gpio/gpio-davinci.c:davinci_direction_in
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_to_irq
  - drivers/gpio/gpio-mpc8xxx.c:mpc5125_gpio_dir_out
  - drivers/gpio/gpio-mpc8xxx.c:mpc5121_gpio_dir_out
  - drivers/gpio/gpio-mpc8xxx.c:mpc8572_gpio_get
  - drivers/gpio/gpio-mpc8xxx.c:ls1028a_gpio_dir_in_init
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_to_irq
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get_direction
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_direction_output
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_direction_input
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_blink
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_set
  - drivers/gpio/gpio-mxc.c:mxc_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-pl061.c:pl061_irq_set_wake
  - drivers/gpio/gpio-pl061.c:pl061_irq_ack
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_set_value
  - drivers/gpio/gpio-pl061.c:pl061_get_value
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
  - drivers/gpio/gpio-pl061.c:pl061_get_direction
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-stmpe.c:stmpe_init_irq_valid_mask
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_unmask
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_mask
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_lock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_set_type
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_request
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_input
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_output
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get_direction
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_set
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_unmask
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_mask
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_sync_unlock
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_lock
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_set_type
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_get_direction
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:xgene_gpio_get_direction
  - drivers/gpio/gpio-xgene.c:xgene_gpio_set
  - drivers/gpio/gpio-xgene.c:__xgene_gpio_set
  - drivers/gpio/gpio-xgene.c:xgene_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffff8000106bd718-ffff8000106bd744: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085cd5c)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_to_irq
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_get
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_set
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_direction_output
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_gpio_direction_input
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_to_irq
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get_direction
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_set
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get_direction
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_free
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_request
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_direction_output
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_set
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_get
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_direction_input
  - drivers/pinctrl/pinctrl-rza2.c:rza2_chip_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_ack
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_unmask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_mask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_unmask
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_mask
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_ack
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_set_irq_type
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_gpio_request
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_direction_output
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_direction_input
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_reqres
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get_direction
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_to_irq
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_direction_output
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_direction_input
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set_direction
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_get
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set_value
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_to_irq
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_set
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_get
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_direction_output
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_request
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_to_irq
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_get_direction
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_to_irq
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_get
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_ack_irq
  - drivers/gpio/gpio-htc-egpio.c:egpio_get_direction
  - drivers/gpio/gpio-htc-egpio.c:egpio_direction_output
  - drivers/gpio/gpio-htc-egpio.c:egpio_set
  - drivers/gpio/gpio-htc-egpio.c:egpio_direction_input
  - drivers/gpio/gpio-htc-egpio.c:egpio_get
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_to_irq
  - drivers/gpio/gpio-mpc8xxx.c:mpc5125_gpio_dir_out
  - drivers/gpio/gpio-mpc8xxx.c:mpc5121_gpio_dir_out
  - drivers/gpio/gpio-mpc8xxx.c:mpc8572_gpio_get
  - drivers/gpio/gpio-mpc8xxx.c:ls1028a_gpio_dir_in_init
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_dbg_show
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_to_irq
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get_direction
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_direction_output
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_direction_input
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_blink
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_get
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_set
  - drivers/gpio/gpio-mxc.c:mxc_gpio_to_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_set_multiple
  - drivers/gpio/gpio-omap.c:omap_gpio_set
  - drivers/gpio/gpio-omap.c:omap_gpio_set_config
  - drivers/gpio/gpio-omap.c:omap_gpio_get_multiple
  - drivers/gpio/gpio-omap.c:omap_gpio_output
  - drivers/gpio/gpio-omap.c:omap_gpio_get
  - drivers/gpio/gpio-omap.c:omap_gpio_input
  - drivers/gpio/gpio-omap.c:omap_gpio_get_direction
  - drivers/gpio/gpio-omap.c:omap_gpio_free
  - drivers/gpio/gpio-omap.c:omap_gpio_request
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_mask_irq
  - drivers/gpio/gpio-omap.c:gpio_irq_bus_sync_unlock
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_bus_lock
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_startup
  - drivers/gpio/gpio-omap.c:omap_gpio_wake_enable
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_type
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-pl061.c:pl061_suspend
  - drivers/gpio/gpio-pl061.c:pl061_irq_set_wake
  - drivers/gpio/gpio-pl061.c:pl061_irq_ack
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_set_value
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
  - drivers/gpio/gpio-pl061.c:pl061_get_direction
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-stmpe.c:stmpe_init_irq_valid_mask
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_unmask
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_mask
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_lock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_set_type
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_request
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_input
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_output
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get_direction
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_set
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_unmask
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_mask
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_sync_unlock
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_lock
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_set_type
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_get_direction
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_get
  - drivers/gpio/gpio-tegra.c:tegra_gpio_to_irq
  - drivers/gpio/gpio-tegra.c:tegra_gpio_set_config
  - drivers/gpio/gpio-tegra.c:tegra_gpio_get_direction
  - drivers/gpio/gpio-tegra.c:tegra_gpio_direction_output
  - drivers/gpio/gpio-tegra.c:tegra_gpio_direction_input
  - drivers/gpio/gpio-tegra.c:tegra_gpio_get
  - drivers/gpio/gpio-tegra.c:tegra_gpio_set
  - drivers/gpio/gpio-tegra.c:tegra_gpio_free
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-twl4030.c:twl_to_irq
  - drivers/gpio/gpio-twl4030.c:twl_get_direction
  - drivers/gpio/gpio-twl4030.c:twl_direction_out
  - drivers/gpio/gpio-twl4030.c:twl_set
  - drivers/gpio/gpio-twl4030.c:twl_get
  - drivers/gpio/gpio-twl4030.c:twl_direction_in
  - drivers/gpio/gpio-twl4030.c:twl_free
  - drivers/gpio/gpio-twl4030.c:twl_request
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_wake
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_unmask
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_mask
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_type
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_ack
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
  - drivers/gpio/gpio-vf610.c:vf610_gpio_direction_output
  - drivers/gpio/gpio-vf610.c:vf610_gpio_direction_output
  - drivers/gpio/gpio-vf610.c:vf610_gpio_direction_input
  - drivers/gpio/gpio-vf610.c:vf610_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_output
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_input
  - drivers/gpio/gpio-zevio.c:zevio_gpio_set
  - drivers/gpio/gpio-zevio.c:zevio_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/sm501.c:sm501_gpio_output
  - drivers/mfd/sm501.c:sm501_gpio_input
  - drivers/mfd/sm501.c:sm501_gpio_set
  - drivers/mfd/sm501.c:sm501_gpio_get
  - drivers/mfd/asic3.c:asic3_gpio_to_irq
  - drivers/mfd/asic3.c:asic3_gpio_set
  - drivers/mfd/asic3.c:asic3_gpio_get
  - drivers/mfd/asic3.c:asic3_gpio_direction
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_direction_output
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_direction_input
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_set
  - drivers/mfd/tc6393xb.c:__tc6393xb_gpio_set
  - drivers/mfd/tc6393xb.c:tc6393xb_gpio_get
  - sound/soc/soc-ac97.c:snd_soc_ac97_gpio_direction_out
  - sound/soc/soc-ac97.c:snd_soc_ac97_gpio_set
  - sound/soc/soc-ac97.c:snd_soc_ac97_gpio_set
  - sound/soc/soc-ac97.c:snd_soc_ac97_gpio_get
  - sound/soc/soc-ac97.c:snd_soc_ac97_gpio_direction_in
```
**Symbols:**

```
c085cd5c-c085cd7c: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000838f60)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_to_irq
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_ack
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_unmask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_mask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_ack_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-stmpe.c:stmpe_init_irq_valid_mask
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_unmask
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_mask
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_lock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_set_type
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_request
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_input
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_output
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get_direction
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_set
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_unmask
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_mask
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_sync_unlock
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_lock
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_set_type
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_get_direction
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
c000000000838f60-c000000000838f74: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a3fb8)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_to_irq
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_ack
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_unmask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_mask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_direction_output
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_get
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_ack_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-stmpe.c:stmpe_init_irq_valid_mask
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_unmask
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_mask
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_sync_unlock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_lock
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq_set_type
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_request
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_input
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_output
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get_direction
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_set
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_get
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_unmask
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_mask
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_sync_unlock
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_lock
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq_set_type
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_get_direction
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffe0004a3fb8-ffffffe0004a3fde: gpiochip_get_data (STB_GLOBAL)
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
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155f250)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
```
**Symbols:**

```
ffffffff8155f250-ffffffff8155f266: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815500a0)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
```
**Symbols:**

```
ffffffff815500a0-ffffffff815500b6: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155ddc0)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff8155ddc0-ffffffff8155ddd6: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *gpiochip_get_data(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81577c50)
Location: drivers/gpio/gpiolib.c:1484
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_sync_unlock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_bus_lock
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_set_type
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_ack
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get_direction
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_resume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_init_hw
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_disable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_output
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_direction_input
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_set
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_get
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/gpio/gpio-palmas.c:palmas_gpio_to_irq
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-palmas.c:palmas_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_get
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_to_irq
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_get
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_to_irq
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_output
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_set
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_get
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_get
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get_direction
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_get
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_get
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_to_irq
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_get
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
**Symbols:**

```
ffffffff81577c50-ffffffff81577c66: gpiochip_get_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip *chip</code>
</li>
</ul>
</details>
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
