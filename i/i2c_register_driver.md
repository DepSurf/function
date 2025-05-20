# Function: <code>i2c_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81679770)
Location: drivers/i2c/i2c-core.c:1868
Inline: True
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_module_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65217.c:tps65217_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/axp20x.c:axp20x_i2c_driver_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
```
**Symbols:**

```
ffffffff81679770-ffffffff81679804: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816daee0)
Location: drivers/i2c/i2c-core.c:2065
Inline: True
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_module_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
```
**Symbols:**

```
ffffffff816daee0-ffffffff816daf7d: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b220)
Location: drivers/i2c/i2c-core.c:2350
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_module_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
```
**Symbols:**

```
ffffffff8170b220-ffffffff8170b2bd: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720280)
Location: drivers/i2c/i2c-core-base.c:1592
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_module_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
```
**Symbols:**

```
ffffffff81720280-ffffffff8172030e: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817915b0)
Location: drivers/i2c/i2c-core-base.c:1616
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_module_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
```
**Symbols:**

```
ffffffff817915b0-ffffffff8179163e: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d4010)
Location: drivers/i2c/i2c-core-base.c:1595
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_module_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff817d4010-ffffffff817d4098: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fb150)
Location: drivers/i2c/i2c-core-base.c:1600
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_module_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff817fb150-ffffffff817fb1d8: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183bdfe)
Location: drivers/i2c/i2c-core-base.c:1690
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff8183d9ef-ffffffff8183da08: i2c_register_driver.cold (STB_LOCAL)
ffffffff8183bdb0-ffffffff8183be35: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186d740)
Location: drivers/i2c/i2c-core-base.c:1695
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff8186d740-ffffffff8186d7d2: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81940ed0)
Location: drivers/i2c/i2c-core-base.c:1657
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff81940ed0-ffffffff81940f87: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819472a0)
Location: drivers/i2c/i2c-core-base.c:1787
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff819472a0-ffffffff81947357: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192aba0)
Location: drivers/i2c/i2c-core-base.c:1847
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_driver_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff8192aba0-ffffffff8192ac57: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1848
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff81d256a3-ffffffff81d256b7: i2c_register_driver.cold (STB_LOCAL)
ffffffff819cdd50-ffffffff819cde1c: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1851
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff81ef147a-ffffffff81ef148f: i2c_register_driver.cold (STB_LOCAL)
ffffffff81b301d0-ffffffff81b302b0: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1845
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff820a7615-ffffffff820a762a: i2c_register_driver.cold (STB_LOCAL)
ffffffff81cc4860-ffffffff81cc4940: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c841)
Location: drivers/i2c/i2c-core-base.c:1958
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff82128a2d-ffffffff82128a42: i2c_register_driver.cold (STB_LOCAL)
ffffffff81d2c7e0-ffffffff81d2c8c0: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de2711)
Location: drivers/i2c/i2c-core-base.c:1973
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff8220a3bf-ffffffff8220a3d4: i2c_register_driver.cold (STB_LOCAL)
ffffffff81de26b0-ffffffff81de2790: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010aaff88)
Location: drivers/i2c/i2c-core-base.c:1695
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/stmpe-i2c.c:stmpe_init
  - drivers/mfd/tc3589x.c:tc3589x_init
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77620.c:max77620_driver_init
  - drivers/mfd/max77686.c:max77686_i2c_driver_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/as3722.c:as3722_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffff800010aaff88-ffff800010ab0038: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b91ffc)
Location: drivers/i2c/i2c-core-base.c:1695
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/stmpe-i2c.c:stmpe_init
  - drivers/mfd/tc3589x.c:tc3589x_init
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65217.c:tps65217_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77620.c:max77620_driver_init
  - drivers/mfd/max77686.c:max77686_i2c_driver_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/as3722.c:as3722_i2c_driver_init
  - drivers/rtc/rtc-pcf8523.c:pcf8523_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_driver_init
```
**Symbols:**

```
c0b91ffc-c0b920b8: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b93d30)
Location: drivers/i2c/i2c-core-base.c:1695
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_driver_init
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_driver_init
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_driver_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/stmpe-i2c.c:stmpe_init
  - drivers/mfd/tc3589x.c:tc3589x_init
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77620.c:max77620_driver_init
  - drivers/mfd/max77686.c:max77686_i2c_driver_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/as3722.c:as3722_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
c000000000b93d30-c000000000b93e24: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b8bfe)
Location: drivers/i2c/i2c-core-base.c:1695
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/stmpe-i2c.c:stmpe_init
  - drivers/mfd/tc3589x.c:tc3589x_init
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77620.c:max77620_driver_init
  - drivers/mfd/max77686.c:max77686_i2c_driver_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/as3722.c:as3722_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffe0006b8bfe-ffffffe0006b8ca6: i2c_register_driver (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff818618d0)
Location: drivers/i2c/i2c-core-base.c:1695
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff818618d0-ffffffff81861962: i2c_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int i2c_register_driver(struct module *owner, struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187cae0)
Location: drivers/i2c/i2c-core-base.c:1695
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_init
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/mfd/wm8400-core.c:wm8400_driver_init
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_init
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_init
  - drivers/mfd/tps65910.c:tps65910_i2c_init
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init
  - drivers/mfd/tps68470.c:tps68470_driver_init
  - drivers/mfd/tps80031.c:tps80031_init
  - drivers/mfd/twl-core.c:twl_driver_init
  - drivers/mfd/twl6040.c:twl6040_driver_init
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init
  - drivers/mfd/da903x.c:da903x_init
  - drivers/mfd/da9052-i2c.c:da9052_i2c_init
  - drivers/mfd/lp8788.c:lp8788_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_init
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init
  - drivers/mfd/max14577.c:max14577_i2c_init
  - drivers/mfd/max77693.c:max77693_i2c_driver_init
  - drivers/mfd/max77843.c:max77843_i2c_init
  - drivers/mfd/max8925-i2c.c:max8925_i2c_init
  - drivers/mfd/max8997.c:max8997_i2c_init
  - drivers/mfd/max8998.c:max8998_i2c_init
  - drivers/mfd/ab3100-core.c:ab3100_i2c_init
  - drivers/mfd/adp5520.c:adp5520_driver_init
  - drivers/mfd/tps6586x.c:tps6586x_init
  - drivers/mfd/tps65090.c:tps65090_init
  - drivers/mfd/aat2870-core.c:aat2870_init
  - drivers/mfd/palmas.c:palmas_i2c_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_init
  - drivers/mfd/sec-core.c:sec_pmic_init
  - drivers/mfd/as3711.c:as3711_i2c_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff8187cae0-ffffffff8187cb72: i2c_register_driver (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
