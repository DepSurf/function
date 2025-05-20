# Function: <code>raw_atomic_fetch_inc</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog_perf.c (ffffffff8125f59d)
Location: include/linux/atomic/atomic-arch-fallback.h:1099
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_enable
```
```
In io_uring/poll.c (ffffffff817de461)
Location: include/linux/atomic/atomic-arch-fallback.h:1099
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
In net/ipv6/ioam6_iptunnel.c (ffffffff82020cd3)
Location: include/linux/atomic/atomic-arch-fallback.h:1099
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In kernel/watchdog_perf.c (ffffffff812795ad)
Location: include/linux/atomic/atomic-arch-fallback.h:1108
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_enable
```
```
In io_uring/poll.c (ffffffff81822831)
Location: include/linux/atomic/atomic-arch-fallback.h:1108
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
In io_uring/waitid.c (ffffffff8182a587)
Location: include/linux/atomic/atomic-arch-fallback.h:1108
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid_wait
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97be8)
Location: include/linux/atomic/atomic-arch-fallback.h:1108
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_open
```
```
In drivers/accel/drm_accel.c (ffffffff81cbcca2)
Location: include/linux/atomic/atomic-arch-fallback.h:1108
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_open
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efe03)
Location: include/linux/atomic/atomic-arch-fallback.h:1108
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
