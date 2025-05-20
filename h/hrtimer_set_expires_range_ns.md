# Function: <code>hrtimer_set_expires_range_ns</code>

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
In kernel/time/hrtimer.c (ffffffff810ef491)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/futex.c (ffffffff811003c6)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff810f6ca0)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff81107d06)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff810fdd61)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff8110f4f6)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81100014)
Location: include/linux/hrtimer.h:211
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff811106a3)
Location: include/linux/hrtimer.h:211
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff8110ae04)
Location: include/linux/hrtimer.h:211
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff8111be40)
Location: include/linux/hrtimer.h:211
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff819f0e40)
Location: include/linux/hrtimer.h:235
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff81129159)
Location: include/linux/hrtimer.h:235
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81a2c1c0)
Location: include/linux/hrtimer.h:232
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff81134649)
Location: include/linux/hrtimer.h:232
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81a9c363)
Location: include/linux/hrtimer.h:232
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff811418f8)
Location: include/linux/hrtimer.h:232
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81ad3c2c)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff8114d95e)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81bcbc43)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff8115cf1e)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81c44a63)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff81159108)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81c37cd0)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff8115b358)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81d56590)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff8117fe81)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81f283fc)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/futex/core.c (ffffffff811b2553)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In fs/aio.c (ffffffff81461fcd)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - fs/aio.c:read_events
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
In kernel/time/hrtimer.c (ffffffff820d404c)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/futex/core.c (ffffffff811f33e3)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In fs/aio.c (ffffffff814f218d)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - fs/aio.c:read_events
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
In kernel/time/hrtimer.c (ffffffff821582a1)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/futex/core.c (ffffffff81207b63)
Location: include/linux/hrtimer.h:252
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In fs/aio.c (ffffffff81528dcd)
Location: include/linux/hrtimer.h:252
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
In kernel/time/hrtimer.c (ffffffff8223b111)
Location: include/linux/hrtimer.h:214
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/futex/core.c (ffffffff8121ed73)
Location: include/linux/hrtimer.h:214
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In fs/aio.c (ffffffff8155cfed)
Location: include/linux/hrtimer.h:214
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
In kernel/time/hrtimer.c (ffff800010da67dc)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffff8000101ba038)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (c0e9e5c8)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (c0403ca4)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (c000000000ee9020)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (c000000000221984)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffe0008c8b90)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffe00013fb3a)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81a72a9c)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff81145f7e)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81a2ee6c)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff8113928e)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81adeeac)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff81143e2e)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/time/hrtimer.c (ffffffff81aeb33c)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/futex.c (ffffffff8114febe)
Location: include/linux/hrtimer.h:251
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
</details>
</li>
</ul>

## Differences
