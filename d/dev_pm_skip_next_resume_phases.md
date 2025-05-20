# Function: <code>dev_pm_skip_next_resume_phases</code>

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
void dev_pm_skip_next_resume_phases(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81656bb0)
Location: drivers/base/power/main.c:537
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq
```
**Symbols:**

```
ffffffff81656bb0-ffffffff81656bc2: dev_pm_skip_next_resume_phases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_skip_next_resume_phases(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81691800)
Location: drivers/base/power/main.c:533
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq
```
**Symbols:**

```
ffffffff81692770-ffffffff81692782: dev_pm_skip_next_resume_phases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_skip_next_resume_phases(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b1df0)
Location: drivers/base/power/main.c:534
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq
```
**Symbols:**

```
ffffffff816b2de0-ffffffff816b2df2: dev_pm_skip_next_resume_phases (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
