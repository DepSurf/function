# Function: <code>tps68470_pmic_get_power</code>

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
int tps68470_pmic_get_power(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815a0210)
Location: drivers/acpi/pmic/tps68470_pmic.c:225
Inline: False
```
**Symbols:**

```
ffffffff815a0210-ffffffff815a0272: tps68470_pmic_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tps68470_pmic_get_power(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815d7ea0)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: False
```
**Symbols:**

```
ffffffff815d7ea0-ffffffff815d7f02: tps68470_pmic_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tps68470_pmic_get_power(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815f17b0)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: False
```
**Symbols:**

```
ffffffff815f17b0-ffffffff815f1812: tps68470_pmic_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tps68470_pmic_get_power(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816236a0)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: False
```
**Symbols:**

```
ffffffff816236a0-ffffffff81623702: tps68470_pmic_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tps68470_pmic_get_power(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81645190)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: False
```
**Symbols:**

```
ffffffff81645190-ffffffff816451f2: tps68470_pmic_get_power (STB_LOCAL)
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f3ede)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8171105e)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f292d)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8176cb6d)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff818a1b80)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff819eb2b0)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a339e0)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a7ee50)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
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
int tps68470_pmic_get_power(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffff8000107b0ee0)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: False
```
**Symbols:**

```
ffff8000107b0ee0-ffff8000107b0f74: tps68470_pmic_get_power (STB_LOCAL)
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
int tps68470_pmic_get_power(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81638fd0)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: False
```
**Symbols:**

```
ffffffff81638fd0-ffffffff81639032: tps68470_pmic_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tps68470_pmic_get_power(struct regmap *regmap, int reg, int bitmask, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81653320)
Location: drivers/acpi/pmic/tps68470_pmic.c:217
Inline: False
```
**Symbols:**

```
ffffffff81653320-ffffffff81653382: tps68470_pmic_get_power (STB_LOCAL)
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
