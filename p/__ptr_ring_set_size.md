# Function: <code>__ptr_ring_set_size</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816976c2)
Location: include/linux/ptr_ring.h:444
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
In kernel/bpf/cpumap.c (ffffffff811b0007)
Location: include/linux/ptr_ring.h:464
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8170258f)
Location: include/linux/ptr_ring.h:464
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
In kernel/bpf/cpumap.c (ffffffff811ca7d3)
Location: include/linux/ptr_ring.h:478
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8174131c)
Location: include/linux/ptr_ring.h:478
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818bd940)
Location: include/linux/ptr_ring.h:478
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818cc531)
Location: include/linux/ptr_ring.h:478
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
In kernel/bpf/cpumap.c (ffffffff811de0ff)
Location: include/linux/ptr_ring.h:478
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8176542d)
Location: include/linux/ptr_ring.h:478
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818e4c81)
Location: include/linux/ptr_ring.h:478
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818f776d)
Location: include/linux/ptr_ring.h:478
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
In kernel/bpf/cpumap.c (ffffffff811f37cb)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8179e87a)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819344e0)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81956e72)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (ffffffff8120056b)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817c230a)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff81967110)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8198d312)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (ffffffff81227fed)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8188a887)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a3a47f)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81a646d0)
Location: include/linux/ptr_ring.h:474
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
In kernel/bpf/cpumap.c (ffffffff8122e823)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81898a87)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a3ca0f)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81a6c810)
Location: include/linux/ptr_ring.h:474
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
In kernel/bpf/cpumap.c (ffffffff81233700)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8187b1c7)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a23963)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81a54fb7)
Location: include/linux/ptr_ring.h:474
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
In kernel/bpf/cpumap.c (ffffffff8126d382)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff8190c9c7)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81ad7f93)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81b0dcf7)
Location: include/linux/ptr_ring.h:474
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
In kernel/bpf/cpumap.c (ffffffff812bc4ba)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81a612b6)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81c58d0f)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81c950fc)
Location: include/linux/ptr_ring.h:474
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
In kernel/bpf/cpumap.c (ffffffff8131f9cb)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81bec5fb)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81e0ebff)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81e50bfc)
Location: include/linux/ptr_ring.h:474
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
In kernel/bpf/cpumap.c (ffffffff8134f9cb)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81c449d8)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81e82286)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81eac41a)
Location: include/linux/ptr_ring.h:474
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
In kernel/bpf/cpumap.c (ffffffff81376edb)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In drivers/net/tun.c (ffffffff81cfa538)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81f43265)
Location: include/linux/ptr_ring.h:474
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81f6eeaa)
Location: include/linux/ptr_ring.h:474
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
In kernel/bpf/cpumap.c (ffff800010288830)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffff8000109dc9ec)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffff800010c0c780)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffff800010c37a60)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (c04b7dd4)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (c0ac6fac)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (c0d24e48)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (c0d4ae30)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (c000000000333d4c)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (c000000000a9f0e8)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (c000000000cf7ea4)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (c000000000d306e8)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (ffffffe0001bc9c8)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffe000627eba)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffe000789b32)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffe0007a9c14)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (ffffffff811f8b8b)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff81786dda)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819070e0)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8192d182)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (ffffffff811eb8db)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff8176672a)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818c0ef0)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818e6c82)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (ffffffff811f695b)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817b718a)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff81958110)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff8197e312)
Location: include/linux/ptr_ring.h:473
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
In kernel/bpf/cpumap.c (ffffffff8120558b)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In drivers/net/tun.c (ffffffff817d13dc)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff8197a220)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff819a0b0d)
Location: include/linux/ptr_ring.h:473
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
</details>
</li>
</ul>

## Differences
