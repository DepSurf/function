# Function: <code>_find_first_zero_bit</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815b3d40)
Location: lib/find_bit.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - lib/idr.c:ida_alloc_range
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/dev.c:__dev_alloc_name
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
**Symbols:**

```
ffffffff815b3d40-ffffffff815b3d76: _find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81619f30)
Location: lib/find_bit.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - lib/idr.c:ida_alloc_range
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/dev.c:__dev_alloc_name
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
**Symbols:**

```
ffffffff81619f30-ffffffff81619f66: _find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff816e7470)
Location: lib/find_bit.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/idr.c:ida_alloc_range
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/scsi/sr.c:sr_probe
  - net/core/dev.c:__dev_alloc_name
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
**Symbols:**

```
ffffffff816e7470-ffffffff816e74be: _find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff817d6d30)
Location: lib/find_bit.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd/iommu.c:domain_id_alloc
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/dev.c:__dev_alloc_name
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff817d6d30-ffffffff817d6d7b: _find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81815d40)
Location: lib/find_bit.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/trace/trace.c:close_pipe_on_cpu
  - kernel/bpf/cpumask.c:bpf_cpumask_full
  - kernel/bpf/cpumask.c:bpf_cpumask_first_zero
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd/iommu.c:domain_id_alloc
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/dev.c:__dev_alloc_name
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff81815d40-ffffffff81815d8b: _find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8185ae80)
Location: lib/find_bit.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/trace/trace.c:close_pipe_on_cpu
  - kernel/bpf/cpumask.c:bpf_cpumask_full
  - kernel/bpf/cpumask.c:bpf_cpumask_first_zero
  - fs/iomap/buffered-io.c:ifs_free
  - fs/iomap/buffered-io.c:ifs_set_range_uptodate
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/acpi/numa/srat.c:acpi_map_pxm_to_node
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/dev.c:__dev_alloc_name
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff8185ae80-ffffffff8185aecb: _find_first_zero_bit (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
