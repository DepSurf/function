# Function: <code>hrtimer_init_sleeper_on_stack</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81ad3c20)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff8114d94a)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff8133b300)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff814efb34)
Location: include/linux/hrtimer.h:396
Inline: True
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
In kernel/time/hrtimer.c (ffffffff81bcbc30)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff8115cf0a)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff81375cc0)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff8154ef53)
Location: include/linux/hrtimer.h:396
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
In kernel/time/hrtimer.c (ffffffff81c44a53)
Location: include/linux/hrtimer.h:397
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff811590f4)
Location: include/linux/hrtimer.h:397
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff81383b90)
Location: include/linux/hrtimer.h:397
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff8156cbb8)
Location: include/linux/hrtimer.h:397
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/hrtimer.c (ffffffff81c37cc3)
Location: include/linux/hrtimer.h:397
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff8115b344)
Location: include/linux/hrtimer.h:397
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff8138a920)
Location: include/linux/hrtimer.h:397
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff81574a58)
Location: include/linux/hrtimer.h:397
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/hrtimer.c (ffffffff81d56583)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff8117fe66)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff813d7c30)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff815d8f76)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/hrtimer.c (ffffffff81f283ee)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex/core.c (ffffffff811b253c)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In fs/aio.c (ffffffff81461fa0)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff81686c81)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/hrtimer.c (ffffffff820d403e)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex/core.c (ffffffff811f33cc)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In fs/aio.c (ffffffff814f2160)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff81744951)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/hrtimer.c (ffffffff82158298)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex/core.c (ffffffff81207b4c)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In fs/aio.c (ffffffff81528da0)
Location: include/linux/hrtimer.h:393
Inline: True
Inline callers:
  - fs/aio.c:read_events
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
In kernel/time/hrtimer.c (ffffffff8223b108)
Location: include/linux/hrtimer.h:355
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex/core.c (ffffffff8121ed5c)
Location: include/linux/hrtimer.h:355
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In fs/aio.c (ffffffff8155ceaf)
Location: include/linux/hrtimer.h:355
Inline: True
Inline callers:
  - fs/aio.c:read_events
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
In kernel/time/hrtimer.c (ffff800010da67c8)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffff8000101ba024)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffff8000103fbd30)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffff8000105ed914)
Location: include/linux/hrtimer.h:396
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
In kernel/time/hrtimer.c (c0e9e5b4)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (c0403c90)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (c05cfb7c)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In block/blk-mq.c (c079b250)
Location: include/linux/hrtimer.h:396
Inline: True
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
In kernel/time/hrtimer.c (c000000000ee9008)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (c000000000221964)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (c0000000005035e0)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (c000000000785034)
Location: include/linux/hrtimer.h:396
Inline: True
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
In kernel/time/hrtimer.c (ffffffe0008c8b7e)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffe00013fb28)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffe0002a99ae)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffe00042e112)
Location: include/linux/hrtimer.h:396
Inline: True
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
In kernel/time/hrtimer.c (ffffffff81a72a90)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff81145f6a)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff813338e0)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff814e8114)
Location: include/linux/hrtimer.h:396
Inline: True
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
In kernel/time/hrtimer.c (ffffffff81a2ee60)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff8113927a)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff81324550)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff814d8684)
Location: include/linux/hrtimer.h:396
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
In kernel/time/hrtimer.c (ffffffff81adeea0)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff81143e1a)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff813313b0)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff814e41a4)
Location: include/linux/hrtimer.h:396
Inline: True
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
In kernel/time/hrtimer.c (ffffffff81aeb330)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff8114feaa)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff81343f9f)
Location: include/linux/hrtimer.h:396
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff814fd724)
Location: include/linux/hrtimer.h:396
Inline: True
```
</details>
</li>
</ul>

## Differences
