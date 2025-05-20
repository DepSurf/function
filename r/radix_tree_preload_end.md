# Function: <code>radix_tree_preload_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118dde9)
Location: include/linux/radix-tree.h:304
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff811a9643)
Location: include/linux/radix-tree.h:304
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmalloc.c (ffffffff811ce9f5)
Location: include/linux/radix-tree.h:304
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff811d2818)
Location: include/linux/radix-tree.h:304
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In block/blk-ioc.c (ffffffff813bf33c)
Location: include/linux/radix-tree.h:304
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff813d9226)
Location: include/linux/radix-tree.h:304
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/block/brd.c (ffffffff8156d005)
Location: include/linux/radix-tree.h:304
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81652d80)
Location: include/linux/radix-tree.h:304
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
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
In mm/filemap.c (ffffffff811a0e81)
Location: include/linux/radix-tree.h:317
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff811c0e62)
Location: include/linux/radix-tree.h:317
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmalloc.c (ffffffff811eb650)
Location: include/linux/radix-tree.h:317
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff811f0909)
Location: include/linux/radix-tree.h:317
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
```
In fs/dax.c (ffffffff81287e57)
Location: include/linux/radix-tree.h:317
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
```
```
In block/blk-ioc.c (ffffffff81403296)
Location: include/linux/radix-tree.h:317
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff8141efa3)
Location: include/linux/radix-tree.h:317
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/block/brd.c (ffffffff815c2827)
Location: include/linux/radix-tree.h:317
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b3709)
Location: include/linux/radix-tree.h:317
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
In mm/filemap.c (ffffffff811b0a81)
Location: include/linux/radix-tree.h:345
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff811d145a)
Location: include/linux/radix-tree.h:345
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmalloc.c (ffffffff811fc8c0)
Location: include/linux/radix-tree.h:345
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff8120130b)
Location: include/linux/radix-tree.h:345
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
```
In fs/dax.c (ffffffff8129afa5)
Location: include/linux/radix-tree.h:345
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/blk-ioc.c (ffffffff8141cfc6)
Location: include/linux/radix-tree.h:345
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff8143a563)
Location: include/linux/radix-tree.h:345
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e18b9)
Location: include/linux/radix-tree.h:345
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
In mm/filemap.c (ffffffff811b7f86)
Location: include/linux/radix-tree.h:350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff811dce6b)
Location: include/linux/radix-tree.h:350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmalloc.c (ffffffff81207538)
Location: include/linux/radix-tree.h:350
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff8120c1b6)
Location: include/linux/radix-tree.h:350
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/dax.c (ffffffff812aad10)
Location: include/linux/radix-tree.h:350
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/blk-ioc.c (ffffffff8142b033)
Location: include/linux/radix-tree.h:350
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81447e1f)
Location: include/linux/radix-tree.h:350
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f588d)
Location: include/linux/radix-tree.h:350
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
In mm/filemap.c (ffffffff811cc646)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff811eed88)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmalloc.c (ffffffff81220628)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff8122587a)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/dax.c (ffffffff812ce543)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/blk-ioc.c (ffffffff81456226)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81474a1f)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8176229d)
Location: include/linux/radix-tree.h:348
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
In mm/filemap.c (ffffffff811ed419)
Location: include/linux/radix-tree.h:352
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8120f8a3)
Location: include/linux/radix-tree.h:352
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmalloc.c (ffffffff81242418)
Location: include/linux/radix-tree.h:352
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff81247e1c)
Location: include/linux/radix-tree.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/dax.c (ffffffff812f8b43)
Location: include/linux/radix-tree.h:352
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/blk-ioc.c (ffffffff81489666)
Location: include/linux/radix-tree.h:352
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff814a8f5c)
Location: include/linux/radix-tree.h:352
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a2c4c)
Location: include/linux/radix-tree.h:352
Inline: True
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
In mm/vmalloc.c (ffffffff81256b4d)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffffffff814a34ac)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff814c3156)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817c8f3a)
Location: include/linux/radix-tree.h:259
Inline: True
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
In mm/vmalloc.c (ffffffff8126ad9f)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffffffff814d1584)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff814f1796)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81808cea)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (ffffffff81279cb8)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffffffff814ea92e)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff8150ad83)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81839baa)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (ffffffff812aa399)
Location: include/linux/radix-tree.h:246
Inline: True
```
```
In block/blk-ioc.c (ffffffff815498ce)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff8156be13)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190c5c1)
Location: include/linux/radix-tree.h:246
Inline: True
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
In block/blk-ioc.c (ffffffff815656fe)
Location: include/linux/radix-tree.h:247
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81586b1e)
Location: include/linux/radix-tree.h:247
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81913fd1)
Location: include/linux/radix-tree.h:247
Inline: True
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
In block/blk-ioc.c (ffffffff8156dd6e)
Location: include/linux/radix-tree.h:247
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff8158d82e)
Location: include/linux/radix-tree.h:247
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f74f1)
Location: include/linux/radix-tree.h:247
Inline: True
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
In block/blk-ioc.c (ffffffff815d235e)
Location: include/linux/radix-tree.h:247
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff815f3289)
Location: include/linux/radix-tree.h:247
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81995a79)
Location: include/linux/radix-tree.h:247
Inline: True
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
In block/blk-ioc.c (ffffffff8167da64)
Location: include/linux/radix-tree.h:249
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff816a47e3)
Location: include/linux/radix-tree.h:249
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af27eb)
Location: include/linux/radix-tree.h:249
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
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
In block/blk-ioc.c (ffffffff8173a674)
Location: include/linux/radix-tree.h:249
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81763549)
Location: include/linux/radix-tree.h:249
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c7fcbb)
Location: include/linux/radix-tree.h:249
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
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
In block/blk-ioc.c (ffffffff81776d72)
Location: include/linux/radix-tree.h:258
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff817a26b6)
Location: include/linux/radix-tree.h:258
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkcg_init_disk
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce699b)
Location: include/linux/radix-tree.h:258
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
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
In block/blk-ioc.c (ffffffff817b8f9f)
Location: include/linux/radix-tree.h:258
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff817e61f3)
Location: include/linux/radix-tree.h:258
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkcg_init_disk
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9bbfb)
Location: include/linux/radix-tree.h:258
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
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
In mm/vmalloc.c (ffff800010310e68)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffff8000105e907c)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffff80001060e5cc)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a77650)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (c052cd40)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (c079573c)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (c07b8e8c)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (c0b4b264)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (c0000000003e1d38)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (c00000000077dd28)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (c0000000007abad0)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (c000000000b4e05c)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (ffffffe000218bbc)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffffffe000429972)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffe000446afa)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffe00068f1ce)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (ffffffff81272308)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffffffff814e2f0e)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81503363)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f1f5a)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (ffffffff81264278)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffffffff814d3898)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff814f382d)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b70fa)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (ffffffff812700a8)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffffffff814def9e)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff814ff3f3)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8182ea2a)
Location: include/linux/radix-tree.h:246
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
In mm/vmalloc.c (ffffffff8127faa4)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In block/blk-ioc.c (ffffffff814f7dee)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-cgroup.c (ffffffff81518555)
Location: include/linux/radix-tree.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81848b86)
Location: include/linux/radix-tree.h:246
Inline: True
```
</details>
</li>
</ul>

## Differences
