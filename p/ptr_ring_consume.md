# Function: <code>ptr_ring_consume</code>

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
In drivers/net/tun.c (ffffffff8165052d)
Location: include/linux/ptr_ring.h:245
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
In drivers/net/tun.c (ffffffff81680c09)
Location: include/linux/ptr_ring.h:255
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff8169620c)
Location: include/linux/ptr_ring.h:302
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff811af8d0)
Location: include/linux/ptr_ring.h:317
Inline: True
```
```
In drivers/net/tun.c (ffffffff817001c0)
Location: include/linux/ptr_ring.h:317
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff811ca902)
Location: include/linux/ptr_ring.h:331
Inline: True
```
```
In drivers/net/tun.c (ffffffff8173ff8f)
Location: include/linux/ptr_ring.h:331
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff818bdc96)
Location: include/linux/ptr_ring.h:331
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:331
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff811de202)
Location: include/linux/ptr_ring.h:331
Inline: True
```
```
In drivers/net/tun.c (ffffffff81763fa9)
Location: include/linux/ptr_ring.h:331
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff818e5076)
Location: include/linux/ptr_ring.h:331
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:331
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff811f392c)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (ffffffff817a1cfb)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (ffffffff8193497f)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff812006cc)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (ffffffff817c29cb)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff8122819f)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_ring_cleanup
```
```
In drivers/net/tun.c (ffffffff8188ec6d)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff8122ef5f)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_ring_cleanup
```
```
In drivers/net/tun.c (ffffffff8189b8c5)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff81233e8d)
Location: include/linux/ptr_ring.h:327
Inline: True
```
```
In drivers/net/tun.c (ffffffff8187f045)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff8126dbcd)
Location: include/linux/ptr_ring.h:327
Inline: True
```
```
In drivers/net/tun.c (ffffffff8191103d)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff812bca1b)
Location: include/linux/ptr_ring.h:327
Inline: True
```
```
In drivers/net/tun.c (ffffffff81a61416)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff8131fe5b)
Location: include/linux/ptr_ring.h:327
Inline: True
```
```
In drivers/net/tun.c (ffffffff81bec776)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff8134f686)
Location: include/linux/ptr_ring.h:327
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c44c76)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff8137665b)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
```
In drivers/net/tun.c (ffffffff81cfa7d6)
Location: include/linux/ptr_ring.h:327
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:327
Inline: False
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
In kernel/bpf/cpumap.c (ffff800010287e68)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (ffff8000109dd4c0)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (c04b8078)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (c0ac5ce4)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (c0000000003332e4)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (c000000000aa3c10)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (ffffffe0001bcae6)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (ffffffe0006286f2)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff811f8cec)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (ffffffff8178749b)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff811eba3c)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (ffffffff81766deb)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff811f6abc)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (ffffffff817b784b)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
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
In kernel/bpf/cpumap.c (ffffffff81204dd3)
Location: include/linux/ptr_ring.h:326
Inline: True
```
```
In drivers/net/tun.c (ffffffff817d1ef1)
Location: include/linux/ptr_ring.h:326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
```
```
In net/core/page_pool.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/ptr_ring.h:326
Inline: False
```
</details>
</li>
</ul>

## Differences
