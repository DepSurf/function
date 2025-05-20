# Function: <code>bitmap_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f90a0)
Location: lib/bitmap.c:252
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_balance_workfn
  - mm/cma.c:cma_alloc
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff813f90a0-ffffffff813f910f: bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8143ff70)
Location: lib/bitmap.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/cma.c:cma_alloc
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8143ff70-ffffffff8143ffe2: bitmap_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_set(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d070)
Location: lib/bitmap.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/cma.c:cma_alloc
  - lib/iommu-helper.c:iommu_area_alloc
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
**Symbols:**

```
ffffffff8145d070-ffffffff8145d0e2: bitmap_set (STB_GLOBAL)
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
In arch/x86/kernel/ioport.c (ffffffff8102e861)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff820ba118)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ae3e)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff8108e38c)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff818feb2e)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In mm/percpu.c (ffffffff811e2b47)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
```
```
In mm/cma.c (ffffffff8124a7f6)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff813fa7a6)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/iommu-helper.c (ffffffff81482d4e)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff814a31e3)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5dc5)
Location: include/linux/bitmap.h:315
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8160cb18)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cf76f)
Location: include/linux/bitmap.h:315
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In arch/x86/kernel/ioport.c (ffffffff81030701)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826c0ac7)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106f73e)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff810951e7)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81988ef5)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff810f8faf)
Location: include/linux/bitmap.h:333
Inline: True
```
```
In mm/percpu.c (ffffffff811f81dc)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff8126a9f6)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff81422c46)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff8148eaa9)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff814bed8e)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff814e1f56)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163cb75)
Location: include/linux/bitmap.h:333
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff816753f6)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173bdbf)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In arch/x86/kernel/ioport.c (ffffffff81031977)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826eacdb)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107260c)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff81098b87)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff819e5859)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8110150f)
Location: include/linux/bitmap.h:364
Inline: True
```
```
In mm/percpu.c (ffffffff8121948c)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff8128f3f7)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff81455216)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff814c389a)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff814eff8b)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pwm/core.c (ffffffff81511766)
Location: include/linux/bitmap.h:364
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677fb6)
Location: include/linux/bitmap.h:364
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff816b2695)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c607)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In arch/x86/kernel/ioport.c (ffffffff81032c87)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81078664)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff810a0f0b)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81a20a31)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8110ce29)
Location: include/linux/bitmap.h:365
Inline: True
```
```
In mm/percpu.c (ffffffff8122c3ec)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff812a430c)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814725f6)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff814d7cca)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff81503eab)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8151fca0)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff81526e14)
Location: include/linux/bitmap.h:365
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81697096)
Location: include/linux/bitmap.h:365
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff816d1d75)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2b67)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
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
In arch/x86/kernel/ioport.c (ffffffff81034a97)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107c1d0)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff810a577e)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81a90f75)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8111650e)
Location: include/linux/bitmap.h:365
Inline: True
```
```
In mm/percpu.c (ffffffff8123c180)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff8128d9f5)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In mm/cma.c (ffffffff812bf70f)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814a02f6)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff81503c3d)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff81532021)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8154dde4)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff81555d65)
Location: include/linux/bitmap.h:365
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfa0f)
Location: include/linux/bitmap.h:365
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8170d584)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e1c92)
Location: include/linux/bitmap.h:365
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff819feda7)
Location: include/linux/bitmap.h:365
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
In arch/x86/kernel/ioport.c (ffffffff810352e7)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107d2c0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff810abd5e)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81ac82b5)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff811228de)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In mm/percpu.c (ffffffff8124a5d0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff8129d645)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In mm/cma.c (ffffffff812d165f)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814ba959)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff81521bdd)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff81552e61)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8156efe4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff815773a5)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/pci/pci.c (ffffffff815858e2)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f384f)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81731884)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812b62)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81a359a7)
Location: include/linux/bitmap.h:389
Inline: True
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
In arch/x86/kernel/ioport.c (ffffffff81037258)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/sysctl.c (ffffffff810b2631)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81121b19)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8112ef2e)
Location: include/linux/bitmap.h:405
Inline: True
```
```
In mm/percpu.c (ffffffff81278830)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff812d1275)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In security/integrity/ima/ima_template.c (ffffffff8151aef9)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff815851e8)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff815dc247)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff816134a4)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff8161baf8)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/pci/pci.c (ffffffff8162c510)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aafe1)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (ffffffff817ee2d8)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a03da)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e3f01)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a996)
Location: include/linux/bitmap.h:405
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In arch/x86/kernel/ioport.c (ffffffff81038318)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/sysctl.c (ffffffff810ade61)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff8111db79)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8112af0e)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffffffff812830a0)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff812dcd95)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In fs/file.c (ffffffff813452fe)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/iomap/buffered-io.c (ffffffff813bc47a)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In security/integrity/ima/ima_template.c (ffffffff81537e99)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff815a22e8)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff815f9ee7)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8163837b)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff816421eb)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/pci/pci.c (ffffffff81652270)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7441)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (ffffffff81802bd8)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818aedc2)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_populate_bitmap_full
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ed3e1)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81b39326)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In arch/x86/kernel/ioport.c (ffffffff81039e58)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/sysctl.c (ffffffff810af0da)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff811032fd)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/irq/irqdesc.c (ffffffff8111de89)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8112b1ac)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffffffff81289270)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff812e4605)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In fs/file.c (ffffffff8134b603)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/iomap/buffered-io.c (ffffffff813c31ca)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In security/integrity/ima/ima_template.c (ffffffff81540500)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff815a9098)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff815dcac7)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8161bebe)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff8162511b)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/pci.c (ffffffff81634d20)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b029)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff817e8f42)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818914c4)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d0bb1)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81b26f07)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In arch/x86/kernel/ioport.c (ffffffff8103f808)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/sysctl.c (ffffffff810c1868)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff81120698)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/irq/irqdesc.c (ffffffff8113e2d5)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8114bb8c)
Location: include/linux/bitmap.h:409
Inline: True
```
```
In mm/percpu.c (ffffffff812c8e60)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff8132b915)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In fs/file.c (ffffffff81399453)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/iomap/buffered-io.c (ffffffff81412b47)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In security/integrity/ima/ima_template.c (ffffffff8159fd3f)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff816123b6)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff81648427)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8168b3e7)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff8169492b)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/pci.c (ffffffff816a4e10)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823b59)
Location: include/linux/bitmap.h:409
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff818752e2)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81924f41)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196b0c1)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81bec969)
Location: include/linux/bitmap.h:409
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In arch/x86/kernel/ioport.c (ffffffff81046f34)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/sysctl.c (ffffffff810d9028)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/build_utility.c (ffffffff8114a2e6)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
```
```
In kernel/irq/irqdesc.c (ffffffff811618a5)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8117152b)
Location: include/linux/bitmap.h:429
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126c295)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In mm/percpu.c (ffffffff81326b00)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff8139b535)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In fs/file.c (ffffffff8141bdb1)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/iomap/buffered-io.c (ffffffff81488fb5)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In security/integrity/ima/ima_template.c (ffffffff8164593a)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff816de623)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff8175e813)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff817a8748)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff817b5486)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/pci.c (ffffffff817c72e4)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/xen/grant-table.c (ffffffff818c73f1)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_set_free
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962fd4)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba1cd)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7ab5e)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac5421)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81d84e20)
Location: include/linux/bitmap.h:429
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In arch/x86/kernel/ioport.c (ffffffff81051094)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/sysctl.c (ffffffff810f7e98)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/build_utility.c (ffffffff81178c9e)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
```
```
In kernel/irq/irqdesc.c (ffffffff81194f55)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff811a7b4b)
Location: include/linux/bitmap.h:453
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c2939)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In mm/percpu.c (ffffffff8139b790)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff8141b565)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In fs/file.c (ffffffff814a7f31)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/iomap/buffered-io.c (ffffffff8151cc25)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In security/integrity/ima/ima_template.c (ffffffff816fde42)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff817ce92c)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff8188c033)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff818c116a)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff818cf70f)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/pci.c (ffffffff818e480e)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/xen/grant-table.c (ffffffff81a17f21)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_set_free
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbc41)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2f6c5)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c4f4b1)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81f529bc)
Location: include/linux/bitmap.h:453
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In arch/x86/kernel/ioport.c (ffffffff81051dc4)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/sysctl.c (ffffffff81104285)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/build_utility.c (ffffffff8118988e)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
```
```
In kernel/irq/matrix.c (ffffffff811b982b)
Location: include/linux/bitmap.h:451
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812e9829)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In mm/percpu.c (ffffffff813ce770)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/vmalloc.c (ffffffff81414ee3)
Location: include/linux/bitmap.h:451
Inline: True
```
```
In mm/sparse.c (ffffffff8144eb05)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In fs/file.c (ffffffff814dcf11)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/iomap/buffered-io.c (ffffffff81554e05)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In security/integrity/ima/ima_template.c (ffffffff81737e62)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff8180ccf5)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff818ce4a3)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff81904117)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff819126cf)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add
```
```
In drivers/pci/pci.c (ffffffff81927e54)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/xen/grant-table.c (ffffffff81a60fb1)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_set_free
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b187bf)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82b38)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb6a51)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81fb23be)
Location: include/linux/bitmap.h:451
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In arch/x86/kernel/ioport.c (ffffffff81058fe4)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In kernel/sysctl.c (ffffffff8110dbd5)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/build_utility.c (ffffffff8119818e)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
```
```
In kernel/irq/matrix.c (ffffffff811c96eb)
Location: include/linux/bitmap.h:428
Inline: True
```
```
In kernel/bpf/core.c (ffffffff81307e89)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In mm/percpu.c (ffffffff813f92d0)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/vmalloc.c (ffffffff814419b2)
Location: include/linux/bitmap.h:428
Inline: True
```
```
In mm/sparse.c (ffffffff814886a5)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In fs/file.c (ffffffff8150f85f)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158b609)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_alloc
  - fs/iomap/buffered-io.c:ifs_alloc
  - fs/iomap/buffered-io.c:ifs_set_range_dirty
  - fs/iomap/buffered-io.c:ifs_set_range_uptodate
```
```
In security/integrity/ima/ima_template.c (ffffffff81778952)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap-str.c (ffffffff81861945)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - lib/bitmap-str.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff81920253)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8194bb49)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pci/pci.c (ffffffff819705f4)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819b17ce)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4808)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/xen/grant-table.c (ffffffff81ab37e1)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_set_free
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e0ff)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
```
In drivers/iommu/iommufd/iova_bitmap.c (ffffffff81b71ba8)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_set
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd6a28)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c93991)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6b7a1)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In drivers/ptp/ptp_clock.c (ffffffff81df003c)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81df0a49)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_open
```
```
In net/ipv6/af_inet6.c (ffffffff8207fb4e)
Location: include/linux/bitmap.h:428
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In kernel/sysctl.c (ffff800010104440)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffff800010d9c140)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In mm/percpu.c (ffff8000102e0344)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffff80001033c70c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In mm/cma.c (ffff800010377044)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffff8000105b2e58)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffff80001062b43c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067afa4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/gpio/gpiolib.c (ffff8000106c4ee4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffff8000106d8094)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/pci/pci.c (ffff8000106ea24c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/pci/controller/pci-aardvark.c (ffff80001071fb24)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_alloc
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff8000107255d0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_alloc
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff800010725ecc)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_alloc
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081c968)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
```
```
In drivers/block/xen-blkfront.c (ffff8000109290b8)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4bba0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffff800010cf5c9c)
Location: include/linux/bitmap.h:389
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
In arch/arm/mm/dma-mapping.c (c031def4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
```
```
In kernel/sysctl.c (c03605fc)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (c0e987a0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In mm/percpu.c (c0504b34)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (c0562c3c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (c0762424)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (c07d26dc)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/irqchip/irq-alpine-msi.c (c081320c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081ea9c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_alloc
```
```
In drivers/gpio/gpiolib.c (c08632d4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (c0875990)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/pci/pci.c (c08851ec)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/dma/ti/edma.c (c092ec7c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
```
```
In drivers/mtd/nand/raw/nand_onfi.c (c0aa66f8)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect
  - drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect
```
```
In drivers/mtd/nand/raw/nand_macronix.c (c0aa7ab0)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1de34)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (c0dfc7f0)
Location: include/linux/bitmap.h:389
Inline: True
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
In arch/powerpc/mm/slice.c (c0000000000a3ef4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/powerpc/mm/slice.c:slice_range_to_mask
```
```
In arch/powerpc/sysdev/msi_bitmap.c (c0000000000b7944)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc_hwirqs
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d92b0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
```
```
In kernel/sysctl.c (c00000000014c74c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (c0000000001d2190)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In mm/percpu.c (c00000000039fb5c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (c0000000004177f8)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In mm/cma.c (c000000000469460)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (c000000000735468)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (c0000000007cd9b4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (c000000000811a90)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (c000000000841a4c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (c000000000850508)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/pci/pci.c (c000000000865508)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b12ad0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (c000000000e1c96c)
Location: include/linux/bitmap.h:389
Inline: True
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
In kernel/sysctl.c (ffffffe0000c9a22)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffe0008c433c)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In mm/percpu.c (ffffffe0001f7d04)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffe00001855e)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
```
```
In mm/cma.c (ffffffe00024f13a)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffe0003fa52e)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffe00045be0a)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a9546)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffe0004b205e)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/pci/pci.c (ffffffe0004c03d6)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668aa6)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffe000841c08)
Location: include/linux/bitmap.h:389
Inline: True
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
In arch/x86/kernel/ioport.c (ffffffff81035447)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107c2c0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff810a567e)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81a67125)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8111aebe)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In mm/percpu.c (ffffffff81242c20)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff81295c25)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In mm/cma.c (ffffffff812c9c3f)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814b2f39)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff8151a1bd)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff8154b441)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff815647a4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff8156c1b5)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81579e02)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b903f)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff816f77f4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817caf42)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff819d5037)
Location: include/linux/bitmap.h:389
Inline: True
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
In arch/x86/kernel/ioport.c (ffffffff81024d87)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b9f0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff8109405e)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81a23be5)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8110bf2e)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In mm/percpu.c (ffffffff81235bf0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff81287835)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In mm/cma.c (ffffffff812bac7f)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814a3959)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff8150a4ad)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff8153b721)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff815555f4)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pci/pci.c (ffffffff81568542)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696c7f)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81991df7)
Location: include/linux/bitmap.h:389
Inline: True
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
In arch/x86/kernel/ioport.c (ffffffff810352a7)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107c270)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff810a562e)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81ad3535)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff81118dae)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In mm/percpu.c (ffffffff812409c0)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff81293a35)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In mm/cma.c (ffffffff812c7a4f)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814aefc9)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff8151624d)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff81547181)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff81563314)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff8156b0f5)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81579632)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e750f)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81724d44)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818079e2)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81a3fab7)
Location: include/linux/bitmap.h:389
Inline: True
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
In arch/x86/kernel/ioport.c (ffffffff810361f2)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107e370)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve
```
```
In kernel/sysctl.c (ffffffff810ad6ee)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/irq/irqdesc.c (ffffffff81adfa35)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/matrix.c (ffffffff8112443e)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In mm/percpu.c (ffffffff81250140)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/sparse.c (ffffffff812a3895)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/sparse.c:subsection_mask_set
```
```
In mm/cma.c (ffffffff812d873f)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
```
```
In security/integrity/ima/ima_template.c (ffffffff814c7a49)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In lib/bitmap.c (ffffffff8152f9dd)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
```
In lib/iommu-helper.c (ffffffff81560fd1)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8157d234)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
```
In drivers/pwm/core.c (ffffffff815855f5)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81593ac2)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_add_dma_alias
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701c0f)
Location: include/linux/bitmap.h:389
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8173fc74)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81821af2)
Location: include/linux/bitmap.h:389
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_schedule
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b5f7)
Location: include/linux/bitmap.h:389
Inline: True
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
</ul>
