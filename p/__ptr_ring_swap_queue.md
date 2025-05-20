# Function: <code>__ptr_ring_swap_queue</code>

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
Location: include/linux/ptr_ring.h:352
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_resize
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
In drivers/net/tun.c (ffffffff8168221e)
Location: include/linux/ptr_ring.h:362
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_resize
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
In drivers/net/tun.c (ffffffff8169765b)
Location: include/linux/ptr_ring.h:526
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff81702527)
Location: include/linux/ptr_ring.h:546
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff81741254)
Location: include/linux/ptr_ring.h:562
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffff818cc41f)
Location: include/linux/ptr_ring.h:562
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffff81765354)
Location: include/linux/ptr_ring.h:562
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffff818f7648)
Location: include/linux/ptr_ring.h:562
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffff8179e7d8)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffff81956d25)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffff817c2268)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffff8198d1c5)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffff8188bd0a)
Location: include/linux/ptr_ring.h:558
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a64e77)
Location: include/linux/ptr_ring.h:558
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
In drivers/net/tun.c (ffffffff81899f8a)
Location: include/linux/ptr_ring.h:558
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a6cfa7)
Location: include/linux/ptr_ring.h:558
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
In drivers/net/tun.c (ffffffff8187c9ee)
Location: include/linux/ptr_ring.h:558
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a5582c)
Location: include/linux/ptr_ring.h:558
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
In drivers/net/tun.c (ffffffff8190dfbe)
Location: include/linux/ptr_ring.h:558
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81b0e5ac)
Location: include/linux/ptr_ring.h:558
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
In drivers/net/tun.c (ffffffff81a61f46)
Location: include/linux/ptr_ring.h:558
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81c952bf)
Location: include/linux/ptr_ring.h:558
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
In drivers/net/tun.c (ffffffff81bed916)
Location: include/linux/ptr_ring.h:558
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81e50ddf)
Location: include/linux/ptr_ring.h:558
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
In drivers/net/tun.c (ffffffff81c45e46)
Location: include/linux/ptr_ring.h:558
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81eac60b)
Location: include/linux/ptr_ring.h:558
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
In drivers/net/tun.c (ffffffff81cfb756)
Location: include/linux/ptr_ring.h:558
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f6f27a)
Location: include/linux/ptr_ring.h:558
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
In drivers/net/tun.c (ffff8000109dc96c)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffff800010c37d30)
Location: include/linux/ptr_ring.h:557
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
In drivers/net/tun.c (c0ac6f2c)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (c0d4ad8c)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (c000000000a9f038)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (c000000000d3063c)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffe000627e20)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffe0007a9b98)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffff81786d38)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffff8192d035)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffff81766688)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffff818e6b35)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffff817b70e8)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffff8197e1c5)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
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
In drivers/net/tun.c (ffffffff817d133b)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_generic.c (ffffffff819a09c9)
Location: include/linux/ptr_ring.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
</details>
</li>
</ul>

## Differences
