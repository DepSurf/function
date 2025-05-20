# Function: <code>pci_ari_enabled</code>

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
In drivers/pci/probe.c (ffffffff8143017f)
Location: include/linux/pci.h:1994
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81433652)
Location: include/linux/pci.h:1994
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/iov.c (ffffffff814570b0)
Location: include/linux/pci.h:1994
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff81487067)
Location: include/linux/pci.h:1994
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff814d1c69)
Location: include/linux/pci.h:1994
Inline: True
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
In drivers/pci/probe.c (ffffffff8147b8df)
Location: include/linux/pci.h:2093
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8147ef42)
Location: include/linux/pci.h:2093
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/iov.c (ffffffff814a38bc)
Location: include/linux/pci.h:2093
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff814d5c9a)
Location: include/linux/pci.h:2093
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8152294d)
Location: include/linux/pci.h:2093
Inline: True
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
In drivers/pci/probe.c (ffffffff8149cdef)
Location: include/linux/pci.h:2169
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814a0622)
Location: include/linux/pci.h:2169
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/iov.c (ffffffff814c551c)
Location: include/linux/pci.h:2169
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff814f82f2)
Location: include/linux/pci.h:2169
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8154ee2d)
Location: include/linux/pci.h:2169
Inline: True
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
In drivers/pci/probe.c (ffffffff814a6cef)
Location: include/linux/pci.h:2201
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814aa2d2)
Location: include/linux/pci.h:2201
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/iov.c (ffffffff814cf6ad)
Location: include/linux/pci.h:2201
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff8150706a)
Location: include/linux/pci.h:2201
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff815633a3)
Location: include/linux/pci.h:2201
Inline: True
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
In drivers/pci/probe.c (ffffffff814e563f)
Location: include/linux/pci.h:2257
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814e9532)
Location: include/linux/pci.h:2257
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/iov.c (ffffffff8150f8bd)
Location: include/linux/pci.h:2257
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff815492b7)
Location: include/linux/pci.h:2257
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff815c7686)
Location: include/linux/pci.h:2257
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
In drivers/pci/probe.c (ffffffff81514acf)
Location: include/linux/pci.h:2268
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81518cc2)
Location: include/linux/pci.h:2268
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff815229d6)
Location: include/linux/pci.h:2268
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff81544bfd)
Location: include/linux/pci.h:2268
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff8157f417)
Location: include/linux/pci.h:2268
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff815ffeff)
Location: include/linux/pci.h:2268
Inline: True
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
In drivers/pci/probe.c (ffffffff8152a1ef)
Location: include/linux/pci.h:2315
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8152e732)
Location: include/linux/pci.h:2315
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff815387b6)
Location: include/linux/pci.h:2315
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff8155bfca)
Location: include/linux/pci.h:2315
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff81597137)
Location: include/linux/pci.h:2315
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8161afcf)
Location: include/linux/pci.h:2315
Inline: True
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
In drivers/pci/probe.c (ffffffff8155994e)
Location: include/linux/pci.h:2389
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8155dee2)
Location: include/linux/pci.h:2389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff815681a9)
Location: include/linux/pci.h:2389
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff8158c097)
Location: include/linux/pci.h:2389
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff815c82e8)
Location: include/linux/pci.h:2389
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8164ece0)
Location: include/linux/pci.h:2389
Inline: True
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
In drivers/pci/probe.c (ffffffff8157a9be)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8157ef52)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff81589489)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff815adc4a)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff815e9508)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8167106f)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff816201aa)
Location: include/linux/pci.h:2384
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81626fb2)
Location: include/linux/pci.h:2384
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff81630365)
Location: include/linux/pci.h:2384
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff816562f8)
Location: include/linux/pci.h:2384
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff81694eea)
Location: include/linux/pci.h:2384
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff81721747)
Location: include/linux/pci.h:2384
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff8164682a)
Location: include/linux/pci.h:2376
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8164cb82)
Location: include/linux/pci.h:2376
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff816559d8)
Location: include/linux/pci.h:2376
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff81676898)
Location: include/linux/pci.h:2376
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff816b213a)
Location: include/linux/pci.h:2376
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff8173e41d)
Location: include/linux/pci.h:2376
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff8162942a)
Location: include/linux/pci.h:2416
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8162f709)
Location: include/linux/pci.h:2416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff81638698)
Location: include/linux/pci.h:2416
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff81658eb8)
Location: include/linux/pci.h:2416
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff816944df)
Location: include/linux/pci.h:2416
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff81721ec1)
Location: include/linux/pci.h:2416
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff81698e0a)
Location: include/linux/pci.h:2425
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8169f459)
Location: include/linux/pci.h:2425
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a89c8)
Location: include/linux/pci.h:2425
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff816caf1a)
Location: include/linux/pci.h:2425
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff8170a1ef)
Location: include/linux/pci.h:2425
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff817a0cff)
Location: include/linux/pci.h:2425
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff817bb9b1)
Location: include/linux/pci.h:2457
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff817c0934)
Location: include/linux/pci.h:2457
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cb688)
Location: include/linux/pci.h:2457
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff817f1535)
Location: include/linux/pci.h:2457
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff81838723)
Location: include/linux/pci.h:2457
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff818da9b7)
Location: include/linux/pci.h:2457
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff818d74d1)
Location: include/linux/pci.h:2496
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff818dd1a4)
Location: include/linux/pci.h:2496
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e8dd8)
Location: include/linux/pci.h:2496
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff81919a60)
Location: include/linux/pci.h:2496
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff8196dab3)
Location: include/linux/pci.h:2496
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff81a2d977)
Location: include/linux/pci.h:2496
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff8191a766)
Location: include/linux/pci.h:2588
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff8192072a)
Location: include/linux/pci.h:2588
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192c3e8)
Location: include/linux/pci.h:2588
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff8195d080)
Location: include/linux/pci.h:2588
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff819b3fe3)
Location: include/linux/pci.h:2588
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff81a77117)
Location: include/linux/pci.h:2588
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff81962b66)
Location: include/linux/pci.h:2659
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff819688ba)
Location: include/linux/pci.h:2659
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff81974d18)
Location: include/linux/pci.h:2659
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff819a66a6)
Location: include/linux/pci.h:2659
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff819fe4ca)
Location: include/linux/pci.h:2659
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/xen/pci.c (ffffffff81ac9327)
Location: include/linux/pci.h:2659
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffff8000106dd434)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (ffff8000106e19e8)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffff8000106edc00)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffff800010717b70)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffff800010776638)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffff80001083c770)
Location: include/linux/pci.h:2357
Inline: True
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
In drivers/pci/probe.c (c0878f38)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (c087d538)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (c0888dfc)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (c08a22a4)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/probe.c (c0000000008555dc)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (c00000000085ad70)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (c00000000086a1bc)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (c000000000887220)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b572e)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (ffffffe0004b94fa)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c26ca)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffe0004e0d94)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
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
In drivers/pci/probe.c (ffffffff8156eede)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81573472)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d319)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff815a1417)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff815da548)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8163712f)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff8155d63e)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81561bd2)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156c0e9)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff815905aa)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff815c4168)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/pci/probe.c (ffffffff8156e70e)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81572ca2)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d1d9)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff815a199a)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff815dd7e8)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff81664eaf)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/probe.c (ffffffff81588bee)
Location: include/linux/pci.h:2357
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8158d182)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_common_swizzle
  - drivers/pci/pci.c:pci_get_interrupt_pin
```
```
In drivers/pci/pci-sysfs.c (ffffffff81597689)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:ari_enabled_show
```
```
In drivers/pci/iov.c (ffffffff815bbd9a)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/acpi/pci_irq.c (ffffffff815f76a8)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/xen/pci.c (ffffffff8167f45f)
Location: include/linux/pci.h:2357
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
</details>
</li>
</ul>

## Differences
