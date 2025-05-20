# Function: <code>intel_crc_pmic_get_power</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_crc_pmic_get_power(struct regmap *regmap, int reg, int bit, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff816f2e60)
Location: drivers/acpi/pmic/intel_pmic_bytcrc.c:188
Inline: False
```
**Symbols:**

```
ffffffff816f2e60-ffffffff816f2ed1: intel_crc_pmic_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_crc_pmic_get_power(struct regmap *regmap, int reg, int bit, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff81710000)
Location: drivers/acpi/pmic/intel_pmic_bytcrc.c:188
Inline: False
```
**Symbols:**

```
ffffffff81710000-ffffffff81710071: intel_crc_pmic_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_crc_pmic_get_power(struct regmap *regmap, int reg, int bit, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff816f18d0)
Location: drivers/acpi/pmic/intel_pmic_bytcrc.c:188
Inline: False
```
**Symbols:**

```
ffffffff816f18d0-ffffffff816f1941: intel_crc_pmic_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_crc_pmic_get_power(struct regmap *regmap, int reg, int bit, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (0)
Location: drivers/acpi/pmic/intel_pmic_bytcrc.c:188
Inline: False
```
**Symbols:**

```
ffffffff8176bbb0-ffffffff8176bc2b: intel_crc_pmic_get_power (STB_LOCAL)
ffffffff81cf27af-ffffffff81cf27d1: intel_crc_pmic_get_power.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_crc_pmic_get_power(struct regmap *regmap, int reg, int bit, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (0)
Location: drivers/acpi/pmic/intel_pmic_bytcrc.c:188
Inline: False
```
**Symbols:**

```
ffffffff818a0940-ffffffff818a09ce: intel_crc_pmic_get_power (STB_LOCAL)
ffffffff81eba8df-ffffffff81eba901: intel_crc_pmic_get_power.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_crc_pmic_get_power(struct regmap *regmap, int reg, int bit, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (0)
Location: drivers/acpi/pmic/intel_pmic_bytcrc.c:188
Inline: False
```
**Symbols:**

```
ffffffff819e9e90-ffffffff819e9f1e: intel_crc_pmic_get_power (STB_LOCAL)
ffffffff82092b88-ffffffff82092baa: intel_crc_pmic_get_power.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_crc_pmic_get_power(struct regmap *regmap, int reg, int bit, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (0)
Location: drivers/acpi/pmic/intel_pmic_bytcrc.c:188
Inline: False
```
**Symbols:**

```
ffffffff81a325b0-ffffffff81a3263e: intel_crc_pmic_get_power (STB_LOCAL)
ffffffff82113902-ffffffff82113924: intel_crc_pmic_get_power.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_crc_pmic_get_power(struct regmap *regmap, int reg, int bit, u64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (0)
Location: drivers/acpi/pmic/intel_pmic_bytcrc.c:188
Inline: False
```
**Symbols:**

```
ffffffff81a7da20-ffffffff81a7daae: intel_crc_pmic_get_power (STB_LOCAL)
ffffffff821f1275-ffffffff821f1297: intel_crc_pmic_get_power.cold (STB_LOCAL)
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
