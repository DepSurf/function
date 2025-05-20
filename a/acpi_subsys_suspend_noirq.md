# Function: <code>acpi_subsys_suspend_noirq</code>

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
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153bb70)
Location: drivers/acpi/device_pm.c:1049
Inline: False
```
**Symbols:**

```
ffffffff8153bb70-ffffffff8153bb97: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81572040)
Location: drivers/acpi/device_pm.c:1049
Inline: True
```
**Symbols:**

```
ffffffff81572040-ffffffff815720a9: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81589e20)
Location: drivers/acpi/device_pm.c:1050
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff81589e20-ffffffff81589e89: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ba8a0)
Location: drivers/acpi/device_pm.c:1094
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff815ba8a0-ffffffff815ba909: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dbb40)
Location: drivers/acpi/device_pm.c:1099
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff815dbb40-ffffffff815dbba9: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81685b70)
Location: drivers/acpi/device_pm.c:1099
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff81685b70-ffffffff81685bb6: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a3980)
Location: drivers/acpi/device_pm.c:1095
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff816a3980-ffffffff816a39c6: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686770)
Location: drivers/acpi/device_pm.c:1094
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff81686770-ffffffff816867b6: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fbb10)
Location: drivers/acpi/device_pm.c:1094
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff816fbb10-ffffffff816fbb56: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81828d20)
Location: drivers/acpi/device_pm.c:1120
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff81828d20-ffffffff81828d6e: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195ae50)
Location: drivers/acpi/device_pm.c:1182
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff8195ae50-ffffffff8195ae9e: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a1320)
Location: drivers/acpi/device_pm.c:1182
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff819a1320-ffffffff819a136e: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819e99d0)
Location: drivers/acpi/device_pm.c:1195
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff819e99d0-ffffffff819e9a1e: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010767c28)
Location: drivers/acpi/device_pm.c:1099
Inline: True
```
**Symbols:**

```
ffff800010767c28-ffff800010767cb4: acpi_subsys_suspend_noirq (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ce210)
Location: drivers/acpi/device_pm.c:1099
Inline: True
```
**Symbols:**

```
ffffffff815ce210-ffffffff815ce279: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7dd0)
Location: drivers/acpi/device_pm.c:1099
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff815b7dd0-ffffffff815b7e39: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cfe20)
Location: drivers/acpi/device_pm.c:1099
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff815cfe20-ffffffff815cfe89: acpi_subsys_suspend_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_suspend_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e9ce0)
Location: drivers/acpi/device_pm.c:1099
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
```
**Symbols:**

```
ffffffff815e9ce0-ffffffff815e9d49: acpi_subsys_suspend_noirq (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
