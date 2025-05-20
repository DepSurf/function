# Function: <code>sync_clear_bit</code>

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
In drivers/xen/events/events_2l.c (ffffffff814c9e92)
Location: arch/x86/include/asm/sync_bitops.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff814ca7d9)
Location: arch/x86/include/asm/sync_bitops.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff8151ae3a)
Location: arch/x86/include/asm/sync_bitops.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151b339)
Location: arch/x86/include/asm/sync_bitops.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff8154730a)
Location: arch/x86/include/asm/sync_bitops.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547809)
Location: arch/x86/include/asm/sync_bitops.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff8155b0da)
Location: arch/x86/include/asm/sync_bitops.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155b5b9)
Location: arch/x86/include/asm/sync_bitops.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff815bf40a)
Location: arch/x86/include/asm/sync_bitops.h:48
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bf8e9)
Location: arch/x86/include/asm/sync_bitops.h:48
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff815f7aea)
Location: arch/x86/include/asm/sync_bitops.h:48
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f7fd9)
Location: arch/x86/include/asm/sync_bitops.h:48
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff81612b9a)
Location: arch/x86/include/asm/sync_bitops.h:48
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81613099)
Location: arch/x86/include/asm/sync_bitops.h:48
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff816469ea)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81646ea9)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff81668e8a)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669349)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff81718f5a)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81719449)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff817364ca)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736649)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff81719f0a)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a099)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff8179836a)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798636)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff818d10b0)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1786)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff81a229c2)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23526)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff81a6bd52)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6c9d9)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff81abddf2)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abea99)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff8162ecfa)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f1b9)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff8165ccca)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d189)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
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
In drivers/xen/events/events_2l.c (ffffffff816772c1)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677799)
Location: arch/x86/include/asm/sync_bitops.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
```
</details>
</li>
</ul>

## Differences
