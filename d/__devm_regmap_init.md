# Function: <code>__devm_regmap_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81564e40)
Location: drivers/base/regmap/regmap.c:923
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81564e40-ffffffff81564eeb: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815b98b0)
Location: drivers/base/regmap/regmap.c:1024
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff815b98b0-ffffffff815b9962: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e8c10)
Location: drivers/base/regmap/regmap.c:1056
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff815e8c10-ffffffff815e8cc2: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fd5f0)
Location: drivers/base/regmap/regmap.c:1056
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff815fd5f0-ffffffff815fd6a2: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816657a0)
Location: drivers/base/regmap/regmap.c:1133
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff816657a0-ffffffff81665852: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a1170)
Location: drivers/base/regmap/regmap.c:1147
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff816a1170-ffffffff816a122f: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c19e0)
Location: drivers/base/regmap/regmap.c:1183
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff816c19e0-ffffffff816c1a9f: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fc6f0)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff816fc6f0-ffffffff816fc795: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81720aa0)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81720aa0-ffffffff81720b45: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817dcc50)
Location: drivers/base/regmap/regmap.c:1172
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
```
**Symbols:**

```
ffffffff817dcc50-ffffffff817dccf5: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f1d10)
Location: drivers/base/regmap/regmap.c:1210
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
```
**Symbols:**

```
ffffffff817f1d10-ffffffff817f1db5: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d65c0)
Location: drivers/base/regmap/regmap.c:1210
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
```
**Symbols:**

```
ffffffff817d65c0-ffffffff817d6665: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81861b90)
Location: drivers/base/regmap/regmap.c:1249
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
```
**Symbols:**

```
ffffffff81861b90-ffffffff81861c3c: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819a99d0)
Location: drivers/base/regmap/regmap.c:1268
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
```
**Symbols:**

```
ffffffff819a99d0-ffffffff819a9a8e: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1cb50)
Location: drivers/base/regmap/regmap.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
```
**Symbols:**

```
ffffffff81b1cb50-ffffffff81b1cc0e: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6bbc0)
Location: drivers/base/regmap/regmap.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
```
**Symbols:**

```
ffffffff81b6bbc0-ffffffff81b6bc7e: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bbf7f0)
Location: drivers/base/regmap/regmap.c:1173
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap
```
**Symbols:**

```
ffffffff81bbf7f0-ffffffff81bbf8ae: __devm_regmap_init (STB_GLOBAL)
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
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010915178)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/altera-sysmgr.c:sysmgr_probe
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
```
**Symbols:**

```
ffff800010915178-ffff800010915238: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fb1c0)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
c09fb1c0-c09fb268: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b7540)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
c0000000009b7540-c0000000009b7648: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000596496)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
ffffffe000596496-ffffffe000596534: __devm_regmap_init (STB_GLOBAL)
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
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e6dd0)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff816e6dd0-ffffffff816e6e75: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1410)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff816c1410-ffffffff816c14b5: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81713f60)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff81713f60-ffffffff81714005: __devm_regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct regmap *__devm_regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8172f150)
Location: drivers/base/regmap/regmap.c:1179
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__devm_regmap_init_mmio_clk
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
**Symbols:**

```
ffffffff8172f150-ffffffff8172f1f5: __devm_regmap_init (STB_GLOBAL)
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
