# Function: <code>kmalloc_array_node</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811cfe81)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In block/blk-mq.c (ffffffff8145de92)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
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
In kernel/events/ring_buffer.c (ffffffff811e2b20)
Location: include/linux/slab.h:661
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff811f1065)
Location: include/linux/slab.h:661
Inline: True
```
```
In block/blk-mq.c (ffffffff814926cf)
Location: include/linux/slab.h:661
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In lib/sbitmap.c (ffffffff814f8ac3)
Location: include/linux/slab.h:661
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/scsi/sd_zbc.c (ffffffff817033b1)
Location: include/linux/slab.h:661
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a6263)
Location: include/linux/slab.h:661
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff811f2f90)
Location: include/linux/slab.h:696
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff81202ec5)
Location: include/linux/slab.h:696
Inline: True
```
```
In block/blk-mq.c (ffffffff814ac497)
Location: include/linux/slab.h:696
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff814cbc78)
Location: include/linux/slab.h:696
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffffffff8150cef3)
Location: include/linux/slab.h:696
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cc39f)
Location: include/linux/slab.h:696
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff8120aca8)
Location: include/linux/slab.h:702
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff8121a2b5)
Location: include/linux/slab.h:702
Inline: True
```
```
In block/blk-mq.c (ffffffff814da6a8)
Location: include/linux/slab.h:702
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff814fa52f)
Location: include/linux/slab.h:702
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffffffff8153b5f3)
Location: include/linux/slab.h:702
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180c593)
Location: include/linux/slab.h:702
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff81217f88)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff81227c25)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (ffffffff814f3a68)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff8151848f)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffffffff8155c403)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183d585)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff81243ad8)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff81254595)
Location: include/linux/slab.h:623
Inline: True
```
```
In block/blk-mq.c (ffffffff81554118)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff81578bd9)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In lib/sbitmap.c (ffffffff815e5cc3)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190cef8)
Location: include/linux/slab.h:623
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff8124e168)
Location: include/linux/slab.h:636
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff8125f1a5)
Location: include/linux/slab.h:636
Inline: True
```
```
In mm/memcontrol.c (ffffffff81308a65)
Location: include/linux/slab.h:636
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
```
```
In block/blk-mq.c (ffffffff815707d8)
Location: include/linux/slab.h:636
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff81595502)
Location: include/linux/slab.h:636
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In lib/sbitmap.c (ffffffff8160a083)
Location: include/linux/slab.h:636
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81914948)
Location: include/linux/slab.h:636
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff81252aa0)
Location: include/linux/slab.h:640
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff81263d15)
Location: include/linux/slab.h:640
Inline: True
```
```
In mm/memcontrol.c (ffffffff8130f185)
Location: include/linux/slab.h:640
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
```
```
In block/blk-mq.c (ffffffff815786a2)
Location: include/linux/slab.h:640
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff8159c3d2)
Location: include/linux/slab.h:640
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In lib/sbitmap.c (ffffffff815ed0e4)
Location: include/linux/slab.h:640
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f7e78)
Location: include/linux/slab.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff8128e36e)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff812a02f5)
Location: include/linux/slab.h:675
Inline: True
```
```
In mm/memcontrol.c (ffffffff81359ff5)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
```
```
In block/blk-mq.c (ffffffff815dd79b)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff816049e9)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In lib/sbitmap.c (ffffffff8165a0bf)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81996488)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff812e31ee)
Location: include/linux/slab.h:686
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff812f78f5)
Location: include/linux/slab.h:686
Inline: True
Inline callers:
  - mm/mempool.c:mempool_init_node
```
```
In mm/memcontrol.c (ffffffff813d33b5)
Location: include/linux/slab.h:686
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
```
```
In block/blk-mq.c (ffffffff8168b4f7)
Location: include/linux/slab.h:686
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-zoned.c (ffffffff816b819d)
Location: include/linux/slab.h:686
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In lib/bitmap.c (ffffffff816de1e0)
Location: include/linux/slab.h:686
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af3384)
Location: include/linux/slab.h:686
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810861dd)
Location: include/linux/slab.h:688
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
```
In kernel/events/ring_buffer.c (ffffffff8134b85e)
Location: include/linux/slab.h:688
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff81361285)
Location: include/linux/slab.h:688
Inline: True
Inline callers:
  - mm/mempool.c:mempool_init_node
```
```
In mm/memcontrol.c (ffffffff81458b75)
Location: include/linux/slab.h:688
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
```
```
In block/blk-mq.c (ffffffff8174951d)
Location: include/linux/slab.h:688
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-zoned.c (ffffffff81777ef2)
Location: include/linux/slab.h:688
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In lib/bitmap.c (ffffffff817ce360)
Location: include/linux/slab.h:688
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c808a4)
Location: include/linux/slab.h:688
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088d7d)
Location: include/linux/slab.h:671
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
```
In kernel/events/ring_buffer.c (ffffffff8137c8ae)
Location: include/linux/slab.h:671
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff81393645)
Location: include/linux/slab.h:671
Inline: True
Inline callers:
  - mm/mempool.c:mempool_init_node
```
```
In mm/memcontrol.c (ffffffff8148e7f5)
Location: include/linux/slab.h:671
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
```
```
In block/blk-mq.c (ffffffff81785c5c)
Location: include/linux/slab.h:671
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-zoned.c (ffffffff817b7a07)
Location: include/linux/slab.h:671
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In lib/bitmap.c (ffffffff8180c810)
Location: include/linux/slab.h:671
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce7585)
Location: include/linux/slab.h:671
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108fc8d)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
```
In kernel/events/ring_buffer.c (ffffffff813a5b16)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff813bd2f5)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - mm/mempool.c:mempool_init_node
```
```
In mm/memcontrol.c (ffffffff814be1b5)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
```
```
In block/blk-mq.c (ffffffff817c830b)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-zoned.c (ffffffff817fc491)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In lib/bitmap.c (ffffffff81852920)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81da090e)
Location: include/linux/slab.h:679
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffff8000102a2a7c)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffff8000102b51c8)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (ffff8000105f32c8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffff80001061fe24)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffff800010669344)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7b4fc)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (c04d25e8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (c04e2540)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (c079f3ec)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (c07c7950)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (c0811fd4)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (c0b4ed34)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (c000000000354d04)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (c00000000036c694)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (c00000000078aafc)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (c0000000007bf460)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (c00000000081f778)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (c000000000b531b8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffe0001d1636)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffe0001da27a)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (ffffffe000431a02)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffe0004525be)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffffffe00049474c)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692a86)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff812105d8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff81220275)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (ffffffff814ec048)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff81510a6f)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffffffff815549f3)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/nvme/host/pci.c (ffffffff8174e1bc)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f5935)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff81203368)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff81213425)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (ffffffff814dc598)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff81500d8f)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffffffff81544c73)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/nvme/host/pci.c (ffffffff8172e05c)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817baad5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff8120e378)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff8121e015)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (ffffffff814e80d8)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff8150caff)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffffffff81550733)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81832405)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In kernel/events/ring_buffer.c (ffffffff8121d288)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff8122d085)
Location: include/linux/slab.h:644
Inline: True
```
```
In block/blk-mq.c (ffffffff81501078)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-zoned.c (ffffffff815261df)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/sbitmap.c (ffffffff8156a573)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184c5e5)
Location: include/linux/slab.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
</details>
</li>
</ul>

## Differences
