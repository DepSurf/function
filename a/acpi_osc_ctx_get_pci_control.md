# Function: <code>acpi_osc_ctx_get_pci_control</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff834a9b93)
Location: include/linux/acpi.h:625
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
```
In drivers/acpi/pci_root.c (ffffffff81eb7add)
Location: include/linux/acpi.h:625
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_run_osc
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
In drivers/acpi/bus.c (ffffffff83ee1922)
Location: include/linux/acpi.h:632
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
```
In drivers/acpi/pci_root.c (ffffffff8196b03f)
Location: include/linux/acpi.h:632
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/bus.c (ffffffff837072e2)
Location: include/linux/acpi.h:623
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
```
In drivers/acpi/pci_root.c (ffffffff819b15f8)
Location: include/linux/acpi.h:623
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/bus.c (ffffffff819ecea3)
Location: include/linux/acpi.h:624
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_osc_negotiate_usb_control
```
```
In drivers/acpi/pci_root.c (ffffffff819fbad8)
Location: include/linux/acpi.h:624
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
