# Function: <code>regmap_irq_chip_get_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8156bc30)
Location: drivers/base/regmap/regmap-irq.c:583
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff8156bc30-ffffffff8156bc62: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815c09b0)
Location: drivers/base/regmap/regmap-irq.c:795
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff815c09b0-ffffffff815c09e2: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff815efdf0)
Location: drivers/base/regmap/regmap-irq.c:795
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff815efdf0-ffffffff815efe22: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81603cb0)
Location: drivers/base/regmap/regmap-irq.c:809
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81603cb0-ffffffff81603cc9: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8166c090)
Location: drivers/base/regmap/regmap-irq.c:809
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff8166c090-ffffffff8166c0a9: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816a7af0)
Location: drivers/base/regmap/regmap-irq.c:809
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff816a7af0-ffffffff816a7b08: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8690)
Location: drivers/base/regmap/regmap-irq.c:871
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff816c8690-ffffffff816c86a8: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (0)
Location: drivers/base/regmap/regmap-irq.c:955
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81704a51-ffffffff81704a6d: regmap_irq_chip_get_base.cold (STB_LOCAL)
ffffffff81703a60-ffffffff81703a7b: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81727e30)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81727e30-ffffffff81727e49: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817e44a0)
Location: drivers/base/regmap/regmap-irq.c:1002
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff817e44a0-ffffffff817e44b9: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817f9300)
Location: drivers/base/regmap/regmap-irq.c:1037
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff817f9300-ffffffff817f9319: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd570)
Location: drivers/base/regmap/regmap-irq.c:1105
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff817dd570-ffffffff817dd589: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81868f30)
Location: drivers/base/regmap/regmap-irq.c:1104
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81868f30-ffffffff81868f49: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1b50)
Location: drivers/base/regmap/regmap-irq.c:1106
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff819b1b50-ffffffff819b1b75: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b263b0)
Location: drivers/base/regmap/regmap-irq.c:1289
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81b263b0-ffffffff81b263d5: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81b76370)
Location: drivers/base/regmap/regmap-irq.c:1101
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81b76370-ffffffff81b76395: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81bca140)
Location: drivers/base/regmap/regmap-irq.c:1101
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81bca140-ffffffff81bca165: regmap_irq_chip_get_base (STB_GLOBAL)
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
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffff80001091cf50)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffff80001091cf50-ffff80001091cf90: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0a029fc)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
c0a029fc-c0a02a40: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (c0000000009c1930)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: False
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
c0000000009c1930-c0000000009c194c: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffe00059cdec)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffe00059cdec-ffffffe00059ce1e: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816edc10)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: True
```
**Symbols:**

```
ffffffff816edc10-ffffffff816edc29: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8250)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: True
```
**Symbols:**

```
ffffffff816c8250-ffffffff816c8269: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b2f0)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff8171b2f0-ffffffff8171b309: regmap_irq_chip_get_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int regmap_irq_chip_get_base(struct regmap_irq_chip_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-irq.c (ffffffff81736650)
Location: drivers/base/regmap/regmap-irq.c:950
Inline: True
Direct callers:
  - drivers/mfd/da9055-core.c:da9055_device_init
  - drivers/mfd/da9063-core.c:da9063_device_init
```
**Symbols:**

```
ffffffff81736650-ffffffff81736669: regmap_irq_chip_get_base (STB_GLOBAL)
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
