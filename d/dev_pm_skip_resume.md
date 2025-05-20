# Function: <code>dev_pm_skip_resume</code>

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
bool dev_pm_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cc057)
Location: drivers/base/power/main.c:574
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_early
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff817ccaf0-ffffffff817ccb32: dev_pm_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e0ac7)
Location: drivers/base/power/main.c:573
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_early
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff817e1520-ffffffff817e1562: dev_pm_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c46c7)
Location: drivers/base/power/main.c:574
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_early
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff817c5930-ffffffff817c5972: dev_pm_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184eaa7)
Location: drivers/base/power/main.c:571
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_early
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff8184fcb0-ffffffff8184fcf2: dev_pm_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81994ae3)
Location: drivers/base/power/main.c:570
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_early
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff819955a0-ffffffff819955f2: dev_pm_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b05603)
Location: drivers/base/power/main.c:570
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_early
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff81b060e0-ffffffff81b06132: dev_pm_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b53613)
Location: drivers/base/power/main.c:570
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_early
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff81b54120-ffffffff81b54172: dev_pm_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81babd05)
Location: drivers/base/power/main.c:570
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_early
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff81bac870-ffffffff81bac8c2: dev_pm_skip_resume (STB_GLOBAL)
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
