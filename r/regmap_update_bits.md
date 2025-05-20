# Function: <code>regmap_update_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815666b0)
Location: drivers/base/regmap/regmap.c:2558
Inline: False
Direct callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/regulator/helpers.c:regulator_enable_regmap
  - drivers/regulator/helpers.c:regulator_disable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_bypass_regmap
  - drivers/tty/serial/max310x.c:max310x_md_proc
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_startup
  - drivers/tty/serial/max310x.c:max310x_break_ctl
  - drivers/tty/serial/max310x.c:max310x_gpio_set
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_output
  - drivers/tty/serial/max310x.c:max310x_gpio_direction_input
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/base/regmap/regmap.c:regmap_field_write
  - drivers/base/regmap/regmap.c:regmap_field_update_bits
  - drivers/base/regmap/regmap.c:regmap_fields_write
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
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
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_power_off
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_set_bits
  - drivers/mfd/twl6040.c:twl6040_clear_bits
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
ffffffff815666b0-ffffffff81566700: regmap_update_bits (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-crystalcove.c (ffffffff8163f825)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
```
```
In drivers/gpio/gpio-palmas.c (ffffffff816401ff)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81640475)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81640b49)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff8170fc89)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff8171015b)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff817105b4)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81710689)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff81710995)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff81710b55)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81710de5)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
```
In drivers/regulator/helpers.c (ffffffff8174d534)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/max310x.c (ffffffff81783dc1)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
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
  - drivers/tty/serial/max310x.c:max310x_power
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817f950a)
Location: include/linux/regmap.h:1108
Inline: True
```
```
In drivers/mfd/88pm860x-i2c.c (ffffffff81806fb3)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
```
```
In drivers/mfd/arizona-core.c (ffffffff81808d90)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/arizona-irq.c (ffffffff8180964c)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-core.c (ffffffff8180ca6d)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
```
In drivers/mfd/wm8350-core.c (ffffffff8180dddd)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8180e8f2)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
```
```
In drivers/mfd/tps65910.c (ffffffff8180ec4d)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_power_off
```
```
In drivers/mfd/tps80031.c (ffffffff81c12e67)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81811a55)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
```
```
In drivers/mfd/lp8788.c (ffffffff81815855)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_update_bits
```
```
In drivers/mfd/max77693.c (ffffffff81c141de)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81c1436c)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8181a795)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_update
```
```
In drivers/mfd/palmas.c (ffffffff8181ba05)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
```
```
In drivers/mfd/rc5t583.c (ffffffff8181be41)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/sec-core.c (ffffffff8181c76b)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f7a0)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff81808490-ffffffff818084a4: regmap_update_bits.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-crystalcove.c (ffffffff81623395)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
```
```
In drivers/gpio/gpio-palmas.c (ffffffff816237cd)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81623a45)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff816240f9)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff816f1559)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff816f1a2b)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff816f1e83)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff816f1f59)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff816f2255)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff816f2425)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f26b5)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
```
In drivers/regulator/helpers.c (ffffffff8173129c)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/max310x.c (ffffffff817676b1)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
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
  - drivers/tty/serial/max310x.c:max310x_power
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd78a)
Location: include/linux/regmap.h:1108
Inline: True
```
```
In drivers/mfd/88pm860x-i2c.c (ffffffff817ebbe3)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
```
```
In drivers/mfd/arizona-core.c (ffffffff817ed932)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/arizona-irq.c (ffffffff817ee22f)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-core.c (ffffffff817f1379)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
```
In drivers/mfd/wm8350-core.c (ffffffff817f25bd)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817f3122)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
```
```
In drivers/mfd/tps65910.c (ffffffff817f347d)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_power_off
```
```
In drivers/mfd/tps80031.c (ffffffff81c04fa5)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817f6185)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
```
```
In drivers/mfd/lp8788.c (ffffffff817f9f25)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_update_bits
```
```
In drivers/mfd/max77693.c (ffffffff81c06531)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81c066bd)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff817fdeb5)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_update
```
```
In drivers/mfd/palmas.c (ffffffff817fedf5)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
```
```
In drivers/mfd/rc5t583.c (ffffffff817ff201)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/mfd/sec-core.c (ffffffff817ffb3b)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_shutdown
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8193317b)
Location: include/linux/regmap.h:1108
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
**Symbols:**

```
ffffffff817ed060-ffffffff817ed074: regmap_update_bits.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-crystalcove.c (ffffffff81692b0d)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81692f80)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81693238)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81693909)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_input
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_output
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_set
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff8176b659)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff8176ba0b)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff8176c054)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff8176c15e)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff8176c495)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff8176c665)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8176c8f5)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
```
In drivers/clk/versatile/clk-icst.c (ffffffff8177f23b)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-icst.c:icst_set_rate
  - drivers/clk/versatile/clk-icst.c:vco_set
```
```
In drivers/regulator/helpers.c (ffffffff817b129b)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec091)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
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
  - drivers/tty/serial/max310x.c:max310x_power
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff818690aa)
Location: include/linux/regmap.h:1148
Inline: True
```
```
In drivers/mfd/88pm860x-i2c.c (ffffffff81878763)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
```
```
In drivers/mfd/wm831x-core.c (ffffffff81879a09)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
```
In drivers/mfd/wm8350-core.c (ffffffff8187b20d)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8187c040)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
```
```
In drivers/mfd/tps65910.c (ffffffff8187c395)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_power_off
```
```
In drivers/mfd/tps80031.c (ffffffff81d082ae)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8187f475)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
```
```
In drivers/mfd/lp8788.c (ffffffff818833d5)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_update_bits
```
```
In drivers/mfd/max77693.c (ffffffff81d099fb)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81d09b87)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81887bc5)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_update
```
```
In drivers/mfd/palmas.c (ffffffff81888d9c)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
```
```
In drivers/mfd/rc5t583.c (ffffffff818892d1)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d652b)
Location: include/linux/regmap.h:1148
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-crystalcove.c (ffffffff817b3635)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
```
```
In drivers/gpio/gpio-palmas.c (ffffffff817b3aee)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff817b3e08)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff818a0302)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff818a0767)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff818a0eee)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff818a100e)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff818a13c5)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff818a15d5)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff818a18b5)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
```
In drivers/regulator/helpers.c (ffffffff818ec9dd)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/max310x.c (ffffffff8192c09c)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
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
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1cfb)
Location: include/linux/regmap.h:1173
Inline: True
```
```
In drivers/mfd/88pm860x-i2c.c (ffffffff819c0b43)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
```
```
In drivers/mfd/wm831x-core.c (ffffffff819c2129)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
```
In drivers/mfd/wm8350-core.c (ffffffff819c3a7d)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
```
```
In drivers/mfd/wm8350-irq.c (ffffffff819c49c0)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
```
```
In drivers/mfd/tps65910.c (ffffffff819c4d55)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_power_off
```
```
In drivers/mfd/twl6040.c (ffffffff819c7a15)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
```
```
In drivers/mfd/lp8788.c (ffffffff819cbe45)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_update_bits
```
```
In drivers/mfd/max77693.c (ffffffff81ed1e48)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81ed1fd4)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff819d0bc5)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_update
```
```
In drivers/mfd/palmas.c (ffffffff819d1f3c)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
```
```
In drivers/mfd/rc5t583.c (ffffffff819d2548)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39062)
Location: include/linux/regmap.h:1173
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-crystalcove.c (ffffffff818cd6b5)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
```
```
In drivers/gpio/gpio-palmas.c (ffffffff818cdc9e)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff818ce038)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff819e977f)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff819e9c87)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff819ea4de)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff819ea61e)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff819eaa45)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff819eacd5)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff819eafc5)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
```
In drivers/regulator/helpers.c (ffffffff81a43dd2)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/max310x.c (ffffffff81a8aabc)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
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
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b279c4)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/88pm860x-i2c.c (ffffffff81b36f63)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
```
```
In drivers/mfd/wm831x-core.c (ffffffff81b37bb9)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
```
In drivers/mfd/wm8350-core.c (ffffffff81b3a03d)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b3b770)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
```
```
In drivers/mfd/tps65910.c (ffffffff81b3bbb5)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_power_off
```
```
In drivers/mfd/twl6040.c (ffffffff81b3e9c5)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
```
```
In drivers/mfd/lp8788.c (ffffffff81b43b45)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_update_bits
```
```
In drivers/mfd/max77693.c (ffffffff81b4566d)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b45a5d)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b49f95)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_update
```
```
In drivers/mfd/palmas.c (ffffffff81b4ba6b)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
```
```
In drivers/mfd/rc5t583.c (ffffffff81b4c794)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cce9f2)
Location: include/linux/regmap.h:1221
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-crystalcove.c (ffffffff81910715)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81910cfe)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81911098)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff81a31e9f)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff81a323a7)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81a32bfe)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81a32d3e)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff81a33165)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff81a333f5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a336f5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
```
In drivers/regulator/helpers.c (ffffffff81a8df66)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad62bd)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
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
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b779d4)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/88pm860x-i2c.c (ffffffff81b8a3e3)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
```
```
In drivers/mfd/wm831x-core.c (ffffffff81b8b021)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
```
In drivers/mfd/wm8350-core.c (ffffffff81b8d49d)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b8eb60)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
```
```
In drivers/mfd/tps65910.c (ffffffff81b8efd5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_power_off
```
```
In drivers/mfd/twl6040.c (ffffffff81b91e45)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
```
```
In drivers/mfd/lp8788.c (ffffffff81b96eb5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_update_bits
```
```
In drivers/mfd/max77693.c (ffffffff81b98a3d)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b98e2d)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9d3f5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_update
```
```
In drivers/mfd/palmas.c (ffffffff81b9eebb)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
```
```
In drivers/mfd/rc5t583.c (ffffffff81b9fc03)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d367c2)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-crystalcove.c (ffffffff819585e5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81958bbe)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_input
  - drivers/gpio/gpio-palmas.c:palmas_gpio_output
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81958f48)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff81a7d30f)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff81a7d817)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81a7e06e)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81a7e1ae)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff81a7e5d5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff81a7e865)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a7eb65)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
```
In drivers/regulator/helpers.c (ffffffff81ae0906)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
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
```
```
In drivers/tty/serial/max310x.c (ffffffff81b2955c)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
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
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcb7d3)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/88pm860x-i2c.c (ffffffff81bde2e3)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_set_bits
```
```
In drivers/mfd/wm831x-core.c (ffffffff81bdef21)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_set_bits
```
```
In drivers/mfd/wm8350-core.c (ffffffff81be13bd)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_set_bits
  - drivers/mfd/wm8350-core.c:wm8350_clear_bits
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81be2a80)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock
```
```
In drivers/mfd/tps65910.c (ffffffff81be2ef5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_power_off
```
```
In drivers/mfd/twl6040.c (ffffffff81be5de5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_clear_bits
  - drivers/mfd/twl6040.c:twl6040_set_bits
```
```
In drivers/mfd/lp8788.c (ffffffff81beae85)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_update_bits
```
```
In drivers/mfd/max77693.c (ffffffff81bec9ed)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81becddd)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf13e5)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_update
```
```
In drivers/mfd/palmas.c (ffffffff81bf3018)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
  - drivers/mfd/palmas.c:palmas_ext_control_req_config
```
```
In drivers/mfd/rc5t583.c (ffffffff81bf3d63)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81deccfc)
Location: include/linux/regmap.h:1238
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
