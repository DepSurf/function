# Function: <code>sync_set_bit</code>

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
In drivers/xen/events/events_2l.c (ffffffff814c9eb2)
Location: arch/x86/include/asm/sync_bitops.h:29
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff814ca819)
Location: arch/x86/include/asm/sync_bitops.h:29
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
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
In drivers/xen/events/events_2l.c (ffffffff8151ae69)
Location: arch/x86/include/asm/sync_bitops.h:29
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151b409)
Location: arch/x86/include/asm/sync_bitops.h:29
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81547339)
Location: arch/x86/include/asm/sync_bitops.h:29
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff815478d9)
Location: arch/x86/include/asm/sync_bitops.h:29
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff8155b10b)
Location: arch/x86/include/asm/sync_bitops.h:29
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155b689)
Location: arch/x86/include/asm/sync_bitops.h:29
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff815bf43b)
Location: arch/x86/include/asm/sync_bitops.h:30
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bf9b9)
Location: arch/x86/include/asm/sync_bitops.h:30
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff815f7b1b)
Location: arch/x86/include/asm/sync_bitops.h:30
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f80a9)
Location: arch/x86/include/asm/sync_bitops.h:30
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81612bf6)
Location: arch/x86/include/asm/sync_bitops.h:30
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81613169)
Location: arch/x86/include/asm/sync_bitops.h:30
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81646a1b)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81646f79)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81668ebb)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669419)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81718f8b)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81719519)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff817364fb)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff817366c9)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81719f3b)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a119)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff8179839b)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798716)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff818d10fc)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1866)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81a22a10)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23626)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81a6bda0)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6cad9)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff81abde40)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abeb99)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/xen/events/events_2l.c (ffffffff8162ed2b)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f289)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hv/channel.c (ffffffff81850dd3)
Location: arch/x86/include/asm/sync_bitops.h:32
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
In drivers/xen/events/events_2l.c (ffffffff8165ccfb)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d259)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
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
In drivers/xen/events/events_2l.c (ffffffff816772fb)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677869)
Location: arch/x86/include/asm/sync_bitops.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
```
</details>
</li>
</ul>

## Differences
