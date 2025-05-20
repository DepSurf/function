# Function: <code>arch_atomic_fetch_inc</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a51f2)
Location: include/linux/atomic-arch-fallback.h:365
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
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
In kernel/watchdog_hld.c (ffffffff811a21e2)
Location: include/linux/atomic-arch-fallback.h:435
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
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
In kernel/watchdog_hld.c (ffffffff811a2ea2)
Location: include/linux/atomic-arch-fallback.h:435
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
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
In kernel/watchdog_hld.c (ffffffff811cc6d2)
Location: include/linux/atomic/atomic-arch-fallback.h:435
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
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
In kernel/watchdog_hld.c (ffffffff812005d2)
Location: include/linux/atomic/atomic-arch-fallback.h:519
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
```
In io_uring/io_uring.c (ffffffff816d1d0d)
Location: include/linux/atomic/atomic-arch-fallback.h:519
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_wake
  - io_uring/io_uring.c:io_poll_wake
  - io_uring/io_uring.c:io_poll_cancel_req
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec0f0)
Location: include/linux/atomic/atomic-arch-fallback.h:519
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In kernel/watchdog_hld.c (ffffffff81248292)
Location: include/linux/atomic/atomic-arch-fallback.h:519
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
```
In io_uring/poll.c (ffffffff8179d231)
Location: include/linux/atomic/atomic-arch-fallback.h:519
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_can_finish_inline
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_get_ownership_slowpath
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfd40)
Location: include/linux/atomic/atomic-arch-fallback.h:519
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
