# Function: <code>sync_test_and_set_bit</code>

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
In drivers/xen/events/events_2l.c (ffffffff814c9ed2)
Location: arch/x86/include/asm/sync_bitops.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff814ca859)
Location: arch/x86/include/asm/sync_bitops.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff8151aeaf)
Location: arch/x86/include/asm/sync_bitops.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151b3b9)
Location: arch/x86/include/asm/sync_bitops.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff8154737f)
Location: arch/x86/include/asm/sync_bitops.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547889)
Location: arch/x86/include/asm/sync_bitops.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff8155b14f)
Location: arch/x86/include/asm/sync_bitops.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155b639)
Location: arch/x86/include/asm/sync_bitops.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff815bf47f)
Location: arch/x86/include/asm/sync_bitops.h:81
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bf969)
Location: arch/x86/include/asm/sync_bitops.h:81
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff815f7b5f)
Location: arch/x86/include/asm/sync_bitops.h:81
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f8059)
Location: arch/x86/include/asm/sync_bitops.h:81
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff81612bc1)
Location: arch/x86/include/asm/sync_bitops.h:81
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81613119)
Location: arch/x86/include/asm/sync_bitops.h:81
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff81646a4c)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81646f29)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff81668eec)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff816693c9)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff81718fbc)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff817194c9)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff8173652c)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81719f6c)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff817983cc)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff818d1134)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81a22a48)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81a6bdd8)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81abde78)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
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
In drivers/xen/events/events_2l.c (ffffffff8162ed5c)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f239)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff8165cd2c)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d209)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
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
In drivers/xen/events/events_2l.c (ffffffff81677333)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677819)
Location: arch/x86/include/asm/sync_bitops.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
```
</details>
</li>
</ul>

## Differences
