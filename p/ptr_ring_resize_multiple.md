# Function: <code>ptr_ring_resize_multiple</code>

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
In drivers/net/tun.c (ffffffff8165048b)
Location: include/linux/ptr_ring.h:396
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
In drivers/net/tun.c (ffffffff8168216b)
Location: include/linux/ptr_ring.h:420
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
In drivers/net/tun.c (ffffffff8169758c)
Location: include/linux/ptr_ring.h:585
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
In drivers/net/tun.c (ffffffff8170243d)
Location: include/linux/ptr_ring.h:605
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
In drivers/net/tun.c (ffffffff81741184)
Location: include/linux/ptr_ring.h:621
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff818cc36d)
Location: include/linux/ptr_ring.h:621
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
In drivers/net/tun.c (ffffffff8176527b)
Location: include/linux/ptr_ring.h:623
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff818f758d)
Location: include/linux/ptr_ring.h:623
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
In drivers/net/tun.c (ffffffff8179e70d)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff81956c8d)
Location: include/linux/ptr_ring.h:618
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
In drivers/net/tun.c (ffffffff817c219d)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff8198d12d)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8188bc20)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_queue_resize
```
```
In net/sched/sch_generic.c (ffffffff81a64dc0)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff8188bc20-ffffffff8188bf05: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
ffffffff81a64dc0-ffffffff81a65067: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81899ea0)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_queue_resize
```
```
In net/sched/sch_generic.c (ffffffff81a6cef0)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff81899ea0-ffffffff8189a185: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
ffffffff81a6cef0-ffffffff81a6d197: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8187c8f0)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff81a55760)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff8187c8f0-ffffffff8187cbdf: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
ffffffff81a55760-ffffffff81a55a14: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8190dec0)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff81b0e4e0)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff8190dec0-ffffffff8190e1af: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
ffffffff81b0e4e0-ffffffff81b0e794: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81a61e60)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff81c95210)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff81a61e60-ffffffff81a621a3: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
ffffffff81c95210-ffffffff81c954fc: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81bed830)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff81e50d30)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff81bed830-ffffffff81bedb73: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
ffffffff81e50d30-ffffffff81e5101c: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81c45d60)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff81eac560)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff81c45d60-ffffffff81c460a3: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
ffffffff81eac560-ffffffff81eac833: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfb670)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff81f6f1a0)
Location: include/linux/ptr_ring.h:619
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffffffff81cfb670-ffffffff81cfb9b3: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
ffffffff81f6f1a0-ffffffff81f6f4a2: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffff8000109dc87c)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffff800010c37c30)
Location: include/linux/ptr_ring.h:618
Inline: True
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
**Symbols:**

```
ffff800010c37c30-ffff800010c37f30: ptr_ring_resize_multiple.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (c0ac6e88)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (c0d4ad10)
Location: include/linux/ptr_ring.h:618
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
In drivers/net/tun.c (c000000000a9ef4c)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (c000000000d30560)
Location: include/linux/ptr_ring.h:618
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
In drivers/net/tun.c (ffffffe000627d94)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffe0007a9af2)
Location: include/linux/ptr_ring.h:618
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
In drivers/net/tun.c (ffffffff81786c6d)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff8192cf9d)
Location: include/linux/ptr_ring.h:618
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
In drivers/net/tun.c (ffffffff817665bd)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff818e6a9d)
Location: include/linux/ptr_ring.h:618
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
In drivers/net/tun.c (ffffffff817b701d)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff8197e12d)
Location: include/linux/ptr_ring.h:618
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
In drivers/net/tun.c (ffffffff817d126d)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/sched/sch_generic.c (ffffffff819a092d)
Location: include/linux/ptr_ring.h:618
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
```
</details>
</li>
</ul>

## Differences
