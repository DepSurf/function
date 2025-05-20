# Function: <code>acpi_dev_pm_explicit_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_pm_explicit_set(struct acpi_device *adev, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147cd53)
Location: drivers/acpi/device_pm.c:128
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power
```
**Symbols:**

```
ffffffff8147cd53-ffffffff8147cdc9: acpi_dev_pm_explicit_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_pm_explicit_set(struct acpi_device *adev, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cb4e6)
Location: drivers/acpi/device_pm.c:129
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff814cb4e6-ffffffff814cb55c: acpi_dev_pm_explicit_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_pm_explicit_set(struct acpi_device *adev, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814ed412)
Location: drivers/acpi/device_pm.c:129
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff814ed412-ffffffff814ed488: acpi_dev_pm_explicit_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814facb3)
Location: drivers/acpi/device_pm.c:130
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff814f9fd0-ffffffff814fa035: acpi_dev_pm_explicit_set.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153c903)
Location: drivers/acpi/device_pm.c:130
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff8153bc90-ffffffff8153bcf5: acpi_dev_pm_explicit_set.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815727b3)
Location: drivers/acpi/device_pm.c:130
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff81571a90-ffffffff81571af5: acpi_dev_pm_explicit_set.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8158a3c3)
Location: drivers/acpi/device_pm.c:131
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff81589860-ffffffff815898c5: acpi_dev_pm_explicit_set.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815bb0a3)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff815ba3a0-ffffffff815ba405: acpi_dev_pm_explicit_set.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dc373)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff815db5e0-ffffffff815db645: acpi_dev_pm_explicit_set.part.0 (STB_LOCAL)
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
In drivers/acpi/device_pm.c (ffffffff81686813)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
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
In drivers/acpi/device_pm.c (ffffffff816a45c3)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
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
In drivers/acpi/device_pm.c (ffffffff8168733d)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
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
In drivers/acpi/device_pm.c (ffffffff816fc7bd)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
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
In drivers/acpi/device_pm.c (ffffffff81829eb7)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
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
In drivers/acpi/device_pm.c (ffffffff8195b325)
Location: drivers/acpi/device_pm.c:141
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/device_pm.c:fix_up_power_if_applicable
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
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
In drivers/acpi/device_pm.c (ffffffff819a17f5)
Location: drivers/acpi/device_pm.c:141
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/device_pm.c:fix_up_power_if_applicable
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
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
In drivers/acpi/device_pm.c (ffffffff819e9ea5)
Location: drivers/acpi/device_pm.c:141
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/device_pm.c:fix_up_power_if_applicable
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffff8000107689d8)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffff800010767640-ffff8000107676d0: acpi_dev_pm_explicit_set.part.0 (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ce9c3)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff815cddc0-ffffffff815cde25: acpi_dev_pm_explicit_set.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b8583)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff815b7930-ffffffff815b7995: acpi_dev_pm_explicit_set.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815d0653)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff815cf8c0-ffffffff815cf925: acpi_dev_pm_explicit_set.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ea513)
Location: drivers/acpi/device_pm.c:139
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
```
**Symbols:**

```
ffffffff815e9780-ffffffff815e97e5: acpi_dev_pm_explicit_set.part.0 (STB_LOCAL)
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
</ul>
