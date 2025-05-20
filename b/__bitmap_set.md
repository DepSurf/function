# Function: <code>__bitmap_set</code>

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
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462300)
Location: lib/bitmap.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/cma.c:cma_alloc
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81462300-ffffffff81462372: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e1e0)
Location: lib/bitmap.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:__bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8148e1e0-ffffffff8148e252: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c2f00)
Location: lib/bitmap.c:253
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:__bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff814c2f00-ffffffff814c2f70: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d75b0)
Location: lib/bitmap.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:__bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff814d75b0-ffffffff814d7620: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503400)
Location: lib/bitmap.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81503400-ffffffff81503469: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815213a0)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff815213a0-ffffffff81521409: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815845c0)
Location: lib/bitmap.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff815845c0-ffffffff81584632: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a16d0)
Location: lib/bitmap.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - fs/file.c:__close_range
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_populate_bitmap_full
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff815a16d0-ffffffff815a1742: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8580)
Location: lib/bitmap.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - fs/file.c:__close_range
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pwm/core.c:pwmchip_add
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff815a8580-ffffffff815a85f2: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611540)
Location: lib/bitmap.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - fs/file.c:__close_range
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pwm/core.c:pwmchip_add
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81611540-ffffffff816115b2: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd670)
Location: lib/bitmap.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - fs/file.c:__close_range
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pwm/core.c:pwmchip_add
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/xen/grant-table.c:gnttab_set_free
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff816dd670-ffffffff816dd6f6: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd580)
Location: lib/bitmap.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - fs/file.c:__close_range
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pwm/core.c:pwmchip_add
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/xen/grant-table.c:gnttab_set_free
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff817cd580-ffffffff817cd606: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180b990)
Location: lib/bitmap.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - fs/file.c:__close_range
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pwm/core.c:pwmchip_add
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/xen/grant-table.c:gnttab_set_free
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8180b990-ffffffff8180ba16: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81852170)
Location: lib/bitmap.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - fs/file.c:__close_range
  - fs/iomap/buffered-io.c:ifs_alloc
  - fs/iomap/buffered-io.c:ifs_alloc
  - fs/iomap/buffered-io.c:ifs_set_range_dirty
  - fs/iomap/buffered-io.c:ifs_set_range_uptodate
  - lib/bitmap-str.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/xen/grant-table.c:gnttab_set_free
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_set
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81852170-ffffffff818521f6: __bitmap_set (STB_GLOBAL)
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
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062aa78)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_alloc
  - drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_alloc
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_alloc
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffff80001062aa78-ffff80001062aaf8: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1c80)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
c07d1c80-c07d1d14: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007ccb90)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - arch/powerpc/mm/slice.c:slice_range_to_mask
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc_hwirqs
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
c0000000007ccb90-c0000000007ccc40: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b3b2)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_map_init
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffe00045b3b2-ffffffe00045b426: __bitmap_set (STB_GLOBAL)
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
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519980)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81519980-ffffffff815199e9: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509c70)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
```
**Symbols:**

```
ffffffff81509c70-ffffffff81509cd9: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515a10)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff81515a10-ffffffff81515a79: __bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f1a0)
Location: lib/bitmap.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/sparse.c:subsection_mask_set
  - mm/cma.c:cma_alloc
  - lib/bitmap.c:bitmap_parselist
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8152f1a0-ffffffff8152f209: __bitmap_set (STB_GLOBAL)
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
