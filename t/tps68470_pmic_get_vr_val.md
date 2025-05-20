# Function: <code>tps68470_pmic_get_vr_val</code>

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
int tps68470_pmic_get_vr_val(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815a01a0)
Location: drivers/acpi/pmic/tps68470_pmic.c:237
Inline: False
```
**Symbols:**

```
ffffffff815a01a0-ffffffff815a01fe: tps68470_pmic_get_vr_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tps68470_pmic_get_vr_val(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815d7e30)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: False
```
**Symbols:**

```
ffffffff815d7e30-ffffffff815d7e8e: tps68470_pmic_get_vr_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tps68470_pmic_get_vr_val(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815f1740)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: False
```
**Symbols:**

```
ffffffff815f1740-ffffffff815f179e: tps68470_pmic_get_vr_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tps68470_pmic_get_vr_val(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81623640)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: False
```
**Symbols:**

```
ffffffff81623640-ffffffff8162369e: tps68470_pmic_get_vr_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tps68470_pmic_get_vr_val(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81645130)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: False
```
**Symbols:**

```
ffffffff81645130-ffffffff8164518e: tps68470_pmic_get_vr_val (STB_LOCAL)
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f3cbe)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81710e3e)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f270d)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8176c94d)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff818a1920)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff819eb030)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a33760)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a7ebd0)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
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
int tps68470_pmic_get_vr_val(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffff8000107b0e08)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: False
```
**Symbols:**

```
ffff8000107b0e08-ffff8000107b0e98: tps68470_pmic_get_vr_val (STB_LOCAL)
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
int tps68470_pmic_get_vr_val(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81638f70)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: False
```
**Symbols:**

```
ffffffff81638f70-ffffffff81638fce: tps68470_pmic_get_vr_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tps68470_pmic_get_vr_val(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816532c0)
Location: drivers/acpi/pmic/tps68470_pmic.c:229
Inline: False
```
**Symbols:**

```
ffffffff816532c0-ffffffff8165331e: tps68470_pmic_get_vr_val (STB_LOCAL)
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
