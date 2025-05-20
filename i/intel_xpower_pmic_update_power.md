# Function: <code>intel_xpower_pmic_update_power</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_xpower_pmic_update_power(struct regmap *regmap, int reg, int bit, bool on);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff816f3390)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:176
Inline: True
```
**Symbols:**

```
ffffffff816f3390-ffffffff816f3471: intel_xpower_pmic_update_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int intel_xpower_pmic_update_power(struct regmap *regmap, int reg, int bit, bool on);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81710430)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:176
Inline: True
```
**Symbols:**

```
ffffffff81710430-ffffffff81710511: intel_xpower_pmic_update_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int intel_xpower_pmic_update_power(struct regmap *regmap, int reg, int bit, bool on);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff816f1d00)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:176
Inline: True
```
**Symbols:**

```
ffffffff816f1d00-ffffffff816f1deb: intel_xpower_pmic_update_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_xpower_pmic_update_power(struct regmap *regmap, int reg, int bit, bool on);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff8176bedc)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:176
Inline: True
```
**Symbols:**

```
ffffffff8176bea0-ffffffff8176bfac: intel_xpower_pmic_update_power (STB_LOCAL)
ffffffff81cf2819-ffffffff81cf284b: intel_xpower_pmic_update_power.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_xpower_pmic_update_power(struct regmap *regmap, int reg, int bit, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (0)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:176
Inline: False
```
**Symbols:**

```
ffffffff818a0c80-ffffffff818a0da8: intel_xpower_pmic_update_power (STB_LOCAL)
ffffffff81eba920-ffffffff81eba952: intel_xpower_pmic_update_power.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_xpower_pmic_update_power(struct regmap *regmap, int reg, int bit, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (0)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:176
Inline: False
```
**Symbols:**

```
ffffffff819ea230-ffffffff819ea358: intel_xpower_pmic_update_power (STB_LOCAL)
ffffffff82092bc9-ffffffff82092bfb: intel_xpower_pmic_update_power.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_xpower_pmic_update_power(struct regmap *regmap, int reg, int bit, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (0)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:176
Inline: False
```
**Symbols:**

```
ffffffff81a32950-ffffffff81a32a78: intel_xpower_pmic_update_power (STB_LOCAL)
ffffffff82113943-ffffffff82113975: intel_xpower_pmic_update_power.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_xpower_pmic_update_power(struct regmap *regmap, int reg, int bit, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/intel_pmic_xpower.c (0)
Location: drivers/acpi/pmic/intel_pmic_xpower.c:176
Inline: False
```
**Symbols:**

```
ffffffff81a7ddc0-ffffffff81a7dee8: intel_xpower_pmic_update_power (STB_LOCAL)
ffffffff821f12b6-ffffffff821f12e8: intel_xpower_pmic_update_power.cold (STB_LOCAL)
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
