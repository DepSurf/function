# Function: <code>acpi_lpss_suspend</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8154a4c0)
Location: drivers/acpi/acpi_lpss.c:804
Inline: True
```
**Symbols:**

```
ffffffff8154a4c0-ffffffff8154a65a: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815807e0)
Location: drivers/acpi/acpi_lpss.c:960
Inline: True
```
**Symbols:**

```
ffffffff815807e0-ffffffff81580987: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81598d50)
Location: drivers/acpi/acpi_lpss.c:993
Inline: True
```
**Symbols:**

```
ffffffff81598d50-ffffffff81598ef7: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c9920)
Location: drivers/acpi/acpi_lpss.c:990
Inline: True
```
**Symbols:**

```
ffffffff815c9920-ffffffff815c9ac6: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815eab40)
Location: drivers/acpi/acpi_lpss.c:1015
Inline: True
```
**Symbols:**

```
ffffffff815eab40-ffffffff815eace6: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81695d20)
Location: drivers/acpi/acpi_lpss.c:993
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff81695d20-ffffffff81695de6: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816b2eb0)
Location: drivers/acpi/acpi_lpss.c:1005
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff816b2eb0-ffffffff816b2f37: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81695050)
Location: drivers/acpi/acpi_lpss.c:1006
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff81695050-ffffffff816951b3: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8170ad40)
Location: drivers/acpi/acpi_lpss.c:1007
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff8170ad40-ffffffff8170aea3: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81839310)
Location: drivers/acpi/acpi_lpss.c:1029
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff81839310-ffffffff8183948c: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8196e830)
Location: drivers/acpi/acpi_lpss.c:1018
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff8196e830-ffffffff8196e9ac: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819b4db0)
Location: drivers/acpi/acpi_lpss.c:1033
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff819b4db0-ffffffff819b4f2c: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819ff230)
Location: drivers/acpi/acpi_lpss.c:997
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff819ff230-ffffffff819ff3ac: acpi_lpss_suspend (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c5560)
Location: drivers/acpi/acpi_lpss.c:1015
Inline: True
```
**Symbols:**

```
ffffffff815c5560-ffffffff815c5706: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815dee20)
Location: drivers/acpi/acpi_lpss.c:1015
Inline: True
```
**Symbols:**

```
ffffffff815dee20-ffffffff815defc6: acpi_lpss_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_lpss_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815f8ce0)
Location: drivers/acpi/acpi_lpss.c:1015
Inline: True
```
**Symbols:**

```
ffffffff815f8ce0-ffffffff815f8e86: acpi_lpss_suspend (STB_LOCAL)
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
