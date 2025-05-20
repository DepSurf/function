# Function: <code>__ptr_ring_discard_one</code>

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
In drivers/net/tun.c (ffffffff81650651)
Location: include/linux/ptr_ring.h:227
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
In drivers/net/tun.c (ffffffff8168233e)
Location: include/linux/ptr_ring.h:232
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
In drivers/net/tun.c (ffffffff8169767f)
Location: include/linux/ptr_ring.h:234
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
In kernel/bpf/cpumap.c (ffffffff811afd0d)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8170254b)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (ffffffff811cab5b)
Location: include/linux/ptr_ring.h:251
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81741282)
Location: include/linux/ptr_ring.h:251
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
In net/core/page_pool.c (ffffffff818bda9a)
Location: include/linux/ptr_ring.h:251
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818cc44b)
Location: include/linux/ptr_ring.h:251
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
In kernel/bpf/cpumap.c (ffffffff811de45b)
Location: include/linux/ptr_ring.h:251
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81765382)
Location: include/linux/ptr_ring.h:251
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
In net/core/page_pool.c (ffffffff818e4e7a)
Location: include/linux/ptr_ring.h:251
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818f7674)
Location: include/linux/ptr_ring.h:251
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
In kernel/bpf/cpumap.c (ffffffff811f3bb3)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8179e818)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (ffffffff819347a1)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff81956d6c)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (ffffffff81200953)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817c22a8)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (ffffffff81967550)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8198d20c)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (ffffffff81228408)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:__cpu_map_ring_cleanup
```
```
In drivers/net/tun.c (ffffffff8188ec9c)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81a3a99f)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a647be)
Location: include/linux/ptr_ring.h:247
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
In kernel/bpf/cpumap.c (ffffffff8122f1df)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:__cpu_map_ring_cleanup
```
```
In drivers/net/tun.c (ffffffff8189b8f5)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81a3cebf)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a6c8fe)
Location: include/linux/ptr_ring.h:247
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
In kernel/bpf/cpumap.c (ffffffff812340f1)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8187f075)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81a23d09)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a55105)
Location: include/linux/ptr_ring.h:247
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
In kernel/bpf/cpumap.c (ffffffff8126ddfb)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81911071)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81ad83b4)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81b0e335)
Location: include/linux/ptr_ring.h:247
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
In kernel/bpf/cpumap.c (ffffffff812bcc59)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81a61447)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81c591c0)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81c947c5)
Location: include/linux/ptr_ring.h:247
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
In kernel/bpf/cpumap.c (ffffffff813200b9)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81bec7a7)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81e0f130)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81e50285)
Location: include/linux/ptr_ring.h:247
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
In kernel/bpf/cpumap.c (ffffffff8134ff1e)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81c44ca7)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81e828f0)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81eaba34)
Location: include/linux/ptr_ring.h:247
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
In kernel/bpf/cpumap.c (ffffffff81376615)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81cfa807)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff81f44a81)
Location: include/linux/ptr_ring.h:247
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81f6e4d4)
Location: include/linux/ptr_ring.h:247
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
In kernel/bpf/cpumap.c (ffff8000102880a8)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffff8000109dc9a0)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffff800010c0cb10)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffff800010c38370)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (c04b832c)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (c0ac6f38)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (c0d25220)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (c0d4ada0)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (c0000000003336f0)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (c000000000a9f088)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (c000000000cf843c)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (c000000000d30688)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (ffffffe0001bcd7c)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffe000627e78)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (ffffffe000789c92)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffe0007a9bce)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (ffffffff811f8f73)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81786d78)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (ffffffff81907520)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8192d07c)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (ffffffff811ebcc3)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817666c8)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (ffffffff818c1330)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818e6b7c)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (ffffffff811f6d43)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817b7128)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (ffffffff81958550)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8197e20c)
Location: include/linux/ptr_ring.h:246
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
In kernel/bpf/cpumap.c (ffffffff8120502d)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817d137a)
Location: include/linux/ptr_ring.h:246
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
In net/core/page_pool.c (ffffffff8197a680)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff819a0a0d)
Location: include/linux/ptr_ring.h:246
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
</ul>

## Differences
