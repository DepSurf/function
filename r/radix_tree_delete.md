# Function: <code>radix_tree_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *radix_tree_delete(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ef380)
Location: lib/radix-tree.c:1427
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - mm/backing-dev.c:cgwb_kill
  - mm/swap_state.c:__delete_from_swap_cache
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/block/brd.c:brd_free_pages
  - drivers/block/brd.c:brd_free_pages
```
**Symbols:**

```
ffffffff813ef380-ffffffff813ef38d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *radix_tree_delete(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435b80)
Location: lib/radix-tree.c:1580
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - mm/backing-dev.c:cgwb_kill
  - mm/swap_state.c:__delete_from_swap_cache
  - fs/dax.c:dax_delete_mapping_entry
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/block/brd.c:brd_free_pages
  - drivers/block/brd.c:brd_free_pages
```
**Symbols:**

```
ffffffff81435b80-ffffffff81435b8d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *radix_tree_delete(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81452170)
Location: lib/radix-tree.c:1899
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - mm/backing-dev.c:cgwb_kill
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_invalidate_mapping_entry
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
```
**Symbols:**

```
ffffffff81452170-ffffffff8145217d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *radix_tree_delete(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1f30)
Location: lib/radix-tree.c:2067
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - mm/backing-dev.c:cgwb_kill
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
```
**Symbols:**

```
ffffffff818f1f30-ffffffff818f1f3d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *radix_tree_delete(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819783e0)
Location: lib/radix-tree.c:2064
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/memremap.c:pgmap_radix_release
  - mm/backing-dev.c:cgwb_kill
  - mm/vmalloc.c:free_vmap_block
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff819783e0-ffffffff819783ed: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *radix_tree_delete(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4b00)
Location: lib/radix-tree.c:2065
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/memremap.c:pgmap_radix_release
  - mm/backing-dev.c:cgwb_kill
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff819d4b00-ffffffff819d4b0d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d760)
Location: lib/radix-tree.c:1467
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff81a0d760-ffffffff81a0d76d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7d0a0)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff81a7d0a0-ffffffff81a7d0ad: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab43d0)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff81ab43d0-ffffffff81ab43dd: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eed70)
Location: lib/radix-tree.c:1446
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - mm/backing-dev.c:cgwb_kill
  - mm/vmalloc.c:free_vmap_block
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:free_pwms
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
```
**Symbols:**

```
ffffffff815eed70-ffffffff815eed7d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816134c0)
Location: lib/radix-tree.c:1446
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:free_pwms
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff816134c0-ffffffff816134cd: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6b20)
Location: lib/radix-tree.c:1447
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff815f6b20-ffffffff815f6b2d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81664220)
Location: lib/radix-tree.c:1447
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff81664220-ffffffff8166422d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177e4b0)
Location: lib/radix-tree.c:1447
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff8177e4b0-ffffffff8177e4c7: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203b0c0)
Location: lib/radix-tree.c:1447
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff8203b0c0-ffffffff8203b0d7: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b95a0)
Location: lib/radix-tree.c:1445
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff820b95a0-ffffffff820b95b7: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82193eb0)
Location: lib/radix-tree.c:1445
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff82193eb0-ffffffff82193ec7: radix_tree_delete (STB_GLOBAL)
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
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e8f8)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_generic_remove_group
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
  - drivers/pinctrl/pinmux.c:pinmux_generic_remove_function
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffff800010d8e8f8-ffff800010d8e910: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e89020)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_generic_remove_group
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
  - drivers/pinctrl/pinmux.c:pinmux_generic_remove_function
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/usb/host/xhci-mem.c:xhci_remove_segment_mapping
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
c0e89020-c0e89038: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed15b0)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - mm/backing-dev.c:cgwb_kill
  - mm/vmalloc.c:free_vmap_block
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_generic_remove_group
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
  - drivers/pinctrl/pinmux.c:pinmux_generic_remove_function
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
c000000000ed15b0-c000000000ed15c0: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b7322)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_generic_remove_group
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
  - drivers/pinctrl/pinmux.c:pinmux_generic_remove_function
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffe0008b7322-ffffffe0008b733c: radix_tree_delete (STB_GLOBAL)
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
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a53220)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff81a53220-ffffffff81a5322d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a10320)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff81a10320-ffffffff81a1032d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf610)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff81abf610-ffffffff81abf61d: radix_tree_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *radix_tree_delete(struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acbae0)
Location: lib/radix-tree.c:1454
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/backing-dev.c:cgwb_kill
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-cgroup.c:blkg_destroy
  - drivers/pinctrl/core.c:pinctrl_free_pindescs
  - drivers/pwm/core.c:pwmchip_remove
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister_single
```
**Symbols:**

```
ffffffff81acbae0-ffffffff81acbaed: radix_tree_delete (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>struct xarray *root</code>
</li>
</ul>
</details>
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
