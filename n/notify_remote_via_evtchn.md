# Function: <code>notify_remote_via_evtchn</code>

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
In drivers/xen/events/events_base.c (ffffffff814c8166)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff814ccab7)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814fea9c)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81518c06)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8151d96c)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154f61d)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff815450f6)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81549dfc)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157be9d)
Location: include/xen/events.h:62
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81559026)
Location: include/xen/events.h:63
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8155dce9)
Location: include/xen/events.h:63
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8159010b)
Location: include/xen/events.h:63
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff815bd406)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815c1ffc)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4c0b)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff815f5ab6)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815fa7cb)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e27b)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81610b76)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8161587b)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c3ab)
Location: include/xen/events.h:64
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81645e4c)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81649420)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680c99)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff816683cc)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8166b8c1)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3349)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff8171855c)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171b409)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755fc9)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81735b0d)
Location: include/xen/events.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81738479)
Location: include/xen/events.h:78
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81771239)
Location: include/xen/events.h:78
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff817192ed)
Location: include/xen/events.h:79
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171c456)
Location: include/xen/events.h:79
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754c39)
Location: include/xen/events.h:79
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81797109)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8179b1c6)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d85e3)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff818d00a9)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff818d407a)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916b6d)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81a21829)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a2630a)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a71506)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81a6abb9)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a6f8e9)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abbd77)
Location: include/xen/events.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff81abce53)
Location: include/xen/events.h:79
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81ac19e9)
Location: include/xen/events.h:79
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0eab6)
Location: include/xen/events.h:79
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffff800010830a68)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffff800010835d34)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffff80001087b9bc)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
</details>
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
In drivers/xen/events/events_base.c (ffffffff8162e0fc)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81631731)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668da9)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff8165c20c)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8165f701)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697189)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In drivers/xen/events/events_base.c (ffffffff816767fc)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81679cfc)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1739)
Location: include/xen/events.h:65
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
</details>
</li>
</ul>

## Differences
