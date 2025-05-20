# Function: <code>dev_pm_test_driver_flags</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: include/linux/device.h:1082
Inline: True
```
```
In drivers/acpi/device_pm.c (0)
Location: include/linux/device.h:1082
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/device.h:1082
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815207fd)
Location: include/linux/device.h:1127
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff815719c5)
Location: include/linux/device.h:1127
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff81693d30)
Location: include/linux/device.h:1127
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8153662d)
Location: include/linux/device.h:1180
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff81589795)
Location: include/linux/device.h:1180
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff816b43b0)
Location: include/linux/device.h:1180
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81565f02)
Location: include/linux/device.h:1213
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff815ba315)
Location: include/linux/device.h:1213
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff816ee279)
Location: include/linux/device.h:1213
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81587262)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff815db555)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff81712259)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162d982)
Location: include/linux/device.h:762
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff81685965)
Location: include/linux/device.h:762
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff817cb905)
Location: include/linux/device.h:762
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81653072)
Location: include/linux/device.h:730
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff816a3775)
Location: include/linux/device.h:730
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff817e0375)
Location: include/linux/device.h:730
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81635b12)
Location: include/linux/device.h:736
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff81686575)
Location: include/linux/device.h:736
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff817c4bb5)
Location: include/linux/device.h:736
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a5d02)
Location: include/linux/device.h:753
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff816fb885)
Location: include/linux/device.h:753
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff8184efc5)
Location: include/linux/device.h:753
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c85a2)
Location: include/linux/device.h:828
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff81828da5)
Location: include/linux/device.h:828
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff81993445)
Location: include/linux/device.h:828
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e5e42)
Location: include/linux/device.h:825
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff8195aef5)
Location: include/linux/device.h:825
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff81b03bc1)
Location: include/linux/device.h:825
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81929482)
Location: include/linux/device.h:951
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff819a13c5)
Location: include/linux/device.h:951
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff81b51c21)
Location: include/linux/device.h:951
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81971c82)
Location: include/linux/device.h:983
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff819e9a75)
Location: include/linux/device.h:983
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff81baa211)
Location: include/linux/device.h:983
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106eba84)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffff8000107675a0)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffff800010902c64)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0886964)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/base/power/main.c (c09ed08c)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c000000000867638)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/base/power/main.c (c0000000009a11f0)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157b432)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff815cdd35)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff816d85d9)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81569ec2)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff815b78a5)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff816b2c39)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157afb2)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff815cf835)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff81705f19)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815955c2)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
```
In drivers/acpi/device_pm.c (ffffffff815e96f5)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/base/power/main.c (ffffffff817208e4)
Location: include/linux/device.h:1455
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
</ul>

## Differences
