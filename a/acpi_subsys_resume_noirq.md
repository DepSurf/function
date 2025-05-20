# Function: <code>acpi_subsys_resume_noirq</code>

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
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153bba0)
Location: drivers/acpi/device_pm.c:1062
Inline: False
```
**Symbols:**

```
ffffffff8153bba0-ffffffff8153bbcb: acpi_subsys_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815720b0)
Location: drivers/acpi/device_pm.c:1080
Inline: True
```
**Symbols:**

```
ffffffff815720b0-ffffffff815720f4: acpi_subsys_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81589e90)
Location: drivers/acpi/device_pm.c:1081
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff81589e90-ffffffff81589ed4: acpi_subsys_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ba910)
Location: drivers/acpi/device_pm.c:1125
Inline: True
```
**Symbols:**

```
ffffffff815ba910-ffffffff815ba955: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dbbb0)
Location: drivers/acpi/device_pm.c:1130
Inline: True
```
**Symbols:**

```
ffffffff815dbbb0-ffffffff815dbbf5: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816859f0)
Location: drivers/acpi/device_pm.c:1128
Inline: False
```
**Symbols:**

```
ffffffff816859f0-ffffffff81685a1b: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a3800)
Location: drivers/acpi/device_pm.c:1124
Inline: False
```
**Symbols:**

```
ffffffff816a3800-ffffffff816a382b: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686600)
Location: drivers/acpi/device_pm.c:1123
Inline: False
```
**Symbols:**

```
ffffffff81686600-ffffffff8168662b: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fb910)
Location: drivers/acpi/device_pm.c:1123
Inline: False
```
**Symbols:**

```
ffffffff816fb910-ffffffff816fb93b: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81828e40)
Location: drivers/acpi/device_pm.c:1149
Inline: False
```
**Symbols:**

```
ffffffff81828e40-ffffffff81828e70: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195afb0)
Location: drivers/acpi/device_pm.c:1211
Inline: False
```
**Symbols:**

```
ffffffff8195afb0-ffffffff8195afe0: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a1480)
Location: drivers/acpi/device_pm.c:1211
Inline: False
```
**Symbols:**

```
ffffffff819a1480-ffffffff819a14b0: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819e9b30)
Location: drivers/acpi/device_pm.c:1224
Inline: False
```
**Symbols:**

```
ffffffff819e9b30-ffffffff819e9b60: acpi_subsys_resume_noirq (STB_LOCAL)
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
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010767cb8)
Location: drivers/acpi/device_pm.c:1130
Inline: True
```
**Symbols:**

```
ffff800010767cb8-ffff800010767d24: acpi_subsys_resume_noirq (STB_LOCAL)
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
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ce280)
Location: drivers/acpi/device_pm.c:1130
Inline: True
```
**Symbols:**

```
ffffffff815ce280-ffffffff815ce2c5: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7e40)
Location: drivers/acpi/device_pm.c:1130
Inline: True
```
**Symbols:**

```
ffffffff815b7e40-ffffffff815b7e85: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cfe90)
Location: drivers/acpi/device_pm.c:1130
Inline: True
```
**Symbols:**

```
ffffffff815cfe90-ffffffff815cfed5: acpi_subsys_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_subsys_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e9d50)
Location: drivers/acpi/device_pm.c:1130
Inline: True
```
**Symbols:**

```
ffffffff815e9d50-ffffffff815e9d95: acpi_subsys_resume_noirq (STB_LOCAL)
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
