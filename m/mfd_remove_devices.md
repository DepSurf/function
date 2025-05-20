# Function: <code>mfd_remove_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8158a6a0)
Location: drivers/mfd/mfd-core.c:328
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm8400-core.c:wm8400_i2c_remove
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/tps65217.c:tps65217_remove
  - drivers/mfd/tps65910.c:tps65910_i2c_remove
  - drivers/mfd/tps65912-core.c:tps65912_device_init
  - drivers/mfd/tps65912-core.c:tps65912_device_exit
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/axp20x.c:axp20x_i2c_remove
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9063-core.c:da9063_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_remove
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997.c:max8997_i2c_remove
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_remove
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/rc5t583.c:rc5t583_i2c_remove
  - drivers/mfd/sec-core.c:sec_pmic_remove
  - drivers/mfd/as3711.c:as3711_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff8158a6a0-ffffffff8158a6f3: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff815df850)
Location: drivers/mfd/mfd-core.c:328
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff815df850-ffffffff815df8a3: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8160c4f0)
Location: drivers/mfd/mfd-core.c:328
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff8160c4f0-ffffffff8160c543: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81620600)
Location: drivers/mfd/mfd-core.c:328
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff81620600-ffffffff81620653: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81688e40)
Location: drivers/mfd/mfd-core.c:328
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff81688e40-ffffffff81688e93: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816c4f90)
Location: drivers/mfd/mfd-core.c:328
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_exit
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff816c4f90-ffffffff816c4fe3: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816e6380)
Location: drivers/mfd/mfd-core.c:328
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff816e6380-ffffffff816e63d3: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8171fb10)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff8171fb10-ffffffff8171fb63: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81743de0)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff81743de0-ffffffff81743e33: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8180210e)
Location: drivers/mfd/mfd-core.c:304
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_msic.c:intel_msic_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff81801990-ffffffff818019a9: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81812f9f)
Location: drivers/mfd/mfd-core.c:387
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_msic.c:intel_msic_remove
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff818126d0-ffffffff81812719: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817f76b6)
Location: drivers/mfd/mfd-core.c:381
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff817f6e10-ffffffff817f6e59: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff818809ed)
Location: drivers/mfd/mfd-core.c:383
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff81880120-ffffffff81880169: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff819c90f7)
Location: drivers/mfd/mfd-core.c:383
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff819c8770-ffffffff819c87c5: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81b40437)
Location: drivers/mfd/mfd-core.c:407
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_remove
```
**Symbols:**

```
ffffffff81b3fa00-ffffffff81b3fa55: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81b937b4)
Location: drivers/mfd/mfd-core.c:377
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_remove
```
**Symbols:**

```
ffffffff81b92e70-ffffffff81b92ec5: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81be7754)
Location: drivers/mfd/mfd-core.c:384
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_remove
```
**Symbols:**

```
ffffffff81be6e10-ffffffff81be6e65: mfd_remove_devices (STB_GLOBAL)
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
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffff80001093fee8)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_remove
```
**Symbols:**

```
ffff80001093fee8-ffff80001093ff50: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (c0a29714)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/asic3.c:asic3_remove
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_remove
  - drivers/mfd/t7l66xb.c:t7l66xb_remove
  - drivers/mfd/tc6387xb.c:tc6387xb_remove
  - drivers/mfd/tc6393xb.c:tc6393xb_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
c0a29714-c0a29784: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (c0000000009e89a0)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
c0000000009e89a0-c0000000009e8a1c: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffe0005b3aca)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffe0005b3aca-ffffffe0005b3b10: mfd_remove_devices (STB_GLOBAL)
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
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81701e80)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff81701e80-ffffffff81701ed3: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816d5c90)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff816d5c90-ffffffff816d5ce3: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817372a0)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff817372a0-ffffffff817372f3: mfd_remove_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mfd_remove_devices(struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817526e0)
Location: drivers/mfd/mfd-core.c:338
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/twl4030-audio.c:twl4030_audio_remove
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/mfd-core.c:devm_mfd_dev_release
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/da9052-core.c:da9052_device_exit
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mfd/lp8788.c:lp8788_remove
  - drivers/mfd/da9055-core.c:da9055_device_exit
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove
```
**Symbols:**

```
ffffffff817526e0-ffffffff81752733: mfd_remove_devices (STB_GLOBAL)
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
