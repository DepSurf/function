# Function: <code>regmap_add_irq_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8156bd00)
Location: drivers/base/regmap/regmap-irq.c:355
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/axp20x.c:axp20x_i2c_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/sec-irq.c:sec_irq_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8156bd00-ffffffff8156c3e6: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815c0c80)
Location: drivers/base/regmap/regmap-irq.c:415
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff815c0c80-ffffffff815c16d1: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815f00c0)
Location: drivers/base/regmap/regmap-irq.c:415
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff815f00c0-ffffffff815f0b11: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81604280)
Location: drivers/base/regmap/regmap-irq.c:426
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81604280-ffffffff81604c52: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8166c660)
Location: drivers/base/regmap/regmap-irq.c:426
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8166c660-ffffffff8166d032: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816a80c0)
Location: drivers/base/regmap/regmap-irq.c:426
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-irq.c:da9063_irq_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816a80c0-ffffffff816a8a8b: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8d10)
Location: drivers/base/regmap/regmap-irq.c:486
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816c8d10-ffffffff816c9665: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (0)
Location: drivers/base/regmap/regmap-irq.c:564
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81704ba9-ffffffff81704cd8: regmap_add_irq_chip.cold (STB_LOCAL)
ffffffff817040c0-ffffffff817048a3: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (0)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81728e6d-ffffffff81728f9c: regmap_add_irq_chip.cold (STB_LOCAL)
ffffffff81728410-ffffffff81728bf3: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817e5370)
Location: drivers/base/regmap/regmap-irq.c:828
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817e5370-ffffffff817e53a3: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817fa290)
Location: drivers/base/regmap/regmap-irq.c:861
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817fa290-ffffffff817fa2ed: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817defb0)
Location: drivers/base/regmap/regmap-irq.c:929
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817defb0-ffffffff817df00d: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8186aa10)
Location: drivers/base/regmap/regmap-irq.c:928
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8186aa10-ffffffff8186aa6d: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff819b36b0)
Location: drivers/base/regmap/regmap-irq.c:930
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff819b36b0-ffffffff819b3720: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b28390)
Location: drivers/base/regmap/regmap-irq.c:1108
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
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
ffffffff81b28390-ffffffff81b28400: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b77fa0)
Location: drivers/base/regmap/regmap-irq.c:920
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
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
ffffffff81b77fa0-ffffffff81b78010: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcbda0)
Location: drivers/base/regmap/regmap-irq.c:920
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
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
ffffffff81bcbda0-ffffffff81bcbe10: regmap_add_irq_chip (STB_GLOBAL)
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
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffff80001091dce8)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
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
ffff80001091dce8-ffff80001091e538: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0a03108)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
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
c0a03108-c0a0393c: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0000000009c2aa0)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
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
c0000000009c2aa0-c0000000009c3458: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffe00059d474)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
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
ffffffe00059d474-ffffffe00059dbd0: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (0)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
**Symbols:**

```
ffffffff816eec4d-ffffffff816eed7c: regmap_add_irq_chip.cold (STB_LOCAL)
ffffffff816ee1f0-ffffffff816ee9d3: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (0)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
**Symbols:**

```
ffffffff816c928d-ffffffff816c93bc: regmap_add_irq_chip.cold (STB_LOCAL)
ffffffff816c8830-ffffffff816c9013: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (0)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8171c32d-ffffffff8171c45c: regmap_add_irq_chip.cold (STB_LOCAL)
ffffffff8171b8d0-ffffffff8171c0b3: regmap_add_irq_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regmap_add_irq_chip(struct regmap *map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip *chip, struct regmap_irq_chip_data **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (0)
Location: drivers/base/regmap/regmap-irq.c:559
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8173768d-ffffffff817377bc: regmap_add_irq_chip.cold (STB_LOCAL)
ffffffff81736c30-ffffffff81737413: regmap_add_irq_chip (STB_GLOBAL)
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
