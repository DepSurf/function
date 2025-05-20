# Function: <code>regulator_desc_list_voltage_linear</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regulator_desc_list_voltage_linear(const struct regulator_desc *desc, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff81730aa9)
Location: drivers/regulator/helpers.c:523
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_list_voltage_linear
```
**Symbols:**

```
ffffffff81730a70-ffffffff81730a9b: regulator_desc_list_voltage_linear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regulator_desc_list_voltage_linear(const struct regulator_desc *desc, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff817b0a79)
Location: drivers/regulator/helpers.c:523
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_list_voltage_linear
```
**Symbols:**

```
ffffffff817b0a40-ffffffff817b0a6b: regulator_desc_list_voltage_linear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regulator_desc_list_voltage_linear(const struct regulator_desc *desc, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff818ebf79)
Location: drivers/regulator/helpers.c:523
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_list_voltage_linear
```
**Symbols:**

```
ffffffff818ebf30-ffffffff818ebf6f: regulator_desc_list_voltage_linear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regulator_desc_list_voltage_linear(const struct regulator_desc *desc, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff81a43239)
Location: drivers/regulator/helpers.c:523
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_list_voltage_linear
```
**Symbols:**

```
ffffffff81a431e0-ffffffff81a4321f: regulator_desc_list_voltage_linear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regulator_desc_list_voltage_linear(const struct regulator_desc *desc, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff81a8d349)
Location: drivers/regulator/helpers.c:523
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_list_voltage_linear
```
**Symbols:**

```
ffffffff81a8d2f0-ffffffff81a8d32f: regulator_desc_list_voltage_linear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_desc_list_voltage_linear(const struct regulator_desc *desc, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff81adfb79)
Location: drivers/regulator/helpers.c:526
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_list_voltage_linear
```
**Symbols:**

```
ffffffff81adfb20-ffffffff81adfb5f: regulator_desc_list_voltage_linear (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
