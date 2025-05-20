# Function: <code>ptr_ring_cleanup</code>

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
In drivers/net/tun.c (ffffffff8164eef9)
Location: include/linux/ptr_ring.h:438
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
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
Location: include/linux/ptr_ring.h:464
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
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
In drivers/net/tun.c (ffffffff81696204)
Location: include/linux/ptr_ring.h:630
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
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
In kernel/bpf/cpumap.c (ffffffff811b0092)
Location: include/linux/ptr_ring.h:650
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff817002b3)
Location: include/linux/ptr_ring.h:650
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
In kernel/bpf/cpumap.c (ffffffff811ca862)
Location: include/linux/ptr_ring.h:666
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:666
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff818bdb8c)
Location: include/linux/ptr_ring.h:666
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_destroy_rcu
```
```
In net/sched/sch_generic.c (ffffffff818cbb72)
Location: include/linux/ptr_ring.h:666
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff811de18a)
Location: include/linux/ptr_ring.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff818e4f6c)
Location: include/linux/ptr_ring.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_destroy_rcu
```
```
In net/sched/sch_generic.c (ffffffff818f6e72)
Location: include/linux/ptr_ring.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff811f387e)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff8193467d)
Location: include/linux/ptr_ring.h:663
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819565a2)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff8120061e)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81967746)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff8198ca42)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff812280b2)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81a3aca5)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff81a644d2)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff8122e93c)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81a3d0c2)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff81a6c612)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff8123381b)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81a23edb)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff81a54da2)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff8126d49d)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81ad8580)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff81b0da22)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff812bc5fa)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81c5940b)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff81c94b12)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff8131fb0c)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81e0f38f)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff81e50572)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff8134fb37)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81e82b4f)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff81eabd17)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff8137668f)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81f44bbb)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81f6e7b7)
Location: include/linux/ptr_ring.h:664
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffff8000102888fc)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffff800010c0ccf4)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffff800010c37790)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (c04b7ea8)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (c0d25344)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (c0d4a258)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (c000000000333e60)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (c000000000cf874c)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (c000000000d2fe6c)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffe0001bca7c)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffe000626e92)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffe000789d9c)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffe0007a9394)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff811f8c3e)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81907716)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff8192c8b2)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff811eb98e)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff818c1526)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff818e63b2)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff811f6a0e)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff81958746)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff8197da42)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
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
In kernel/bpf/cpumap.c (ffffffff81205648)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (0)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_detach
```
```
In net/core/page_pool.c (ffffffff8197a868)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/sched/sch_generic.c (ffffffff8199ffb2)
Location: include/linux/ptr_ring.h:663
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_destroy
```
</details>
</li>
</ul>

## Differences
