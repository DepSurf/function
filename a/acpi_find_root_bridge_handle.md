# Function: <code>acpi_find_root_bridge_handle</code>

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
In drivers/pci/pcie/portdrv_acpi.c (ffffffff8144943c)
Location: include/linux/pci-acpi.h:27
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8144e8c6)
Location: include/linux/pci-acpi.h:27
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452a5a)
Location: include/linux/pci-acpi.h:27
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
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
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81495736)
Location: include/linux/pci-acpi.h:29
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8149b078)
Location: include/linux/pci-acpi.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149f460)
Location: include/linux/pci-acpi.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
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
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814b70f6)
Location: include/linux/pci-acpi.h:31
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814bcc58)
Location: include/linux/pci-acpi.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff814c69bb)
Location: include/linux/pci-acpi.h:31
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pciehp_is_native
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814c1a37)
Location: include/linux/pci-acpi.h:31
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814c7428)
Location: include/linux/pci-acpi.h:31
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff814d092b)
Location: include/linux/pci-acpi.h:31
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pciehp_is_native
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81501c4e)
Location: include/linux/pci-acpi.h:32
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815079e8)
Location: include/linux/pci-acpi.h:32
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff81510b60)
Location: include/linux/pci-acpi.h:32
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pciehp_is_native
```
</details>
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
