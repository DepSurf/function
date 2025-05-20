# Function: <code>ktime_get_ts</code>

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
In kernel/time/posix-timers.c (ffffffff810f0b76)
Location: include/linux/timekeeping.h:64
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811349fb)
Location: include/linux/timekeeping.h:64
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In fs/select.c (ffffffff81220d32)
Location: include/linux/timekeeping.h:64
Inline: True
Inline callers:
  - fs/select.c:poll_select_copy_remaining
```
```
In fs/eventpoll.c (ffffffff812553f9)
Location: include/linux/timekeeping.h:64
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/compat.c (ffffffff81263e22)
Location: include/linux/timekeeping.h:64
Inline: True
Inline callers:
  - fs/compat.c:poll_select_copy_remaining
```
```
In net/socket.c (ffffffff816ff86e)
Location: include/linux/timekeeping.h:64
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
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
In kernel/time/posix-timers.c (ffffffff810f7b96)
Location: include/linux/timekeeping.h:80
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113ce8b)
Location: include/linux/timekeeping.h:80
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In fs/compat.c (ffffffff8128ff86)
Location: include/linux/timekeeping.h:80
Inline: True
Inline callers:
  - fs/compat.c:poll_select_copy_remaining
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
In kernel/time/posix-timers.c (ffffffff81105536)
Location: include/linux/timekeeping.h:80
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81146c3b)
Location: include/linux/timekeeping.h:80
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In fs/compat.c (ffffffff812a4fc6)
Location: include/linux/timekeeping.h:80
Inline: True
Inline callers:
  - fs/compat.c:poll_select_copy_remaining
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
In kernel/debug/kdb/kdb_main.c (ffffffff81148728)
Location: include/linux/timekeeping.h:69
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In fs/select.c (ffffffff8126894a)
Location: include/linux/timekeeping.h:69
Inline: True
Inline callers:
  - fs/select.c:compat_poll_select_copy_remaining
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
In kernel/debug/kdb/kdb_main.c (ffffffff81154fd8)
Location: include/linux/timekeeping32.h:41
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
</details>
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In sound/core/timer.c (c0c8cd10)
Location: include/linux/timekeeping32.h:22
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_user_tinterrupt
  - sound/core/timer.c:snd_timer_notify1
```
```
In sound/core/pcm_native.c (c0c93e0c)
Location: include/linux/timekeeping32.h:22
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_trigger_tstamp
  - sound/core/pcm_native.c:snd_pcm_status
```
```
In sound/core/pcm_lib.c (c0c99580)
Location: include/linux/timekeeping32.h:22
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:update_audio_tstamp
  - sound/core/pcm_lib.c:__snd_pcm_xrun
```
</details>
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
