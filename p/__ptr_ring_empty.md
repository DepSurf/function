# Function: <code>__ptr_ring_empty</code>

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
In drivers/net/tun.c (ffffffff8164cbbd)
Location: include/linux/ptr_ring.h:176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
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
In drivers/net/tun.c (ffffffff8167e8ed)
Location: include/linux/ptr_ring.h:181
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
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
In drivers/net/tun.c (ffffffff81693ae2)
Location: include/linux/ptr_ring.h:183
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
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
In kernel/bpf/cpumap.c (ffffffff811afd9a)
Location: include/linux/ptr_ring.h:195
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff816fd915)
Location: include/linux/ptr_ring.h:195
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
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
In kernel/bpf/cpumap.c (ffffffff811cac67)
Location: include/linux/ptr_ring.h:198
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8173c9a5)
Location: include/linux/ptr_ring.h:198
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff818bdc15)
Location: include/linux/ptr_ring.h:198
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818cc09e)
Location: include/linux/ptr_ring.h:198
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff811de55e)
Location: include/linux/ptr_ring.h:198
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81760eb5)
Location: include/linux/ptr_ring.h:198
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff818e4ff5)
Location: include/linux/ptr_ring.h:198
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818f6ade)
Location: include/linux/ptr_ring.h:198
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff811f3e4b)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8179eb4a)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81934905)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8195626e)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff81200beb)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817c25da)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff8196729a)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8198c70e)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff812285ef)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8188d0b5)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81a3ae15)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a64781)
Location: include/linux/ptr_ring.h:194
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
In kernel/bpf/cpumap.c (ffffffff8122f148)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8189b336)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81a3d535)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a6c8c1)
Location: include/linux/ptr_ring.h:194
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
In kernel/bpf/cpumap.c (ffffffff8123405d)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8187dfc6)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81a24355)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81a550ca)
Location: include/linux/ptr_ring.h:194
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
In kernel/bpf/cpumap.c (ffffffff8126dd84)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8190f7ab)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81ad8945)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81b0e2fa)
Location: include/linux/ptr_ring.h:194
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
In kernel/bpf/cpumap.c (ffffffff812bcbf1)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81a62d6e)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81c59915)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81c9478a)
Location: include/linux/ptr_ring.h:194
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
In kernel/bpf/cpumap.c (ffffffff81320051)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81bee01e)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81e0f905)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81e5024a)
Location: include/linux/ptr_ring.h:194
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
In kernel/bpf/cpumap.c (ffffffff8134fefa)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81c4654e)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81e83145)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81eab9f9)
Location: include/linux/ptr_ring.h:194
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
In kernel/bpf/cpumap.c (ffffffff81377333)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff81cfbe5e)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff81f437e5)
Location: include/linux/ptr_ring.h:194
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/sched/sch_generic.c (ffffffff81f6e499)
Location: include/linux/ptr_ring.h:194
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
In kernel/bpf/cpumap.c (ffff800010287ff8)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffff8000109dce78)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffff800010c0d120)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffff800010c38340)
Location: include/linux/ptr_ring.h:193
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
In kernel/bpf/cpumap.c (c04b8278)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (c0ac24ec)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (c0d24fa8)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (c0d49efc)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (c000000000333608)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (c000000000aa2878)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (c000000000cf8088)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (c000000000d31238)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffe0001bcce8)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffe000627b6a)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffe00078a008)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffe0007a8f34)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff811f920b)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817870aa)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff8190726a)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8192c57e)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff811ebf5b)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817669fa)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff818c107a)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff818e607e)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff811f6fdb)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817b745a)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff8195829a)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8197d70e)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
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
In kernel/bpf/cpumap.c (ffffffff812052bf)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817cf4fe)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/page_pool.c (ffffffff8197a3c1)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/sched/sch_generic.c (ffffffff8199fc7e)
Location: include/linux/ptr_ring.h:193
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
</ul>

## Differences
