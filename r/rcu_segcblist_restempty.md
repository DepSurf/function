# Function: <code>rcu_segcblist_restempty</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f3602)
Location: kernel/rcu/rcu_segcblist.h:109
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff810f74c2)
Location: kernel/rcu/rcu_segcblist.h:109
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_extract_pend_cbs
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_new_cbs
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
In kernel/rcu/tree.c (ffffffff810fd052)
Location: kernel/rcu/rcu_segcblist.h:87
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811013c2)
Location: kernel/rcu/rcu_segcblist.h:87
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
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
In kernel/rcu/tree.c (ffffffff81106ae9)
Location: kernel/rcu/rcu_segcblist.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81109852)
Location: kernel/rcu/rcu_segcblist.h:87
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
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
In kernel/rcu/tree.c (ffffffff81112d6e)
Location: kernel/rcu/rcu_segcblist.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81115022)
Location: kernel/rcu/rcu_segcblist.h:87
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
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
In kernel/rcu/tree.c (ffffffff8111c6c7)
Location: kernel/rcu/rcu_segcblist.h:74
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8111ee52)
Location: kernel/rcu/rcu_segcblist.h:74
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
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
In kernel/rcu/tree.c (ffffffff81128f97)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b54f)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff811358b6)
Location: kernel/rcu/rcu_segcblist.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81139a9f)
Location: kernel/rcu/rcu_segcblist.h:73
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff81131066)
Location: kernel/rcu/rcu_segcblist.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8113456f)
Location: kernel/rcu/rcu_segcblist.h:73
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff811337a9)
Location: kernel/rcu/rcu_segcblist.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8113541c)
Location: kernel/rcu/rcu_segcblist.h:108
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff81155baa)
Location: kernel/rcu/rcu_segcblist.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81157dc8)
Location: kernel/rcu/rcu_segcblist.h:108
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff8117e453)
Location: kernel/rcu/rcu_segcblist.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81181118)
Location: kernel/rcu/rcu_segcblist.h:110
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff811b92da)
Location: kernel/rcu/rcu_segcblist.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811bba78)
Location: kernel/rcu/rcu_segcblist.h:110
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff811cb5f3)
Location: kernel/rcu/rcu_segcblist.h:112
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce418)
Location: kernel/rcu/rcu_segcblist.h:112
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff811df991)
Location: kernel/rcu/rcu_segcblist.h:112
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e3008)
Location: kernel/rcu/rcu_segcblist.h:112
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffff8000101903dc)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffff8000101937bc)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (c03ddab8)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (c03e0ab4)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (c0000000001eb1bc)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (c0000000001ee7d8)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffe000122bec)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffe000125c8a)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff81121577)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81123b2f)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff811123b1)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811165af)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff8111f467)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81121a1f)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
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
In kernel/rcu/tree.c (ffffffff8112b5b2)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8112e02f)
Location: kernel/rcu/rcu_segcblist.h:94
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
```
</details>
</li>
</ul>

## Differences
