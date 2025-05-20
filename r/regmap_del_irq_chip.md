# Function: <code>regmap_del_irq_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8156bbc0)
Location: drivers/base/regmap/regmap-irq.c:560
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/tps65910.c:tps65910_i2c_remove
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/axp20x.c:axp20x_i2c_remove
  - drivers/mfd/axp20x.c:axp20x_i2c_probe
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9063-irq.c:da9063_irq_exit
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_remove
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/sec-irq.c:sec_irq_exit
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8156bbc0-ffffffff8156bc2b: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815c0b5d)
Location: drivers/base/regmap/regmap-irq.c:669
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9063-irq.c:da9063_irq_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff815c0a30-ffffffff815c0b17: regmap_del_irq_chip.part.3 (STB_LOCAL)
ffffffff815c0b20-ffffffff815c0b43: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815eff9d)
Location: drivers/base/regmap/regmap-irq.c:669
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9063-irq.c:da9063_irq_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff815efe70-ffffffff815eff57: regmap_del_irq_chip.part.3 (STB_LOCAL)
ffffffff815eff60-ffffffff815eff83: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816041d8)
Location: drivers/base/regmap/regmap-irq.c:680
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9063-irq.c:da9063_irq_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816040d0-ffffffff816041b0: regmap_del_irq_chip.part.7 (STB_LOCAL)
ffffffff816041b0-ffffffff816041c7: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8166c5b8)
Location: drivers/base/regmap/regmap-irq.c:680
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9063-irq.c:da9063_irq_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8166c4b0-ffffffff8166c590: regmap_del_irq_chip.part.7 (STB_LOCAL)
ffffffff8166c590-ffffffff8166c5a7: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816a8018)
Location: drivers/base/regmap/regmap-irq.c:680
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9063-irq.c:da9063_irq_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816a7f10-ffffffff816a7ff0: regmap_del_irq_chip.part.7 (STB_LOCAL)
ffffffff816a7ff0-ffffffff816a8006: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8c68)
Location: drivers/base/regmap/regmap-irq.c:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816c8b60-ffffffff816c8c40: regmap_del_irq_chip.part.7 (STB_LOCAL)
ffffffff816c8c40-ffffffff816c8c56: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81703fd8)
Location: drivers/base/regmap/regmap-irq.c:826
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81703ed0-ffffffff81703fb0: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff81703fb0-ffffffff81703fc6: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81728368)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81728260-ffffffff81728340: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff81728340-ffffffff81728356: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817e45c8)
Location: drivers/base/regmap/regmap-irq.c:845
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817e44c0-ffffffff817e45a0: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff817e45a0-ffffffff817e45b6: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817f9428)
Location: drivers/base/regmap/regmap-irq.c:878
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817f9320-ffffffff817f93fe: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff817f9400-ffffffff817f9416: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd6a8)
Location: drivers/base/regmap/regmap-irq.c:946
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817dd590-ffffffff817dd678: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff817dd680-ffffffff817dd696: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81869218)
Location: drivers/base/regmap/regmap-irq.c:945
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff818690c0-ffffffff818691e2: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff818691f0-ffffffff81869206: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1e98)
Location: drivers/base/regmap/regmap-irq.c:947
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff819b1d20-ffffffff819b1e5d: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff819b1e60-ffffffff819b1e86: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b26e28)
Location: drivers/base/regmap/regmap-irq.c:1125
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffffffff81b26c50-ffffffff81b26dca: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff81b26de0-ffffffff81b26e06: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b77368)
Location: drivers/base/regmap/regmap-irq.c:937
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffffffff81b77190-ffffffff81b77309: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff81b77320-ffffffff81b77346: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcb138)
Location: drivers/base/regmap/regmap-irq.c:937
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffffffff81bcaf60-ffffffff81bcb0d9: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff81bcb0f0-ffffffff81bcb116: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffff80001091dc5c)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffff80001091db20-ffff80001091dc04: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffff80001091dc08-ffff80001091dc40: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0a03018)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
c0a02f14-c0a02fdc: regmap_del_irq_chip.part.0 (STB_LOCAL)
c0a02fdc-c0a03000: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0000000009c2a14)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
c0000000009c28a0-c0000000009c29d8: regmap_del_irq_chip.part.0 (STB_LOCAL)
c0000000009c29e0-c0000000009c29fc: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffe00059d404)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffffffe00059d2c8-ffffffe00059d3b8: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffe00059d3b8-ffffffe00059d3ec: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816ee148)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
**Symbols:**

```
ffffffff816ee040-ffffffff816ee120: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff816ee120-ffffffff816ee136: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8788)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
**Symbols:**

```
ffffffff816c8680-ffffffff816c8760: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff816c8760-ffffffff816c8776: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b828)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8171b720-ffffffff8171b800: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff8171b800-ffffffff8171b816: regmap_del_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81736b88)
Location: drivers/base/regmap/regmap-irq.c:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81736a80-ffffffff81736b60: regmap_del_irq_chip.part.0 (STB_LOCAL)
ffffffff81736b60-ffffffff81736b76: regmap_del_irq_chip (STB_GLOBAL)
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
