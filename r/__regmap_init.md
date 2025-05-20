# Function: <code>__regmap_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81564380)
Location: drivers/base/regmap/regmap.c:522
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81564380-ffffffff81564e35: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815b8c90)
Location: drivers/base/regmap/regmap.c:582
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff815b8c90-ffffffff815b98a8: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e7fc0)
Location: drivers/base/regmap/regmap.c:605
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff815e7fc0-ffffffff815e8c0e: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fc980)
Location: drivers/base/regmap/regmap.c:605
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff815fc980-ffffffff815fd5e2: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81664b20)
Location: drivers/base/regmap/regmap.c:651
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81664b20-ffffffff81665793: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a0440)
Location: drivers/base/regmap/regmap.c:654
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff816a0440-ffffffff816a116f: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c0bd0)
Location: drivers/base/regmap/regmap.c:686
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff816c0bd0-ffffffff816c19d7: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff816ff0ac-ffffffff816ff16f: __regmap_init.cold (STB_LOCAL)
ffffffff816fb9f0-ffffffff816fc6e3: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff817234b7-ffffffff8172357a: __regmap_init.cold (STB_LOCAL)
ffffffff8171fda0-ffffffff81720a93: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:674
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff817df6ca-ffffffff817df78d: __regmap_init.cold (STB_LOCAL)
ffffffff817dbeb0-ffffffff817dcc50: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:701
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81c0f35b-ffffffff81c0f41e: __regmap_init.cold (STB_LOCAL)
ffffffff817f0f40-ffffffff817f1d0e: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:701
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81c014a9-ffffffff81c0156c: __regmap_init.cold (STB_LOCAL)
ffffffff817d57e0-ffffffff817d65bb: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:729
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81d046b3-ffffffff81d0488d: __regmap_init.cold (STB_LOCAL)
ffffffff81860d30-ffffffff81861b81: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:729
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81ecd097-ffffffff81ecd23f: __regmap_init.cold (STB_LOCAL)
ffffffff819a89a0-ffffffff819a99c9: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:718
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff82098e79-ffffffff82098f8a: __regmap_init.cold (STB_LOCAL)
ffffffff81b1ba70-ffffffff81b1cb35: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:718
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff82119f5b-ffffffff8211a06c: __regmap_init.cold (STB_LOCAL)
ffffffff81b6ab10-ffffffff81b6bbaa: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:664
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff821f7e00-ffffffff821f7f11: __regmap_init.cold (STB_LOCAL)
ffffffff81bbe7d0-ffffffff81bbf7d4: __regmap_init (STB_GLOBAL)
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
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010914528)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_regmap_init
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
```
**Symbols:**

```
ffff800010914528-ffff800010915178: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fa468)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_regmap_init
```
**Symbols:**

```
c09fa468-c09fb1c0: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b6590)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
c0000000009b6590-c0000000009b753c: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe00059594e)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffe00059594e-ffffffe000596496: __regmap_init (STB_GLOBAL)
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
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff816e97e7-ffffffff816e98aa: __regmap_init.cold (STB_LOCAL)
ffffffff816e60d0-ffffffff816e6dc3: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff816c3e27-ffffffff816c3eea: __regmap_init.cold (STB_LOCAL)
ffffffff816c0710-ffffffff816c1403: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81716977-ffffffff81716a3a: __regmap_init.cold (STB_LOCAL)
ffffffff81713260-ffffffff81713f53: __regmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct regmap *__regmap_init(struct device *dev, const struct regmap_bus *bus, void *bus_context, const struct regmap_config *config, struct lock_class_key *lock_key, const char *lock_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:682
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
  - drivers/base/regmap/regmap-mmio.c:__regmap_init_mmio_clk
```
**Symbols:**

```
ffffffff81731c17-ffffffff81731cda: __regmap_init.cold (STB_LOCAL)
ffffffff8172e450-ffffffff8172f143: __regmap_init (STB_GLOBAL)
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
