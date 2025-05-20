# Function: <code>__bitmap_clear</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462380)
Location: lib/bitmap.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_balance_workfn
  - mm/cma.c:cma_clear_bitmap
  - lib/iommu-common.c:iommu_tbl_range_free
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
**Symbols:**

```
ffffffff81462380-ffffffff814623f8: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e260)
Location: lib/bitmap.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - lib/iommu-common.c:iommu_tbl_range_free
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
**Symbols:**

```
ffffffff8148e260-ffffffff8148e2d8: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c2f70)
Location: lib/bitmap.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
**Symbols:**

```
ffffffff814c2f70-ffffffff814c2fe6: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7620)
Location: lib/bitmap.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff814d7620-ffffffff814d7696: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503470)
Location: lib/bitmap.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81503470-ffffffff815034df: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521410)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81521410-ffffffff8152147f: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584640)
Location: lib/bitmap.c:370
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - lib/bitmap.c:bitmap_parse
  - lib/xarray.c:xas_store
  - drivers/pwm/core.c:free_pwms
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff81584640-ffffffff815846b8: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1750)
Location: lib/bitmap.c:370
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - lib/bitmap.c:bitmap_parse
  - lib/xarray.c:xas_store
  - drivers/pwm/core.c:free_pwms
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff815a1750-ffffffff815a17c8: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8600)
Location: lib/bitmap.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - lib/bitmap.c:bitmap_parse
  - lib/xarray.c:xas_store
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff815a8600-ffffffff815a8678: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816115c0)
Location: lib/bitmap.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - lib/bitmap.c:bitmap_parse
  - lib/xarray.c:xas_squash_marks
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff816115c0-ffffffff81611638: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd700)
Location: lib/bitmap.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - kernel/bpf/core.c:bpf_prog_pack_free
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - lib/bitmap.c:bitmap_parse
  - lib/xarray.c:xas_store
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff816dd700-ffffffff816dd78c: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd620)
Location: lib/bitmap.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:free_iommu
  - kernel/irq/irqdesc.c:irq_free_descs
  - kernel/bpf/core.c:bpf_prog_pack_free
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - lib/bitmap.c:bitmap_parse
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - lib/xarray.c:xas_squash_marks
```
**Symbols:**

```
ffffffff817cd620-ffffffff817cd6ac: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180ba30)
Location: lib/bitmap.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:free_iommu
  - kernel/bpf/core.c:bpf_prog_pack_free
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vb_free
  - lib/bitmap.c:bitmap_parse
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - lib/xarray.c:xas_squash_marks
```
**Symbols:**

```
ffffffff8180ba30-ffffffff8180babc: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81852210)
Location: lib/bitmap.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:free_iommu
  - kernel/bpf/core.c:bpf_prog_pack_free
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vb_free
  - lib/bitmap-str.c:bitmap_parse
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - lib/xarray.c:xas_squash_marks
```
**Symbols:**

```
ffffffff81852210-ffffffff8185229c: __bitmap_clear (STB_GLOBAL)
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
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062aaf8)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - arch/arm64/mm/context.c:check_and_switch_context
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_free
  - drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_free
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_free
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffff80001062aaf8-ffff80001062ab78: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1d14)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_remove_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_free_sgi
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_free
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
c07d1d14-c07d1da8: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007ccc40)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:__iommu_free
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_free_hwirqs
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
c0000000007ccc40-c0000000007cccf0: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b426)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffe00045b426-ffffffe00045b4a0: __bitmap_clear (STB_GLOBAL)
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
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815199f0)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff815199f0-ffffffff81519a5f: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509ce0)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81509ce0-ffffffff81509d4f: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515a80)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81515a80-ffffffff81515aef: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f210)
Location: lib/bitmap.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_clear_bitmap
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff8152f210-ffffffff8152f27f: __bitmap_clear (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
