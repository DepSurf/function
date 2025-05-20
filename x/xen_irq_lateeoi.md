# Function: <code>xen_irq_lateeoi</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81732e80)
Location: drivers/xen/events/events_base.c:676
Inline: False
```
**Symbols:**

```
ffffffff81732e80-ffffffff81732f04: xen_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716930)
Location: drivers/xen/events/events_base.c:706
Inline: False
```
**Symbols:**

```
ffffffff81716930-ffffffff817169b4: xen_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81793cc0)
Location: drivers/xen/events/events_base.c:706
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
```
**Symbols:**

```
ffffffff81793cc0-ffffffff81793d62: xen_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cc7d0)
Location: drivers/xen/events/events_base.c:706
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
```
**Symbols:**

```
ffffffff818cc7d0-ffffffff818cc87c: xen_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1ddf0)
Location: drivers/xen/events/events_base.c:708
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
```
**Symbols:**

```
ffffffff81a1ddf0-ffffffff81a1de9c: xen_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a670c0)
Location: drivers/xen/events/events_base.c:709
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
```
**Symbols:**

```
ffffffff81a670c0-ffffffff81a6716c: xen_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81aba170)
Location: drivers/xen/events/events_base.c:698
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
```
**Symbols:**

```
ffffffff81aba170-ffffffff81aba21a: xen_irq_lateeoi (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
