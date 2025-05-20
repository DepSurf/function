# Function: <code>acpi_thermal_get_info</code>

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
Location: drivers/acpi/thermal.c:1016
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
Location: drivers/acpi/thermal.c:1016
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
Location: drivers/acpi/thermal.c:1017
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
Location: drivers/acpi/thermal.c:1017
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
Location: drivers/acpi/thermal.c:1017
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
Location: drivers/acpi/thermal.c:1017
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
Location: drivers/acpi/thermal.c:1017
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
Location: drivers/acpi/thermal.c:1003
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
Location: drivers/acpi/thermal.c:998
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff816e73cf)
Location: drivers/acpi/thermal.c:1000
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff81704c8f)
Location: drivers/acpi/thermal.c:964
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_get_info(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:944
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff816e61c0-ffffffff816e6388: acpi_thermal_get_info (STB_LOCAL)
ffffffff81bf4956-ffffffff81bf496d: acpi_thermal_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_get_info(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:944
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff8175f4f0-ffffffff8175f6de: acpi_thermal_get_info (STB_LOCAL)
ffffffff81cf1aae-ffffffff81cf1ac5: acpi_thermal_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_get_info(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:943
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81892e10-ffffffff8189301f: acpi_thermal_get_info (STB_LOCAL)
ffffffff81eb9a43-ffffffff81eb9a59: acpi_thermal_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_thermal_get_info(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff819da820)
Location: drivers/acpi/thermal.c:943
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff819da820-ffffffff819daa45: acpi_thermal_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_get_info(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:886
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81a22410-ffffffff81a2265c: acpi_thermal_get_info (STB_LOCAL)
ffffffff82113520-ffffffff8211358e: acpi_thermal_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
Location: drivers/acpi/thermal.c:998
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
Location: drivers/acpi/thermal.c:998
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
Location: drivers/acpi/thermal.c:998
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
</ul>
