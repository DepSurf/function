# Function: <code>mfd_add_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8158adb0)
Location: drivers/mfd/mfd-core.c:272
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-core.c:tps65912_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/axp20x.c:axp20x_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8158adb0-ffffffff8158aeb9: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff815e0090)
Location: drivers/mfd/mfd-core.c:272
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff815e0090-ffffffff815e01ac: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8160cd30)
Location: drivers/mfd/mfd-core.c:272
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8160cd30-ffffffff8160ce4c: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81620e20)
Location: drivers/mfd/mfd-core.c:272
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81620e20-ffffffff81620f29: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81689640)
Location: drivers/mfd/mfd-core.c:272
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81689640-ffffffff81689749: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816c5760)
Location: drivers/mfd/mfd-core.c:272
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816c5760-ffffffff816c587b: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816e6b50)
Location: drivers/mfd/mfd-core.c:272
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff816e6b50-ffffffff816e6c67: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81720200)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81720200-ffffffff817202e2: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817444d0)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817444d0-ffffffff817445b2: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81801f80)
Location: drivers/mfd/mfd-core.c:261
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_regulator_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:init_regulator
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81801f80-ffffffff81802017: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81812db0)
Location: drivers/mfd/mfd-core.c:332
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_regulator_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:init_regulator
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81812db0-ffffffff81812e7b: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817f74d0)
Location: drivers/mfd/mfd-core.c:323
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_regulator_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:init_regulator
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff817f74d0-ffffffff817f759b: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81880800)
Location: drivers/mfd/mfd-core.c:325
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_regulator_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:init_regulator
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81880800-ffffffff818808cb: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff819c8ee0)
Location: drivers/mfd/mfd-core.c:325
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_regulator_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:init_regulator
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff819c8ee0-ffffffff819c8fb9: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81b40210)
Location: drivers/mfd/mfd-core.c:342
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_regulator_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:init_regulator
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff81b40210-ffffffff81b402e9: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81b93590)
Location: drivers/mfd/mfd-core.c:312
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_regulator_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:init_regulator
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff81b93590-ffffffff81b93666: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81be7530)
Location: drivers/mfd/mfd-core.c:319
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_power_init
  - drivers/mfd/88pm860x-core.c:device_regulator_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:init_regulator
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff81be7530-ffffffff81be7606: mfd_add_devices (STB_GLOBAL)
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
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffff8000109405f0)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/sun6i-prcm.c:sun6i_prcm_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe
```
**Symbols:**

```
ffff8000109405f0-ffff800010940740: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (c0a29cc4)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
**Symbols:**

```
c0a29cc4-c0a29dd8: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (c0000000009e8f80)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
c0000000009e8f80-c0000000009e9168: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffe0005b3f9c)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffe0005b3f9c-ffffffe0005b4064: mfd_add_devices (STB_GLOBAL)
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
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81702570)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81702570-ffffffff81702652: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816d6380)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff816d6380-ffffffff816d6462: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81737990)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81737990-ffffffff81737a72: mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mfd_add_devices(struct device *parent, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81752dd0)
Location: drivers/mfd/mfd-core.c:282
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8606_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff81752dd0-ffffffff81752eb2: mfd_add_devices (STB_GLOBAL)
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
