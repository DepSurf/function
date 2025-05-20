# Function: <code>pci_get_domain_bus_and_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143ac80)
Location: drivers/pci/search.c:220
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8143ac80-ffffffff8143ad26: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81486ba0)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81486ba0-ffffffff81486c41: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a8350)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff814a8350-ffffffff814a83f1: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b22e0)
Location: drivers/pci/search.c:228
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff814b22e0-ffffffff814b237d: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f19d0)
Location: drivers/pci/search.c:228
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff814f19d0-ffffffff814f1a6d: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521c60)
Location: drivers/pci/search.c:229
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81521c60-ffffffff81521cfd: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537a90)
Location: drivers/pci/search.c:229
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81537a90-ffffffff81537b2d: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81567430)
Location: drivers/pci/search.c:225
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81567430-ffffffff815674cf: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81588780)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81588780-ffffffff8158881f: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f430)
Location: drivers/pci/search.c:230
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
```
**Symbols:**

```
ffffffff8162f430-ffffffff8162f4cf: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81654ac0)
Location: drivers/pci/search.c:230
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_hw_error
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
```
**Symbols:**

```
ffffffff81654ac0-ffffffff81654b5f: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81637450)
Location: drivers/pci/search.c:228
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/edd.c:edd_device_register
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81637450-ffffffff81637545: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a76c0)
Location: drivers/pci/search.c:228
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/edd.c:edd_device_register
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff816a76c0-ffffffff816a77bd: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817ca0f0)
Location: drivers/pci/search.c:228
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/edd.c:edd_device_register
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff817ca0f0-ffffffff817ca204: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e7ba0)
Location: drivers/pci/search.c:228
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818e7ba0-ffffffff818e7cb4: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192b1c0)
Location: drivers/pci/search.c:228
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/firmware/edd.c:edd_init
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8192b1c0-ffffffff8192b2c3: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81973a40)
Location: drivers/pci/search.c:228
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81973a40-ffffffff81973b43: pci_get_domain_bus_and_slot (STB_GLOBAL)
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
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106ecd10)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
```
**Symbols:**

```
ffff8000106ecd10-ffff8000106ecdc0: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0887f88)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
```
**Symbols:**

```
c0887f88-c0888048: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c000000000868bb0)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/eeh.c:eeh_dev_check_write
  - arch/powerpc/kernel/pci_dn.c:pci_remove_device_node_info
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
```
**Symbols:**

```
c000000000868bb0-c000000000868cbc: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c1b98)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
```
**Symbols:**

```
ffffffe0004c1b98-ffffffe0004c1c06: pci_get_domain_bus_and_slot (STB_GLOBAL)
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
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c610)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8157c610-ffffffff8157c6af: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b3e0)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8156b3e0-ffffffff8156b47f: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c4d0)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8157c4d0-ffffffff8157c56f: pci_get_domain_bus_and_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_dev *pci_get_domain_bus_and_slot(int domain, unsigned int bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81596980)
Location: drivers/pci/search.c:224
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/firmware/edd.c:edd_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81596980-ffffffff81596a1f: pci_get_domain_bus_and_slot (STB_GLOBAL)
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
