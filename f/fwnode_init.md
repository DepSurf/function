# Function: <code>fwnode_init</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112598b)
Location: include/linux/fwnode.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
```
```
In drivers/acpi/scan.c (ffffffff816a9898)
Location: include/linux/fwnode.h:154
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/property.c (ffffffff816b9119)
Location: include/linux/fwnode.h:154
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
```
In drivers/base/swnode.c (ffffffff817d7ce6)
Location: include/linux/fwnode.h:154
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
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
In kernel/irq/irqdomain.c (ffffffff81125c7b)
Location: include/linux/fwnode.h:166
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
```
```
In drivers/acpi/scan.c (ffffffff8168c001)
Location: include/linux/fwnode.h:166
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/property.c (ffffffff8169b119)
Location: include/linux/fwnode.h:166
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
```
In drivers/base/swnode.c (ffffffff817bb88a)
Location: include/linux/fwnode.h:166
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
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
In kernel/irq/irqdomain.c (ffffffff8114641b)
Location: include/linux/fwnode.h:171
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
```
```
In drivers/acpi/scan.c (ffffffff817017c1)
Location: include/linux/fwnode.h:171
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/property.c (ffffffff81710fb9)
Location: include/linux/fwnode.h:171
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
```
In drivers/acpi/viot.c (ffffffff832f6b95)
Location: include/linux/fwnode.h:171
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_get_iommu
```
```
In drivers/base/swnode.c (ffffffff8184579a)
Location: include/linux/fwnode.h:171
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/firmware/efi/sysfb_efi.c (ffffffff8330f5d5)
Location: include/linux/fwnode.h:171
Inline: True
Inline callers:
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
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
In kernel/irq/irqdomain.c (ffffffff8116a6dc)
Location: include/linux/fwnode.h:177
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
```
```
In drivers/acpi/scan.c (ffffffff8182f450)
Location: include/linux/fwnode.h:177
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/property.c (ffffffff8183fd2e)
Location: include/linux/fwnode.h:177
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
```
In drivers/acpi/viot.c (ffffffff834af0f3)
Location: include/linux/fwnode.h:177
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_get_iommu
```
```
In drivers/base/swnode.c (ffffffff81989a54)
Location: include/linux/fwnode.h:177
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/firmware/efi/sysfb_efi.c (ffffffff834c9364)
Location: include/linux/fwnode.h:177
Inline: True
Inline callers:
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
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
In kernel/irq/irqdomain.c (ffffffff8119f28c)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
```
```
In drivers/acpi/scan.c (ffffffff819624b2)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/property.c (ffffffff819762fe)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
```
In drivers/acpi/viot.c (ffffffff83ee8763)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_get_iommu
```
```
In drivers/base/swnode.c (ffffffff81af8d94)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/firmware/efi/sysfb_efi.c (ffffffff83f0a8fd)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/firmware/efi/sysfb_efi.c:sysfb_apply_efi_quirks
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
In kernel/irq/irqdomain.c (ffffffff811b115c)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
```
```
In drivers/acpi/scan.c (ffffffff819a88b2)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/property.c (ffffffff819bcc66)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
```
In drivers/acpi/viot.c (ffffffff8370e11f)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_get_iommu
```
```
In drivers/base/swnode.c (ffffffff81b472c3)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/firmware/efi/sysfb_efi.c (ffffffff83730a4a)
Location: include/linux/fwnode.h:190
Inline: True
Inline callers:
  - drivers/firmware/efi/sysfb_efi.c:sysfb_set_efifb_fwnode
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
In kernel/irq/irqdomain.c (ffffffff811c0f0b)
Location: include/linux/fwnode.h:192
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
```
```
In drivers/acpi/scan.c (ffffffff819f12c2)
Location: include/linux/fwnode.h:192
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/property.c (ffffffff81a07b23)
Location: include/linux/fwnode.h:192
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
```
In drivers/acpi/viot.c (ffffffff8394185d)
Location: include/linux/fwnode.h:192
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_get_iommu
```
```
In drivers/base/swnode.c (ffffffff81b9f652)
Location: include/linux/fwnode.h:192
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/firmware/efi/sysfb_efi.c (ffffffff83964faa)
Location: include/linux/fwnode.h:192
Inline: True
Inline callers:
  - drivers/firmware/efi/sysfb_efi.c:sysfb_set_efifb_fwnode
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
