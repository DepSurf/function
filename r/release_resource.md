# Function: <code>release_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086010)
Location: kernel/resource.c:323
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_del
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
```
**Symbols:**

```
ffffffff81086010-ffffffff8108608a: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81088ec0)
Location: kernel/resource.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_del
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81088ec0-ffffffff81088ef0: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108de10)
Location: kernel/resource.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_del
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8108de10-ffffffff8108de40: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ae40)
Location: kernel/resource.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8108ae40-ffffffff8108ae70: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091b20)
Location: kernel/resource.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81091b20-ffffffff81091b50: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810955d0)
Location: kernel/resource.c:309
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810955d0-ffffffff81095600: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109d950)
Location: kernel/resource.c:309
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8109d950-ffffffff8109d980: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1f00)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810a1f00-ffffffff810a1f32: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a84c0)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810a84c0-ffffffff810a84f2: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0455)
Location: kernel/resource.c:310
Inline: True
Inline callers:
  - kernel/resource.c:devm_resource_release
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:additional_memory_resource
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810afd90-ffffffff810afdc4: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810abb75)
Location: kernel/resource.c:310
Inline: True
Inline callers:
  - kernel/resource.c:devm_resource_release
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810ab4d0-ffffffff810ab504: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810acef5)
Location: kernel/resource.c:309
Inline: True
Inline callers:
  - kernel/resource.c:devm_resource_release
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810ac650-ffffffff810ac684: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bea65)
Location: kernel/resource.c:309
Inline: True
Inline callers:
  - kernel/resource.c:devm_resource_release
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810be1d0-ffffffff810be204: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5b54)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:devm_resource_release
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810d5240-ffffffff810d5284: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f4cc4)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:devm_resource_release
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810f42f0-ffffffff810f4334: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811010f4)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:devm_resource_release
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:__crash_shrink_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81100720-ffffffff81100764: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110a874)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:devm_resource_release
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:__crash_shrink_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81109ee0-ffffffff81109f24: release_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000101009a8)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_release
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffff8000101009a8-ffff800010100a90: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035c594)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_release
  - drivers/base/platform.c:platform_device_add
  - drivers/mfd/sm501.c:sm501_plat_remove
  - drivers/mfd/sm501.c:sm501_pci_remove
  - drivers/mfd/sm501.c:sm501_dev_remove
  - drivers/mfd/sm501.c:sm501_pci_probe
  - drivers/mfd/sm501.c:sm501_plat_probe
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/t7l66xb.c:t7l66xb_remove
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6387xb.c:tc6387xb_remove
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_remove
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/memory/omap-gpmc.c:gpmc_cs_free
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
  - drivers/memory/omap-gpmc.c:gpmc_cs_delete_mem
```
**Symbols:**

```
c035c594-c035c634: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000146db0)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/pci_dlpar.c:remove_phb_dynamic
  - arch/powerpc/platforms/pseries/pci_dlpar.c:remove_phb_dynamic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c000000000146db0-c000000000146e84: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c75a8)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - kernel/resource.c:devm_resource_release
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/base/platform.c:platform_device_add
```
**Symbols:**

```
ffffffe0000c75a8-ffffffe0000c7626: release_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1de0)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810a1de0-ffffffff810a1e12: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810907c0)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810907c0-ffffffff810907f2: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1d90)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810a1d90-ffffffff810a1dc2: release_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int release_resource(struct resource *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9db0)
Location: kernel/resource.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/resource.c:devm_resource_release
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/rapidio/rio.c:rio_release_outb_dbell
  - drivers/rapidio/rio.c:rio_release_inb_dbell
  - drivers/rapidio/rio.c:rio_release_outb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_release_inb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/acpi/pci_root.c:acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/intel-gtt.c:i9xx_cleanup
  - drivers/base/platform.c:platform_device_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_release_resources
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:free_all_mmcfg
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff810a9db0-ffffffff810a9ded: release_resource (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
