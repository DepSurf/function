# Function: <code>bitmap_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9110)
Location: lib/bitmap.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_balance_workfn
  - mm/cma.c:cma_clear_bitmap
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_get_empty_slot
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
**Symbols:**

```
ffffffff813f9110-ffffffff813f9185: bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8143fff0)
Location: lib/bitmap.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_balance_workfn
  - mm/cma.c:cma_clear_bitmap
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_get_empty_slot
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff8143fff0-ffffffff81440068: bitmap_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_clear(long unsigned int *map, unsigned int start, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d0f0)
Location: lib/bitmap.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/percpu.c:pcpu_balance_workfn
  - mm/cma.c:cma_clear_bitmap
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_get_empty_slot
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff8145d0f0-ffffffff8145d168: bitmap_clear (STB_GLOBAL)
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
In arch/x86/kernel/ioport.c (ffffffff8102e846)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810694ab)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106a2dd)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff818fed0c)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In mm/percpu.c (ffffffff811e457a)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/cma.c (ffffffff8124a5e6)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In lib/iommu-common.c (ffffffff8148322e)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_range_free
```
```
In drivers/pwm/core.c (ffffffff814a2593)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81600e3a)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff8160ae28)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cf578)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
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
In arch/x86/kernel/ioport.c (ffffffff810306e6)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106dd5b)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ebed)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff810ed557)
Location: include/linux/bitmap.h:347
Inline: True
```
```
In mm/percpu.c (ffffffff811f9a93)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff8126a7e6)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In lib/iommu-common.c (ffffffff814bf26e)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_range_free
```
```
In drivers/pwm/core.c (ffffffff814e12e3)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816691aa)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff816736f8)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173bbc8)
Location: include/linux/bitmap.h:347
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
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
In arch/x86/kernel/ioport.c (ffffffff810319ee)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81070c6a)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81071aca)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff810f5925)
Location: include/linux/bitmap.h:378
Inline: True
```
```
In mm/percpu.c (ffffffff8121bc98)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff8128f1d6)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/pwm/core.c (ffffffff81510ad3)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816a4b38)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff816b1548)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c438)
Location: include/linux/bitmap.h:378
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
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
In arch/x86/kernel/ioport.c (ffffffff81032cfe)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059dd0)
Location: include/linux/bitmap.h:379
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81076c5d)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81077ae7)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff811010b5)
Location: include/linux/bitmap.h:379
Inline: True
```
```
In mm/percpu.c (ffffffff8122ec78)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff812a40d6)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/pwm/core.c (ffffffff81526183)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c5678)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff816d1888)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2998)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In lib/xarray.c (ffffffff81a187c1)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/kernel/ioport.c (ffffffff81034b0e)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b3df)
Location: include/linux/bitmap.h:379
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a7fd)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b647)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff811098b5)
Location: include/linux/bitmap.h:379
Inline: True
```
```
In mm/percpu.c (ffffffff8123e250)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff812bf4c6)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/pwm/core.c (ffffffff815550a0)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/hmat/hmat.c (ffffffff828f4190)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81700788)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff8170d30a)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e1a9b)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (ffffffff819fedba)
Location: include/linux/bitmap.h:379
Inline: True
```
```
In lib/xarray.c (ffffffff81a883cc)
Location: include/linux/bitmap.h:379
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/kernel/ioport.c (ffffffff8103535e)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bcef)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b8ed)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107c737)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff81115c85)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffffffff8124c6a3)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff812d1416)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/pwm/core.c (ffffffff81576710)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/hmat/hmat.c (ffffffff8163aea7)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81724ad8)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff8173160a)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8181296b)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (ffffffff81a359ba)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (ffffffff81abf66c)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/kernel/ioport.c (ffffffff810372b1)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810619ef)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81082bed)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In kernel/irq/irqdesc.c (ffffffff81121785)
Location: include/linux/bitmap.h:419
Inline: True
```
```
In mm/percpu.c (ffffffff8127a8e4)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/bitmap.c (ffffffff81584c59)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse
```
```
In lib/xarray.c (ffffffff815fbb38)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/pwm/core.c (ffffffff8161b162)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - drivers/pwm/core.c:free_pwms
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e7e49)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817e0de8)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff817edf0a)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f7ba)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e39b7)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ethtool/bitset.c (ffffffff81a879ca)
Location: include/linux/bitmap.h:419
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a9a9)
Location: include/linux/bitmap.h:419
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
In arch/x86/kernel/ioport.c (ffffffff81038371)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fdfa)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8108465d)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In kernel/irq/irqdesc.c (ffffffff8111d8b5)
Location: include/linux/bitmap.h:417
Inline: True
```
```
In mm/percpu.c (ffffffff81285076)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/bitmap.c (ffffffff815a1d59)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse
```
```
In lib/xarray.c (ffffffff816206c8)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/pwm/core.c (ffffffff816418e6)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/pwm/core.c:free_pwms
```
```
In drivers/acpi/numa/hmat.c (ffffffff817055b7)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817f5b38)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff8180283a)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae81a)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ece97)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ethtool/bitset.c (ffffffff81a91351)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv6/af_inet6.c (ffffffff81b39339)
Location: include/linux/bitmap.h:417
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
In arch/x86/kernel/ioport.c (ffffffff81039eb1)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060391)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810853c3)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In kernel/irq/irqdesc.c (ffffffff8111da75)
Location: include/linux/bitmap.h:417
Inline: True
```
```
In mm/percpu.c (ffffffff8128afe9)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/bitmap.c (ffffffff815a8b69)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse
```
```
In lib/xarray.c (ffffffff81603d09)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/pwm/core.c (ffffffff8162489c)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e6c52)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817da2e8)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff817e8ada)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892b36)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d0697)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ethtool/bitset.c (ffffffff81a7ab53)
Location: include/linux/bitmap.h:417
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv6/af_inet6.c (ffffffff81b26f1a)
Location: include/linux/bitmap.h:417
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
In arch/x86/kernel/ioport.c (ffffffff8103f861)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069543)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81094333)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In kernel/irq/irqdesc.c (ffffffff8113de85)
Location: include/linux/bitmap.h:423
Inline: True
```
```
In mm/percpu.c (ffffffff812c8ecb)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/bitmap.c (ffffffff81611e09)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse
```
```
In lib/xarray.c (ffffffff8166fee5)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
```
```
In drivers/pwm/core.c (ffffffff81693e19)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/numa/hmat.c (ffffffff8176022b)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81865b28)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff81874f8a)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81925585)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196af17)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ethtool/bitset.c (ffffffff81b34f71)
Location: include/linux/bitmap.h:423
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv6/af_inet6.c (ffffffff81bec97c)
Location: include/linux/bitmap.h:423
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
In arch/x86/kernel/ioport.c (ffffffff81046f96)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81076712)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6523)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In kernel/irq/irqdesc.c (ffffffff81161465)
Location: include/linux/bitmap.h:443
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126e98f)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
```
```
In mm/percpu.c (ffffffff81326b7b)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/bitmap.c (ffffffff816de099)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse
```
```
In lib/xarray.c (ffffffff8178cae8)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/pwm/core.c (ffffffff817b47f9)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/numa/hmat.c (ffffffff81893c28)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/xen/grant-table.c (ffffffff818c874c)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff819adfdb)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff819b9d68)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7e3d5)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac5268)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ethtool/bitset.c (ffffffff81cc0781)
Location: include/linux/bitmap.h:443
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv6/af_inet6.c (ffffffff81d84e33)
Location: include/linux/bitmap.h:443
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
In arch/x86/kernel/ioport.c (ffffffff810510f6)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810862d2)
Location: include/linux/bitmap.h:469
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810bf43f)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:free_iommu
```
```
In kernel/irq/irqdesc.c (ffffffff811949c5)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_free_descs
```
```
In kernel/bpf/core.c (ffffffff812c414c)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
```
```
In mm/vmscan.c (ffffffff8137db92)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - mm/vmscan.c:iterate_mm_list
```
```
In mm/percpu.c (ffffffff8139b81b)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In lib/bitmap.c (ffffffff817ce075)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff818be026)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
```
```
In drivers/pwm/core.c (ffffffff818ceb89)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/numa/hmat.c (ffffffff819db7ba)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/xen/grant-table.c (ffffffff81a1917c)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b21a3b)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2f228)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c4f2e8)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ethtool/bitset.c (ffffffff81e7f3da)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv6/af_inet6.c (ffffffff81f529cf)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In lib/xarray.c (ffffffff82047721)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
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
In arch/x86/kernel/ioport.c (ffffffff81051e3d)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088f02)
Location: include/linux/bitmap.h:467
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c2aff)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:free_iommu
```
```
In kernel/bpf/core.c (ffffffff812eb0fc)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
```
```
In mm/vmscan.c (ffffffff813b3bc1)
Location: include/linux/bitmap.h:467
Inline: True
```
```
In mm/percpu.c (ffffffff813ce7fb)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/vmalloc.c (ffffffff814164d9)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - mm/vmalloc.c:vb_free
```
```
In lib/bitmap.c (ffffffff8180c520)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff81900b93)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
```
```
In drivers/pwm/core.c (ffffffff81911bd6)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a23469)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/xen/grant-table.c (ffffffff81a621fc)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b70ccb)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82678)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb6888)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In drivers/firmware/efi/unaccepted_memory.c (ffffffff81dd4698)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
```
In net/ethtool/bitset.c (ffffffff81edb9ca)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv6/af_inet6.c (ffffffff81fb23d1)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In lib/xarray.c (ffffffff820c5dbf)
Location: include/linux/bitmap.h:467
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
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
In arch/x86/kernel/ioport.c (ffffffff8105905d)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108fd82)
Location: include/linux/bitmap.h:444
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810caf3f)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:free_iommu
```
```
In kernel/bpf/core.c (ffffffff8130961f)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
```
```
In mm/vmscan.c (ffffffff813dd221)
Location: include/linux/bitmap.h:444
Inline: True
```
```
In mm/percpu.c (ffffffff813f935b)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/vmalloc.c (ffffffff81442fa9)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - mm/vmalloc.c:vb_free
```
```
In fs/iomap/buffered-io.c (ffffffff8158af0c)
Location: include/linux/bitmap.h:444
Inline: True
```
```
In lib/bitmap-str.c (ffffffff818616c0)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - lib/bitmap-str.c:bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff819483c3)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819b1c00)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4932)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a6e29f)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
```
```
In drivers/xen/grant-table.c (ffffffff81ab4a2c)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6ea07)
Location: include/linux/bitmap.h:444
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81bc49cb)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd6538)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6b5d8)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81df0fd7)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/firmware/efi/unaccepted_memory.c (ffffffff81e8c762)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
```
In net/ethtool/bitset.c (ffffffff81f9f791)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv6/af_inet6.c (ffffffff8207fb61)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In lib/xarray.c (ffffffff821a073f)
Location: include/linux/bitmap.h:444
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
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
In arch/arm64/mm/context.c (ffff8000100afef0)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In kernel/irq/irqdesc.c (ffff800010177424)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffff8000102e2d44)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffff800010376b70)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b44c)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/gpio/gpiolib-of.c (ffff8000106c86f0)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
```
In drivers/pwm/core.c (ffff8000106d7a68)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/pci/controller/pci-aardvark.c (ffff80001071fa8c)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_free
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff8000107254b4)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_free
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff800010725d90)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_free
```
```
In drivers/acpi/hmat/hmat.c (ffff8000107a6124)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffff800010919734)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffff800010928bfc)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4b988)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (ffff800010cf5cb8)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (ffff800010d9a874)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/arm/mm/dma-mapping.c (c031cccc)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_remove_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
```
```
In arch/arm/mm/context.c (c0322640)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In kernel/irq/irqdesc.c (c03c9340)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (c0506ff4)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (c0562994)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/irqchip/irq-alpine-msi.c (c0813118)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_free_sgi
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081ea20)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_free
```
```
In drivers/gpio/gpiolib-of.c (c0865d24)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
```
In drivers/pwm/core.c (c08749c4)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/base/regmap/regcache-rbtree.c (c09ff3bc)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/mtd/nand/raw/nand_macronix.c (c0aa7ad0)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1dc38)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (c0dfc7f0)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (c0e976a0)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/powerpc/kernel/iommu.c (c00000000005195c)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:__iommu_free
```
```
In arch/powerpc/sysdev/msi_bitmap.c (c0000000000b7a60)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_free_hwirqs
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d94f0)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
```
```
In kernel/irq/irqdesc.c (c0000000001d0fac)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (c0000000003a3894)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (c0000000004690fc)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/gpio/gpiolib-of.c (c000000000845f68)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
```
In drivers/pwm/core.c (c00000000084e9a8)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/base/regmap/regcache-rbtree.c (c0000000009bd360)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b127f0)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (c000000000e1c998)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (c000000000ee0f8c)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In kernel/irq/irqdesc.c (ffffffe000112462)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffffffe0001f9ee4)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffe00024eed4)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/gpio/gpiolib-of.c (ffffffe0004abee8)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
```
In drivers/pwm/core.c (ffffffe0004b1244)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffe000599884)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe0006688e0)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (ffffffe000841c1c)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (ffffffe0008c2df0)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/kernel/ioport.c (ffffffff810354be)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b86f)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a8ed)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b737)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff8110e265)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffffffff81244cf3)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff812c99f6)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/pwm/core.c (ffffffff8156b520)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/hmat/hmat.c (ffffffff81608207)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816eae08)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff816f757a)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cad4b)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (ffffffff819d504a)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (ffffffff81a5e4bc)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/kernel/ioport.c (ffffffff81024dfe)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104ba3f)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a01d)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ae67)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff810fefc5)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffffffff812379fd)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff812baa36)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/acpi/hmat/hmat.c (ffffffff815fa357)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c5448)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In net/ipv6/af_inet6.c (ffffffff81991e0a)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (ffffffff81a1b58c)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/kernel/ioport.c (ffffffff8103531e)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bc9f)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a89d)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b6e7)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff8110c155)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffffffff81242a93)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff812c7806)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/pwm/core.c (ffffffff8156a460)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81717f98)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff81724aca)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818077eb)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (ffffffff81a3faca)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (ffffffff81aca8ac)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/kernel/ioport.c (ffffffff81036279)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d18f)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c99d)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107d7e7)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_free
```
```
In kernel/irq/irqdesc.c (ffffffff81117885)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In mm/percpu.c (ffffffff81251f7a)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/cma.c (ffffffff812d84f6)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - mm/cma.c:cma_clear_bitmap
```
```
In drivers/pwm/core.c (ffffffff81584960)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/hmat/hmat.c (ffffffff81649027)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817332f8)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
```
```
In drivers/block/xen-blkfront.c (ffffffff8173d0ea)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818218fb)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:pmap_unschedule
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b60a)
Location: include/linux/bitmap.h:403
Inline: True
```
```
In lib/xarray.c (ffffffff81ad6e7c)
Location: include/linux/bitmap.h:403
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
