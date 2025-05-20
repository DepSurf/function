# Function: <code>pci_is_bridge</code>

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
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:514
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/pci.h:514
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (0)
Location: include/linux/pci.h:514
Inline: True
```
```
In drivers/pci/hotplug/pciehp_pci.c (0)
Location: include/linux/pci.h:514
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/linux/pci.h:514
Inline: True
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci.h:514
Inline: True
```
```
In arch/x86/pci/fixup.c (0)
Location: include/linux/pci.h:514
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
In drivers/pci/probe.c (ffffffff8147e368)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8148c805)
Location: include/linux/pci.h:513
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8149ad1d)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8149c6e1)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149e95c)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/pci-acpi.c (ffffffff814a44a9)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
```
```
In arch/x86/pci/fixup.c (ffffffff8175d4ff)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8149fa28)
Location: include/linux/pci.h:543
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus
```
```
In drivers/pci/setup-bus.c (ffffffff814adff5)
Location: include/linux/pci.h:543
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff814bc8fd)
Location: include/linux/pci.h:543
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814be261)
Location: include/linux/pci.h:543
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c058c)
Location: include/linux/pci.h:543
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/pci-acpi.c (ffffffff814c62b9)
Location: include/linux/pci.h:543
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
```
```
In arch/x86/pci/fixup.c (ffffffff81789a2f)
Location: include/linux/pci.h:543
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff814a97d8)
Location: include/linux/pci.h:570
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b2645)
Location: include/linux/pci.h:570
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff814b8395)
Location: include/linux/pci.h:570
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814bce7d)
Location: include/linux/pci.h:570
Inline: True
Inline callers:
  - drivers/pci/quirks.c:hibmc_fixup_vgaarb
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff814c70bf)
Location: include/linux/pci.h:570
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814c8a31)
Location: include/linux/pci.h:570
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cacb6)
Location: include/linux/pci.h:570
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/pci-acpi.c (ffffffff814d0189)
Location: include/linux/pci.h:570
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
```
```
In arch/x86/pci/fixup.c (ffffffff817a8b0f)
Location: include/linux/pci.h:570
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff814e8854)
Location: include/linux/pci.h:591
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f1d35)
Location: include/linux/pci.h:591
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff814f663f)
Location: include/linux/pci.h:591
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8150768c)
Location: include/linux/pci.h:591
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81508fe1)
Location: include/linux/pci.h:591
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150b283)
Location: include/linux/pci.h:591
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/pci-acpi.c (ffffffff815103c1)
Location: include/linux/pci.h:591
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
```
```
In arch/x86/pci/fixup.c (ffffffff8181fdaf)
Location: include/linux/pci.h:591
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff81517e7a)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci-sysfs.c (ffffffff81521fa5)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff8152736c)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8153869c)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81539f41)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8153da1c)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81540873)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/pci-acpi.c (ffffffff815454f5)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In arch/x86/pci/fixup.c (ffffffff81869fff)
Location: include/linux/pci.h:595
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8152d8fa)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci-sysfs.c (ffffffff81537dd5)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff8153d20c)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81541535)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8154f9fc)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8155127f)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81554dcc)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81557abd)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff8188a07f)
Location: include/linux/pci.h:616
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8155c078)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci-sysfs.c (ffffffff815677c5)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff8156c834)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81570e75)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8157f86c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815811ff)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81584edc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81587af2)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff818d46e1)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8157d148)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff81584b3d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff81588ac5)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff8158fb46)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81592065)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff815a12ac)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815a2cff)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff815a68bc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a94cd)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff81906a61)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff81622738)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff8162b775)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff8162fa35)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff81636c75)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81640955)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff81649c4c)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8164b87f)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8164f5cc)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8165215a)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff81bb7151)
Location: include/linux/pci.h:660
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff81649328)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff81651475)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff816550c5)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff8165bd35)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81666d75)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8166e6ba)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8166fbff)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81672b2c)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674b1a)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff81bcc1e1)
Location: include/linux/pci.h:676
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8162bee8)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff81633ef5)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff81637cf5)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff8163e2d5)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81649155)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff81650c0a)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816520ff)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8165502c)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8165704b)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff81bbfc21)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8169b3b8)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff816a40d5)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a7f65)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff816aee35)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff816ba9d1)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff816c294a)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816c3e4f)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff816c6f4a)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8fcf)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff81c8fbb1)
Location: include/linux/pci.h:690
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff817bcb53)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff817c64c5)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff817caaa5)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff817d22c5)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff817e05e4)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff817e833e)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff817e9993)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff817eceda)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817ef217)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff81e3ec15)
Location: include/linux/pci.h:703
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff818d8ac3)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff818e387d)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e85f5)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff818f2915)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff819035a4)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8190dabe)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8190f973)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8191408a)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81917334)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff82018835)
Location: include/linux/pci.h:707
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8191be03)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff81926e13)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192bc05)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff81935d35)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81946c44)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8195113e)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81953065)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff819576ea)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a939)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff82098e05)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/bus.c (0)
Location: include/linux/pci.h:710
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81964233)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff8196f5b3)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff819744f5)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff8197eae5)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff8198ff70)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff8199a59e)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8199c4f5)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff819a0c5a)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a3f36)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff821702e5)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffff8000106e086c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffff8000106e9194)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ed154)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffff8000106f45bc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffff8000106f7e34)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffff800010709a04)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffff80001070b5c0)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffff80001070f3fc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff8000107127bc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/probe.c (c087c5dc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (c0884138)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (c08883cc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (c088efd0)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
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
In arch/powerpc/kernel/pci-hotplug.c (c00000000006b3cc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices
```
```
In arch/powerpc/kernel/pci_of_scan.c (c00000000006f9ac)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_of_scan.c:__of_scan_bus
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d7b18)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_setup_bridge
```
```
In drivers/pci/probe.c (c00000000085980c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (c000000000863fbc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (c000000000869148)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (c000000000872e7c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (c000000000882c3c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
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
In drivers/pci/probe.c (ffffffe0004b8614)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffe0004bf594)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c1eec)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffe0004c7658)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffe0004d6e88)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffe0004d81e6)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffe0004db718)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
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
In drivers/pci/probe.c (ffffffff81571668)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff8157905d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157c955)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff815839ca)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81585ef5)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff81594abc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8159650f)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8159a0cc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159cc9d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff818a5e21)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8155fdc8)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff8156779d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156b725)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff815727a6)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81574cc5)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff81583c4c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8158569f)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8158925c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158be2d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff81860951)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff81570e98)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff8157888d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157c815)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff81583896)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81585db5)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff81594ffc)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81596a4f)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8159a60c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d21d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff818f7481)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
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
In drivers/pci/probe.c (ffffffff8158b378)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
```
In drivers/pci/pci.c (ffffffff81592d4d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff81596cc5)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
```
```
In drivers/pci/setup-bus.c (ffffffff8159dd46)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff815a0265)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/hotplug/cpci_hotplug_pci.c (ffffffff815af47c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815b0ecf)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff815b4a4c)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b764d)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In arch/x86/pci/fixup.c (ffffffff81918581)
Location: include/linux/pci.h:633
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
```
</details>
</li>
</ul>

## Differences
