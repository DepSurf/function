# Function: <code>__radix_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __radix_tree_insert(struct radix_tree_root *root, long unsigned int index, unsigned int order, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff814355b0)
Location: lib/radix-tree.c:633
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/memremap.c:devm_memremap_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff814355b0-ffffffff8143567f: __radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __radix_tree_insert(struct radix_tree_root *root, long unsigned int index, unsigned int order, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81451c00)
Location: lib/radix-tree.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/memremap.c:devm_memremap_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff81451c00-ffffffff81451e12: __radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __radix_tree_insert(struct radix_tree_root *root, long unsigned int index, unsigned int order, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1ae0)
Location: lib/radix-tree.c:985
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/memremap.c:devm_memremap_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:grab_mapping_entry
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
**Symbols:**

```
ffffffff818f1ae0-ffffffff818f1cea: __radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __radix_tree_insert(struct radix_tree_root *root, long unsigned int index, unsigned int order, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977f90)
Location: lib/radix-tree.c:984
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/memremap.c:devm_memremap_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/hmm.c:hmm_devmem_pages_create
  - fs/dax.c:grab_mapping_entry
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
**Symbols:**

```
ffffffff81977f90-ffffffff8197819a: __radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __radix_tree_insert(struct radix_tree_root *root, long unsigned int index, unsigned int order, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d46d0)
Location: lib/radix-tree.c:985
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/memremap.c:devm_memremap_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/hmm.c:hmm_devmem_pages_create
  - fs/dax.c:grab_mapping_entry
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff819d46d0-ffffffff819d48ef: __radix_tree_insert (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
