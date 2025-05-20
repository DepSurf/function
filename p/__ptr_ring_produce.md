# Function: <code>__ptr_ring_produce</code>

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
In drivers/net/tun.c (ffffffff8164d531)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff8167f259)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/tun.c (ffffffff8169446c)
Location: include/linux/ptr_ring.h:105
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In kernel/bpf/cpumap.c (ffffffff811af7af)
Location: include/linux/ptr_ring.h:107
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff816fe596)
Location: include/linux/ptr_ring.h:107
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In kernel/bpf/cpumap.c (ffffffff811ca2a6)
Location: include/linux/ptr_ring.h:108
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff8173cd77)
Location: include/linux/ptr_ring.h:108
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff818bde97)
Location: include/linux/ptr_ring.h:108
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818cc241)
Location: include/linux/ptr_ring.h:108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_enqueue
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
In kernel/bpf/cpumap.c (ffffffff811ddbc6)
Location: include/linux/ptr_ring.h:108
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff81760817)
Location: include/linux/ptr_ring.h:108
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff818e5277)
Location: include/linux/ptr_ring.h:108
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818f7871)
Location: include/linux/ptr_ring.h:108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_enqueue
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
In kernel/bpf/cpumap.c (ffffffff811f3279)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff8179ed88)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81934b9e)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81956f94)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (ffffffff81200019)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff817c3568)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81967907)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8198d434)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (ffffffff81227c11)
Location: include/linux/ptr_ring.h:104
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188e813)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81a3b0e3)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/sched/sch_generic.c (ffffffff81a65124)
Location: include/linux/ptr_ring.h:104
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
In kernel/bpf/cpumap.c (ffffffff8122e620)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff8189d17d)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81a3d3fd)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/sched/sch_generic.c (ffffffff81a6d254)
Location: include/linux/ptr_ring.h:104
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
In kernel/bpf/cpumap.c (ffffffff81233500)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff8187f9ac)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81a24225)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/sched/sch_generic.c (ffffffff81a55ad4)
Location: include/linux/ptr_ring.h:104
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
In kernel/bpf/cpumap.c (ffffffff8126e68c)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff81910b36)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81ad8813)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/sched/sch_generic.c (ffffffff81b0e854)
Location: include/linux/ptr_ring.h:104
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
In kernel/bpf/cpumap.c (ffffffff812bd59a)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff81a6091c)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81c5969b)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/sched/sch_generic.c (ffffffff81c94e04)
Location: include/linux/ptr_ring.h:104
Inline: True
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
In kernel/bpf/cpumap.c (ffffffff81320a37)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff81becedd)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81e0f67b)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/sched/sch_generic.c (ffffffff81e508b4)
Location: include/linux/ptr_ring.h:104
Inline: True
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
In kernel/bpf/cpumap.c (ffffffff813508e7)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff81c453de)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81e82e5f)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/sched/sch_generic.c (ffffffff81eac0a0)
Location: include/linux/ptr_ring.h:104
Inline: True
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
In kernel/bpf/cpumap.c (ffffffff81377d17)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff81cfad0d)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81f43c4c)
Location: include/linux/ptr_ring.h:104
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
  - net/core/page_pool.c:page_pool_put_unrefed_page
```
```
In net/sched/sch_generic.c (ffffffff81f6eb30)
Location: include/linux/ptr_ring.h:104
Inline: True
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
In kernel/bpf/cpumap.c (ffff8000102884d0)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffff8000109def3c)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffff800010c0d3ac)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (ffff800010c38738)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (c04b78f8)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (c0ac2b34)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (c0d25624)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (c0d4a8d4)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (c000000000332be8)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (c000000000aa088c)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (c000000000cf8a84)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (c000000000d3157c)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (ffffffe0001bc442)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffe000628162)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffe00078a218)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (ffffffe0007a9dc4)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (ffffffff811f8639)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff81787ff9)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff819078d7)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8192d2a4)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (ffffffff811eb389)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff81767949)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff818c16e7)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818e6da4)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (ffffffff811f6409)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff817b83e8)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81958907)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8197e434)
Location: include/linux/ptr_ring.h:103
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
In kernel/bpf/cpumap.c (ffffffff81204979)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In drivers/net/tun.c (ffffffff817d06ed)
Location: include/linux/ptr_ring.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff8197aa47)
Location: include/linux/ptr_ring.h:103
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819a05f4)
Location: include/linux/ptr_ring.h:103
Inline: True
```
</details>
</li>
</ul>

## Differences
