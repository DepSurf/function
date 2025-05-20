# Function: <code>ti_tps68470_regmap_update_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ti_tps68470_regmap_update_bits(struct regmap *regmap, int reg, int bitmask, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815a0180)
Location: drivers/acpi/pmic/tps68470_pmic.c:273
Inline: False
```
**Symbols:**

```
ffffffff815a0180-ffffffff815a0198: ti_tps68470_regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ti_tps68470_regmap_update_bits(struct regmap *regmap, int reg, int bitmask, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815d7e10)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: False
```
**Symbols:**

```
ffffffff815d7e10-ffffffff815d7e28: ti_tps68470_regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ti_tps68470_regmap_update_bits(struct regmap *regmap, int reg, int bitmask, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815f1720)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: False
```
**Symbols:**

```
ffffffff815f1720-ffffffff815f1738: ti_tps68470_regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ti_tps68470_regmap_update_bits(struct regmap *regmap, int reg, int bitmask, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81623550)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: False
```
**Symbols:**

```
ffffffff81623550-ffffffff81623568: ti_tps68470_regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ti_tps68470_regmap_update_bits(struct regmap *regmap, int reg, int bitmask, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81645040)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: False
```
**Symbols:**

```
ffffffff81645040-ffffffff81645058: ti_tps68470_regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f3c65)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81710de5)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f26b5)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8176c8f5)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff818a18b5)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff819eafc5)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a336f5)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a7eb65)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
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
int ti_tps68470_regmap_update_bits(struct regmap *regmap, int reg, int bitmask, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffff8000107b0db0)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: False
```
**Symbols:**

```
ffff8000107b0db0-ffff8000107b0e08: ti_tps68470_regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
int ti_tps68470_regmap_update_bits(struct regmap *regmap, int reg, int bitmask, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81638e80)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: False
```
**Symbols:**

```
ffffffff81638e80-ffffffff81638e98: ti_tps68470_regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ti_tps68470_regmap_update_bits(struct regmap *regmap, int reg, int bitmask, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816531d0)
Location: drivers/acpi/pmic/tps68470_pmic.c:265
Inline: False
```
**Symbols:**

```
ffffffff816531d0-ffffffff816531e8: ti_tps68470_regmap_update_bits (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
