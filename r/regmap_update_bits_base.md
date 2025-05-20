# Function: <code>regmap_update_bits_base</code>

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
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815bb200)
Location: drivers/base/regmap/regmap.c:2676
Inline: False
Direct callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff815bb200-ffffffff815bb27c: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ea610)
Location: drivers/base/regmap/regmap.c:2714
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_single_ended
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_single_ended
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff815ea610-ffffffff815ea68c: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fef70)
Location: drivers/base/regmap/regmap.c:2721
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff815fef70-ffffffff815fefec: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81667220)
Location: drivers/base/regmap/regmap.c:2800
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/tps68470_pmic.c:ti_tps68470_regmap_update_bits
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81667220-ffffffff816672a8: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a2ae0)
Location: drivers/base/regmap/regmap.c:2755
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/tps68470_pmic.c:ti_tps68470_regmap_update_bits
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff816a2ae0-ffffffff816a2b68: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3500)
Location: drivers/base/regmap/regmap.c:2915
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/tps68470_pmic.c:ti_tps68470_regmap_update_bits
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff816c3500-ffffffff816c3588: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fe3b0)
Location: drivers/base/regmap/regmap.c:2912
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/tps68470_pmic.c:ti_tps68470_regmap_update_bits
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff816fe3b0-ffffffff816fe438: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817227d0)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/tps68470_pmic.c:ti_tps68470_regmap_update_bits
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff817227d0-ffffffff81722858: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817deba8)
Location: drivers/base/regmap/regmap.c:2914
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff817dea30-ffffffff817deab8: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f3c28)
Location: drivers/base/regmap/regmap.c:3071
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff817f3ab0-ffffffff817f3b38: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d849e)
Location: drivers/base/regmap/regmap.c:3071
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff817d8320-ffffffff817d83a8: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81863bce)
Location: drivers/base/regmap/regmap.c:3112
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/clk/versatile/clk-icst.c:icst_set_rate
  - drivers/clk/versatile/clk-icst.c:vco_set
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81863a30-ffffffff81863ab8: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819abd6c)
Location: drivers/base/regmap/regmap.c:3129
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff819abbb0-ffffffff819abc4a: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1f30c)
Location: drivers/base/regmap/regmap.c:3283
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81b1f130-ffffffff81b1f1ca: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6e507)
Location: drivers/base/regmap/regmap.c:3312
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81b6e340-ffffffff81b6e3da: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bc2107)
Location: drivers/base/regmap/regmap.c:3192
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81bc1f40-ffffffff81bc1fda: regmap_update_bits_base (STB_GLOBAL)
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
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff8000109170a0)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_enable_bias
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_enable_bias
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set_gpio_bit
  - drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_set_mux
  - drivers/pinctrl/meson/pinctrl-meson-axg-pmx.c:meson_axg_pmx_update_function
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_set_mux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_set_pull
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_set_mux
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_ack
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_unmask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_mask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux
  - drivers/pinctrl/berlin/berlin.c:berlin_pinmux_set
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_regmap_mpp_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_set
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_direction_output
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_direction_output
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_direction_input
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_set_by_name
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mode
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mode
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_direction_output
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_direction_input
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_blink
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/acpi/pmic/tps68470_pmic.c:ti_tps68470_regmap_update_bits
  - drivers/clk/actions/owl-reset.c:owl_reset_deassert
  - drivers/clk/actions/owl-reset.c:owl_reset_assert
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_clr_bit_no_setclr
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_set_bit_no_setclr
  - drivers/clk/mediatek/clk-cpumux.c:clk_cpumux_set_parent
  - drivers/clk/mediatek/reset.c:mtk_reset_deassert
  - drivers/clk/mediatek/reset.c:mtk_reset_assert
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_disable
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_enable
  - drivers/clk/meson/clk-cpu-dyndiv.c:meson_clk_cpu_dyndiv_set_rate
  - drivers/clk/meson/clk-cpu-dyndiv.c:meson_clk_cpu_dyndiv_set_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_set_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_set_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_set_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_set_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_set_rate
  - drivers/clk/meson/clk-mpll.c:mpll_init
  - drivers/clk/meson/clk-mpll.c:mpll_init
  - drivers/clk/meson/clk-mpll.c:mpll_init
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_disable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_disable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_init
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_init
  - drivers/clk/meson/clk-regmap.c:clk_regmap_mux_set_parent
  - drivers/clk/meson/clk-regmap.c:clk_regmap_div_set_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_gate_endisable
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_parent
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_parent
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_gate_disable
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_gate_enable
  - drivers/clk/rockchip/clk-muxgrf.c:rockchip_muxgrf_set_parent
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/reset/reset-imx7.c:imx8mq_reset_set
  - drivers/reset/reset-imx7.c:imx7_reset_set
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77620.c:max77620_set_fps_period
  - drivers/mfd/max77620.c:max77620_pm_power_off
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_irq_global_unmask
  - drivers/mfd/max77620.c:max77620_irq_global_mask
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_power_off
  - drivers/mfd/palmas.c:palmas_power_off
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/power/reset/as3722-poweroff.c:as3722_pm_power_off
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
ffff8000109170a0-ffff800010917138: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fcf88)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_cpu_kill
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_cpu_kill
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_cpu_kill
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_cpu_kill
  - arch/arm/mach-meson/platsmp.c:meson8_smp_cpu_kill
  - arch/arm/mach-meson/platsmp.c:meson8_smp_cpu_kill
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8_smp_boot_secondary
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_machine
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_machine
  - arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_machine
  - arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_machine
  - arch/arm/mach-imx/mach-imx6ul.c:imx6ul_init_machine
  - arch/arm/mach-imx/mach-imx7d.c:imx7d_init_machine
  - arch/arm/mach-imx/mach-imx7d.c:imx7d_init_machine
  - arch/arm/mach-imx/pm-imx6.c:imx6sl_pm_init
  - arch/arm/mach-imx/pm-imx6.c:imx6_pm_common_init
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_power_off
  - drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_power_on
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_power_off
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_power_off
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_power_on
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_power_on
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_power_off
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_power_on
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_enable_bias
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_enable_bias
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set_gpio_bit
  - drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_set_mux
  - drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_disable_other_groups
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_set_mux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_set_pull
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_set_mux
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_ack
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_unmask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_mask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pin_config_set
  - drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c:aspeed_g6_sig_expr_set
  - drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c:aspeed_g6_sig_expr_set
  - drivers/pinctrl/berlin/berlin.c:berlin_pinmux_set
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_regmap_mpp_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_twsi_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_twsi_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_nand_ctrl_set
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_setfunc
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_setfunc
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_setfunc
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_remove
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_set
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pmx_set_one_mux
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_input_enable
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mode
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-mt2701.c:mt2701_spec_pinmux_set
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_set_type
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_direction_output
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_direction_input
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_blink
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_unaligned_memaccess
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/clk/clk-aspeed.c:aspeed_reset_assert
  - drivers/clk/clk-aspeed.c:aspeed_reset_deassert
  - drivers/clk/clk-aspeed.c:aspeed_clk_disable
  - drivers/clk/clk-aspeed.c:aspeed_clk_enable
  - drivers/clk/clk-aspeed.c:aspeed_clk_enable
  - drivers/clk/clk-aspeed.c:aspeed_clk_enable
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/actions/owl-reset.c:owl_reset_deassert
  - drivers/clk/actions/owl-reset.c:owl_reset_assert
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_clr_bit_no_setclr
  - drivers/clk/mediatek/clk-gate.c:mtk_cg_set_bit_no_setclr
  - drivers/clk/mediatek/clk-cpumux.c:clk_cpumux_set_parent
  - drivers/clk/mediatek/reset.c:mtk_reset_deassert
  - drivers/clk/mediatek/reset.c:mtk_reset_assert
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_disable
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_enable
  - drivers/clk/meson/clk-mpll.c:mpll_init
  - drivers/clk/meson/clk-mpll.c:mpll_init
  - drivers/clk/meson/clk-mpll.c:mpll_init
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_disable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_disable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_init
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_init
  - drivers/clk/meson/clk-regmap.c:clk_regmap_mux_set_parent
  - drivers/clk/meson/clk-regmap.c:clk_regmap_div_set_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_gate_endisable
  - drivers/clk/meson/meson8b.c:meson8b_clk_reset_deassert
  - drivers/clk/meson/meson8b.c:meson8b_clk_reset_assert
  - drivers/clk/rockchip/clk-muxgrf.c:rockchip_muxgrf_set_parent
  - drivers/clk/ti/clk.c:clk_memmap_rmw
  - drivers/clk/uniphier/clk-uniphier-gate.c:uniphier_clk_gate_disable
  - drivers/clk/uniphier/clk-uniphier-gate.c:uniphier_clk_gate_enable
  - drivers/clk/uniphier/clk-uniphier-mux.c:uniphier_clk_mux_set_parent
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_on
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_on
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_off
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_off
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/reset/reset-imx7.c:imx7_reset_update
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/iommu/omap-iommu.c:dra7_cfg_dspsys_mmu
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_connect_dcvdd
  - drivers/mfd/arizona-core.c:arizona_isolate_dcvdd
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77620.c:max77620_set_fps_period
  - drivers/mfd/max77620.c:max77620_pm_power_off
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_irq_global_unmask
  - drivers/mfd/max77620.c:max77620_irq_global_mask
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_power_off
  - drivers/mfd/palmas.c:palmas_power_off
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/power/reset/as3722-poweroff.c:as3722_pm_power_off
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_set_event
  - sound/soc/soc-io.c:snd_soc_component_update_bits_async
  - sound/soc/soc-io.c:snd_soc_component_update_bits
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_resume
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_remove
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_remove
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_trigger
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_dai_tdm_slot
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_dai_tdm_slot
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_dai_tdm_slot
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_dai_tdm_slot
  - sound/soc/fsl/fsl_ssi.c:_fsl_ssi_set_dai_fmt
  - sound/soc/fsl/fsl_ssi.c:_fsl_ssi_set_dai_fmt
  - sound/soc/fsl/fsl_ssi.c:_fsl_ssi_set_dai_fmt
  - sound/soc/fsl/fsl_ssi.c:_fsl_ssi_set_dai_fmt
  - sound/soc/fsl/fsl_ssi.c:_fsl_ssi_set_dai_fmt
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_bclk
```
**Symbols:**

```
c09fcf88-c09fd008: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b9e80)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_set_mux
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_ack
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_unmask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_mask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_connect_dcvdd
  - drivers/mfd/arizona-core.c:arizona_isolate_dcvdd
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77620.c:max77620_set_fps_period
  - drivers/mfd/max77620.c:max77620_pm_power_off
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_irq_global_unmask
  - drivers/mfd/max77620.c:max77620_irq_global_mask
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_power_off
  - drivers/mfd/palmas.c:palmas_power_off
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/power/reset/as3722-poweroff.c:as3722_pm_power_off
  - drivers/power/reset/syscon-reboot.c:syscon_restart_handle
  - drivers/power/reset/syscon-poweroff.c:syscon_poweroff
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
c0000000009b9e80-c0000000009b9f34: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000597ab8)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_set_mux
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_ack
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_unmask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_mask
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set_direction
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_connect_dcvdd
  - drivers/mfd/arizona-core.c:arizona_isolate_dcvdd
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77620.c:max77620_pm_power_off
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/mfd/max77620.c:max77620_irq_global_unmask
  - drivers/mfd/max77620.c:max77620_irq_global_mask
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_power_off
  - drivers/mfd/palmas.c:palmas_power_off
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/power/reset/as3722-poweroff.c:as3722_pm_power_off
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
ffffffe000597ab8-ffffffe000597b28: regmap_update_bits_base (STB_GLOBAL)
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
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e8b00)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
**Symbols:**

```
ffffffff816e8b00-ffffffff816e8b88: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3140)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
**Symbols:**

```
ffffffff816c3140-ffffffff816c31c8: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81715c90)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/tps68470_pmic.c:ti_tps68470_regmap_update_bits
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81715c90-ffffffff81715d18: regmap_update_bits_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_update_bits_base(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool async, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81730f30)
Location: drivers/base/regmap/regmap.c:2919
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
  - drivers/acpi/pmic/tps68470_pmic.c:ti_tps68470_regmap_update_bits
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_active_discharge_regmap
  - drivers/regulator/helpers.c:regulator_set_pull_down_regmap
  - drivers/regulator/helpers.c:regulator_set_soft_start_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_set_config
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_rs_proc
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/lp8788.c:lp8788_update_bits
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_update
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
**Symbols:**

```
ffffffff81730f30-ffffffff81730fb8: regmap_update_bits_base (STB_GLOBAL)
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
