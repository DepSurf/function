# Function: <code>ptr_ring_init</code>

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
In drivers/net/tun.c (ffffffff8164e382)
Location: include/linux/ptr_ring.h:338
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In drivers/net/tun.c (ffffffff81680092)
Location: include/linux/ptr_ring.h:348
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In drivers/net/tun.c (ffffffff816954f6)
Location: include/linux/ptr_ring.h:457
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In kernel/bpf/cpumap.c (ffffffff811aff98)
Location: include/linux/ptr_ring.h:477
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8170000c)
Location: include/linux/ptr_ring.h:477
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
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
In kernel/bpf/cpumap.c (ffffffff811ca7a9)
Location: include/linux/ptr_ring.h:491
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8173bba3)
Location: include/linux/ptr_ring.h:491
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff818bd91a)
Location: include/linux/ptr_ring.h:491
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818cbfbf)
Location: include/linux/ptr_ring.h:491
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff811de0d5)
Location: include/linux/ptr_ring.h:491
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8175f4c3)
Location: include/linux/ptr_ring.h:491
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff818e4c5d)
Location: include/linux/ptr_ring.h:491
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818f732f)
Location: include/linux/ptr_ring.h:491
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff811f37a1)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8179ccf1)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff819344ba)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81956a34)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff81200541)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817c0791)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff819670ea)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8198ced4)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff81227fb4)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8188a871)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a3a459)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81a646a1)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff8122e7e4)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81898a71)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a3c9e9)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81a6c7e1)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff812336cc)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8187b1b1)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a2393d)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81a54f84)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff8126d34e)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8190c9b1)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81ad7f6d)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81b0dcc4)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff812bc486)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81a612a1)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81c58ce9)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81c950a0)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff8131f98c)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81bec5e6)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81e0ebd9)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81e50ba0)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff8134f98c)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81c449c3)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81e82260)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81eac3b0)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff81376e9c)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81cfa523)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81f4323f)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81f6ee40)
Location: include/linux/ptr_ring.h:487
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffff800010288818)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffff8000109daccc)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffff800010c0c764)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffff800010c37a48)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (c04b7db8)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (c0ac1be4)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (c0d24e2c)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (c0d4ac14)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (c000000000333d38)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (c000000000a9d218)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (c000000000cf7e90)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (c000000000d303f8)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffe0001bc9a8)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffe000625c36)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffe000789b10)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffe0007a9904)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff811f8b61)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff81785261)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff819070ba)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8192cd44)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff811eb8b1)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff81764bb1)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff818c0eca)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818e6844)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff811f6931)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817b5611)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff819580ea)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8197ded4)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
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
In kernel/bpf/cpumap.c (ffffffff81205561)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817cf7f1)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff8197a1fa)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff819a0804)
Location: include/linux/ptr_ring.h:486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
</details>
</li>
</ul>

## Differences
