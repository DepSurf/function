# Function: <code>__devm_regmap_init_i2c</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff8156abe0)
Location: drivers/base/regmap/regmap-i2c.c:300
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/axp20x.c:axp20x_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8156abe0-ffffffff8156ac2a: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff815bf780)
Location: drivers/base/regmap/regmap-i2c.c:300
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff815bf780-ffffffff815bf7ca: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff815eeb90)
Location: drivers/base/regmap/regmap-i2c.c:300
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff815eeb90-ffffffff815eebda: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81602db0)
Location: drivers/base/regmap/regmap-i2c.c:300
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81602db0-ffffffff81602dfa: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff8166b180)
Location: drivers/base/regmap/regmap-i2c.c:300
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8166b180-ffffffff8166b1ca: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff816a6b80)
Location: drivers/base/regmap/regmap-i2c.c:296
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816a6b80-ffffffff816a6bca: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff816c76c0)
Location: drivers/base/regmap/regmap-i2c.c:296
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816c76c0-ffffffff816c770a: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81702970)
Location: drivers/base/regmap/regmap-i2c.c:292
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81702970-ffffffff817029ba: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81726cc0)
Location: drivers/base/regmap/regmap-i2c.c:292
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81726cc0-ffffffff81726d0a: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff817e31e0)
Location: drivers/base/regmap/regmap-i2c.c:353
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817e31e0-ffffffff817e3251: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff817f7e40)
Location: drivers/base/regmap/regmap-i2c.c:353
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817f7e40-ffffffff817f7eb1: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff817dc680)
Location: drivers/base/regmap/regmap-i2c.c:353
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817dc680-ffffffff817dc6ca: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81868080)
Location: drivers/base/regmap/regmap-i2c.c:384
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81868080-ffffffff818680ca: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff819b08f0)
Location: drivers/base/regmap/regmap-i2c.c:384
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff819b08f0-ffffffff819b094c: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81b246f0)
Location: drivers/base/regmap/regmap-i2c.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff81b246f0-ffffffff81b2474c: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81b74800)
Location: drivers/base/regmap/regmap-i2c.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff81b74800-ffffffff81b7485c: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff81bc8650)
Location: drivers/base/regmap/regmap-i2c.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff81bc8650-ffffffff81bc86ac: __devm_regmap_init_i2c (STB_GLOBAL)
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
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffff80001091be58)
Location: drivers/base/regmap/regmap-i2c.c:292
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
ffff80001091be58-ffff80001091bec0: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (c0a016cc)
Location: drivers/base/regmap/regmap-i2c.c:292
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
**Symbols:**

```
c0a016cc-c0a01720: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (c0000000009c0600)
Location: drivers/base/regmap/regmap-i2c.c:292
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
c0000000009c0600-c0000000009c068c: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffe00059b8e2)
Location: drivers/base/regmap/regmap-i2c.c:292
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
ffffffe00059b8e2-ffffffe00059b93c: __devm_regmap_init_i2c (STB_GLOBAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff8171a180)
Location: drivers/base/regmap/regmap-i2c.c:292
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8171a180-ffffffff8171a1ca: __devm_regmap_init_i2c (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init_i2c(struct i2c_client *i2c, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-i2c.c (ffffffff817354e0)
Location: drivers/base/regmap/regmap-i2c.c:292
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817354e0-ffffffff8173552a: __devm_regmap_init_i2c (STB_GLOBAL)
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
