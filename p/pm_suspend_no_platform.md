# Function: <code>pm_suspend_no_platform</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81565bd7)
Location: include/linux/suspend.h:288
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
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
In drivers/pci/pci-driver.c (ffffffff81586ef5)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff815e6285)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff8162d857)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff81691815)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff81652f47)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff816af555)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff816359fb)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff81691b65)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff816a5beb)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff81707605)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff817c8f4d)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff818357b5)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff818e686d)
Location: include/linux/suspend.h:290
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff819696f5)
Location: include/linux/suspend.h:290
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff81929e9f)
Location: include/linux/suspend.h:294
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff819afce5)
Location: include/linux/suspend.h:294
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff81972d57)
Location: include/linux/suspend.h:294
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff819fa195)
Location: include/linux/suspend.h:294
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffff8000106eaf14)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffff80001077158c)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c08865b8)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0000000008663e0)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: include/linux/suspend.h:340
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff81569b55)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff815c1d35)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff8157ac45)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff815da565)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/pci/pci-driver.c (ffffffff81595255)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/ec.c (ffffffff815f4425)
Location: include/linux/suspend.h:289
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_set_gpe_wake_mask
  - drivers/acpi/ec.c:acpi_ec_suspend
```
</details>
</li>
</ul>

## Differences
