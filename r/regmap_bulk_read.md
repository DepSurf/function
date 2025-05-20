# Function: <code>regmap_bulk_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81565ae0)
Location: drivers/base/regmap/regmap.c:2410
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/misc/bmp085.c:bmp085_update_raw_temperature
  - drivers/misc/bmp085.c:show_pressure
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm8400-core.c:wm8400_block_read
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81565ae0-ffffffff81565db7: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ba570)
Location: drivers/base/regmap/regmap.c:2510
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm8400-core.c:wm8400_block_read
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815ba570-ffffffff815ba869: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e9970)
Location: drivers/base/regmap/regmap.c:2548
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm8400-core.c:wm8400_block_read
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815e9970-ffffffff815e9c69: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fe340)
Location: drivers/base/regmap/regmap.c:2553
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm8400-core.c:wm8400_block_read
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff815fe340-ffffffff815fe639: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81666570)
Location: drivers/base/regmap/regmap.c:2632
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm8400-core.c:wm8400_block_read
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81666570-ffffffff81666872: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a28e0)
Location: drivers/base/regmap/regmap.c:2635
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm8400-core.c:wm8400_block_read
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff816a28e0-ffffffff816a2adb: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c31e0)
Location: drivers/base/regmap/regmap.c:2795
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm8400-core.c:wm8400_block_read
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff816c31e0-ffffffff816c33db: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fe080)
Location: drivers/base/regmap/regmap.c:2792
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff816fe080-ffffffff816fe27b: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817224a0)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff817224a0-ffffffff8172269b: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817de4c0)
Location: drivers/base/regmap/regmap.c:2794
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffff817de4c0-ffffffff817de6f0: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f34e0)
Location: drivers/base/regmap/regmap.c:2951
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffff817f34e0-ffffffff817f3710: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d7d60)
Location: drivers/base/regmap/regmap.c:2951
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffff817d7d60-ffffffff817d7f90: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2992
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffff81d04b69-ffffffff81d04bab: regmap_bulk_read.cold (STB_LOCAL)
ffffffff81863440-ffffffff8186368a: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3009
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffff81ecd577-ffffffff81ecd5b6: regmap_bulk_read.cold (STB_LOCAL)
ffffffff819ab550-ffffffff819ab7e6: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3158
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffff8209926b-ffffffff820992ac: regmap_bulk_read.cold (STB_LOCAL)
ffffffff81b1e9e0-ffffffff81b1ece6: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3188
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffff8211a31d-ffffffff8211a35e: regmap_bulk_read.cold (STB_LOCAL)
ffffffff81b6dc30-ffffffff81b6deeb: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3076
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffff821f81a4-ffffffff821f81e5: regmap_bulk_read.cold (STB_LOCAL)
ffffffff81bc1840-ffffffff81bc1ae5: regmap_bulk_read (STB_GLOBAL)
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
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010916d50)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffff800010916d50-ffff800010916f70: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fccc0)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_suspend
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
c09fccc0-c09fce6c: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b9a10)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
c0000000009b9a10-c0000000009b9cc8: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000597860)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
**Symbols:**

```
ffffffe000597860-ffffffe0005979e6: regmap_bulk_read (STB_GLOBAL)
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
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e87d0)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
```
**Symbols:**

```
ffffffff816e87d0-ffffffff816e89cb: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c2e10)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
```
**Symbols:**

```
ffffffff816c2e10-ffffffff816c300b: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81715960)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81715960-ffffffff81715b5b: regmap_bulk_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap *map, unsigned int reg, void *val, size_t val_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81730c00)
Location: drivers/base/regmap/regmap.c:2799
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-core.c:arizona_overclocked
  - drivers/mfd/wm831x-core.c:wm831x_bulk_read
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/lp8788.c:lp8788_read_multi_bytes
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81730c00-ffffffff81730dfb: regmap_bulk_read (STB_GLOBAL)
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
