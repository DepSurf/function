# Function: <code>devm_mfd_add_devices</code>

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
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff815e01b0)
Location: drivers/mfd/mfd-core.c:349
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff815e01b0-ffffffff815e0258: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8160ce50)
Location: drivers/mfd/mfd-core.c:349
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff8160ce50-ffffffff8160cef8: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81620f30)
Location: drivers/mfd/mfd-core.c:349
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
**Symbols:**

```
ffffffff81620f30-ffffffff81620fd5: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81689750)
Location: drivers/mfd/mfd-core.c:349
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81689750-ffffffff816897f5: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816c5880)
Location: drivers/mfd/mfd-core.c:349
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff816c5880-ffffffff816c5925: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816e6c70)
Location: drivers/mfd/mfd-core.c:349
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff816e6c70-ffffffff816e6d15: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817202f0)
Location: drivers/mfd/mfd-core.c:359
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff817202f0-ffffffff81720393: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817445c0)
Location: drivers/mfd/mfd-core.c:359
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff817445c0-ffffffff81744663: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81802020)
Location: drivers/mfd/mfd-core.c:322
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81802020-ffffffff81802121: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81812e80)
Location: drivers/mfd/mfd-core.c:417
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81812e80-ffffffff81812fbe: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817f75a0)
Location: drivers/mfd/mfd-core.c:411
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff817f75a0-ffffffff817f76d5: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff818808d0)
Location: drivers/mfd/mfd-core.c:413
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff818808d0-ffffffff81880a0c: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff819c8fc0)
Location: drivers/mfd/mfd-core.c:413
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff819c8fc0-ffffffff819c9121: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81b40300)
Location: drivers/mfd/mfd-core.c:437
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81b40300-ffffffff81b40461: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81b93680)
Location: drivers/mfd/mfd-core.c:407
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81b93680-ffffffff81b937de: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81be7620)
Location: drivers/mfd/mfd-core.c:414
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81be7620-ffffffff81be777e: devm_mfd_add_devices (STB_GLOBAL)
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
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffff800010940740)
Location: drivers/mfd/mfd-core.c:359
Inline: False
Direct callers:
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
ffff800010940740-ffff80001094081c: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (c0a29dd8)
Location: drivers/mfd/mfd-core.c:359
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
c0a29dd8-c0a29e8c: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (c0000000009e9170)
Location: drivers/mfd/mfd-core.c:359
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
c0000000009e9170-c0000000009e92a8: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffe0005b4064)
Location: drivers/mfd/mfd-core.c:359
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
**Symbols:**

```
ffffffe0005b4064-ffffffe0005b4108: devm_mfd_add_devices (STB_GLOBAL)
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
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81702660)
Location: drivers/mfd/mfd-core.c:359
Inline: False
```
**Symbols:**

```
ffffffff81702660-ffffffff81702703: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816d6470)
Location: drivers/mfd/mfd-core.c:359
Inline: False
```
**Symbols:**

```
ffffffff816d6470-ffffffff816d6513: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81737a80)
Location: drivers/mfd/mfd-core.c:359
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81737a80-ffffffff81737b23: devm_mfd_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device *dev, int id, const struct mfd_cell *cells, int n_devs, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81752ec0)
Location: drivers/mfd/mfd-core.c:359
Inline: False
Direct callers:
  - drivers/mfd/wm8400-core.c:wm8400_register_codec
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps68470.c:tps68470_probe
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81752ec0-ffffffff81752f63: devm_mfd_add_devices (STB_GLOBAL)
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
