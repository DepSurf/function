# Function: <code>dev_pm_smart_suspend_and_suspended</code>

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
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816589c0)
Location: drivers/base/power/main.c:1941
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_late
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_freeze_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_freeze_late
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
```
**Symbols:**

```
ffffffff816589c0-ffffffff816589e0: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81691dfb)
Location: drivers/base/power/main.c:2117
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_late
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_freeze_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_freeze_late
```
**Symbols:**

```
ffffffff81694380-ffffffff816943a0: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b245b)
Location: drivers/base/power/main.c:2123
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_late
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_freeze_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_freeze_late
```
**Symbols:**

```
ffffffff816b4a00-ffffffff816b4a20: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ec237)
Location: drivers/base/power/main.c:2111
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff816ee8c0-ffffffff816ee8e0: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817102a7)
Location: drivers/base/power/main.c:2132
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff817128a0-ffffffff817128c0: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
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
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff800010900958)
Location: drivers/base/power/main.c:2132
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
```
**Symbols:**

```
ffff800010903480-ffff8000109034c8: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09eaadc)
Location: drivers/base/power/main.c:2132
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
**Symbols:**

```
c09ed850-c09ed884: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099e180)
Location: drivers/base/power/main.c:2132
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
**Symbols:**

```
c0000000009a1cb0-c0000000009a1ce8: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
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
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d63a7)
Location: drivers/base/power/main.c:2132
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
```
**Symbols:**

```
ffffffff816d8c20-ffffffff816d8c40: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b0c97)
Location: drivers/base/power/main.c:2132
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff816b3260-ffffffff816b3280: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81703f67)
Location: drivers/base/power/main.c:2132
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff81706560-ffffffff81706580: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171ecb7)
Location: drivers/base/power/main.c:2132
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff81720f70-ffffffff81720f90: dev_pm_smart_suspend_and_suspended (STB_GLOBAL)
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
