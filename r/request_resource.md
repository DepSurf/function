# Function: <code>request_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81085fd0)
Location: kernel/resource.c:309
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - kernel/resource.c:reserve_setup
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff81085fd0-ffffffff81086010: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81088e80)
Location: kernel/resource.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - kernel/resource.c:reserve_setup
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff81088e80-ffffffff81088ec0: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ddd0)
Location: kernel/resource.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - kernel/resource.c:reserve_setup
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff8108ddd0-ffffffff8108de10: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ae00)
Location: kernel/resource.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - kernel/resource.c:reserve_setup
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff8108ae00-ffffffff8108ae40: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091ae0)
Location: kernel/resource.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - kernel/resource.c:reserve_setup
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff81091ae0-ffffffff81091b20: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff826f3506)
Location: kernel/resource.c:295
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff810963f0-ffffffff8109640b: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff828aa2ee)
Location: kernel/resource.c:295
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff8109e760-ffffffff8109e77b: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff828c2ad6)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/eisa/eisa-bus.c:eisa_root_register
```
**Symbols:**

```
ffffffff810a2dd0-ffffffff810a2deb: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff828cb0df)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810a9410-ffffffff810a942b: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff82ced532)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe_mmaps
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810b0e10-ffffffff810b0e9e: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff82fd9b8c)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe_mmaps
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810ac570-ffffffff810ac5fe: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff831e444c)
Location: kernel/resource.c:295
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810ad780-ffffffff810ad80b: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff832c80de)
Location: kernel/resource.c:295
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810bf300-ffffffff810bf38b: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8347b14d)
Location: kernel/resource.c:282
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810d6670-ffffffff810d6715: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff83ea5e9a)
Location: kernel/resource.c:282
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810f5c10-ffffffff810f5cb5: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff836ca56a)
Location: kernel/resource.c:282
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff81102060-ffffffff81102110: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff838fb21a)
Location: kernel/resource.c:282
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/eisa/eisa-bus.c:eisa_request_resources
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff8110b7f0-ffffffff8110b8a0: request_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800011442720)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/setup.c:setup_arch
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffff800010101140-ffff800010101180: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c151c71c)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - drivers/memory/omap-gpmc.c:gpmc_cs_insert_mem
```
**Symbols:**

```
c035d7bc-c035d7e4: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000001366448)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources
  - arch/powerpc/mm/mem.c:add_system_ram_resources
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
c000000000148860-c0000000001488a8: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe000004c28)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
**Symbols:**

```
ffffffe0000c8518-ffffffe0000c8550: request_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff828b3ed2)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810a2d30-ffffffff810a2d4b: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff828ac053)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff81091710-ffffffff8109172b: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff828c6dd1)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810a2ce0-ffffffff810a2cfb: request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int request_resource(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff828cc11c)
Location: kernel/resource.c:296
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
Direct callers:
  - arch/x86/kernel/setup.c:reserve_standard_io_resources
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/paravirt.c:paravirt_disable_iospace
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/eisa/eisa-bus.c:eisa_root_register
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffffffff810aad80-ffffffff810aad9b: request_resource (STB_GLOBAL)
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
