# Function: <code>hlist_move_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ebafb)
Location: include/linux/list.h:685
Inline: True
Inline callers:
  - kernel/time/timer.c:cascade
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (ffffffff8122bc5c)
Location: include/linux/list.h:685
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7a3e)
Location: include/linux/list.h:685
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f4046)
Location: include/linux/list.h:695
Inline: True
```
```
In fs/namespace.c (ffffffff812543cc)
Location: include/linux/list.h:695
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff81824d4e)
Location: include/linux/list.h:695
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fb1e6)
Location: include/linux/list.h:711
Inline: True
```
```
In fs/namespace.c (ffffffff812677dc)
Location: include/linux/list.h:711
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff81855f0b)
Location: include/linux/list.h:711
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fd76e)
Location: include/linux/list.h:724
Inline: True
```
```
In fs/namespace.c (ffffffff81274e9c)
Location: include/linux/list.h:724
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff81879b1d)
Location: include/linux/list.h:724
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff81107e9b)
Location: include/linux/list.h:725
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (ffffffff8129775c)
Location: include/linux/list.h:725
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa56d)
Location: include/linux/list.h:725
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff81114a2a)
Location: include/linux/list.h:725
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (ffffffff812bd94c)
Location: include/linux/list.h:725
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff8195106d)
Location: include/linux/list.h:725
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff8111f1ca)
Location: include/linux/list.h:778
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (ffffffff812d2dec)
Location: include/linux/list.h:778
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff81984729)
Location: include/linux/list.h:778
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff811296b2)
Location: include/linux/list.h:838
Inline: True
```
```
In fs/namespace.c (ffffffff812f1444)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee409)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff81135655)
Location: include/linux/list.h:838
Inline: True
```
```
In fs/namespace.c (ffffffff81302ff4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff81a252e9)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff81145535)
Location: include/linux/list.h:936
Inline: True
```
```
In fs/namespace.c (ffffffff8133cab4)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/core/sock_map.c (ffffffff81a4e59e)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16f19)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff8114162f)
Location: include/linux/list.h:963
Inline: True
```
```
In fs/namespace.c (ffffffff81348974)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/core/sock_map.c (ffffffff81a5457e)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25189)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff81142e41)
Location: include/linux/list.h:963
Inline: True
```
```
In fs/namespace.c (ffffffff8134ed44)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/core/sock_map.c (ffffffff81a503dd)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/xfrm/xfrm_state.c (ffffffff81b12da9)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff811663d1)
Location: include/linux/list.h:963
Inline: True
```
```
In fs/namespace.c (ffffffff8139cde4)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/core/sock_map.c (ffffffff81b08fdd)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6ca9)
Location: include/linux/list.h:963
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff8119902f)
Location: include/linux/list.h:1009
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In fs/namespace.c (ffffffff8141fd34)
Location: include/linux/list.h:1009
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/core/sock_map.c (ffffffff81c8f04a)
Location: include/linux/list.h:1009
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d8d1)
Location: include/linux/list.h:1009
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff811d758f)
Location: include/linux/list.h:1009
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In fs/namespace.c (ffffffff814ac244)
Location: include/linux/list.h:1009
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/core/sock_map.c (ffffffff81e4a29a)
Location: include/linux/list.h:1009
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38eb1)
Location: include/linux/list.h:1009
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff811eb8ef)
Location: include/linux/list.h:1024
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In fs/namespace.c (ffffffff814e1014)
Location: include/linux/list.h:1024
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/core/sock_map.c (ffffffff81ea59aa)
Location: include/linux/list.h:1024
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98bb1)
Location: include/linux/list.h:1024
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff81201a3f)
Location: include/linux/list.h:1113
Inline: True
Inline callers:
  - kernel/time/timer.c:__run_timers
```
```
In fs/namespace.c (ffffffff815150e4)
Location: include/linux/list.h:1113
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/core/sock_map.c (ffffffff81f6846a)
Location: include/linux/list.h:1113
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/xfrm/xfrm_state.c (ffffffff82065f11)
Location: include/linux/list.h:1113
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffff80001019e7e4)
Location: include/linux/list.h:838
Inline: True
```
```
In fs/namespace.c (ffff8000103b63cc)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffff800010ce4280)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (c03e841c)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (c0594708)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (c0debc5c)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (c0000000001fe8c8)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (c0000000004b2a10)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (c000000000e0581c)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffe00012c566)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (ffffffe000279088)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffe000831158)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff8112de05)
Location: include/linux/list.h:838
Inline: True
```
```
In fs/namespace.c (ffffffff812fb5d4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4979)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff811206b4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (ffffffff812ec1f4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff81981769)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff8112bb25)
Location: include/linux/list.h:838
Inline: True
```
```
In fs/namespace.c (ffffffff812f93c4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f3f9)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
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
In kernel/time/timer.c (ffffffff81138214)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
```
```
In fs/namespace.c (ffffffff8130a6e4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ad49)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
</details>
</li>
</ul>

## Differences
