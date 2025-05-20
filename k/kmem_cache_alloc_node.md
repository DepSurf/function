# Function: <code>kmem_cache_alloc_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eb3b0)
Location: mm/slub.c:2598
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:alloc_request_struct
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:ioc_create_icq
  - block/cfq-iosched.c:cfq_get_queue
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb_head
```
**Symbols:**

```
ffffffff811eb3b0-ffffffff811eb5b4: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120b800)
Location: mm/slub.c:2727
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:alloc_request_struct
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - block/cfq-iosched.c:cfq_get_queue
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb_head
```
**Symbols:**

```
ffffffff8120b800-ffffffff8120b9ab: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121d830)
Location: mm/slub.c:2749
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:alloc_request_struct
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - block/cfq-iosched.c:cfq_get_queue
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb_head
```
**Symbols:**

```
ffffffff8121d830-ffffffff8121d9db: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81228470)
Location: mm/slub.c:2746
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/slub.c:__kmem_cache_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:alloc_request_simple
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - block/cfq-iosched.c:cfq_get_queue
  - drivers/scsi/scsi_lib.c:scsi_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_request
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb_head
```
**Symbols:**

```
ffffffff81228470-ffffffff8122861a: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81244550)
Location: mm/slub.c:2759
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/slub.c:__kmem_cache_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:alloc_request_simple
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - block/cfq-iosched.c:cfq_get_queue
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81244550-ffffffff81244707: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81266a40)
Location: mm/slub.c:2742
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:alloc_request_simple
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - block/cfq-iosched.c:cfq_get_queue
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81266a40-ffffffff81266c4a: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127b760)
Location: mm/slub.c:2792
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8127b760-ffffffff8127b95d: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812971b0)
Location: mm/slub.c:2804
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812971b0-ffffffff81297401: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a6fb0)
Location: mm/slub.c:2800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812a6fb0-ffffffff812a7201: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dbf30)
Location: mm/slub.c:2858
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:init_kmem_cache_nodes
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812dbf30-ffffffff812dc18a: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e8520)
Location: mm/slub.c:2926
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:init_kmem_cache_nodes
  - block/blk-core.c:blk_alloc_queue
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812e8520-ffffffff812e8735: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812effc0)
Location: mm/slub.c:2948
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/events/core.c:perf_event_alloc
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812effc0-ffffffff812f020c: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813399c0)
Location: mm/slub.c:3247
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/events/core.c:perf_event_alloc
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff813399c0-ffffffff81339cbd: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a9d80)
Location: mm/slub.c:3291
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/events/core.c:perf_event_alloc
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:init_kmem_cache_nodes
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:alloc_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff813a9d80-ffffffff813aa0ac: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142ab80)
Location: mm/slub.c:3495
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/events/core.c:perf_event_alloc
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:alloc_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8142ab80-ffffffff8142af06: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81460090)
Location: mm/slub.c:3513
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/events/core.c:perf_event_alloc
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:alloc_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:kmalloc_reserve
  - net/core/skbuff.c:kmalloc_reserve
```
**Symbols:**

```
ffffffff81460090-ffffffff8146043f: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145b1c0)
Location: mm/slub.c:3901
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/events/core.c:perf_event_alloc
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - mm/zswap.c:zswap_store
  - block/blk-core.c:blk_alloc_queue
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:alloc_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:kmalloc_reserve
  - net/core/skbuff.c:kmalloc_reserve
```
**Symbols:**

```
ffffffff8145b1c0-ffffffff8145b523: kmem_cache_alloc_node (STB_GLOBAL)
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
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010348380)
Location: mm/slub.c:2800
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffff800010348380-ffff800010348610: kmem_cache_alloc_node (STB_GLOBAL)
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
In kernel/fork.c (c0351d38)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (c037519c)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In mm/vmalloc.c (c052b75c)
Location: include/linux/slab.h:425
Inline: True
```
```
In mm/slub.c (c054f4c0)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In block/blk-core.c (c078e4a0)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
```
```
In block/blk-ioc.c (c0795654)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
```
```
In drivers/scsi/scsi_lib.c (c0a4a74c)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
```
```
In net/core/skbuff.c (c0ccfecc)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000426980)
Location: mm/slub.c:2800
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_open
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
c000000000426980-c000000000426d18: kmem_cache_alloc_node (STB_GLOBAL)
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
In kernel/fork.c (ffffffe0000bfd5a)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/workqueue.c (ffffffe0000da194)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In mm/vmalloc.c (ffffffe000217980)
Location: include/linux/slab.h:425
Inline: True
```
```
In mm/slub.c (ffffffe00023cb7a)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In block/blk-core.c (ffffffe000423766)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
```
```
In block/blk-ioc.c (ffffffe00042986e)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005de574)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
```
```
In net/core/skbuff.c (ffffffe000743676)
Location: include/linux/slab.h:425
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
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
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129f590)
Location: mm/slub.c:2800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8129f590-ffffffff8129f7e1: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812910b0)
Location: mm/slub.c:2800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812910b0-ffffffff81291301: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129d3a0)
Location: mm/slub.c:2800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8129d3a0-ffffffff8129d5f1: kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ad740)
Location: mm/slub.c:2800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:alloc_unbound_pwq
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/slub.c:kmem_cache_open
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812ad740-ffffffff812ad996: kmem_cache_alloc_node (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
