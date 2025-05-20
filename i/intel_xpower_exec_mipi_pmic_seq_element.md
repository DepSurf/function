# Function: <code>intel_xpower_exec_mipi_pmic_seq_element</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_xpower_exec_mipi_pmic_seq_element(struct regmap *regmap, u16 i2c_address, u32 reg_address, u32 value, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81cf27f0)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:273
Inline: True
```
**Symbols:**

```
ffffffff8176be30-ffffffff8176be97: intel_xpower_exec_mipi_pmic_seq_element (STB_LOCAL)
ffffffff81cf27f0-ffffffff81cf2819: intel_xpower_exec_mipi_pmic_seq_element.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_xpower_exec_mipi_pmic_seq_element(struct regmap *regmap, u16 i2c_address, u32 reg_address, u32 value, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81eba952)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:273
Inline: True
```
**Symbols:**

```
ffffffff818a0db0-ffffffff818a0e29: intel_xpower_exec_mipi_pmic_seq_element (STB_LOCAL)
ffffffff81eba952-ffffffff81eba97b: intel_xpower_exec_mipi_pmic_seq_element.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int intel_xpower_exec_mipi_pmic_seq_element(struct regmap *regmap, u16 i2c_address, u32 reg_address, u32 value, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff819ea370)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:273
Inline: True
```
**Symbols:**

```
ffffffff819ea370-ffffffff819ea40b: intel_xpower_exec_mipi_pmic_seq_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int intel_xpower_exec_mipi_pmic_seq_element(struct regmap *regmap, u16 i2c_address, u32 reg_address, u32 value, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81a32a90)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:273
Inline: True
```
**Symbols:**

```
ffffffff81a32a90-ffffffff81a32b2b: intel_xpower_exec_mipi_pmic_seq_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int intel_xpower_exec_mipi_pmic_seq_element(struct regmap *regmap, u16 i2c_address, u32 reg_address, u32 value, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81a7df00)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:273
Inline: True
```
**Symbols:**

```
ffffffff81a7df00-ffffffff81a7df9b: intel_xpower_exec_mipi_pmic_seq_element (STB_LOCAL)
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
