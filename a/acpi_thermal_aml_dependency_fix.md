# Function: <code>acpi_thermal_aml_dependency_fix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff814b0ad8)
Location: drivers/acpi/thermal.c:996
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81500409)
Location: drivers/acpi/thermal.c:996
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81523105)
Location: drivers/acpi/thermal.c:997
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff8153524d)
Location: drivers/acpi/thermal.c:997
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81596b21)
Location: drivers/acpi/thermal.c:997
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff815cdf20)
Location: drivers/acpi/thermal.c:997
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff815e7502)
Location: drivers/acpi/thermal.c:997
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81619188)
Location: drivers/acpi/thermal.c:983
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff8163a7a8)
Location: drivers/acpi/thermal.c:978
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_thermal_aml_dependency_fix(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff816e61b0)
Location: drivers/acpi/thermal.c:980
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff816e61b0-ffffffff816e627d: acpi_thermal_aml_dependency_fix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_thermal_aml_dependency_fix(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81703960)
Location: drivers/acpi/thermal.c:944
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81703960-ffffffff81703a2d: acpi_thermal_aml_dependency_fix (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff816e61fd)
Location: drivers/acpi/thermal.c:924
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_get_info
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
In drivers/acpi/thermal.c (ffffffff8175f52f)
Location: drivers/acpi/thermal.c:924
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_get_info
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
In drivers/acpi/thermal.c (ffffffff81892e4f)
Location: drivers/acpi/thermal.c:923
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_get_info
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
In drivers/acpi/thermal.c (ffffffff819da85f)
Location: drivers/acpi/thermal.c:923
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_get_info
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
In drivers/acpi/thermal.c (ffffffff81a2244f)
Location: drivers/acpi/thermal.c:866
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_get_info
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
In drivers/acpi/thermal.c (ffffffff81a6cd9f)
Location: drivers/acpi/thermal.c:750
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffff8000107a56ec)
Location: drivers/acpi/thermal.c:978
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff8162ea88)
Location: drivers/acpi/thermal.c:978
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81648928)
Location: drivers/acpi/thermal.c:978
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
