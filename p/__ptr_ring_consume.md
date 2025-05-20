# Function: <code>__ptr_ring_consume</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81650624)
Location: include/linux/ptr_ring.h:234
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_resize
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81682311)
Location: include/linux/ptr_ring.h:239
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_resize
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8169766f)
Location: include/linux/ptr_ring.h:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
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
In kernel/bpf/cpumap.c (ffffffff811afced)
Location: include/linux/ptr_ring.h:282
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81702529)
Location: include/linux/ptr_ring.h:282
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_queue_purge
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
In kernel/bpf/cpumap.c (ffffffff811cab2d)
Location: include/linux/ptr_ring.h:295
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81741254)
Location: include/linux/ptr_ring.h:295
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff818bdae6)
Location: include/linux/ptr_ring.h:295
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818cc41f)
Location: include/linux/ptr_ring.h:295
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff811de42d)
Location: include/linux/ptr_ring.h:295
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81765354)
Location: include/linux/ptr_ring.h:295
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff818e4ec6)
Location: include/linux/ptr_ring.h:295
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818f7648)
Location: include/linux/ptr_ring.h:295
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff811f3bf1)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8179e7d8)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff8193476e)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff81956d25)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff81200991)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817c2268)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff8196751d)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8198d1c5)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff8122844e)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:__cpu_map_ring_cleanup
```
```
In drivers/net/tun.c (ffffffff8188ec72)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81a3a970)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a647a7)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff8122f224)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:__cpu_map_ring_cleanup
```
```
In drivers/net/tun.c (ffffffff8189b8ca)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81a3ce90)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a6c8e7)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff81234134)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8187f04a)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81a23cd6)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a550ee)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff8126de3e)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81911042)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81ad8381)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81b0e31e)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff812bcc90)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81a6141b)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81c59191)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81c947ae)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff813200f0)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81bec77b)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81e0f101)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81e5026e)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff8134ff55)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81c44c7b)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81e828c1)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81eaba1d)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff81376663)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81cfa7db)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81f44ae6)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81f6e4bd)
Location: include/linux/ptr_ring.h:291
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffff800010288090)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffff8000109dc96c)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffff800010c0caf4)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffff800010c38340)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (c04b836c)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (c0ac6f2c)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (c0d25200)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (c0d4ad8c)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (c0000000003336d0)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (c000000000a9f038)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (c000000000cf8418)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (c000000000d3063c)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffe0001bcd62)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffe000627e48)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffe000789c74)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffe0007a9b98)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff811f8fb1)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81786d38)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff819074ed)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8192d035)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff811ebd01)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81766688)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff818c12fd)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818e6b35)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff811f6d81)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817b70e8)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff8195851d)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8197e1c5)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In kernel/bpf/cpumap.c (ffffffff8120506f)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817d133b)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff8197a64d)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff819a09c9)
Location: include/linux/ptr_ring.h:290
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
</ul>

## Differences
