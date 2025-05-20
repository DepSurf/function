# Function: <code>i2c_del_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81679810)
Location: drivers/i2c/i2c-core.c:1909
Inline: True
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_exit
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/wm8400-core.c:wm8400_module_exit
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit
  - drivers/mfd/tps65217.c:tps65217_exit
  - drivers/mfd/tps65910.c:tps65910_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_exit
  - drivers/mfd/tps80031.c:tps80031_exit
  - drivers/mfd/twl-core.c:twl_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/axp20x.c:axp20x_i2c_driver_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_exit
  - drivers/mfd/max77843.c:max77843_i2c_exit
  - drivers/mfd/max8925-i2c.c:max8925_i2c_exit
  - drivers/mfd/max8997.c:max8997_i2c_exit
  - drivers/mfd/max8998.c:max8998_i2c_exit
  - drivers/mfd/ab3100-core.c:ab3100_i2c_exit
  - drivers/mfd/adp5520.c:adp5520_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/tps65090.c:tps65090_exit
  - drivers/mfd/aat2870-core.c:aat2870_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/rc5t583.c:rc5t583_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3711.c:as3711_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/i2c/i2c-core.c:i2c_exit
```
**Symbols:**

```
ffffffff81679810-ffffffff81679858: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816daf80)
Location: drivers/i2c/i2c-core.c:2106
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/wm8400-core.c:wm8400_module_exit
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit
  - drivers/mfd/tps65910.c:tps65910_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/tps80031.c:tps80031_exit
  - drivers/mfd/twl-core.c:twl_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/ab3100-core.c:ab3100_i2c_exit
  - drivers/mfd/adp5520.c:adp5520_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/tps65090.c:tps65090_exit
  - drivers/mfd/aat2870-core.c:aat2870_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/rc5t583.c:rc5t583_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3711.c:as3711_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/i2c/i2c-core.c:i2c_exit
```
**Symbols:**

```
ffffffff816daf80-ffffffff816dafc4: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b2c0)
Location: drivers/i2c/i2c-core.c:2391
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/wm8400-core.c:wm8400_module_exit
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit
  - drivers/mfd/tps65910.c:tps65910_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/tps80031.c:tps80031_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/adp5520.c:adp5520_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/tps65090.c:tps65090_exit
  - drivers/mfd/aat2870-core.c:aat2870_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/rc5t583.c:rc5t583_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3711.c:as3711_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core.c:i2c_exit
```
**Symbols:**

```
ffffffff8170b2c0-ffffffff8170b304: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720310)
Location: drivers/i2c/i2c-core-base.c:1633
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/wm8400-core.c:wm8400_module_exit
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit
  - drivers/mfd/tps65910.c:tps65910_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/tps80031.c:tps80031_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/adp5520.c:adp5520_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/tps65090.c:tps65090_exit
  - drivers/mfd/aat2870-core.c:aat2870_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/rc5t583.c:rc5t583_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3711.c:as3711_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81720310-ffffffff81720354: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81791640)
Location: drivers/i2c/i2c-core-base.c:1657
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/wm8400-core.c:wm8400_module_exit
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit
  - drivers/mfd/tps65910.c:tps65910_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/tps80031.c:tps80031_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/adp5520.c:adp5520_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/tps65090.c:tps65090_exit
  - drivers/mfd/aat2870-core.c:aat2870_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/rc5t583.c:rc5t583_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3711.c:as3711_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81791640-ffffffff81791684: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d40a0)
Location: drivers/i2c/i2c-core-base.c:1636
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/wm8400-core.c:wm8400_module_exit
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit
  - drivers/mfd/tps65910.c:tps65910_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/tps80031.c:tps80031_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/adp5520.c:adp5520_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/tps65090.c:tps65090_exit
  - drivers/mfd/aat2870-core.c:aat2870_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/rc5t583.c:rc5t583_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3711.c:as3711_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff817d40a0-ffffffff817d40e4: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fb1e0)
Location: drivers/i2c/i2c-core-base.c:1641
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/wm8400-core.c:wm8400_module_exit
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit
  - drivers/mfd/tps65910.c:tps65910_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/tps80031.c:tps80031_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/adp5520.c:adp5520_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/tps65090.c:tps65090_exit
  - drivers/mfd/aat2870-core.c:aat2870_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/rc5t583.c:rc5t583_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3711.c:as3711_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff817fb1e0-ffffffff817fb224: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183be40)
Location: drivers/i2c/i2c-core-base.c:1731
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff8183be40-ffffffff8183be84: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186d7e0)
Location: drivers/i2c/i2c-core-base.c:1736
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff8186d7e0-ffffffff8186d824: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81940da0)
Location: drivers/i2c/i2c-core-base.c:1698
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81940da0-ffffffff81940e0e: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81947170)
Location: drivers/i2c/i2c-core-base.c:1828
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81947170-ffffffff819471de: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192aa80)
Location: drivers/i2c/i2c-core-base.c:1888
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_driver_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff8192aa80-ffffffff8192aaee: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cdc30)
Location: drivers/i2c/i2c-core-base.c:1889
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff819cdc30-ffffffff819cdc9b: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b300a0)
Location: drivers/i2c/i2c-core-base.c:1892
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81b300a0-ffffffff81b30127: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc4740)
Location: drivers/i2c/i2c-core-base.c:1886
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81cc4740-ffffffff81cc47c7: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c6c0)
Location: drivers/i2c/i2c-core-base.c:1999
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81d2c6c0-ffffffff81d2c747: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de2590)
Location: drivers/i2c/i2c-core-base.c:2014
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81de2590-ffffffff81de2617: i2c_del_driver (STB_GLOBAL)
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
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab0038)
Location: drivers/i2c/i2c-core-base.c:1736
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/stmpe-i2c.c:stmpe_exit
  - drivers/mfd/tc3589x.c:tc3589x_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77686.c:max77686_i2c_driver_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3722.c:as3722_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffff800010ab0038-ffff800010ab00a0: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b920b8)
Location: drivers/i2c/i2c-core-base.c:1736
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/stmpe-i2c.c:stmpe_exit
  - drivers/mfd/tc3589x.c:tc3589x_exit
  - drivers/mfd/tps65217.c:tps65217_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77686.c:max77686_i2c_driver_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3722.c:as3722_i2c_driver_exit
  - drivers/rtc/rtc-pcf8523.c:pcf8523_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_driver_exit
```
**Symbols:**

```
c0b920b8-c0b92110: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b93e30)
Location: drivers/i2c/i2c-core-base.c:1736
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_driver_exit
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_driver_exit
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_driver_exit
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/stmpe-i2c.c:stmpe_exit
  - drivers/mfd/tc3589x.c:tc3589x_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77686.c:max77686_i2c_driver_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3722.c:as3722_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
c000000000b93e30-c000000000b93ec0: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b8ca6)
Location: drivers/i2c/i2c-core-base.c:1736
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/stmpe-i2c.c:stmpe_exit
  - drivers/mfd/tc3589x.c:tc3589x_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77686.c:max77686_i2c_driver_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/as3722.c:as3722_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffe0006b8ca6-ffffffe0006b8d18: i2c_del_driver (STB_GLOBAL)
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
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81861970)
Location: drivers/i2c/i2c-core-base.c:1736
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff81861970-ffffffff818619b4: i2c_del_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void i2c_del_driver(struct i2c_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187cb80)
Location: drivers/i2c/i2c-core-base.c:1736
Inline: True
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_i2c_exit
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit
  - drivers/mfd/twl6040.c:twl6040_driver_exit
  - drivers/mfd/da903x.c:da903x_exit
  - drivers/mfd/da9052-i2c.c:da9052_i2c_exit
  - drivers/mfd/lp8788.c:lp8788_exit
  - drivers/mfd/da9055-i2c.c:da9055_i2c_exit
  - drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit
  - drivers/mfd/max14577.c:max14577_i2c_exit
  - drivers/mfd/max77693.c:max77693_i2c_driver_exit
  - drivers/mfd/tps6586x.c:tps6586x_exit
  - drivers/mfd/palmas.c:palmas_i2c_exit
  - drivers/mfd/sec-core.c:sec_pmic_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
**Symbols:**

```
ffffffff8187cb80-ffffffff8187cbc4: i2c_del_driver (STB_GLOBAL)
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
