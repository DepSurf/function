# Function: <code>dev_pm_skip_suspend</code>

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
bool dev_pm_skip_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cb56e)
Location: drivers/base/power/main.c:2009
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff817ce0c0-ffffffff817ce0e0: dev_pm_skip_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817dfffe)
Location: drivers/base/power/main.c:2008
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff817e29d0-ffffffff817e29f0: dev_pm_skip_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c54a2)
Location: drivers/base/power/main.c:2009
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff817c6db0-ffffffff817c6dd0: dev_pm_skip_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184f852)
Location: drivers/base/power/main.c:2037
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff81851190-ffffffff818511b0: dev_pm_skip_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81993bf8)
Location: drivers/base/power/main.c:2035
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff81996ca0-ffffffff81996cc6: dev_pm_skip_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b04408)
Location: drivers/base/power/main.c:2035
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff81b07a80-ffffffff81b07aa6: dev_pm_skip_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b53328)
Location: drivers/base/power/main.c:2035
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff81b55ad0-ffffffff81b55af6: dev_pm_skip_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool dev_pm_skip_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81bab6c8)
Location: drivers/base/power/main.c:2034
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
**Symbols:**

```
ffffffff81bae090-ffffffff81bae0b6: dev_pm_skip_suspend (STB_GLOBAL)
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
