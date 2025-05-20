# Function: <code>ptr_ring_produce</code>

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
In drivers/net/tun.c (ffffffff8164d51a)
Location: include/linux/ptr_ring.h:114
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
In drivers/net/tun.c (ffffffff8167f242)
Location: include/linux/ptr_ring.h:119
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
In drivers/net/tun.c (ffffffff81694455)
Location: include/linux/ptr_ring.h:121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816fe57f)
Location: include/linux/ptr_ring.h:127
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
In drivers/net/tun.c (ffffffff8173d749)
Location: include/linux/ptr_ring.h:128
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff818bde92)
Location: include/linux/ptr_ring.h:128
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818cc239)
Location: include/linux/ptr_ring.h:128
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
In drivers/net/tun.c (ffffffff817610f1)
Location: include/linux/ptr_ring.h:128
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff818e5272)
Location: include/linux/ptr_ring.h:128
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818f7869)
Location: include/linux/ptr_ring.h:128
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
In drivers/net/tun.c (ffffffff8179ed79)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81934b99)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81956f80)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (ffffffff817c3559)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81967902)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8198d420)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (ffffffff8188e804)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81a3b0de)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/sched/sch_generic.c (ffffffff81a6511b)
Location: include/linux/ptr_ring.h:124
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
In drivers/net/tun.c (ffffffff8189d16e)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81a3d7e0)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/sched/sch_generic.c (ffffffff81a6d24b)
Location: include/linux/ptr_ring.h:124
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
In drivers/net/tun.c (ffffffff8187f99d)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81a248b0)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/sched/sch_generic.c (ffffffff81a55acb)
Location: include/linux/ptr_ring.h:124
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
In kernel/bpf/cpumap.c (ffffffff8126e680)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In drivers/net/tun.c (ffffffff81910b26)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81ad91a8)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/sched/sch_generic.c (ffffffff81b0e84b)
Location: include/linux/ptr_ring.h:124
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
In kernel/bpf/cpumap.c (ffffffff812bd58e)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In drivers/net/tun.c (ffffffff81a6090d)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81c5a35a)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/sched/sch_generic.c (ffffffff81c94dfb)
Location: include/linux/ptr_ring.h:124
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
In kernel/bpf/cpumap.c (ffffffff81320a2b)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In drivers/net/tun.c (ffffffff81becece)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81e0fe2a)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/sched/sch_generic.c (ffffffff81e508ab)
Location: include/linux/ptr_ring.h:124
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
In kernel/bpf/cpumap.c (ffffffff813508db)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In drivers/net/tun.c (ffffffff81c453cf)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81e83764)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/sched/sch_generic.c (ffffffff81eac098)
Location: include/linux/ptr_ring.h:124
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
In kernel/bpf/cpumap.c (ffffffff81377d0b)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In drivers/net/tun.c (ffffffff81cfacfd)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81f441b4)
Location: include/linux/ptr_ring.h:124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_unrefed_page
```
```
In net/sched/sch_generic.c (ffffffff81f6eb28)
Location: include/linux/ptr_ring.h:124
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
In drivers/net/tun.c (ffff8000109def14)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffff800010c0d388)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (ffff800010c38708)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (c0ac2b30)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (c0d25620)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (c0d4a8cc)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (c000000000aa0884)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (c000000000cf8a7c)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (c000000000d31570)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (ffffffe000628156)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffe00078a208)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (ffffffe0007a9db4)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (ffffffff81787fea)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff819078d2)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8192d290)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (ffffffff8176793a)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff818c16e2)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818e6d90)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (ffffffff817b83d9)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff81958902)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8197e420)
Location: include/linux/ptr_ring.h:123
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
In drivers/net/tun.c (ffffffff817d06de)
Location: include/linux/ptr_ring.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/page_pool.c (ffffffff8197aa42)
Location: include/linux/ptr_ring.h:123
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819a05eb)
Location: include/linux/ptr_ring.h:123
Inline: True
```
</details>
</li>
</ul>

## Differences
