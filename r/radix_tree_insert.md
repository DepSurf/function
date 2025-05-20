# Function: <code>radix_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int radix_tree_insert(struct radix_tree_root *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813eee30)
Location: lib/radix-tree.c:448
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - mm/swap_state.c:__add_to_swap_cache
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff813eee30-ffffffff813eef01: radix_tree_insert (STB_GLOBAL)
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
In kernel/irq/irqdesc.c (ffffffff81892bd6)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff810e6c89)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In kernel/memremap.c (ffffffff8119dffa)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/shmem.c (ffffffff811c06bb)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffffffff811c8877)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff811eb61b)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff811f03f2)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8121aca9)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (ffffffff81287e35)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
```
```
In block/blk-ioc.c (ffffffff8140320d)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff8141da51)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pinctrl/core.c (ffffffff8146710f)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_register
```
```
In drivers/pwm/core.c (ffffffff8147820f)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/block/brd.c (ffffffff815c2805)
Location: include/linux/radix-tree.h:270
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b36f5)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
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
In kernel/irq/irqdesc.c (ffffffff818c74be)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff810ed679)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In kernel/memremap.c (ffffffff811ada2d)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/shmem.c (ffffffff811d0c9b)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffffffff811d8999)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff811fc88b)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff81200db8)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8122c499)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In block/blk-ioc.c (ffffffff8141cf3d)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81439011)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pinctrl/core.c (ffffffff814863ff)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_register
```
```
In drivers/pwm/core.c (ffffffff8149956f)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e18a5)
Location: include/linux/radix-tree.h:290
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
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
In kernel/irq/irqdesc.c (ffffffff818fec4f)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff810ed03e)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In kernel/memremap.c (ffffffff811b4d90)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/shmem.c (ffffffff811d922d)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffffffff811e1b80)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81207503)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff8120bb12)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81238d38)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In block/blk-ioc.c (ffffffff8142af9d)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81446835)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pinctrl/core.c (ffffffff8148f4cc)
Location: include/linux/radix-tree.h:294
Inline: True
```
```
In drivers/pwm/core.c (ffffffff814a3177)
Location: include/linux/radix-tree.h:294
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f587c)
Location: include/linux/radix-tree.h:294
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff81988e40)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff810f4ae9)
Location: include/linux/radix-tree.h:293
Inline: True
```
```
In mm/shmem.c (ffffffff811ee50d)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffffffff811f7c19)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff812205f3)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff81225104)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81257436)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/hmm.c (ffffffff8126d9a5)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_pages_create
```
```
In block/blk-ioc.c (ffffffff8145618d)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81473408)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pinctrl/core.c (ffffffff814cb62c)
Location: include/linux/radix-tree.h:293
Inline: True
```
```
In drivers/pwm/core.c (ffffffff814e1ee7)
Location: include/linux/radix-tree.h:293
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_add_with_polarity
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8176228c)
Location: include/linux/radix-tree.h:293
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8181186a)
Location: include/linux/radix-tree.h:293
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff819e57bc)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff810fcee5)
Location: include/linux/radix-tree.h:297
Inline: True
```
```
In mm/shmem.c (ffffffff8120ee28)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffffffff81218f5a)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff812423df)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff812476f0)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8127b35d)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/hmm.c (ffffffff8129208a)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_pages_create
```
```
In block/blk-ioc.c (ffffffff814895c1)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff814a7be4)
Location: include/linux/radix-tree.h:297
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pinctrl/core.c (ffffffff814fc5a6)
Location: include/linux/radix-tree.h:297
Inline: True
```
```
In drivers/pwm/core.c (ffffffff81511746)
Location: include/linux/radix-tree.h:297
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a2c3b)
Location: include/linux/radix-tree.h:297
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b8d0)
Location: include/linux/radix-tree.h:297
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d3f0)
Location: lib/radix-tree.c:725
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffff81a0d3f0-ffffffff81a0d59b: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7cd20)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81a7cd20-ffffffff81a7ced5: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab4050)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81ab4050-ffffffff81ab4205: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eea60)
Location: lib/radix-tree.c:704
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_insert_irq
  - kernel/irq/irqdomain.c:irq_domain_associate
  - mm/backing-dev.c:cgwb_create
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pinctrl/core.c:pinctrl_register_one_pin
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
  - net/mptcp/token.c:mptcp_token_new_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
**Symbols:**

```
ffffffff815eea60-ffffffff815eeb3f: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816131b0)
Location: lib/radix-tree.c:704
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_insert_irq
  - kernel/irq/irqdomain.c:irq_domain_associate
  - mm/backing-dev.c:cgwb_create
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pinctrl/core.c:pinctrl_register_one_pin
  - drivers/pwm/core.c:pwmchip_add_with_polarity
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff816131b0-ffffffff8161328f: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f65f0)
Location: lib/radix-tree.c:704
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - mm/backing-dev.c:cgwb_create
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pwm/core.c:pwmchip_add
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff815f65f0-ffffffff815f67a3: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:704
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - mm/backing-dev.c:cgwb_create
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pwm/core.c:pwmchip_add
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81cdf8ab-ffffffff81cdf902: radix_tree_insert.cold (STB_LOCAL)
ffffffff81663e50-ffffffff81664020: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:704
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - mm/backing-dev.c:cgwb_create
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pwm/core.c:pwmchip_add
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81ea604b-ffffffff81ea6092: radix_tree_insert.cold (STB_LOCAL)
ffffffff8177e080-ffffffff8177e25c: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:704
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
  - mm/backing-dev.c:cgwb_create
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pwm/core.c:pwmchip_add
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff820b79c8-ffffffff820b7a0f: radix_tree_insert.cold (STB_LOCAL)
ffffffff8203ac30-ffffffff8203ae18: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:703
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
  - mm/backing-dev.c:cgwb_create
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff82138e3c-ffffffff82138e7f: radix_tree_insert.cold (STB_LOCAL)
ffffffff820b9120-ffffffff820b9307: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:703
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
  - mm/backing-dev.c:cgwb_create
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pinctrl/core.c:pinctrl_register_pins
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff8221abe1-ffffffff8221ac24: radix_tree_insert.cold (STB_LOCAL)
ffffffff82193a30-ffffffff82193c17: radix_tree_insert (STB_GLOBAL)
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
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e3e8)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffff800010d8e3e8-ffff800010d8e5e0: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88c00)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
c0e88c00-c0e88e08: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed1030)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_associate
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
c000000000ed1030-c000000000ed1328: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6ff2)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffffffe0008b6ff2-ffffffe0008b719c: radix_tree_insert (STB_GLOBAL)
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
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52ea0)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81a52ea0-ffffffff81a53055: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0ffa0)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81a0ffa0-ffffffff81a10155: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf290)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81abf290-ffffffff81abf445: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb760)
Location: lib/radix-tree.c:712
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
  - mm/backing-dev.c:wb_get_create
  - mm/vmalloc.c:vm_map_ram
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-cgroup.c:blkg_create
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81acb760-ffffffff81acb915: radix_tree_insert (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
