# Function: <code>dev_pm_may_skip_resume</code>

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
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81656149)
Location: drivers/base/power/main.c:550
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81656bd0-ffffffff81656bf0: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81691702)
Location: drivers/base/power/main.c:564
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81692790-ffffffff816927b0: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b1cf2)
Location: drivers/base/power/main.c:565
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff816b2e00-ffffffff816b2e20: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ebb9b)
Location: drivers/base/power/main.c:557
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff816ecc20-ffffffff816ecc40: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170fc29)
Location: drivers/base/power/main.c:585
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff81710c90-ffffffff81710cb0: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff800010900288)
Location: drivers/base/power/main.c:585
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffff800010901490-ffff8000109014dc: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09ea4e8)
Location: drivers/base/power/main.c:585
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
c09eb6ac-c09eb6ec: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099d99c)
Location: drivers/base/power/main.c:585
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
c00000000099f1c0-c00000000099f208: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
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
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d5be9)
Location: drivers/base/power/main.c:585
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816d7010-ffffffff816d7030: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b0619)
Location: drivers/base/power/main.c:585
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff816b1670-ffffffff816b1690: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817038e9)
Location: drivers/base/power/main.c:585
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff81704950-ffffffff81704970: dev_pm_may_skip_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_may_skip_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171e639)
Location: drivers/base/power/main.c:585
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff8171f1c0-ffffffff8171f1e0: dev_pm_may_skip_resume (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
