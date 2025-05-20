# Function: <code>__ptr_ring_init_queue_alloc</code>

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
In drivers/net/tun.c (ffffffff816504e1)
Location: include/linux/ptr_ring.h:333
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_resize
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
In drivers/net/tun.c (ffffffff816821ce)
Location: include/linux/ptr_ring.h:343
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_resize
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
In drivers/net/tun.c (ffffffff816975bf)
Location: include/linux/ptr_ring.h:439
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
Location: include/linux/ptr_ring.h:457
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8170246e)
Location: include/linux/ptr_ring.h:457
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
Location: include/linux/ptr_ring.h:471
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8174119d)
Location: include/linux/ptr_ring.h:471
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818bd91a)
Location: include/linux/ptr_ring.h:471
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818cc37e)
Location: include/linux/ptr_ring.h:471
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:471
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff81765294)
Location: include/linux/ptr_ring.h:471
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818e4c5d)
Location: include/linux/ptr_ring.h:471
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818f759e)
Location: include/linux/ptr_ring.h:471
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8179e726)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819344ba)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81956c9e)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817c21b6)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819670ea)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8198d13e)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8188a871)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a3a459)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81a646a1)
Location: include/linux/ptr_ring.h:467
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
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81898a71)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a3c9e9)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81a6c7e1)
Location: include/linux/ptr_ring.h:467
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
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8187b1b1)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a2393d)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81a54f84)
Location: include/linux/ptr_ring.h:467
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
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8190c9b1)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81ad7f6d)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81b0dcc4)
Location: include/linux/ptr_ring.h:467
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
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81a612a1)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81c58ce9)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81c950a0)
Location: include/linux/ptr_ring.h:467
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
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81bec5e6)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81e0ebd9)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81e50ba0)
Location: include/linux/ptr_ring.h:467
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
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81c449c3)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81e82260)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81eac3b0)
Location: include/linux/ptr_ring.h:467
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
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81cfa523)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81f4323f)
Location: include/linux/ptr_ring.h:467
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81f6ee40)
Location: include/linux/ptr_ring.h:467
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffff8000109dc894)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffff800010c0c764)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffff800010c37a48)
Location: include/linux/ptr_ring.h:466
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (c0ac6ea0)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (c0d24e2c)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (c0d4ad20)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (c000000000a9ef60)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (c000000000cf7e90)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (c000000000d30570)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffe000627db8)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffe000789b10)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffe0007a9b30)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff81786c86)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819070ba)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8192cfae)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817665d6)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818c0eca)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818e6aae)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817b7036)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819580ea)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8197e13e)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817d1286)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff8197a1fa)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff819a093e)
Location: include/linux/ptr_ring.h:466
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
</details>
</li>
</ul>

## Differences
