# Function: <code>lpss_reg_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8148789c)
Location: drivers/acpi/acpi_lpss.c:436
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff8148789c-ffffffff814879a8: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff814d65c7)
Location: drivers/acpi/acpi_lpss.c:468
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff814d65c7-ffffffff814d66d0: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff814f8c27)
Location: drivers/acpi/acpi_lpss.c:479
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff814f8c27-ffffffff814f8d30: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81507940)
Location: drivers/acpi/acpi_lpss.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff81507940-ffffffff81507a64: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81549dc0)
Location: drivers/acpi/acpi_lpss.c:525
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff81549dc0-ffffffff81549eb5: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8157ffd0)
Location: drivers/acpi/acpi_lpss.c:671
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff8157ffd0-ffffffff815800c5: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81597eb0)
Location: drivers/acpi/acpi_lpss.c:704
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff81597eb0-ffffffff81597fa8: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (0)
Location: drivers/acpi/acpi_lpss.c:701
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff815c91e0-ffffffff815c92d3: lpss_reg_read (STB_LOCAL)
ffffffff815ca42c-ffffffff815ca460: lpss_reg_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815ea270)
Location: drivers/acpi/acpi_lpss.c:726
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff815ea270-ffffffff815ea368: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816960c0)
Location: drivers/acpi/acpi_lpss.c:704
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff816960c0-ffffffff816961b8: lpss_reg_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816b3210)
Location: drivers/acpi/acpi_lpss.c:711
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff816b3210-ffffffff816b3308: lpss_reg_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81695490)
Location: drivers/acpi/acpi_lpss.c:712
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff81695490-ffffffff81695588: lpss_reg_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8170b1c0)
Location: drivers/acpi/acpi_lpss.c:713
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff8170b1c0-ffffffff8170b2b8: lpss_reg_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81839720)
Location: drivers/acpi/acpi_lpss.c:735
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff81839720-ffffffff818397fd: lpss_reg_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8196ed00)
Location: drivers/acpi/acpi_lpss.c:724
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff8196ed00-ffffffff8196eddd: lpss_reg_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819b5280)
Location: drivers/acpi/acpi_lpss.c:739
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff819b5280-ffffffff819b535d: lpss_reg_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819ff600)
Location: drivers/acpi/acpi_lpss.c:703
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff819ff600-ffffffff819ff6dd: lpss_reg_read.constprop.0 (STB_LOCAL)
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c4ce0)
Location: drivers/acpi/acpi_lpss.c:726
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff815c4ce0-ffffffff815c4dd8: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815de550)
Location: drivers/acpi/acpi_lpss.c:726
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff815de550-ffffffff815de648: lpss_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lpss_reg_read(struct device *dev, unsigned int reg, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815f8410)
Location: drivers/acpi/acpi_lpss.c:726
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:lpss_ltr_mode_show
  - drivers/acpi/acpi_lpss.c:lpss_ltr_show
```
**Symbols:**

```
ffffffff815f8410-ffffffff815f8508: lpss_reg_read (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
</ul>
<b>Flavor</b>
<ul>
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
