# Function: <code>device_set_run_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8144b8d0)
Location: include/linux/pm_runtime.h:80
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/pci-acpi.c (ffffffff814577fc)
Location: include/linux/pm_runtime.h:80
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
```
In drivers/acpi/pci_root.c (ffffffff814857e1)
Location: include/linux/pm_runtime.h:80
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
```
In drivers/ata/libata-zpodd.c (ffffffff815e2452)
Location: include/linux/pm_runtime.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81497cdc)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4425)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
```
In drivers/acpi/pci_root.c (ffffffff814d436e)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
```
In drivers/ata/libata-zpodd.c (ffffffff8163c173)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff814b961a)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/pci-acpi.c (ffffffff814c6235)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
```
In drivers/acpi/pci_root.c (ffffffff814f69bd)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
```
In drivers/ata/libata-zpodd.c (ffffffff8166d1f3)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d43ad)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
```
</details>
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
